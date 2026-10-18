# Verify: identifiers are derived, prefixed, and regenerated on collision

## Objective

Verify that document and change-request creation generates a UUIDv4, derives the identifier body from its first 30 bits, prefixes it with the configured prefix and the type abbreviation (CHG for CRs), and regenerates on collision.

## Preconditions

An initialised config-schema-2 repository with the prefix RE and unique 3-5 character type abbreviations.

## Steps

Create several documents of different types and a change request; inspect their sidecars; force an identifier collision with an existing identifier and create another.

## Expected result

Every identifier is the configured prefix, the type abbreviation (CHG for CRs) and a six-character Crockford base32 encoding of the UUID first 30 bits; on collision a new UUID is generated and the check repeats.

## Notes
*Add supporting notes, links, or open questions.*
