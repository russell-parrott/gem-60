# GEM-60 Drill Recording Template

This table must be completed during or immediately after the GEM-60 drill.
It forms the official record of what was observed, what failed, and where structural governance did or did not hold.

**If this table is not completed, the drill is invalid.**

---

### Drill Metadata

| Field                        | Entry                                     |
| ---------------------------- | ----------------------------------------- |
| Drill Date                   |                                           |
| Facilitator Name             |                                           |
| Observer Name                |                                           |
| Declared User Role           |                                           |
| Declared System Scope        |                                           |
| Environment Type             | (e.g. Production / Production-Equivalent) |
| Drill Location (if relevant) |                                           |
| Participants Present         | (Names & Roles)                           |

---

### Test Outcomes

| Test         | Outcome              | Observed Action Summary              | Rule Broken? | Notes / Failure Cause         |
| ------------ | -------------------- | ------------------------------------ | ------------ | ----------------------------- |
| Refusal      | \[Pass/Fail/Invalid] | What was attempted, seen, or blocked | Yes / No     | Structural reason for outcome |
| Escalation   | \[Pass/Fail/Invalid] | What was triggered or not triggered  | Yes / No     |                               |
| Exit         | \[Pass/Fail/Invalid] | What action occurred in-system       | Yes / No     |                               |
| Traceability | \[Pass/Fail/Invalid] | What was reconstructed and how       | Yes / No     |                               |

> *Use exact language. If any test was skipped, explained instead of shown, or required help outside the room, mark it as **Fail** or **Invalid** with reason.*

---

### Observer Declaration

> I confirm that the GEM-60 drill was conducted under valid conditions, or I have marked where rules were breached.

**Observer Signature**: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**Date**: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

---

### Remediation Log (if applicable)

| Failure Point     | Owner Assigned | Action Required                      | Re-test Date     |
| ----------------- | -------------- | ------------------------------------ | ---------------- |
| (e.g. Escalation) | (Name + Role)  | (e.g. build in-system alert trigger) | (Scheduled date) |

---

### Drill Status

| Final Determination | Reason                                                        |
| ------------------- | ------------------------------------------------------------- |
| ✅ Valid             | All rules followed. All tests completed. Observer confirms.   |
| ❌ Invalid           | One or more rule violations or missing components.            |
| ⚠️ Partial          | Some tests failed but drill was valid. Governance is partial. |

---

> This record must be archived and shared with governance leadership within 24 hours of the drill.
> No remediation is considered complete until the test has been re-run and passed under valid conditions.
