# Verify: directed edges live on the source only

## Objective
Verify that directed edges are stored on the source document only and inbound edges are computed from an index.

## Preconditions
Documents A and B with edge `A refines B`.

## Steps
Inspect both sidecars and run `gregraph show B`.

## Expected result
The edge appears only in A's sidecar; B's sidecar contains no copy; `show B` lists the inbound edge from the index.

## Notes
*Add supporting notes, links, or open questions.*
