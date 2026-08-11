# Public Decision Log

This directory is the durable index of formal CAIPE decisions. Proposals and
discussion stay in public issues or pull requests; a decision record captures
the final motion, authority, votes, recusals, outcome, and follow-up work.

## Decisions that require a record

Create a record for:

- formal Steering Committee votes;
- charter, governance, election, or contributor-role policy changes;
- repository admission, transfer, archival, or removal;
- project-wide Maintainer appointments or exceptions to the contributor
  ladder;
- license, trademark, domain, fiscal-host, or foundation decisions;
- material organization-wide security or release-policy changes; and
- emergency decisions made under a shortened review period.

Routine pull requests and repository-local technical choices do not need a
separate record unless the responsible Maintainers determine that the decision
has lasting cross-project impact.

## Record format

- File name: `YYYY-NNN-short-title.md`.
- Numbers restart at `001` each calendar year and are never reused.
- Status: `accepted`, `rejected`, or `superseded`.
- Use [TEMPLATE.md](TEMPLATE.md).
- Link the proposal, review window, vote, implementation work, and superseding
  decision when applicable.

## Workflow

1. Open the proposal under [DECISION-MAKING.md](../DECISION-MAKING.md).
2. Complete the required public review and vote.
3. The Secretary or decision owner opens a record pull request within seven
   calendar days of the outcome.
4. Reviewers verify the record against the proposal and vote.
5. Merge the record and add it to the index below.

Decision records are append-only history. Correct factual errors through a pull
request that explains the correction. Do not rewrite a past outcome; create a
new record that supersedes it.

## Index

| ID | Date | Status | Decision | Record |
| --- | --- | --- | --- | --- |
| _No decisions recorded yet_ | N/A | N/A | N/A | N/A |
