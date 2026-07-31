# The callable toolkit concept (unbuilt)

_Preserved from this repository's original README, 2026-07-31, when the repo became the
home of the AI adoption skills. This is a separate and later product idea. Nothing here
has been built, and the open questions below are not open questions about the seven
published skills._

⚠️ **Two things in the original text were wrong and are corrected here.** It described the
repository as **Private** when it is and was **public**, and it assigned the work to the
**Mick Cairn** brand. The published material is **Michael Carroll's**, and a Mick label on
a public repository holding his material would create exactly the cross-identity link that
is meant to stay closed. If this toolkit is ever built and it genuinely belongs to Mick, it
needs its own repository rather than this one.

## The concept

Two layers:

- **Skills** — focused, reusable capabilities (a prompt plus a method, and maybe a small
  tool). Composable.
- **Agents** — orchestrators that chain skills to complete a bigger job.

Design principle, locked: build an original executive operating-system concept, not a
clone of anyone's second brain. Original framing, with a stated opinion.

## Starter skill list (keep / cut / add)

- **Money and ops:** receipt and statement reconciler, renewal watchdog, portfolio
  monitor, KPI and P&L snapshot
- **Attention and decisions:** inbox triage, daily brief, decision-memo drafter, decision
  journal
- **Leverage and comms:** meeting prep, weekly review, content repurposer, market and
  competitor scan

⚠️ **Firewall check before any of the money and ops line is built.** "Portfolio monitor"
and "P&L snapshot" mean the operator's own book of businesses, which is bookkeeping and
fine. If either ever means securities, markets or investment positions, it is out, and the
distinction needs to be explicit in the skill itself rather than assumed by whoever builds
it.

## Starter agents

- **Finance agent** — reconciler, renewal watchdog, P&L snapshot
- **Chief of staff agent** — inbox triage, daily brief, weekly review
- **Comms agent** — decision memo, repurposer, meeting prep
- **Ops and portfolio agent** — portfolio monitor, KPI snapshot

## The north-star first skill

The receipt and statement reconciler, because it is literally the manual work already done
by hand in the finance sweep.

**The principle underneath it is the valuable part:** every time something is done by hand
in this workspace, it should become a callable skill. The toolkit writes its own spec from
what is already being done.

## Open questions, still open

- **Who exactly?** Founders, corporate VPs and above, or solo operators.
- **Revenue shape?** A paid skill and agent pack, a toolkit subscription, or lead
  generation for `mick-services`.
- **Format?** Claude Code skills and subagents, portable prompt packs, or both.

_Resolved: the repository is public, and it carries Michael Carroll's identity._

## Suggested layout, if built

```
skills/     one folder per skill (SKILL.md plus any tool)
agents/     orchestrators that call skills
docs/       concept, decisions, revenue model
```
