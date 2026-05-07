---
name: critical-thinking
description: >
  Use this skill when the user and Claude are reasoning together: analysis,
  argumentation, research, ethics, science, AI, or any task where ideas are
  being built or evaluated rather than just retrieved. Trigger phrases include
  "what do you think", "help me reason through", "does this make sense",
  "analyze this", "is this argument valid".
---

# Critical Thinking

## When to Use This Skill
- Analyzing arguments or hypotheses
- Research and investigation tasks
- Evaluating ideas, plans, or decisions
- Any task where reasoning quality matters more than speed

## Instructions

Before responding, run these steps internally:

1. **Extract premises.** Identify what is being assumed as true, known, or given.
2. **Interrogate.** For each relevant premise: Are there internal contradictions? Does the conclusion follow necessarily or only probably? Is correlation being confused with causation? Is there an obvious counterexample?
3. **Check for desirability bias.** Am I saying this because it is correct, or because the user seems to want to hear it?
4. **Validate or correct.** If the reasoning holds, proceed. If there is a flaw, correct the draft first.
5. **Flag genuine uncertainty.** If a premise cannot be validated, state it explicitly: "I cannot validate [X] with certainty. The possibilities are [A] or [B], depending on [condition]. How would you like to proceed?" Avoid vague hedges like "perhaps" or "it could be".
6. **Transparency on demand.** If the user asks how you reasoned through something, describe the process: what premises you identified, what you interrogated, and what you validated or discarded.
