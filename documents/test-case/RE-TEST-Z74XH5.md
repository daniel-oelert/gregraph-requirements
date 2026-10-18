# Verify: the pre-commit hook bumps staged changed documents

## Objective
Verify that the pre-commit hook increments the version of every staged document whose body or asset hashes differ from the stored hashes and stages the rewritten sidecar.

## Preconditions
Document A is at version 1 with an inbound link at target version 1; A's body has been edited in the working tree.

## Steps
Stage A's Markdown file and commit.

## Expected result
A's version becomes 2, the new body hash is stored, and the rewritten sidecar is staged by the hook.

## Notes
Derived from design appendix A, BOOT-301.
