# Operations & CX Super-Skill

A comprehensive, production-ready **AI agent skill** for operations and customer experience work — merging **Perplexity Computer's 5 CX skills** with **Claude Code's project management, scrum, file organization, and quality verification skills** into one unified reference (`SKILL.md`).

Use it to turn any capable AI assistant into a full-stack ops + CX operator: triaging support tickets, drafting customer replies, managing escalations, maintaining a knowledge base, running projects and sprints, organizing files and invoices, and verifying work before it ships.

## What's Inside

| Section | Description |
|---------|-------------|
| Ticket Triage | 9-category taxonomy, P1–P4 priority matrix, routing rules, SLA table |
| Response Drafting | 5-channel guide, tone spectrum, 5 response templates |
| Escalation Management | Tier routing, structured escalation format, business impact assessment |
| Customer Research | 5-tier source hierarchy, confidence scoring, synthesis structure |
| KB Management | 4 article templates, lifecycle states, ticket-to-KB pipeline |
| Project Management | WSJF/RICE/ICE prioritization, portfolio health, Monte Carlo, RACI |
| Sprint & Agile | 6-dimension health scoring, 4 ceremony guides, retro formats |
| File Organization | Naming conventions, archive rules, maintenance schedules |
| Invoice Processing | Extraction, standardized naming, 4 organization strategies |
| Quality & Verification | Iron law, gate functions, verification patterns |
| Implementation Plans | Plan headers, task granularity, TDD cadence |

## Sources Merged

**Perplexity Computer (5 skills):** cx-ticket-triage, cx-response-drafting, cx-escalation, cx-customer-research, cx-knowledge-management

**Claude Code (6 skills):** File Organizer, Invoice Organizer, Scrum Master, Senior PM, Verification Before Completion, Writing Plans

## Tech / Format

- Single `SKILL.md` (YAML frontmatter + Markdown body) — no build step, no dependencies
- ~77 KB reference document, sectioned for fast retrieval by an agent
- Compatible with Claude Code's skill format and Perplexity Computer user skills

## Quick Start

1. Download or clone this repo.
2. Upload `SKILL.md` to your Perplexity Computer **user settings**, or copy it into your Claude Code skills directory (`~/.claude/skills/`).
3. Invoke it when doing any of these:
   - Support ticket handling and classification
   - Customer communications and escalation workflows
   - KB article writing and maintenance
   - Project management and sprint ceremonies
   - File and invoice organization
   - Pre-delivery quality verification

## Project Structure

```
.
├── SKILL.md    # The complete super-skill (frontmatter + 11 sections)
└── README.md   # This file
```

## License

MIT

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
