# The pre-commit hook bumps staged changed documents

## Statement
WHEN the pre-commit hook runs, the tool shall increment the version of every staged document whose normalised body hash or asset hashes differ from the stored hashes, and stage the rewritten sidecar.

## Rationale
Version increments must be automatic and tied to what is actually committed, or the history lies.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
