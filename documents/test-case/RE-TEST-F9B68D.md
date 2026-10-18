# Verify: the pre-commit hook blocks newly outdated links

## Objective
Verify that a commit that would newly outdate at least one link is aborted and the exact refresh commands are listed.

## Preconditions
The hook bump scenario: A's body is edited and staged while a link points at A at target version 1; `versioning.on_outdated_links` is `block`.

## Steps
Commit the staged change; then run the printed `gregraph link refresh` command and commit again.

## Expected result
The first commit is aborted and the refresh command is printed; the second commit succeeds and the link records version 2.

## Notes
Derived from design appendix A, BOOT-301.
