# Task 2 — Formalize Constraints

## Automated Railway Level-Crossing Control System

The following constraints are formalized using logical notation such as:

- `∧` — AND
- `∨` — OR
- `¬` — NOT
- `→` — IMPLIES / IF-THEN

---

### C1 — Train Present

**Formal Expression:**

```text
Train_Present → ¬Barrier_Open
