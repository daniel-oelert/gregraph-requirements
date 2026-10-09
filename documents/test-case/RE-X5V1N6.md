# Verify: init creates the layout, templates, config, and hook

## Objective
Verify that `gregraph init` creates the repository layout, copies all built-in templates as version 1, writes the default configuration, and installs the pre-commit hook.

## Preconditions
An empty directory that does not contain `.gregraph/`; Git is available.

## Steps
Run `gregraph init` in the directory.

## Expected result
The repository layout exists, `.gregraph/templates/` holds every built-in template at version 1, `config.toml` holds the default configuration, and the pre-commit hook is installed.

## Notes
*Add supporting notes, links, or open questions.*
