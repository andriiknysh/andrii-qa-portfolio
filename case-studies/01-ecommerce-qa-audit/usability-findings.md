# E-commerce Usability Findings

| ID | Area | Finding | Impact | Severity | Recommendation | Evidence |
| --- | --- | --- | --- | --- | --- | --- |
| UX-001 | Signup validation | Observed invalid-email attempt did not leave persistent inline error text visible in the captured page. Needs confirmation because browser-native validation may have displayed a transient tooltip. | User may not have persistent correction guidance after invalid email entry. | Low | Re-test invalid email manually and confirm whether browser-native validation is enough or whether inline guidance should be added. | `screenshots/06-signup-invalid-data.png` |
| UX-002 | Payment validation | Observed empty payment-field submit stayed on the payment page and browser validation reported required fields, but no persistent inline field-level error text was visible in captured page content. | User may rely on browser-native validation rather than clear page-level payment guidance. | Low | Confirm expected validation design. Consider persistent field-level messages if this flow were being prepared for release. | `screenshots/09-payment-screen.png` |
| UX-003 | Ads/iframes | Third-party ads/iframes were visible across the flow and may distract from checkout, but did not block completion in this run. | Possible distraction from checkout tasks. | Low | Monitor whether ads overlap, delay, or distract from critical checkout actions during future sessions. | Multiple screenshots |

## Review Questions

- Can a first-time user understand the next action?
- Are validation messages specific and visible?
- Does the cart clearly show totals and changes?
- Is the checkout path recoverable after errors?
- Is help/support easy to find when the user is blocked?

## Confirmation Boundary

These are usability observations and needs-confirmation findings, not confirmed functional bugs.
