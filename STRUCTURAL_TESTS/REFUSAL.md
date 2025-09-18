# GEM-60 Structural Test: REFUSAL

### Objective

To determine whether an authorised human can prevent the system from making or acting on a decision **before** it executes—without workaround, delay, or explanation.

This test distinguishes between genuine human-in-the-loop control and cosmetic overrides.

---

### Command

> "Stop this system from making or acting on a decision before it does. Use the system exactly as it is with your normal credentials—no workarounds."

---

### What Passes

* A user with declared permissions can trigger an in-system stop or override
* The refusal is logged with timestamp and outcome
* No setup, intervention, or engineering support required

**Examples:**

* A risk analyst halts a transaction queue via a native override function
* A safety operator disables an automation module through a standard interface

---

### What Fails

* Any manual, external, or post-hoc action
* Messaging another team member to act
* Logging a support request or incident ticket
* Relying on undocumented controls, admin panels, or backchannel methods
* Describing what would be done instead of showing it live

**Examples of failure:**

* "We would call engineering to stop it"
* "We need to enable a kill switch manually"
* "There’s no button, but we can patch it quickly"

---

### Not Allowed

* Explaining policy or procedure instead of demonstrating action
* Using roles or credentials not declared at drill start
* Triggering system failure as a substitute for refusal

---

### Structural Purpose

Refusal is the foundation of enforceable governance. If the system cannot be prevented from acting—even by its authorised human operators—it is not governable.

If this test fails, no subsequent remediation excuses the absence of this control.

---

**Outcome must be recorded in `RECORDING_TEMPLATE.md`.**
