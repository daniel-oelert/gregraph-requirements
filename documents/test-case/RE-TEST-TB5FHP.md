# Verify: sync bumps versions without Git

## Objective
Verify that without a Git repository `gregraph sync` performs the version increments the hook would perform.

## Preconditions
A repository initialised with `--no-git`; a document whose body was edited since its last bump.

## Steps
Run `gregraph sync`.

## Expected result
The document's version is incremented by one and the stored hashes are updated, exactly as the hook would.

## Notes
*Add supporting notes, links, or open questions.*
