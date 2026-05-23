# Support Ticket: Password Reset Email Not Received

## Customer Issue

User reports they cannot reset their password because the reset email is not arriving.

## Clarifying Questions

- Which email address is on the account?
- Did the user check spam, promotions, or junk folders?
- When was the last reset request submitted?
- Does the user receive other emails from the product?
- Is the user trying from web, mobile web, or the mobile app?

## Troubleshooting Steps

1. Confirm the account email.
2. Ask the user to check spam, promotions, and junk folders.
3. Ask the user to wait a few minutes and request one new reset link.
4. Confirm whether the reset request shows as triggered in the support/admin view, if available.
5. Escalate with timestamp and email-delivery details if the message is not delivered.

## Customer-Facing Response

Thanks for the details. I can help check the password reset flow. Please confirm the email address on your account and whether you checked spam, promotions, or junk folders. If the email still does not arrive after one new reset request, I will escalate this with the delivery details.

## Internal Escalation Note

User cannot receive password reset email. Confirmed account email: [to be added]. Last reset request time: [to be added]. Please check whether the reset email was generated, whether delivery failed, and whether the email provider blocked or delayed the message.

## QA/Product Follow-Up If Reproducible

If multiple users report this issue, test the password reset flow across browsers and devices. Confirm whether success messaging is clear and whether rate limits or email-delivery failures are explained to the user.
