# Identifiers are derived, prefixed, and regenerated on collision

## Statement
WHEN a document is created, the tool shall generate a UUIDv4, derive a 6-character Crockford base32 identifier from its first 30 bits, prefix it with the configured prefix, and regenerate on collision with any existing identifier.

## Rationale
Short, readable, derivable identifiers keep references usable while the UUID keeps global uniqueness.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
