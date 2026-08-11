# Contributor Ladder

CAIPE uses an earned, scoped contributor ladder. Responsibility grows through
sustained contribution, sound judgment, and service to other contributors.
Authority belongs to a defined project area; a role in one area does not grant
authority everywhere.

This policy adapts the Kubernetes community membership model and the CNCF
project contributor-ladder template to CAIPE's current size. CAIPE policy takes
precedence where the upstream models differ.

## Roles

- **Participant:** joins public project work; visible through public activity.
- **Contributor:** makes accepted contributions; visible through project
  history and community records.
- **Reviewer:** reviews a defined area; recorded in repository-local ownership.
- **Maintainer:** accepts changes and stewards an area; recorded centrally and
  in repository-local controls.
- **Emeritus:** recognizes a former Reviewer or Maintainer; recorded in the
  applicable central or local ownership file.

GitHub organization membership is an access mechanism, not a separate status
level. Access must follow the role and least-privilege requirements below.

## Participant

Participants use CAIPE, join discussions, attend meetings, report problems,
help other users, or test releases.

Participants must:

- follow the [Code of Conduct](CODE_OF_CONDUCT.md);
- communicate constructively; and
- avoid sharing confidential security or conduct information publicly.

Anyone may participate. No nomination is required.

## Contributor

Contributors make accepted project contributions. Contributions may include:

- code, tests, documentation, design, or review;
- issue triage, release work, security work, or infrastructure;
- user support, meeting facilitation, or community programs; and
- proposals, research, or other work accepted by a project team.

Contributors must follow the applicable contribution and security policies.
There is no activity quota and no special repository access for this role.

## Reviewer

Reviewers provide timely, constructive review for a defined repository,
component, documentation area, release function, or community program.

### Reviewer responsibilities

- Review changes within the recorded scope.
- Explain requested changes and distinguish blockers from suggestions.
- Apply project standards consistently.
- Escalate security, conduct, or cross-project concerns appropriately.
- Help Contributors grow into Reviewers.
- Keep affiliation, availability, and areas of expertise current.

### Reviewer promotion signals

A Reviewer nominee normally has:

- at least three months of sustained participation;
- at least five accepted contributions, including useful reviews, or an
  equivalent body of non-code work;
- demonstrated knowledge of the proposed scope;
- a record of respectful, reliable collaboration; and
- two active Maintainer sponsors familiar with the nominee's work.

These are evidence guidelines, not contribution counters. A complex design,
release, incident, security response, or community program may demonstrate the
same readiness as several pull requests.

### Reviewer promotion process

1. A sponsor opens a public pull request updating the relevant repository-local
   ownership file or team definition.
2. The pull request states the scope, evidence, sponsors, and nominee's current
   affiliation.
3. The nominee publicly accepts the responsibilities.
4. Two active Maintainers for the scope approve. When practical, the sponsors
   should represent different employer affiliations.
5. The pull request remains open for at least seven calendar days before merge.

Reviewer authority is limited to the scope recorded by the relevant
repository. Review alone does not grant merge or release access.

## Maintainer

Maintainers accept changes and steward the health of a defined repository or
project area. They are accountable for users, contributors, releases, security,
and long-term maintainability within that scope.

### Maintainer responsibilities

- Review and accept changes within the recorded scope.
- Maintain quality gates, releases, security response, and operational health.
- Make decisions transparently under [DECISION-MAKING.md](DECISION-MAKING.md).
- Mentor Contributors and Reviewers and identify succession candidates.
- Keep ownership files and the central registry accurate.
- Disclose affiliations and conflicts of interest and recuse when appropriate.
- Act for the project rather than an employer or product interest.

### Maintainer promotion signals

A Maintainer nominee normally has:

- served effectively as a Reviewer for at least six months;
- sustained contributions over the preceding twelve months;
- broad knowledge of the proposed scope and its users and dependencies;
- demonstrated judgment in reviews, compatibility, security, or releases;
- mentored other contributors; and
- two active Maintainer sponsors from different employer affiliations.

Equivalent non-code leadership counts. The nomination must explain the
evidence instead of relying on raw contribution totals.

### Maintainer promotion process

1. A sponsor opens a public issue describing the proposed scope and evidence.
2. The nominee publicly accepts the responsibilities and discloses affiliation
   and relevant conflicts.
3. A pull request updates [MAINTAINERS.md](MAINTAINERS.md) and the applicable
   repository-local ownership files.
4. The nomination receives approval from two active Maintainers for the scope
   who have different employer affiliations.
5. The nomination remains open for at least fourteen calendar days.
6. If the scope has fewer than two active Maintainers, or the nomination grants
   project-wide authority, the Steering Committee decides under
   [DECISION-MAKING.md](DECISION-MAKING.md).

The nominee may not approve their own nomination. Exceptions to sponsorship,
affiliation, or review-period requirements require a recorded Steering
Committee decision.

### Authority and access

The central registry does not grant access by itself. Repository-local
`MAINTAINERS.md`, `CODEOWNERS`, teams, rulesets, and branch protections define
operational authority. Access must be the minimum needed for the recorded
scope, and self-approval should not be used to bypass independent review.

## Emeritus

Emeritus status recognizes prior service while removing active review, merge,
release, voting, and incident-response obligations.

Reviewers and Maintainers may request emeritus status at any time. Inactive
role transitions follow [INACTIVITY.md](INACTIVITY.md). Emeritus contributors
may advise the project but do not exercise active authority.

Returning from emeritus status uses the normal promotion process. Prior service
may satisfy experience requirements, but current availability, affiliation,
scope knowledge, and sponsorship must be demonstrated.

## Role changes and appeals

- Promotions, scope changes, and voluntary transitions are public.
- Security, access-safety, and Code of Conduct actions may require confidential
  handling; public records must not expose protected details.
- A person may appeal a process or scope decision under the appeals process in
  [DECISION-MAKING.md](DECISION-MAKING.md).
- Role activity and cleanup follow [INACTIVITY.md](INACTIVITY.md).

## References

- [Kubernetes community membership](https://github.com/kubernetes/community/blob/main/community-membership.md)
- [Kubernetes OWNERS guidance](https://www.kubernetes.dev/docs/guide/owners/)
- [CNCF project contributor-ladder template](https://github.com/cncf/project-template/blob/main/CONTRIBUTOR_LADDER.md)
