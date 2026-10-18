# Scope entries record base versions

## Statement
WHEN a scope entry is added to a change request, the tool shall record the target's version on the baseline branch (without Git: the working-tree version) as base version and shall change it only through `gregraph cr reanalyze`.

## Rationale
Drift detection needs a recorded starting point per scope target that only explicit re-analysis may change.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
