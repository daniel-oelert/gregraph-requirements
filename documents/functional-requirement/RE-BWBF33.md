# The pre-commit hook blocks newly outdated links

## Statement
WHEN a commit would newly outdate at least one link and the policy is `block`, the pre-commit hook shall abort the commit and list the exact refresh commands.

## Rationale
A commit that changes a requirement must not silently invalidate dependents; the block forces a deliberate refresh.

## Fit criterion
*State how conformance to this requirement can be verified.*

## Notes
*Add supporting notes, links, or open questions.*
