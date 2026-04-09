# Uri PMF Advisor

Uri is a Claude Code skill that grills every business decision through the product-market fit lens. It runs after the daily board meeting, reads all proposals and decisions, and applies Uri Levine + Ash Maurya methodology to surface what's real and what's hope.

## Setup

1. Copy `uri-review.md` to `~/.claude/commands/uri-review.md`
2. Copy `.env.example` to `~/.claude/.env` and fill in your keys
3. Run `/uri-review` from Claude Code

## Required Environment Variables

- `NOTION_API_KEY` .. your Notion integration token (for members DB + pipeline data)
- `DISCORD_WEBHOOK_AGENTS` .. Discord webhook URL for advisor output

## Optional Environment Variables

- `DISCORD_WEBHOOK_CERTIFICATION` .. Discord webhook for certification-specific PMF signals
- `OBSIDIAN_VAULT_PATH` .. path to your Obsidian vault for board meeting files
- `GOOGLE_CLIENT_ID` .. Google OAuth client ID (for YouTube analytics + Sheets)
- `GOOGLE_CLIENT_SECRET` .. Google OAuth client secret
- `GOOGLE_REFRESH_TOKEN_FULL` .. Google OAuth refresh token
- `GMAIL_CONFIGURED` .. set to `true` if Gmail MCP is connected

## What It Does

Each run:
1. Reads today's Board Meeting file from Obsidian
2. Pulls retention data from Notion Members database
3. Reads Buyer's Journey scorecard and live content metrics
4. Checks Sprint Dashboard for active initiatives
5. Runs PMF critique on every board decision and proposal
6. Generates an Offer PMF Scorecard (Proven / Signal / Assumption / No Data)
7. Appends full analysis to the Board Meeting file
8. Posts summary to Discord

## Notion Setup

Uri reads from these Notion databases (set IDs in the skill file):
- Members DB .. membership status, joined/cancelled dates, cohort retention
- Buyer's Journey .. funnel metrics, conversion rates
- Sprint Dashboard .. active initiatives and experiments
- Refinery DB .. content production pipeline

## PMF Status Definitions

- **Proven** .. retention curve flattened + 40%+ Sean Ellis + organic growth > 30%
- **Signal** .. some positive retention data but not yet conclusive
- **Assumption** .. no hard data.. just belief
- **No Data** .. haven't measured yet

## Customization

Edit the methodology, voice, and PMF gates in `uri-review.md` to match your business context. Uri's voice is Israeli-direct.. relentless.. numbers or nothing.
