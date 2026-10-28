# Troubleshooting FAQ — Fictional Recruitment CRM

> These are illustrative support patterns, not verified instructions for Recruit CRM. Product menus and available options may differ; confirm with current product documentation before giving customer-specific directions.

## A user cannot sign in
- Confirm the account/workspace and login email without asking for the password.
- Ask whether the user recently reset their password or uses single sign-on.
- Have them use the official password-reset flow and check link expiry.
- If multiple users are affected or there are signs of compromise, escalate through the approved security process.

## Imported candidates do not appear
- Check that the import completed and note success/skipped/failed counts.
- Clear search filters and confirm workspace, candidate status, and visibility permissions.
- Search by a unique test field and confirm the import mapped the expected columns.
- Do not request real candidate data in an unapproved channel.

## CSV import shows validation errors
- Use the current approved template and exact required column names.
- Check date format, empty required values, delimiter, encoding, and duplicate rows.
- Reproduce with a small, synthetic sample and capture the exact error text.
- Escalate if a valid sample still fails; include steps and a sanitized file.

## A job opening is missing
- Check job status, owner, team access, active filters, and whether it is closed or archived.
- Verify the user is in the correct workspace and team.
- If access is inappropriate or data appears in the wrong workspace, stop and escalate.

## Email activity stopped syncing
- Ask when sync last worked and whether the connection or authorisation changed.
- Check supported connection settings and permissions in the approved workflow.
- Reconnect only using the official settings path and user consent.
- Escalate if the issue persists; avoid asking for email passwords or tokens.

## A report total differs from the pipeline
- Align date range, time zone, stage/status filters, record owner, and included archived records.
- Confirm how the metric is defined and whether it counts candidates, jobs, or placements.
- Compare a small sample to find the difference before suggesting a defect.

## Interview reminder not received
- Check time zone, event date/time, recipient, notification preferences, and supported delivery channel.
- Verify reminder configuration and offer a safe calendar invite workaround if appropriate.
- Escalate repeated failures with a timestamp and test case.

## A team member cannot see a client record
- Check role, team membership, record sharing, and workspace selection.
- Confirm with an authorised admin before changing permissions.
- Never bypass access controls to get the ticket closed.

## What information should a customer include in a ticket?
Share the action attempted, expected result, observed result, approximate timestamp/time zone, non-sensitive error message, impact, and steps already tried. Do not include passwords, authentication codes, or unnecessary candidate/client personal data.
