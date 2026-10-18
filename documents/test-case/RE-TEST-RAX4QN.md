# Verify: modification after decision warns

## Objective
Verify that a change request whose version exceeds the version recorded by its last non-open decision warns as modified after decision.

## Preconditions
An accepted change request that has been modified after its acceptance.

## Steps
Run `gregraph validate`, then `gregraph cr reaffirm` and validate again.

## Expected result
`W-CR-MODIFIED-AFTER-DECISION` is reported until `gregraph cr reaffirm` is run.

## Notes
Derived from design appendix A, BOOT-302.
