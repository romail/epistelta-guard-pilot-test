# EPISTELTA required-check probe

This file exists only to create a harmless test pull request.

Expected lifecycle:
1. No fresh approved review -> failing epistelta/decision-integrity check.
2. Fresh authorized human approval -> passing check.
3. Tracked openapi.yaml or .epistelta/review-policy.json changes on main -> failing check until new approval.
4. Verify that GitHub branch protection rejects merge when the check fails.

DO NOT MERGE until the test is complete and evidence is recorded.
No API keys or proprietary source data.
