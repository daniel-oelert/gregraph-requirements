# Verify: missing arguments prompt or fail under --no-input

## Objective
Verify that a missing required argument prompts with a filtered picker on a terminal and fails under `--no-input`.

## Preconditions
One run with stdin as a terminal and one run with `--no-input`; both omit a required argument.

## Steps
Run `gregraph new` without a type or title in both setups.

## Expected result
The interactive run shows a filtered picker; the `--no-input` run fails as a usage error.

## Notes
*Add supporting notes, links, or open questions.*
