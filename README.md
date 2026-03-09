# 💰 /revenue — Revenue Advisor for Claude

**Stop guessing where revenue is hiding. Let Claude find it.**

`/revenue` is an AI-powered revenue diagnostics command that reads your entire business context — notes, docs, emails, calendar, meeting transcripts — and surfaces exactly where you're leaving money on the table.

It doesn't just list ideas. It diagnoses your revenue **system**, finds what's broken, and tells you what to build this week.

---

## What It Does

The `/revenue` command runs a 9-step revenue analysis:

1. **Deep Context Scan** — Reads your Obsidian vault, Google Docs, Calendar, Gmail, Granola meeting notes, and Notion to build a complete picture of your business
2. **Asset Inventory** — Maps your demonstrated skills, relationships, IP, audience, and credibility signals
3. **Revenue Diagnostics** — Diagnoses your attention-to-revenue conversion, revenue type mix, sales system, pricing structure, and product vs. service ratio
4. **Beyond the Vault** — Identifies blind spots, market context, packaging gaps, and positioning problems you can't see from inside your own perspective
5. **Revenue Opportunities** — Surfaces services to sell, products to build, low-hanging fruit, and undermonetized assets — with specific dollar amounts
6. **Temporal Tracking** — Compares against previous runs to track what's working and prevent redundant suggestions
7. **Anti-Pattern Filtering** — Blocks generic advice (no "start a newsletter"), respects your constraints, and refuses to sugarcoat
8. **Prioritization** — Ranks the top 5 opportunities by effort-to-revenue ratio, identifies the immediate play, the biggest upside, and the structural fix
9. **Actionable Builds** — Ends with specific documents and tools Claude can build immediately: pitch decks, pricing pages, outreach templates, service offerings

---

## Usage

```
/revenue              # Full revenue analysis
/revenue [domain]     # Focused on a specific area (e.g., /revenue consulting)
```

---

## Supported Data Sources

| Source | What It Reads |
|--------|--------------|
| **Obsidian** | Daily notes, projects, tags, backlinks, orphaned ideas |
| **Google Docs** | Business plans, proposals, strategy docs, pricing docs |
| **Google Calendar** | Client meetings, sales calls, time allocation patterns |
| **Gmail** | Deal flow, invoices, proposals, inbound opportunities |
| **Granola** | Meeting transcripts, decisions, action items |
| **Notion** | Pipelines, trackers, dashboards, SOPs, business databases |

---

## Installation

### Claude Code (Slash Command)
```bash
# From your project root
mkdir -p .claude/commands
cp revenue.md .claude/commands/revenue.md
```

Then run `/revenue` inside Claude Code.

### Claude Cowork
Paste the `revenue.md` content as a skill or reference it directly in conversation.

### Any Claude-Powered Environment
Use `revenue.md` as a system prompt or instruction set.

---

## What Makes This Different

Most "revenue advice" from AI is generic. `/revenue` is not.

- **Evidence-based** — Every suggestion cites data from your actual business context
- **System-first** — Diagnoses WHY revenue isn't flowing before suggesting WHAT to sell
- **Honest** — If your pricing is wrong or your sales system doesn't exist, it says so
- **Specific** — No "significant revenue potential." Instead: "$5K-10K/month from packaging your sprint methodology as a licensed framework"
- **Actionable** — Ends every run with artifacts Claude can build on the spot

---

## Example Output

After scanning your context, `/revenue` delivers:

**The Immediate Play** — One thing to do this week with a specific first step

**The Biggest Upside** — The opportunity with the highest ceiling and why evidence supports it

**The Surprising One** — The non-obvious opportunity most people (and most AIs) would miss

**The Structural Fix** — The one change to how revenue works that impacts all future revenue

**Actionable Builds** — "I can build this now": service offerings docs, pitch decks, pricing pages, outreach templates

---

## Credits

Inspired by [internetVin's Obsidian Commands](https://internetvin.com/Obsidian+Commands). Adapted and extended with multi-source data integration for real-world business use.

---

## Built by Strategy Sprints

[Strategy Sprints](https://strategysprints.com) helps entrepreneurs accelerate sales in 90-day sprints. Founded by **Simon Severino**, the methodology has been used by thousands of founders to build predictable revenue systems.

📘 **Book:** [Strategy Sprints](https://strategysprints.com/book) — The framework behind the method

🎙️ **Podcast:** [Strategy Sprints Podcast](https://strategysprints.com/podcast) — Weekly conversations on sales acceleration

💼 **LinkedIn:** [Simon Severino](https://www.linkedin.com/in/simonseverino/)

🐦 **X:** [@simonseverino](https://x.com/simonseverino)

📺 **YouTube:** [Strategy Sprints](https://www.youtube.com/@strategysprints)

---

### More Claude Skills by Strategy Sprints

- [**ClaudeSkills-SprintClub**](https://github.com/SimonTheSalesBooster/ClaudeSkills-SprintClub) — 18 sales skills for prospecting, closing, and enterprise deals
- [**Leverage**](https://github.com/SimonTheSalesBooster/leverage) — Find the 3-7 moves that change your trajectory by 10x-100x

---

*The best revenue system is one that sees what you can't see from inside your own perspective. Let Claude be that outside eye.*
