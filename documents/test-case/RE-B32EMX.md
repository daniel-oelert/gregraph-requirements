# Verify: identifiers are derived, prefixed, and regenerated on collision

## Objective
Verify that document creation generates a UUIDv4, derives the identifier from its first 30 bits, prefixes it, and regenerates on collision.

## Preconditions
An initialised repository with the configured prefix `RE`.

## Steps
Create several documents and inspect their sidecars; force an identifier collision with an existing document and create another.

## Expected result
Every identifier is the configured prefix plus a 6-character Crockford base32 encoding of the UUID's first 30 bits; on collision a new UUID is generated and the check repeats.

## Notes
*Add supporting notes, links, or open questions.*
