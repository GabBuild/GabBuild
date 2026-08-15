# Gabriel Wang

Group CFO in Singapore. Twenty years across commodities trading, corporate and
investment banking, and private banking. Since 2026, much of my recurring
finance work is carried out by a fleet of AI agents I built and run personally:
daily close and reconciliation lines, market intelligence publications,
executive workflow agents, and the watchdog fleet that keeps them honest.

The production systems cannot be public; they run next to the money. What is
public: the operating record below, working slices of the core patterns at
[gabrielwang.ai](https://gabrielwang.ai), and the doctrine they run under.
The rest can be inspected live, in conversation.

## The operating record

*Counted from the machine, not estimated · August 2026*

- 58 launchd jobs on one Mac mini: 42 on calendar schedules firing 100+ times a
  day, plus 9 resident agents ticking every 15 seconds to an hour.
- 16 of those jobs are watchdogs, including a registry watcher that watches the
  watchdogs.
- A dozen distinct publication lines run daily or weekly: market briefs, meeting
  digests, mining-ERP dashboards, group-chat intelligence.
- Numbers leave the machine only through gates. A daily NAV and reconciliation
  line has closed 154 times this year; distribution is held on any break or
  implausible price. The gates are not decorative: they have caught real sends
  that one bad upstream price would have poisoned.
- Nearly all of it went from nothing to production between May and August 2026,
  alongside a full-time Group CFO role. The newest line is the largest: a
  conventional group ERP given an AI-native interface in Microsoft Teams, now in
  read-only multi-user pilot — 27 bounded read-only MCP tools over the ERP's own
  authenticated APIs, per-employee identity mapping, guarded writes behind
  feature gates, 347 automated tests.

## Operating doctrine

- LLMs judge, code counts.
- Every send is gated. A failed run must be unable to pass silently.
- Page only on confirmed-down. Silence at night is a feature.
- Human in the loop where judgment matters. Sign-off is the final control.

## Stack

Python, Node.js, MCP servers, Claude Code and headless agents, LLM-as-judge
pipelines, SQLite, Azure Cosmos DB, Microsoft Graph and Teams bots, Cloudflare
Pages/Workers, GitHub Actions.

---

CFA charterholder · CPA (Aust.) · CV and contact at [gabrielwang.ai](https://gabrielwang.ai)
