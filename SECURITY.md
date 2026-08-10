# CAIPE Security Policy

Security is a core project responsibility. CAIPE welcomes responsible security
research and treats credible vulnerability reports as urgent, confidential
engineering work.

## Report a vulnerability privately

Email [caipe-security@googlegroups.com](mailto:caipe-security@googlegroups.com).

Do not report a suspected vulnerability in a public issue, discussion, pull
request, chat channel, or meeting. If a vulnerability is reported publicly,
avoid adding details and notify the security team immediately.

Use private reporting for vulnerabilities affecting CAIPE-maintained:

- source code, dependencies, packages, and container images;
- authentication, authorization, identity, and secret handling;
- build, release, signing, and software supply-chain systems;
- hosted services, project domains, and project-controlled infrastructure; or
- documentation when following it creates a security exposure.

When uncertain whether an issue is security-sensitive, report it privately.
The security team will redirect it if needed.

## What to include

Provide enough information for the team to reproduce and assess the issue:

- affected repository, component, version, image, or endpoint;
- vulnerability type and expected impact;
- prerequisites and a minimal reproduction or proof of concept;
- relevant logs, traces, screenshots, or configuration with secrets removed;
- known workarounds or remediation ideas;
- whether the issue has been disclosed to anyone else; and
- your preferred name and whether you want public credit.

Do not email active credentials, private keys, personal data, or other sensitive
material. Describe what you have and the team will arrange an appropriate
private exchange method when necessary.

## What to expect

The CAIPE security team aims to:

- acknowledge a new report within two business days;
- provide an initial assessment within five business days;
- share a status update at least every seven calendar days while the report is
  active;
- coordinate validation, remediation, release, and disclosure with the
  reporter and affected maintainers; and
- credit the reporter in the advisory unless they prefer anonymity.

These are response targets, not guarantees. Complexity, third-party
coordination, and release safety may affect remediation time. The team will
communicate material delays.

## Coordination and remediation

Access to an active report is limited to people needed to investigate and fix
it. The security team will:

1. confirm scope, impact, affected versions, and exploitability;
2. assign severity and remediation priority using a recognized vulnerability
   scoring framework and project context;
3. develop and validate a fix in private;
4. coordinate with affected dependencies, distributors, and downstream users
   when necessary;
5. prepare patched releases, upgrade guidance, and mitigations; and
6. publish a GitHub Security Advisory and release notes after coordinated
   disclosure.

The team may request a CVE identifier when appropriate. Public disclosure is
coordinated with the reporter and affected stakeholders so users have a
reasonable opportunity to update.

## Supported versions

Each CAIPE repository should publish the versions it currently supports. In
general, security fixes target maintained releases and the default development
branch. The team may provide mitigations instead of patches for versions that
are no longer maintained.

If the affected repository does not state its support window, include the
version in the private report and the security team will clarify coverage.

## Public project communication

Security vulnerabilities are the exception to CAIPE's public-by-default
workflow. Use public channels for everything that does not require confidential
handling:

- [GitHub Discussions](https://github.com/caipe-io/governance/discussions) for
  questions, support, ideas, and community conversation;
- the applicable CAIPE repository's issue tracker for ordinary bugs, feature
  requests, and documentation problems; and
- [CAIPE governance issues](https://github.com/caipe-io/governance/issues) for
  governance proposals and policy changes.

Code of Conduct reports are also confidential, but they follow the separate
[Code of Conduct reporting process](CODE_OF_CONDUCT.md#reporting-and-enforcement)
and must not be sent to the security address.

## Transparency

After coordinated disclosure, CAIPE publishes an advisory describing affected
versions, severity, impact, remediation, mitigations, and acknowledgements. The
project may withhold exploit details temporarily when publication would create
an immediate risk to users who have not had a reasonable opportunity to update.
