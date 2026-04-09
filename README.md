# Uri .. Your AI Product-Market Fit Griller

Most founders skip PMF validation and jump straight to scaling. Uri grills every decision through the PMF lens.. retention curves, the Sean Ellis 40% test, and Lean Canvas.. before you waste money scaling something nobody wants.

Built on Uri Levine (Waze founder) + Ash Maurya (Running Lean / Scaling Lean). Adapted for Claude Code.

## What Happens When You Run It

```
Uri PMF Review -- 2026-04-09

OFFER PMF SCORECARD:
  Sprint Club    | Signal   | 94% M1 retention | Pull > Push | 10x: Yes
  200K Club      | Signal   | 4/5 retained M3   | Pull        | 10x: Pending
  Private Impl.  | Proven   | 0% churn           | Pull        | 10x: 144x ROI
  Certification  | Assumption | No cohort data   | Push        | 10x: Not tested

BOARD DECISION PMF AUDIT:
  "Scale cold email to 200/day"
  PMF Impact: Neutral
  Stage: You're still at Problem-Solution Fit for this channel.
  Verdict: Scaling outbound before proving inbound pull is burning money.
  Next validation step: Run Sean Ellis survey on last 30 trial members. 48 hours. <40% = stop scaling.

THE ONE THING: You have product-market hope, not product-market fit.
  Sprint Club retention curve hasn't flattened yet. Month 4+ data is missing.
  Run the boyfriend/girlfriend test this week.. "Would you be upset if Sprint Club disappeared?"
  If <40% say "very disappointed".. you're not ready to scale.
```

This is real output from Strategy Sprints, where Uri runs daily alongside 14 other AI advisors managing sales, strategy, distribution, health, and investing.

## Core Methodology

Every run applies these gates and tests to YOUR data:

| Test | The Question It Answers |
|------|------------------------|
| **3-Stage Gates** | Problem-Solution Fit.. Product-Market Fit.. Scale. Where are you? No skipping. |
| **Retention Curves** | Are users staying? Does the curve flatten or bleed? |
| **Sean Ellis 40%** | Would 40% of users be "very disappointed" without you? |
| **10x Test** | Is this 10x better than the existing alternative? Not 2x. 10x. |
| **Push vs Pull Ratio** | Are customers seeking you out.. or are you convincing them? |
| **Boyfriend/Girlfriend Test** | Would they be upset if this disappeared.. or shrug? |
| **Lean Canvas Validation** | Every new initiative needs a filled canvas before a dollar is spent. |

## Key Features

- Reads the board cascade and deepens PMF analysis on every decision
- Retention curve analysis.. are users staying?
- Sean Ellis test.. would 40% of users be "very disappointed" without you?
- Lean Canvas validation on every new offer or pivot
- Level 3 adversarial.. always demolition + construction. Never leaves you with just "this is wrong".. always provides the next experiment
- Generates an Offer PMF Scorecard across all products
- Identifies "the question you're avoiding"

## Install in 2 Minutes

```bash
# 1. Copy the skill
cp uri-review.md ~/.claude/commands/uri-review.md

# 2. Add your API keys
cp .env.example ~/.claude/.env
# Edit with your Notion token + Discord webhook

# 3. Run
/uri-review
```

Uri works best with Notion (members + pipeline data) and Discord (notifications). Google Sheets and Gmail are optional.

## Part of a 15-Advisor Board

Uri is one piece of a full AI operations system. The advisors that founders use most:

| Advisor | What It Does | Repo |
|---------|-------------|------|
| **Jay** | $21B growth playbook.. 8 revenue frameworks daily | [jay-advisor](https://github.com/SimonTheSalesBooster/jay-advisor) |
| **Anthony** | Scores your sales calls, coaches daily | [anthony-sales](https://github.com/SimonTheSalesBooster/anthony-sales) |
| **Richard** | Audits your strategy against Rumelt's kernel | [richard-strategy](https://github.com/SimonTheSalesBooster/richard-strategy) |
| **Greg** | 6 distribution strategies running in parallel | [greg-distribution](https://github.com/SimonTheSalesBooster/greg-distribution) |
| **Boris** | Fractional CTO.. stack health, cost audit | [boris-technical](https://github.com/SimonTheSalesBooster/boris-technical) |

[See all 15 advisors](https://github.com/SimonTheSalesBooster/board-of-advisors)

## The Full System

These advisors run autonomously inside **Strategy Sprints**.. a 90-day operating system for B2B founders.

One client grew revenue 130% in 90 days (144x ROI on a $9K/month engagement). 254 founders run a lighter version through Sprint Club at $49/month.

Curious what Uri would find in your business? [Book a coffee with Simon](https://calendly.com/simonseverino/coffee-with-simon) and we'll run it live.

---

Built by [Simon Severino](https://www.youtube.com/@TheSalesShow) with [Claude Code](https://claude.ai/code).
