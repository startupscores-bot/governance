# CAIPE Transfer Plan

## Goal

Consolidate CAIPE repositories and project assets in `caipe-io` while preserving
repository history, contributor attribution, releases, issue links, package
continuity, and public governance evidence.

## Current state

- The `caipe-io` GitHub organization was created on December 11, 2025.
- The `caipe.io` domain is registered.
- The `@caipe` npm scope and CAIPE-branded automation already exist.
- Governance approval, asset custody, and operational cutover remain.

## Hard prerequisite

Before any repository is transferred:

- [ ] Open a public issue in
  [`caipe-io/governance`](https://github.com/caipe-io/governance/issues/new)
  requesting approval of the CAIPE transfer plan.
- [ ] Record the transfer decision in that issue.
- [ ] Confirm the decision explicitly covers source repositories, history,
  issues, releases, packages, domains, trademarks, and other project assets.
- [ ] Link the approved issue from [README.md](README.md) and this document.

**Approval issue:** Not yet recorded.

This gate supplies the public provenance required for a clean sub-project split
and future foundation due diligence. This repository does not itself authorize
the separation.

## Phase 1: Governance bootstrap

- [ ] Adopt the CAIPE charter and decision process.
- [ ] Define and seat the initial Steering Committee through a separate public
  governance proposal.
- [ ] Publish committee affiliations, terms, and conflict disclosures.
- [ ] Establish private Code of Conduct and security reporting channels.
- [ ] Create GitHub teams for steering, maintainers, security, and working-group
  leads with least-privilege access.
- [ ] Ensure at least two unaffiliated administrators can recover critical
  assets.

## Phase 2: Inventory and dependency audit

Create a public transfer inventory before moving repositories. For each asset,
record its current owner, target owner, responsible person, dependencies,
cutover date, rollback path, and evidence link.

Inventory at least:

- GitHub repositories, teams, branch rules, environments, webhooks, apps, and
  deploy keys;
- issues, pull requests, discussions, projects, releases, tags, and GitHub
  Pages;
- container registries, package namespaces, signing keys, provenance, and
  release automation;
- CI secrets, cloud resources, DNS, domains, email aliases, calendars, and chat
  spaces;
- documentation, redirects, trademarks, logos, and social accounts; and
- external dependencies whose URLs or permissions do not use `caipe-io`.

The code split being clean does not remove the need to audit build, release,
identity, documentation, and operational dependencies.

## Phase 3: Repository transfer

- [ ] Freeze organization-level configuration changes during the cutover.
- [ ] Transfer repositories with GitHub's repository-transfer mechanism so
  history and redirects are preserved; do not recreate repositories by copying
  files.
- [ ] Recreate teams and verify permissions before unfreezing merges.
- [ ] Reapply rulesets, required checks, environments, secrets, webhooks, apps,
  and package permissions.
- [ ] Update `CODEOWNERS`, badges, documentation, module metadata, container
  references, and repository links.
- [ ] Verify forks, clones, issues, pull requests, releases, discussions, and
  redirects.

Move one low-risk repository first. Complete validation before transferring the
remaining repositories in dependency order.

## Phase 4: Identity and distribution cutover

- [ ] Make `caipe.io` the canonical project domain and preserve relevant
  redirects from previous documentation locations.
- [ ] Verify ownership and recovery for the `@caipe` npm scope.
- [ ] Move or reissue package, container, signing, and provenance credentials.
- [ ] Keep CAIPE bot identities where already correct; update authorization and
  installation ownership.
- [ ] Publish a migration notice with dates, expected redirects, and support
  contacts.

## Phase 5: Independence validation

The Steering Committee signs off only after verifying:

- [ ] no required build, release, deploy, or governance action depends on
  privileged access outside the `caipe-io` organization;
- [ ] all public links and redirects resolve as documented;
- [ ] releases and packages can be produced from `caipe-io`;
- [ ] vulnerability and conduct reports reach the intended private groups;
- [ ] the Steering Committee and maintainers have documented, recoverable
  access; and
- [ ] the public evidence bundle is complete.

## Public evidence bundle

Retain links to:

- the CAIPE transfer issue and recorded decision;
- the adopted CAIPE charter and initial committee acceptances;
- the asset inventory and transfer decision;
- repository transfer audit logs or receipts;
- post-transfer validation results; and
- the public migration announcement.

## Rollback

Repository transfers should be scheduled with source and destination
administrators available. If a critical repository cannot build, release, or
enforce required controls after transfer, freeze merges and releases, preserve
the audit trail, and either repair forward or restore the affected repository
under the authority documented in the approved transfer issue.
