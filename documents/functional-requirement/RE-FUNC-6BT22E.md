# Identifiers are derived, prefixed, and regenerated on collision

## Statement

WHEN a document or change request is created, the tool shall generate a UUIDv4, derive a six-character Crockford base32 identifier from its first 30 bits, prefix it with the configured prefix and the configured type abbreviation (CHG for change requests), and regenerate on collision with any existing identifier.

## Rationale
Short, readable, derivable identifiers keep references usable while the UUID keeps global uniqueness.

## Fit criterion

Every generated identifier has the form <PREFIX>-<ABBREVIATION>-<BODY>, uses the configured prefix and the type abbreviation (CHG for change requests), and is unique in the shared document/CR ID space.

## Notes
*Add supporting notes, links, or open questions.*
