<div align="center">

# Influencer Marketing.skill

> *"The core of influencer marketing isn't the 'influencer' — it's the 'marketing'."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)

<br>

Your boss told you to reach out to 100 creators. You did.<br>
5 replied, 2 went live, total views: 3,000.<br>
**Then your boss asks: "Where's the ROI?"**<br>

Don't panic. This Skill distills 5 years of hands-on overseas influencer marketing experience<br>
into an actionable knowledge base — from competitor analysis to budget planning,<br>
from writing Briefs to negotiating rates.<br>
**Fewer pitfalls, more viral hits.**

<br>

Covers 9 key scenarios across the full influencer marketing workflow:<br>
**Competitor Analysis · Strategy · Brief Writing · Outreach · Influencer Selection · Negotiation · Data Analysis · Budget Planning · Career Growth**<br>
Not just Q&A — it can generate emails, Briefs, budget plans, and more.

[Installation](#installation) · [Usage](#usage) · [Examples](#examples) · [中文](README.md)

</div>

---

## Installation

### Claude Code

> **Important**: Claude Code looks for skills in `.claude/skills/` from the **git repo root**. Run these commands in the correct location.

```bash
# Install in current project (run from git repo root)
mkdir -p .claude/skills
git clone https://github.com/waynefu2020/influencer-marketing-skill .claude/skills/红人营销

# Or install globally (available in all projects)
git clone https://github.com/waynefu2020/influencer-marketing-skill ~/.claude/skills/红人营销
```

---

## Usage

In Claude Code, type:

```
/红人营销
```

Describe your question or task, and the Skill will identify the scenario and provide actionable advice.

### Supported Scenarios

| Scenario | Description | Can Generate |
|----------|-------------|-------------|
| Competitor Analysis | Select competitors, analyze products, creators, content | Analysis framework |
| Marketing Strategy | Goal breakdown, phased planning, KOL/KOC mix | Campaign plan |
| Brief Writing | Structure, best practices, dos and don'ts | Brief document |
| Outreach | Cold emails, follow-ups, reply rate optimization | Bilingual emails |
| Influencer Selection | Tools, data evaluation, quality assessment | — |
| Negotiation | Rate evaluation, bargaining tactics, contracts | Negotiation scripts |
| Data Analysis | AARRR funnel, performance analysis, optimization | Review report |
| Budget Planning | CPM-based projection, phased allocation | Annual/quarterly plan |
| Career Growth | Company selection, skill model, promotion paths | — |

---

## Examples

**Scenario 1: Getting Started**

```
User                      ❯ Just started this job, boss wants me to reach out to creators,
                            where do I begin?

influencer-marketing.skill ❯ Don't blast emails yet. Figure out 3 things first:

                             1. Who's your target customer?
                             2. What creators and content formats are competitors using?
                             3. What's your budget? Gifting only or paid?

                             Spend half a day on a quick competitor analysis:
                             Search competitor names on TikTok, find their top 5 videos,
                             check creator follower counts and content formats.
                             That'll tell you what kind of creators to target.

                             Tool tip: Install the Wednesday Chrome extension (free).
                             It shows creator stats right on the TikTok page.
```

**Scenario 2: Budget Planning**

```
User                      ❯ Boss gave me $50K for one quarter, how should I split it?

influencer-marketing.skill ❯ $50,000 for one quarter, split into 3 phases:

                             Month 1 (Testing) — $10,000
                               80% KOCs, test messaging and content templates
                               Goal: Find 3-5 promising content directions

                             Month 2 (Scaling hits) — $18,000
                               Increase mid-tier KOLs to 40%, replicate winning templates
                               Goal: Create 1-2 viral hits (100K+ views)

                             Month 3 (Amplification) — $22,000
                               KOLs at 60%, maximize exposure
                               Goal: Measurable brand search volume growth

                             Creator fees: 80% ($40K), Paid amplification: 20% ($10K)
                             — boost content that's already performing organically.
```

---

## Knowledge Base

The Skill contains 6 knowledge modules built on 5 years of hands-on experience:

| Module | Key Topics |
|--------|-----------|
| **Competitor Analysis** | 3 methods to select competitors, USP mining, creator matrix, AI-assisted research |
| **Marketing Strategy** | CPM-based budgeting, 3-phase planning, KOL/KOC mix, content horse-racing |
| **Creator Collaboration** | 4-step outreach, email templates, selection SOP, 5 negotiation tactics, contracts |
| **Content Strategy** | Brief writing, format selection, co-creation principles, review workflow |
| **Data Analysis** | AARRR funnel, effectiveness metrics, anomaly diagnosis, review templates |
| **Budget Planning** | Annual budget structure (60/80/20 rule), platform allocation, phased distribution |

### Built-in Templates

| Template | Purpose |
|----------|---------|
| Brief Template | Content collaboration requirements for creators |
| Outreach Email Templates | First contact, gifting, paid collab, follow-up |
| Budget Plan Template | Annual/quarterly budget breakdown |
| Competitor Analysis Framework | Competitor info, creator matrix, content strategy tables |

---

## Project Structure

```
influencer-marketing-skill/
├── SKILL.md                          # Skill entry point
├── knowledge/                        # Knowledge base
│   ├── 01_competitor.md              #   Competitor analysis
│   ├── 02_strategy.md                #   Marketing strategy
│   ├── 03_brief.md                   #   Brief writing
│   ├── 04_outreach.md                #   Outreach & emails
│   ├── 05_influencer_selection.md    #   Influencer selection
│   ├── 06_negotiation.md             #   Negotiation & pricing
│   ├── 07_data_analysis.md           #   Data analysis & review
│   ├── 08_budget.md                  #   Budget planning
│   └── 09_career.md                  #   Career development
├── templates/                        # Output templates
│   ├── brief_template.md             #   Brief template
│   ├── outreach_email.md             #   Outreach email templates
│   ├── budget_plan.md                #   Budget plan template
│   └── competitor_analysis.md        #   Competitor analysis framework
├── README.md                         # 中文文档
├── README_EN.md                      # English docs
└── LICENSE
```

---

## Who Is This For

- **Entry-level influencer marketing specialists** — get up to speed fast, avoid common mistakes
- **Experienced practitioners** — fill knowledge gaps, refine methodology
- **Marketing managers** — strategy planning, budget framework reference
- **Cross-border e-commerce / App teams going global** — end-to-end influencer marketing guidance

---

## Notes

- Knowledge base is built on hands-on experience across TikTok, Instagram, and YouTube
- Pricing data is industry reference ranges — actual rates vary by category, region, and individual creators
- For questions outside the knowledge base, the Skill will reason from experience and clearly label it as "inference"
- When generating deliverables, it will proactively confirm key details — no made-up data

---

### Final Words

> "The core of influencer marketing isn't the 'influencer' — it's the 'marketing'. Consumers engage with your content first, then develop affinity for your product, and only then do they buy."

AI can handle outreach scripts, but the real test is your understanding of the consumer and the product's value proposition.

This Skill can't replace your judgment, but it can help you build a complete methodology faster and avoid the detours.

**Here's to everyone finding their viral hit on the road to going global!**

MIT License © [waynefu2020](https://github.com/waynefu2020)
