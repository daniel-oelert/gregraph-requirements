# Verify: kind-rule violations are refused with the rule named

## Objective
Verify that a link violating an edge type's kind rule is refused and the rule is named.

## Preconditions
A repository with a goal document and a test-case document.

## Steps
Request the link `goal verifies test-case`.

## Expected result
The tool exits with code 4 and the refusal names the violated kind rule.

## Notes
*Add supporting notes, links, or open questions.*
