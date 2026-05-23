# E-commerce QA Audit Test Plan

## Scope

Manual QA audit of a public demo e-commerce flow from homepage through product discovery, cart, signup/login entry points, checkout validation, payment-form behavior using demo/test data only, and confirmation or blocked-step messaging.

## Out Of Scope

- Real purchases
- Real payment cards
- Private account data
- Admin dashboards
- Backend database validation
- Automated test scripts
- Security penetration testing
- Performance/load testing

## Risks

- Users may abandon checkout if validation messages are unclear.
- Cart totals may create trust issues if they do not update clearly.
- Signup or login friction may block checkout completion.
- Mobile layout issues may hide important actions or error messages.
- Payment-form behavior may confuse users if demo/test data rules are not explained.

## Entry Criteria

- Public demo site is reachable.
- Test account or demo flow is allowed by the site.
- Browser, OS, device, and screen size are recorded.
- Screenshot folder is prepared.
- Screen recording is optional; no Loom recording was captured in the 2026-05-23 evidence run.
- Demo/test payment data rules are understood before testing payment behavior.

## Exit Criteria

- Core user flows have actual results recorded.
- Screenshots or Loom evidence are attached where available.
- Any bug reports include reproduction steps, expected result, actual result, impact, and suggested fix.
- Usability findings include impact and recommendation.
- Release-readiness summary states overall status, major risks, minor risks, and next steps.

## Test Approach

Use manual scenario-based testing. Start as a first-time user, follow the main shopping flow, record actual results, capture evidence for failures or confusing states, and summarize release risk in practical language.

## Tools

- Browser
- Browser DevTools when needed
- GitHub Markdown
- Screenshots
- Loom, if recorded
- Google Sheets or Markdown tables for test tracking

## Deliverables

- Test cases with actual results
- Bug reports
- Usability findings
- Exploratory notes
- Evidence log
- Release-readiness summary
