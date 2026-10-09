# Verify: cycle-creating links are refused with the cycle path

## Objective
Verify that a link that would create a directed cycle is refused and the cycle path is printed.

## Preconditions
A repository with document A linked `refines` to document B.

## Steps
Request the link `B depends-on A`.

## Expected result
The tool exits with code 4 and prints the cycle A through B back to A.

## Notes
Derived from design appendix A, BOOT-300.
