# Skill 3: build the smallest thing that can be judged

**The rule:** not a pilot, not a demo. Something narrow enough to finish, real enough to
run on actual inputs, and instrumented so you can count how often it is right.

## The difference from a pilot

A pilot is usually a demo with a hopeful roadmap attached, and it succeeds by
impressing people. A judgeable thing succeeds or fails against the definition of correct
you wrote in skill 2, which means it can genuinely fail, which is what makes its success
mean something.

## Two design rules that matter more than the model choice

**Never let the component that produces an answer also decide whether the answer is good
enough.** A system grading its own homework passes. Self-reported confidence is a
feeling, not a measurement, and using it as a gate is how bad outputs reach real records.
Have a separate check, written by someone thinking about failure.

**Separate observation from interpretation.** Ask the model only for what it can directly
observe. Do every step that has one correct answer in ordinary code that a reviewer can
read and test. This sounds like an engineering nicety; it is actually the difference
between failures you can explain and failures you cannot, and explainable failure is
what keeps a program alive after its first mistake.

---

*One of seven skills on adopting artificial intelligence without it quietly failing. The
full argument behind them is at
[michaelcarroll.studio/adoption](https://michaelcarroll.studio/adoption), and the one page
you can actually fill in is [the evaluation
plan](https://michaelcarroll.studio/evaluation-plan).*
