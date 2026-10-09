# Verify: supersede accepts multiple targets

## Objective
Verify that supersession with multiple targets creates one document with one `supersedes` edge per target.

## Preconditions
Documents A and B of the same kind.

## Steps
Run `gregraph supersede A B --title "Replacement"`.

## Expected result
One new document is created carrying one `supersedes` edge per target; A and B both become superseded.

## Notes
*Add supporting notes, links, or open questions.*
