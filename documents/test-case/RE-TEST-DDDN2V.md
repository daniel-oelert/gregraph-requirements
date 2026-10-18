# Verify: deprecated template versions warn per document

## Objective
Verify that `gregraph validate` warns for every document pinned to a deprecated template version.

## Preconditions
A template version marked deprecated with at least one document pinned to it.

## Steps
Run `gregraph validate`.

## Expected result
`W-TEMPLATE-DEPRECATED` is reported once per pinned document.

## Notes
*Add supporting notes, links, or open questions.*
