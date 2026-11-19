Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
Failed to create stream fd: Operation not permitted
# Security Policy

## Reporting a vulnerability

Please do not report security vulnerabilities in public issues, discussions, or pull requests.

For this GitHub repository, use **Security → Advisories → Report a vulnerability** to send a private report to the maintainers. Include the affected version/commit, impact, steps to reproduce, and any proof of concept needed to understand the issue. Avoid including real learner data or live credentials. The maintainers should acknowledge receipt, coordinate a fix and disclosure timeline with the reporter, and publish an advisory when disclosure is appropriate.

If private vulnerability reporting is unavailable for this fork, contact the repository owner through a private channel before sharing technical details. Vulnerabilities in inherited DeepTutor code should also be reported privately to [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor/security/advisories/new), so upstream maintainers can assess affected releases.

## Secrets and sensitive data

- Never commit provider/API keys, access tokens, passwords, signing keys, or production configuration. Rotate any credential that is accidentally exposed.
- Keep project-root `.env` files out of version control. DeepTutor runtime settings and provider credentials are stored under the runtime home; treat that tree as private.
- Do not share unredacted logs, database files, screenshots, traces, uploaded documents, or learner conversations in issues or PRs.
- Use synthetic or consented data for development and evaluation. Minimize personal data, restrict access, and define retention/deletion before any pilot with real learners, especially minors.
- Treat uploaded documents and retrieved text as untrusted input. Do not grant students access to administrative tools, arbitrary subprocess execution, or privileged MCP/CLI integrations by default.
- Enforce authentication, authorization, tenant/workspace boundaries, and any future quotas on the server. Hiding a control in the frontend is not access control.
- Keep dependencies and generated images/artifacts reviewed; check third-party notices and licenses before enabling optional parsers or integrations in a hosted service.

The PDF's proposed AI Teacher plan calls for a specific privacy/consent policy, moderation design, least-privilege student access, and a dependency-license review before public hosting. Those controls are project work items and must be implemented and reviewed before using this fork with real learner accounts.
