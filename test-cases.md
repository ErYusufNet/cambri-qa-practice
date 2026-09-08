# Test Cases and Results

Jira ticket IDs (KAN-7 to KAN-15) refer to the actual Jira board used to track this work.

---

### TC-001 (KAN-7): Verify user can create a new Data Collection study
Result: PASS. Study setup screen loaded correctly with all expected sections.

---

### TC-002 (KAN-8): Study cannot proceed without a name
Result: Not fully executed - documented as a known gap.

---

### TC-003 (KAN-9): Study name accepts standard text input
Result: PASS. Name was accepted, saved correctly, and persisted through later steps.

---

### TC-004 (KAN-10): Define audience/screening criteria
Result: Not fully executed - documented as a known gap.

---

### TC-005 (KAN-11): Zero or negative sample size is rejected
Result: Not fully executed - documented as a known gap.

---

### TC-006 (KAN-12): Save study as draft (does not consume budget)
My assumption going in was wrong: attempting Save as draft without a survey and participant count triggered validation errors on both. Draft mode still enforces mandatory fields.
Result: Documented as a finding.

---

### TC-007 (KAN-13): Complete study as test participant (happy path)
Result: PASS. Created a real 3-question survey, completed it via Preview as participant, reached the Preview complete screen.

---

### TC-008 (KAN-14): Exploratory - abandon study mid-way and resume
Result: Not fully executed - flagged as a follow-up.

---

### BUG-001 (KAN-15): Auto-scroll after selecting dropdown answer misdirects next input
See bug-reports/BUG-001.md for full details. Severity: Low-Medium.

---

## Summary

PASS: 3 (TC-001, TC-003, TC-007)
Finding (wrong assumption): 1 (TC-006)
Not fully executed: 4 (TC-002, TC-004, TC-005, TC-008)
Bugs found: 1 (BUG-001)
