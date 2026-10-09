# Verify: origin_cr and introduces are recorded with --cr

## Objective
Verify that `--cr` records the change request in the new document's `origin_cr` and adds the document's ID to the change request's `introduces` list.

## Preconditions
An open change request.

## Steps
Create a document with `--cr` naming the change request and inspect both sidecars.

## Expected result
The new document's `origin_cr` names the change request and the change request's `introduces` lists the new document's identifier.

## Notes
*Add supporting notes, links, or open questions.*
