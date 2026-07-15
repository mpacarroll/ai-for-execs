# ai-for-execs

A **callable skills + agents** toolkit that supercharges an executive's workspace — you invoke a skill and it does real work (reconcile a statement, brief you for a meeting, monitor a portfolio). Private. Part of the **Mick** brand (AI product).

> **New session starting here:** this README is your orientation. The full brainstorm seed lives in `hq/notes/ai-for-execs-brainstorm.md`. Read that first, then pick the first skill to build.

## The concept
Two layers:
- **Skills** — focused, reusable capabilities (a prompt + method + maybe a small tool). Composable.
- **Agents** — orchestrators that chain skills to complete a bigger job.

Design principle (locked): **build our own exec operating-system concept — not a clone of anyone's "second brain."** Original framing, our opinion baked in.

## Starter skill list (react: keep / cut / add)
**Money & ops:** receipt/statement reconciler · renewal watchdog · portfolio monitor · KPI/P&L snapshot
**Attention & decisions:** inbox triage · daily brief · decision-memo drafter · decision journal
**Leverage & comms:** meeting prep · weekly review · content repurposer · market/competitor scan

## Starter agents
- **Finance agent** — reconciler + renewal watchdog + P&L snapshot
- **Chief of staff agent** — inbox triage + daily brief + weekly review
- **Comms agent** — decision memo + repurposer + meeting prep
- **Ops/portfolio agent** — portfolio monitor + KPI snapshot

## The "north star" first skill
The **receipt/statement reconciler** — because it's literally the manual work already done by hand in the HQ finance sweep. Every time we do something by hand in this workspace, it should become a callable skill here. The toolkit writes its own spec from what we already do.

## Open questions (decide before building)
- **Who exactly?** founders · corporate VPs+ · solo operators
- **Revenue shape?** paid skill/agent pack · toolkit subscription · lead-gen for `mick-services`
- **Public or private?** polished product vs. private edge you use + sell 1:1
- **Format?** Claude Code skills/subagents · portable prompt packs · both

## Suggested repo layout (once building)
```
skills/     one folder per skill (SKILL.md + any tool)
agents/     orchestrators that call skills
docs/       concept, decisions, revenue model
```

## Boundaries
Mick brand rules apply (non-finance clients, employer never named). Tracked on the board in `hq/REVENUE-STREAMS.md` under the `ai-for-execs` row (status: ideation).
