# Cycle-creating links are refused with the cycle path

## Statement
WHEN a link is requested that would create a directed cycle over the directed edge types, the tool shall refuse the link and print the cycle path.

## Rationale
A cyclic dependency graph cannot be reasoned about topologically; refusing at link time keeps the graph acyclic.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
