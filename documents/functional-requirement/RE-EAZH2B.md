# link refresh --follow follows supersession chains

## Statement
WHEN a link's target is superseded, `gregraph link refresh --follow` shall re-point the link to the end of the supersession chain, or fail if the chain forks.

## Rationale
When a requirement is replaced, dependents should be re-pointed to the successor in one review act.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
