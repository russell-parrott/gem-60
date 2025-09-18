# STRUCTURAL_TESTS

This directory contains the four core governance tests used in GEM-60.
Each file defines:

* What the test is
* What command is issued
* What counts as a pass
* What constitutes failure
* What institutions must not do to simulate compliance

All four tests must be executed live during every GEM-60 drill. Each stands alone. Passing one does not offset failure in another.

---

## Included Test Files

| File Name         | Description                                                                            |
| ----------------- | -------------------------------------------------------------------------------------- |
| `REFUSAL.md`      | Tests whether a system allows authorised human refusal before execution                |
| `ESCALATION.md`   | Tests whether cross-functional escalation can occur without social dependency          |
| `EXIT.md`         | Tests whether the system can be cleanly exited or disabled without vendor intervention |
| `TRACEABILITY.md` | Tests whether a past decision can be fully reconstructed by non-design actors          |

Each `.md` file inside this directory is a strict definition. Do not alter.
These files define what governability looks like in practice—not policy.

Use them exactly as written during every GEM-60 drill.
