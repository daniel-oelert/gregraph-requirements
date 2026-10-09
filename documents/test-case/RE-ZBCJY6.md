# Verify: draft and active are derived from the baseline branch

## Objective
Verify that `draft` and `active` statuses are derived by comparing with the configured baseline branch and that `unknown` is reported without Git.

## Preconditions
A Git repository whose baseline branch contains one document; a second document exists only in the working tree or on a side branch.

## Steps
Run `gregraph status` on the branch, then in a copy without the `.git` directory.

## Expected result
The merged document reports `active` and the other `draft`; without Git both report `unknown`.

## Notes
*Add supporting notes, links, or open questions.*
