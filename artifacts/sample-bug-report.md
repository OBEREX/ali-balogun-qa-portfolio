# Sample defect report

**Status:** Fictional example for portfolio use only.

**Title:** Booking confirmation accepts a second submission after the first succeeds

**Environment:** Demo booking app · QA environment · desktop browser · build 0.8.2

**Severity proposal:** High — possible duplicate booking and user confusion. Product owner to confirm priority.

**Preconditions:** An available appointment is selected and valid sample customer details are entered.

**Steps to reproduce:**

1. Open the confirmation step.
2. Activate **Confirm booking** twice in quick succession.
3. Check the booking list and confirmation references.

**Expected:** One booking is created. The button disables or provides progress feedback while the request is processed.

**Actual:** Two booking records are created and two confirmation references are shown.

**Impact:** The customer may believe they have one appointment while the service has reserved two.

**Evidence:** Attach a short screen recording and test record from the fictional QA environment; no real personal data.

**Retest:** Pending. After the fix, repeat this case and verify one record is created; also run BK-004 and BK-010 as regression checks.
