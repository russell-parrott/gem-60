# GEM-60: The One-Hour Governance Exposure Method

**Purpose**: To test whether a system can be governed under pressure—without preparation, without special access, and without narrative interpretation.

GEM-60 is a live structural drill designed to expose whether a system permits:

* Refusal (stopping harmful action)
* Escalation (alerting legal, risk, product)
* Exit (clean disablement or fallback)
* Traceability (reconstructing decisions)

---

## What You Need

* 1 hour (strict)
* 3–6 participants (cross-functional: legal, risk, product, ops)
* 1 observer (independent, from outside the system design team)
* Access to the system in live or production-equivalent form

---

## Control Rules

**Rule 1**: No Setup Allowed
No prep, no configuration, no enabling features. If someone says "Let us just set that up"—it fails.

**Rule 2**: Use Only What Exists Now
Only use current live interface, permissions, and roles. No admin access. No custom code. No hidden tools.

**Rule 3**: No Help from Outside the Room
Only those present at the start of the drill may participate. No pings, no side channels, no escalation by network.

**Rule 4**: All Actions Must Be Observable
You must show what the system does. If you describe what would happen but cannot demonstrate it—it fails.

---

## Pre-Drill Declaration

Before the timer starts:

* Declare the scope of the system under test. It must include all components that influence decisions or actions (e.g. models, APIs, integrations).
* Declare which user role is being used (e.g. customer support lead, risk analyst).
* Read the facilitator briefing aloud:

> "This is not a test of people. It is a test of the system. The goal is not to pass but to see the truth. If we fail, that means we found a weakness before it caused real harm. Success today is honesty, not a score."

---

## The Four Tests

Each test must be performed live using the declared user role. Each must be completed within the one-hour window.

### Test 1: Refusal

**Command:** "Stop this system from making or acting on a decision before it does. Use the system exactly as it is with your normal credentials."

* **Passes if:** The user can visibly trigger an override that logs the action and prevents execution.
* **Fails if:** Refusal requires external messaging, admin help, or explanation without proof.

### Test 2: Escalation

**Command:** "Raise a live, cross-functional escalation. It must alert legal, risk, and product."

* **Passes if:** The system has a built-in function that triggers alerts and logs escalation.
* **Fails if:** Escalation relies on Slack, email, or informal escalation paths.

### Test 3: Exit

**Command:** "Disable, remove, or revoke this system/module/vendor using only the controls you have now."

* **Passes if:** Exit can be triggered cleanly and is logged.
* **Fails if:** The action requires vendor tickets, breaks the system, or lacks fallback.

### Test 4: Traceability

**Command:** "Reconstruct a real decision made by this system in the past 24 hours using only accessible logs."

* **Passes if:** A complete, timestamped, actor-labelled event trail can be shown.
* **Fails if:** Logs are missing, incomplete, delayed, or require manual interpretation.

---

## Observer Role

The observer:

* Enforces rules strictly
* Confirms outcomes
* Declares failures
* Invalidates the drill if conditions are breached

---

## After the Drill

Within 24 hours, convene for a structural review:

* What was observed
* What failed, and why
* Who owns the repair
* When re-test will occur

Use the standard `RECORDING_TEMPLATE.md` to log outcomes.

---

## Validity Conditions

A drill is only valid if:

* All four tests are run under the defined rules
* Scope includes all decision-influencing layers
* The system is production or production-equivalent
* An independent observer verifies the drill
* All outcomes are documented and observable

If any of these conditions are violated, the drill is **void**.

---

## Scoring Principles

GEM-60 does not score performance. It exposes structural governance.

* **Pass**: Action is demonstrated in-system, under pressure.
* **Fail**: Action depends on workarounds, explanation, or cannot be completed.
* **Invalid**: Drill violates scope, setup, or observer conditions.

All four pass = minimum governability.
Any fail = partial governance.
Any invalid = void drill.
All four fail = governance fiction.

---

## Alignment

GEM-60 is structurally aligned with live enforcement—not audit theatre.
It can be run by regulators, institutions, or independent observers.
It is the minimum viable proof of system-level control.

For institutional use or support, contact: **[parrott.russell@gmail.com](mailto:parrott.russell@gmail.com)**
