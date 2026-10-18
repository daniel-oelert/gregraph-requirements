# init creates the layout, templates, config, and hook

## Statement
WHEN `gregraph init` is run in a directory without `.gregraph/`, the tool shall create the repository layout, copy all built-in templates as version 1, write the default configuration, and install the pre-commit hook if Git is available.

## Rationale
One command must produce a complete, consistent repository so every team starts from the same layout and hook discipline.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
