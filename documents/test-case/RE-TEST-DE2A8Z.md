# Verify: check reports the hook's findings without modifying files

## Objective
Verify that `gregraph check` reports what the pre-commit hook would report for all working-tree changes without modifying files.

## Preconditions
A repository with working-tree changes, including an edited document whose inbound link is now behind its version.

## Steps
Run `gregraph check`, then inspect the working tree.

## Expected result
The report lists the bumps, newly outdated links, and findings the hook would produce; no file is modified; the exit code is non-zero when the hook would block.

## Notes
*Add supporting notes, links, or open questions.*
