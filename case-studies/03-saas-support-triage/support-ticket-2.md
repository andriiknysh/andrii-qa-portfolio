# Sample Support Workflow 2: File Upload Stuck In Processing

## Customer Issue

User reports that an uploaded file appears stuck in processing.

## Clarifying Questions

- What file type and file size was uploaded?
- What time was the file uploaded?
- Does the issue happen with every file or only this one?
- Which browser, OS, and device were used?
- Did the user refresh, retry, or upload a smaller file?

## Troubleshooting Steps

1. Confirm file type, file size, upload time, browser, OS, and device.
2. Ask the user to refresh and check whether the status changes.
3. Ask whether a smaller safe test file uploads successfully.
4. Check whether any visible error message appears.
5. Escalate with upload details if processing remains stuck.

## Customer-Facing Response

I can help investigate the upload. Please share the file type, approximate file size, upload time, browser, and device used. I will use that information to check whether this looks like a temporary processing delay, file-specific issue, or product problem.

## Internal Escalation Note

File upload stuck in processing. File type: [to be added]. File size: [to be added]. Upload time: [to be added]. Browser/OS/device: [to be added]. Please check upload logs, processing queue status, timeout behavior, and file-validation errors.

## QA/Product Follow-Up

If reproducible, create test cases for supported file types, max file size, slow network behavior, processing timeout messaging, retry handling, and user-facing error messages.

## Severity/Priority Draft

- Severity: Medium
- Priority: High if users cannot complete a core workflow
