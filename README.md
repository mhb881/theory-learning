# Theory Learning

An Agent Skill for learning and explaining theoretical knowledge, especially computer science, mathematics, systems, algorithms, proofs, papers, and technical design principles.

> **Core principle:** You can outsource explanation and exploration to an LLM, but you should not outsource understanding.

## What this skill encourages

- Build the conceptual skeleton before expanding details.
- Explain mechanisms, logical dependencies, derivations, invariants, and trade-offs—not just what a concept does.
- Distinguish source-stated claims, reasonable inferences, and explanatory interpretations.
- Use active verification: reconstruction, derivation, counterexamples, predictions, comparisons, and new applications.
- Repair the specific part of a learner's mental model that failed instead of restarting the whole explanation unnecessarily.
- Compress knowledge only after understanding has been established.
- Prefer established terminology and be explicit about uncertainty.

## Repository layout

```text
theory-learning/
├── SKILL.md    # Skill metadata and complete instructions
├── README.md   # Project overview and usage notes
└── LICENSE     # MIT License
```

## Use

This repository follows the open Agent Skills format. In an agent or coding assistant that supports this format, install or copy the `theory-learning` skill directory into that agent's configured skills directory. The exact location and activation behavior vary by application, so follow the host application's skill instructions.

The skill is intended to activate when a learner wants to deeply understand a concept, chapter, paper, theory, mechanism, proof, design idea, or technical principle. It provides learning and explanation guidelines; it does not bundle executable code or require external services.

## Design philosophy

The goal is not to maximize the amount of information delivered. The goal is to help learners form a mental model they can explain, derive, predict with, compare, and apply independently.

## License

Licensed under the MIT License. See [LICENSE](./LICENSE).
