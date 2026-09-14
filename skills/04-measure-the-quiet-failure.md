# Skill 4: measure the failure that looks fine

**The rule:** the number that matters is not accuracy. It is how often the system is
wrong while looking right.

## The central fact about these systems

They do not fail loudly. They fail plausibly. A crash is cheap because it is visible and
somebody fixes it the same afternoon. A confident, well-formatted, subtly wrong answer is
expensive because it flows downstream and is found a month later by an auditor, and by
then it has been trusted.

## What to actually measure

- **The confidently-wrong rate.** How often is the output incorrect with no signal of
  uncertainty? This is the only number that predicts whether the system is safe to give
  more autonomy.
- **Whether refusals are the right refusals.** A system tuned for caution often becomes
  useless rather than safe. The two look identical in a summary statistic.
- **What human reviewers actually changed.** Their edits are the specification you
  failed to write. Read them as requirements, not as noise.

## The discipline

Set the threshold for "good enough to widen" before you see the results. Deciding what
counts as success after you know the score is how programs talk themselves into
shipping things they should not.

---

*One of seven skills on adopting artificial intelligence without it quietly failing. The
full argument behind them is at
[michaelcarroll.studio/adoption](https://michaelcarroll.studio/adoption), and the one page
you can actually fill in is [the evaluation
plan](https://michaelcarroll.studio/evaluation-plan).*
