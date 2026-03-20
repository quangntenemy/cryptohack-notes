## Log

Working through multiple challenges reveals a pattern:

The system rarely fails at the point of implementation.
It fails at the level of assumption.

Need to get faster at identifying the assumption before touching the mechanics.

---
Session 07

Noticed a recurring failure mode:
Systems that aim to “hide” data often preserve enough structure
to allow partial reconstruction.

Still too slow at spotting this early.

---
Session 08

Noticed how easily strong guarantees collapse
when implementation details override design assumptions.

The system didn’t fail at the conceptual level —
it failed at the boundary between intention and code.
