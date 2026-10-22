# CI Evidence Pack

This file is the auditable evidence pack for the `ci-evidence-demo` disposable repository.

## CI Run Evidence

- **Repository:** `mcpmark-eval-liuhezi/ci-evidence-demo`
- **Workflow:** Evidence Builder (`.github/workflows/evidence.yml`), triggered on demand via `workflow_dispatch`
- **Run number:** 1
- **Run conclusion:** success
- **Run URL:** https://github.com/mcpmark-eval-liuhezi/ci-evidence-demo/actions/runs/39715561472
- **Run logs:** deleted after the artifact was captured (evidence pack retains artifacts, not logs)

## Artifact Evidence

- **Artifact name:** `evidence-manifest`
- **Artifact ID:** 12398593847
- **Artifact size:** 212 bytes
- **Digest:** sha256:b9dbf9bdfe7f6eb7d630d13e4ec57b71e7cfe577c9abf12824123b2ff86b6df4
- **Download link:** https://api.github.com/repos/mcpmark-eval-liuhezi/ci-evidence-demo/actions/artifacts/12398593847/zip
- **Artifact expiry:** 2027-01-20T03:12:30Z
- **Manifest contents:** repo name (`mcpmark-eval-liuhezi/ci-evidence-demo`), run number (`1`), build date (`2026-10-22`)

## Secrets Check Outcome

- **Result:** Could not be verified programmatically.
- The GitHub Personal Access Token in use for this session does not have the
  `secret_scanning_alerts` permission, so the repository's secret scanning
  alerts endpoint returned `403 Resource not accessible by personal access token`.
  No alert data (including a zero-alert result) can be reported from this token.
- **Required action:** re-run the secret scanning check with a token that grants
  read access to secret scanning alerts, or review it in the GitHub UI under
  Security > Secret scanning.

## Inbox / Notifications Check Outcome

- **Result:** Could not be verified programmatically.
- The GitHub Personal Access Token in use for this session does not have the
  `notifications` permission. Listing notifications and setting the repository
  subscription to "ignore" both returned `403 Resource not accessible by personal
  access token`.
- **Required action:** run the notifications check with a token that grants the
  `notifications` permission, or mute the repository manually in the GitHub UI
  (Watch > Ignore on the repo page).

## Provenance Note

- This repository was created under the organization `mcpmark-eval-liuhezi`
  rather than the personal account `HeziLiu`, because the personal namespace
  returned `403 Resource not accessible by personal access token` on repository
  creation. All other steps were completed against this repository.
