# Verify: effective change request status comes from the baseline branch

## Objective
Verify that the effective status is derived from the change request's sidecar on the baseline branch and the working-tree status is shown as proposed when the two differ.

## Preconditions
A change request whose working-tree sidecar records a newer status than the sidecar on the baseline branch.

## Steps
Run `gregraph cr list --pending` and `gregraph status`.

## Expected result
The effective status is read from the baseline branch and the working-tree status is shown as proposed.

## Notes
*Add supporting notes, links, or open questions.*
