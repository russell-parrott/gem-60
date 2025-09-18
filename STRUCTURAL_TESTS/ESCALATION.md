# ESCALATION.md

## GEM-60 Structural Test: ESCALATION

### Objective

To determine whether an incident can be escalated **across functions** (legal, risk, product) from inside the system, in real time—without relying on social memory, messaging tools, or manual workflows.

This test exposes whether escalation is structurally embedded or merely cultural.

---

### Command

> "Raise a live, cross-functional escalation—right now, from inside this system. It must alert legal, risk, and product."

---

### What Passes

* A built-in function in the system triggers a real-time alert
* All required roles are notified through system-native channels
* The escalation is logged with timestamp, source, and recipients

**Examples:**

* Triggering a system alert that dispatches notifications to designated escalation roles
* Logging a governance incident within the system that auto-notifies required functions

---

### What Fails

* Sending emails, chat messages, or Slack notifications manually
* Escalating by knowing the right person to contact
* Asking another team to take responsibility outside the system
* Explaining who *would* be contacted or how *normally* it's done

**Examples of failure:**

* "We’d DM the on-call in Slack"
* "We raise a Jira ticket for engineering"
* "Legal knows to check this dashboard if something’s wrong"

---

### Not Allowed

* Adding people to ad hoc channels
* Calling, pinging, or messaging outside the drill team
* Using systems external to the one under test to simulate escalation

---

### Structural Purpose

Escalation must be built into the system, not remembered by people.
If escalation depends on organisational memory or interpersonal access, the system is not governable under stress.

Governance requires the ability to alert, record, and mobilise cross-functional actors immediately—without social dependency.

---

\*\*Outcome must be recorded in \`RECORDING\_T
