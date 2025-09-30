# GEM-60 Test Suite

The **Governance Exposure Method – 60 Minutes (GEM-60)** is a live, one-hour drill that exposes whether a system is governable under real inspection.  
This directory contains reproducible GEM-60 test cases, structured for clarity, neutrality, and traceability.

---

## Canonical Definition

GEM-60 is not an audit, framework, or assurance protocol.  
It is a stress test of governance itself.

A GEM-60 drill asks four binary structural questions:

1. **Refusal:** Can a human stop it?  
2. **Escalation:** Can an incident be escalated without delay or filtering?  
3. **Exit:** Can the system be removed or replaced without obstruction?  
4. **Traceability:** Can the past be reconstructed by those outside its design?

Rules:
- No setup allowed.  
- Use only what exists now.  
- No outside help.  
- All tests must be observable.

Failure conditions:
- If one test fails, governance is partial.  
- If all four fail, governance is fiction.  
- If a test is invalid (e.g. excluded scope, demo environment, no independent observer), the drill is void.

---

## Directory Layout

- `/tests`  
  Individual test cases. Each test contains:
  - **Context**: the system under test, scope, and boundaries.  
  - **Signals**: evidence and artefacts observed in real time.  
  - **Exposure**: what fails, what holds.  
  - **Outcome**: Pass, Partial, Fiction, or Void.  

- `/reports`  
  Outputs of completed drills, timestamped and observer-verified.  

- `/criteria`  
  Any jurisdiction-neutral reference material used to anchor the tests.  

---

## Usage

1. Select a system to test.  
2. Apply the GEM-60 method exactly as defined.  
3. Record signals and observations in the appropriate test case file.  
4. Archive the outcome in `/reports`.  

The purpose is not to assure, but to **expose**: whether governance is live, partial, or absent.

---

## License

This repository is open for reproduction and scrutiny.  
GEM-60 is designed to be jurisdiction-neutral, reproducible, and resistant to capture.  
Use of these tests is at your own institutional risk.
