# DevTools/API Troubleshooting Investigation Plan

## Scope

Investigate a visible web issue using browser DevTools and document what can be observed from the browser side.

## Out Of Scope

- Source-code changes
- Backend access
- Database access
- Credential handling
- Private user data
- Security testing
- Load testing

## Investigation Steps

1. Record tested URL/app name, date, browser, OS, device, and screen size.
2. Reproduce the user-visible issue.
3. Open browser DevTools.
4. Check the Console tab for errors or warnings.
5. Check the Network tab for failed requests, slow requests, status codes, and response timing.
6. Record reproduction steps.
7. Record what was checked and what was ruled out.
8. Write an escalation report with evidence and next suggested owner.

## Questions To Answer

- What user action triggers the issue?
- Does the issue reproduce consistently?
- Are there visible console errors?
- Are any network requests failing?
- What HTTP status codes appear?
- Is timing unusually slow?
- Does the error message help the user recover?
- What information should be escalated?
