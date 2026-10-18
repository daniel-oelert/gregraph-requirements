# Verify: unlinked identifier mentions warn

## Objective
Verify that a body mention of an identifier with no edge in either direction produces a warning.

## Preconditions
A document whose body mentions another document's identifier; no edge connects them.

## Steps
Run `gregraph validate`.

## Expected result
`W-MENTION-UNLINKED` is reported for the mentioning document.

## Notes
*Add supporting notes, links, or open questions.*
