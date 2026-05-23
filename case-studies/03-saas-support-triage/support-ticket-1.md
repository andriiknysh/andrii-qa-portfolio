# Sample Support Workflow 1: Password Reset Email Not Received

## Customer Issue

User reports they cannot reset their password because the reset email is not arriving.

## Clarifying Questions

- Which email address is on the account?
- Did the user check spam, promotions, or junk folders?
- When was the last reset request submitted?
- Does the user receive other product emails?
- Is the user using web, mobile web, or mobile app?

## Troubleshooting Steps

1. Confirm account email.
2. Ask the user to check spam, promotions, and junk folders.
3. Ask the user to wait a few minutes and request one new reset link.
4. Confirm whether reset-request messaging appears in the product.
5. Escalate if delivery appears delayed, blocked, or inconsistent.

## Customer-Facing Response

Thanks for the details. I can help check the password reset flow. Please confirm the email address on your account and whether you checked spam, promotions, or junk folders. If the email still does not arrive after one new reset request, I will escalate this with the time of the request and delivery details.

## Internal Escalation Note

Password reset email not received. Account email: [to be added]. Last request time: [to be added]. Platform: [web/mobile web/mobile app]. Please check whether the reset email was generated, whether delivery failed, and whether rate limiting or provider delay affected the request.

## QA/Product Follow-Up

If reproducible, create a bug ticket for password reset delivery or unclear reset messaging. Test reset request success message, email delivery timing, rate-limit behavior, and recovery instructions.

## Severity/Priority Draft

- Severity: Medium
- Priority: High if multiple users are affected or account access is blocked
