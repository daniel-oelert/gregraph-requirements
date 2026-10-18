# Verify: documents are validated against their pinned template version

## Objective
Verify that each document is validated against the template version pinned in its sidecar.

## Preconditions
A document pinned to `requirement-ears` version 1, and a `requirement-ears` version 2 that adds a required section.

## Steps
Run `gregraph validate`.

## Expected result
Only the pinned version's sections are enforced for the document; the extra version 2 section is not required of it.

## Notes
*Add supporting notes, links, or open questions.*
