# Security Policy (org-wide default)

This is the default disclosure policy for repositories under the [`avinash-matrixgard`](https://github.com/avinash-matrixgard) organization. **Individual repos may override with their own `SECURITY.md`** — if a repo has one, follow that instead.

## Reporting a vulnerability

**Please do NOT open a public GitHub issue for security vulnerabilities.**

Use one of these private channels:

1. **GitHub Private Vulnerability Reporting** — every public repo in this org has it enabled. From the repo, navigate to **Security → Report a vulnerability**.
2. **Email:** `security@matrixgard.com`. Request a PGP key in your initial mail and we'll respond with one before you send sensitive details.

Include in your report:

- Repository name + commit SHA / version affected
- Clear description of the issue
- Reproduction steps or proof-of-concept
- Impact assessment
- Proposed fix, if you have one
- Whether you'd like credit in the disclosure (and the name / handle to use)

## Response timeline

| Stage | Target |
|-------|--------|
| Acknowledgement | within 48 hours |
| Initial assessment + severity rating | within 5 business days |
| Patch developed + tested | within 30 days for HIGH/CRITICAL, 60 days for MEDIUM, 90 days for LOW |
| Public disclosure | coordinated with reporter — typically within 14 days of patch release |

We follow responsible-disclosure best practice and will keep you informed at each stage.

## Scope

In scope: any code or documentation in any public repo under this organization.

Out of scope:
- Documented design choices that the repo's README explicitly calls out as scope-limited
- Generic AWS / GCP / Azure service vulnerabilities (report to the cloud provider directly)
- Issues in third-party dependencies (report upstream)

## Maintainer

[MatrixGard](https://matrixgard.com) — `security@matrixgard.com`.
