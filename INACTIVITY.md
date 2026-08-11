# Role Activity and Inactivity Policy

CAIPE keeps ownership current so contributors receive timely review and the
project can respond to releases, incidents, and security reports. This policy
uses outreach and graceful transitions before removal.

## What counts as activity

Activity is contribution within a person's recorded scope, including:

- authoring or reviewing code, documentation, designs, or proposals;
- issue triage, user support, testing, or release work;
- security, incident, infrastructure, or dependency maintenance;
- mentoring, meeting facilitation, governance, or community programs; and
- communicating availability or an agreed leave plan.

Commit counts alone do not determine activity. Review quality, responsibility,
and responsiveness matter more than raw volume.

## Review cadence

- Maintainers review role and ownership records at least every six months.
- Each review checks central and repository-local records, affiliations,
  scopes, access, and recovery coverage.
- The review is tracked in a public issue. Personal, conduct, security, or
  medical details are not recorded publicly.

## Planned leave

A Reviewer or Maintainer may request a planned leave for up to six months by
notifying the relevant Maintainers. The public record only needs the dates,
affected scope, and temporary coverage. Leave may be extended when coverage is
healthy.

Urgent access may be reduced during leave under least-privilege rules without
changing the person's recognized role.

## Reviewer inactivity

After six months without activity or an agreed leave plan:

1. A Maintainer contacts the Reviewer privately and opens a public cleanup
   issue that does not include personal details.
2. The Reviewer has 30 calendar days to confirm a return plan, request leave,
   narrow scope, or step down.
3. If there is no response or return plan, a public pull request removes the
   Reviewer from active repository-local ownership.
4. A returning former Reviewer uses the normal Reviewer promotion process;
   prior service may satisfy experience requirements.

## Maintainer inactivity

After six months without activity or an agreed leave plan:

1. Two active Maintainers, or one Maintainer and one Steering Committee member,
   contact the Maintainer privately.
2. The Maintainer has 30 calendar days to confirm availability, request leave,
   narrow scope, or request emeritus status.
3. Critical access may be reduced immediately if coverage, security, or
   recovery would otherwise be unsafe.

After twelve months without activity:

1. A public pull request proposes emeritus status or removal of the inactive
   scope in [MAINTAINERS.md](MAINTAINERS.md) and local ownership files.
2. The proposal remains open for at least 30 calendar days and directly
   notifies the Maintainer when possible.
3. Two active Maintainers for the scope approve. If fewer than two are active,
   the Steering Committee decides under [DECISION-MAKING.md](DECISION-MAKING.md).
4. Access is reconciled when the role change takes effect.

Emeritus is the preferred outcome for a Maintainer who served in good standing.

## Voluntary transitions and return

- A Reviewer or Maintainer may narrow scope, step down, or request emeritus
  status at any time through a public pull request.
- The project should thank and recognize the contributor's service.
- Return from emeritus follows [CONTRIBUTOR_LADDER.md](CONTRIBUTOR_LADDER.md).
  Prior service may satisfy experience requirements, but current sponsorship,
  availability, affiliation, and scope knowledge are required.

## Involuntary and emergency changes

Code of Conduct, security, legal, or access-safety actions may require immediate
and confidential changes. The authorized body may suspend access first and use
the applicable confidential process. Public records state only the resulting
role or access change and must not expose protected information.

Inactivity must not be used as a substitute for the Code of Conduct process.

## Policy inspiration

This policy adapts Kubernetes' periodic ownership cleanup and emeritus model
and the CNCF project template's inactivity guidance. CAIPE uses broader
activity evidence and a human outreach period because it is smaller and
includes substantial non-code project work.

- [Kubernetes OWNERS cleanup and emeritus guidance](https://www.kubernetes.dev/docs/guide/owners/)
- [CNCF contributor-ladder template](https://github.com/cncf/project-template/blob/main/CONTRIBUTOR_LADDER.md)
