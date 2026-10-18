# Missing arguments prompt or fail under --no-input

## Statement
WHEN a required argument is missing and stdin is a terminal, the tool shall prompt with a filtered picker; WHERE `--no-input` is given, the tool shall fail instead.

## Rationale
Interactive use should guide; automation must fail loudly instead of hanging.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
