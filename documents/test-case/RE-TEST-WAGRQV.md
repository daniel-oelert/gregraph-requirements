# Verify: glossary terms are slug-identified with usage reports

## Objective
Verify that glossary terms are managed as slug-identified Markdown files outside the graph and that usage is reported.

## Preconditions
An initialised repository.

## Steps
Add the term `Traceability` with an alias; run `gregraph term usage` for its slug.

## Expected result
The term is stored as a slug-named Markdown file under `glossary/`; usage lists every document that mentions the term.

## Notes
*Add supporting notes, links, or open questions.*
