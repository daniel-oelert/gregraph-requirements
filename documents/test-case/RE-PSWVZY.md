# Verify: scope drift warns while a change request is open or accepted

## Objective
Verify that drift is warned about while a change request's effective status is `open` or `accepted`.

## Preconditions
An accepted change request on a side branch with scope entry X at base version 2; another branch changes X and is merged into the baseline branch.

## Steps
Run `gregraph validate` on the change request's branch.

## Expected result
`W-CR-BASE-DRIFT` is reported for X while the effective status is accepted.

## Notes
Derived from design appendix A, BOOT-302.
