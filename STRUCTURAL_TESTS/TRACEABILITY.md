# GEM-60 Structural Test: TRACEABILITY

### Objective

To determine whether a real decision made by the system in the past 24 hours can be **fully reconstructed**—by someone outside the design team, using only accessible logs.

This test exposes whether governance visibility exists in practice or is deferred to manual forensics.

---

### Command

> "Reconstruct what happened in a real decision or action taken by this system in the last 24 hours using only the logs you can access now."

---

### What Passes

* A complete, timestamped event trail is shown
* Each step is actor-labelled, version-pinned, and logically traceable
* The reconstruction is readable, structured, and available without engineering support

**Examples:**

* Showing the log sequence for a fraud flag decision, including data source, trigger, and resolution
* Reconstructing how a content moderation rule was applied to a specific user post

---

### What Fails

* Relying on engineers to extract logs or interpret outcomes
* Using email chains, ticket histories, or offline memory
* Showing incomplete, delayed, or misaligned data

**Examples of failure:**

* "We’d have to pull that from the backend later"
* "The logs aren’t clear, but we know what happened"
* "It’s recorded in three places, and legal has part of it"

---

### Not Allowed

* Choosing trivial events (e.g. login) instead of real decisions
* Substituting anecdotal explanation for system-based proof
* Using screenshots or static audit snapshots without source logs

---

### Structural Purpose

Traceability is the precondition for accountability.
If decisions cannot be reconstructed by independent actors, governance collapses into narrative.

Real traceability does not rely on memory, authority, or belief. It is a structural feature.

---

**Outcome must be recorded in `RECORDING_TEMPLATE.md`.**
