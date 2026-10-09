# Verify: scope entries record base versions

## Objective
Verify that adding a scope entry records the target's version on the baseline branch as base version, changed only through `gregraph cr reanalyze`.

## Preconditions
A change request; target X at version 2 on the baseline branch.

## Steps
Add X to the change request's scope; let X advance to version 3 on the baseline branch; run `gregraph cr reanalyze`; attempt to change the base version any other way.

## Expected result
The base version is 2 when the entry is added, becomes 3 only after `cr reanalyze`, and no other command changes it.

## Notes
Derived from design appendix A, BOOT-302.
