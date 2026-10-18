# Verify: validate --strict fails on any warning or error

## Objective
Verify that `gregraph validate --strict` exits non-zero if any warning or error is found.

## Preconditions
A repository that reports at least one warning and no errors.

## Steps
Run `gregraph validate` and then `gregraph validate --strict`.

## Expected result
The first run exits 0; the second exits non-zero.

## Notes
*Add supporting notes, links, or open questions.*
