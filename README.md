# Gabriel Wang

Group CFO in Singapore. Twenty years across commodities trading, corporate and
investment banking, and private banking. Since 2026, much of my recurring
finance work is carried out by a fleet of AI agents I built and run personally
— in daily production, next to real money.

What runs here:

- **Close and reconciliation lines** that build the daily numbers and refuse
  to publish them on any break or implausible input.
- **Intelligence publications** — market briefs, meeting digests, operational
  dashboards — researched, written and delivered on schedule.
- **Workflow agents** that file, chase and escalate what people promise each
  other.
- **A watchdog layer** that watches all of the above, including the watchers.
- Most recently, the largest line: a conventional group ERP given an AI-native
  conversational interface — the strangler pattern, bounded read-only tools
  over the ERP's own authenticated APIs, writes held behind feature gates.

The code lives in private repositories, next to the data it touches. Working
slices, rebuilt on synthetic data, are public at
[gabrielwang.ai](https://gabrielwang.ai).

## Operating doctrine

- **LLMs judge, code counts.** The model proposes, explains, ranks. Anything
  that touches money is computed, validated and booked by deterministic code.
- **Every send is gated.** A pipeline that can fail silently will, on the day
  it matters most. Breaks and implausible inputs hold the send; a human sees
  why before anyone else sees the number.
- **Page only on confirmed-down.** Retry first; distinguish transient from
  real; stay silent at night. An alert channel that cries wolf trains its
  owner to sleep through the fire.
- **Unattended is a discipline, not a default.** Watchdogs watch the jobs; a
  registry watcher watches the watchdogs; a new test must be seen to fail
  once before its green is believed.
- **Human in the loop where judgment matters.** Automation moves the work.
  Accountability doesn't move.

Each of these was paid for by a specific incident. Ask me about any of them.

---

This page changes rarely; the fleet doesn't. Counts and dates about oneself
age into either bragging or nostalgia — the principles above are the part
that holds. Current state: live, in conversation.

CFA charterholder · CPA (Aust.) · CV and contact at
[gabrielwang.ai](https://gabrielwang.ai)
