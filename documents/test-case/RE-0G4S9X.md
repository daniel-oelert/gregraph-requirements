# Verify: link refresh --follow follows supersession chains

## Objective
Verify that `gregraph link refresh --follow` re-points a stale link to the end of the supersession chain, or fails if the chain forks.

## Preconditions
One setup where A is superseded by B, which is superseded by C, with a link pointing at A; a second setup where A is superseded by both B and C.

## Steps
Run `gregraph link refresh --follow` on the link in each setup under `--no-input`.

## Expected result
In the chain setup the link is re-pointed to C; in the fork setup the tool fails with `E-SUPERSEDE-FORK`.

## Notes
*Add supporting notes, links, or open questions.*
