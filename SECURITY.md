# Security Policy

This repository is a **transport-only** placeholder for the Orhan Control Plane
GitHub event transport. It is deliberately public and content-minimal.

## Scope

- No secrets, credentials, API keys, SSH material or private infrastructure data.
- No Control Plane source, Governor state, FinNote content or customer data.

## Workflow rules

- Triggers: `workflow_dispatch` only. PR, `pull_request_target`, `push`,
  `schedule` and `repository_dispatch` execution is blocked by policy.
- Allowed actor: the repository owner (`orhanzeki`) only.
- The single workflow is an inert, fail-closed placeholder that never schedules a job.
- Runner access is restricted to this repository and to the exact workflow
  pinned at `refs/heads/main`.

## Reporting

Report a suspected issue privately to the repository owner rather than opening a
public issue.
