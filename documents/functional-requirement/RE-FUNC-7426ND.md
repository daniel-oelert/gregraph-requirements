# The hook ignores drift and CR scope changes

## Statement
The pre-commit hook shall not abort a commit because of drift or because documents in a change request's scope changed.

## Rationale
Drift and scope churn are review topics; they must not block unrelated commits on the change request's branch.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
