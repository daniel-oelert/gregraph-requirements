# Validate 5,000 documents within 5 seconds

## Statement
The tool shall load a repository of 5,000 documents and complete `gregraph validate` within 5 seconds on a laptop-class machine.

## Rationale
5,000 documents is the design sizing assumption (§1.5); validate is the hot path for hooks and CI.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
