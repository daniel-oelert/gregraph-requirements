# Scope drift warns while a change request is open or accepted

## Statement
WHILE a change request's effective status is `open` or `accepted`, IF a scope target's version on the baseline branch exceeds its base version, or the target is superseded or deprecated on the baseline branch, THEN `gregraph validate` shall warn of drift.

## Rationale
A change request decided against older baseline content no longer reflects reality and must be re-examined.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
