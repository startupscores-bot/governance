# Maintainer Registry

This file is CAIPE's canonical project-wide directory of active and emeritus
Maintainers. It records identity, affiliation, status, and scope so the
community and foundations can evaluate project ownership and diversity.

It is not an access-control file. Repository-local `MAINTAINERS.md`,
`CODEOWNERS`, GitHub teams, rulesets, and branch protections remain the
operational sources for merge, release, and administration authority. If the
central and local records disagree, access should be restricted until a public
pull request reconciles them.

## Active Maintainers

The initial registry below is imported from the current
[`ai-platform-engineering` maintainer list](https://github.com/cnoe-io/ai-platform-engineering/blob/main/MAINTAINERS.md).
Affiliations are self-reported and must be updated within 30 days of a change.

| Name | GitHub | Affiliation | Scope | Status |
| --- | --- | --- | --- | --- |
| Adam Dickinson | [@adickinson72](https://github.com/adickinson72) | Demandbase | `ai-platform-engineering` | Active |
| Arthur Drozdov | [@artdroz](https://github.com/artdroz) | Cisco Outshift | `ai-platform-engineering` | Active |
| Carlos Santana | [@csantanapr](https://github.com/csantanapr) | AWS | `ai-platform-engineering` | Active |
| Erik Lutz | [@cisco-erilutz](https://github.com/cisco-erilutz) | Splunk | `ai-platform-engineering` | Active |
| Hasith Kalpage | [@haskalpa](https://github.com/haskalpa) | Cisco Outshift | `ai-platform-engineering` | Active |
| Kevin Kantesaria | [@kevkantes](https://github.com/kevkantes) | Splunk | `ai-platform-engineering` | Active |
| Niall Thomson | [@niallthomson](https://github.com/niallthomson) | AWS | `ai-platform-engineering` | Active |
| Shubham Bakshi | [@subbaksh](https://github.com/subbaksh) | Cisco Outshift | `ai-platform-engineering` | Active |
| Sri Aradhyula | [@sriaradhyula](https://github.com/sriaradhyula) | Cisco Outshift | `ai-platform-engineering` | Active |
| Sunny Whang | [@suwhang-cisco](https://github.com/suwhang-cisco) | Cisco Outshift | `ai-platform-engineering` | Active |

Steering Committee membership is a separate governance role recorded in
[STEERING-COMMITTEE.md](STEERING-COMMITTEE.md). A person may hold both roles,
but one does not automatically grant the other.

## Emeritus Maintainers

Emeritus Maintainers retain recognition and may be consulted, but they do not
have active merge, release, voting, or incident-response authority.

| Name | GitHub | Former scope | Emeritus since |
| --- | --- | --- | --- |
| _None recorded_ | N/A | N/A | N/A |

## Registry rules

- Promotion follows [CONTRIBUTOR_LADDER.md](CONTRIBUTOR_LADDER.md).
- Inactivity and return follow [INACTIVITY.md](INACTIVITY.md).
- Each scope must link to repository-local ownership and access controls before
  operational privileges are granted.
- Maintainers must update affiliation, scope, or availability within 30 days.
- The registry is reviewed at least twice each year and before a foundation
  application, election, or material repository transfer.
- Registry changes use public pull requests except when temporary access must
  be removed immediately for security or safety.

## Adding or changing a record

A registry pull request must include:

- the affected person and GitHub account;
- active, emeritus, or removed status;
- employer or independent affiliation;
- exact repository or component scope;
- links to the nomination, decision, and repository-local ownership change;
- the effective date; and
- acknowledgement from the affected person when practical.

The Secretary or a delegated Maintainer keeps the central and repository-local
records synchronized.
