# Identifiers include the configured type abbreviation

## Statement

WHEN a document or change request is created, the tool shall insert the configured type abbreviation (or the reserved CHG for change requests) between the repository prefix and the six-character UUID-derived body, using a unique 3-5 character uppercase abbreviation per document type.

## Rationale

The type segment makes identifiers self-describing without sacrificing the stable random body; configuration keeps user-defined types in control of their own abbreviation.

## Fit criterion

Every generated identifier matches <PREFIX>-<ABBREVIATION>-<BODY>, the abbreviation matches [A-Z]{3,5}, abbreviations are unique per type, CHG is reserved for change requests, and validate reports E-ID-DERIVATION or E-TYPE-ABBREVIATION-CHANGED when the invariant is broken.

## Notes

*Add supporting notes, links, or open questions.*
