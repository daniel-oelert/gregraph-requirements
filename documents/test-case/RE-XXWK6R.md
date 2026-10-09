# Verify: asset changes count as content changes

## Objective
Verify that a document's asset list and hashes are recomputed on reconcile and that any asset change is treated as a content change.

## Preconditions
A document referencing an asset under its `assets/<ID>/` folder.

## Steps
Modify the asset's bytes and commit the change.

## Expected result
The hook bumps the document's version and stores the new asset hash.

## Notes
*Add supporting notes, links, or open questions.*
