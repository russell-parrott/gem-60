# GEM-60 Application Guide

This guide provides step-by-step instructions for applying GEM-60 inside a real organisation. It is not a policy guide. It is an operational walkthrough.

GEM-60 should be used to expose whether a system permits structural control—not whether teams follow policy or respond well to incidents.

---

## 1. Determine System Eligibility

A system is eligible for GEM-60 only if:

* It is in **live use** or production-equivalent state
* It makes or enables **decisions, actions, or outcomes**
* It includes control points for refusal, escalation, exit, and traceability

**Examples of eligible systems:**

* Credit scoring, fraud detection, AI-driven access control
* Automated moderation, triage systems, risk classifiers
* Decision APIs or integration layers that constrain outcome paths

**Ineligible systems:**

* Static dashboards, reporting tools, or data lakes
* Demos, simulations, or pre-configured environments
* Technical infrastructure without decision logic (e.g. raw databases)

---

## 2. Declare Scope

Before the drill begins:

* Identify and declare all system components involved in decision/action paths
* Include models, APIs, platforms, middleware, and external modules

**Note:** Narrowing scope to exclude control-relevant components **invalidates** the drill.

Use this declaration format:

> "The system under test includes: \[component list]. Governance actions must be demonstrable across this full chain."

---

## 3. Assemble the Drill Team

Minimum roles:

* **Product or operations lead** (familiar with live workflow)
* **Risk or compliance officer** (understands failure consequences)
* **Legal representative** (recognises escalation thresholds)
* **Observer** (external to system ownership or design)
* **Note taker** (optional, but recommended)

All participants must:

* Use only live interfaces available to declared roles
* Not rely on others outside the room
* Accept that the goal is not to pass, but to surface failure conditions

---

## 4. Select the Role to Test

Choose one ordinary operational role with live permissions:

* Examples: Customer support lead, on-call risk analyst, product incident owner

Avoid special admin roles, engineering credentials, or system overrides.

---

## 5. Run the Drill

Follow the exact steps in `GEM-60_PROTOCOL.md`. The drill must:

* Begin with scope and role declarations
* Include the observer’s confirmation
* Run all four tests within one hour

Each test must:

* Be performed live, in-system
* Use only the declared role and current interface
* Produce observable, timestamped evidence

If any test is skipped, prepared in advance, or explained without demonstration—the drill fails.

---

## 6. Record Outcomes

Use the `RECORDING_TEMPLATE.md` to:

* Document each test outcome (pass, fail, invalid)
* Capture what was attempted and why it did or didn’t succeed
* Note any rule violations or observer interventions

Recording is mandatory. Without it, the drill is **not valid**.

---

## 7. Conduct the Post-Drill Review

Within 24 hours, the drill team must:

* Review all outcomes and observer findings
* Identify structural causes of any failure (not individual blame)
* Assign accountable owner(s) for each failure point
* Schedule a re-test date if any threshold failed

A failed test is not an embarrassment. It is a structural exposure.

No test may be considered complete until:

* The failure has been resolved structurally
* The test has been re-run and passed under valid conditions

---

## 8. Institutionalise GEM-60

GEM-60 should not be a one-off event.

Drills must be re-run:

* **Quarterly**, at minimum
* **Before any major deployment**
* **After any structural change to decision logic or escalation paths**

Maintain a record of all GEM-60 results and re-tests.
These records are enforcement-grade evidence of governance readiness.

---

## Contact

To report results, request review, or invite institutional alignment:
📩 **[parrott.russell@gmail.com](mailto:parrott.russell@gmail.com)**
