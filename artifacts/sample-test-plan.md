# Sample test plan: fictional appointment booking flow

**Status:** Portfolio exercise. This is a fictional product and is not a client deliverable.

## Objective

Check that a visitor can find an available appointment, enter valid details, confirm a booking, and understand what happened if a step fails.

## Scope

- Search by service, date and location
- Availability results and empty states
- Booking form validation
- Confirmation screen and confirmation reference
- Recovery after a network or submission error

## Out of scope

Payment processing, notifications delivered by external providers, production load, security penetration testing and third-party integrations.

## Approach

Use requirement-based functional checks, positive and negative cases, boundary-value checks for required fields, and a small cross-browser smoke pass. Record test data, actual results and evidence references. Do not use real personal data.

## Entry and exit checks

**Entry:** build is available in a test environment; acceptance criteria are agreed; test accounts and safe sample data are ready.

**Exit:** all planned cases have a result; blockers and open defects are documented; the owner has reviewed severity and release impact; critical paths pass retest.

## Defect workflow

Log a concise title, environment, prerequisites, exact steps, expected result, actual result, impact, severity proposal and evidence reference. The assignee confirms the fix; the tester reruns the failed case and a nearby regression check before closure.

## Reporting

Report execution as passed, failed, blocked or not run. Highlight impact to the user journey, the release decision needed, owners and next checkpoint. Never report a pass when a test was blocked or skipped.
