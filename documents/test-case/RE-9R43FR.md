# Verify: the hook ignores drift and CR scope changes

## Objective
Verify that the pre-commit hook does not abort a commit because of drift or because documents in a change request's scope changed.

## Preconditions
An accepted change request whose scope contains X; drift findings for the change request exist.

## Steps
Edit X and commit the change on the change request's branch.

## Expected result
The hook output contains no finding about the change request and the commit is not aborted because of it.

## Notes
Derived from design appendix A, BOOT-303.
