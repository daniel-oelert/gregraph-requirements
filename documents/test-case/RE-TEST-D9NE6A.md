# Verify: identifiers include the configured type abbreviation

## Objective

Verify that documents and change requests use typed identifiers derived from the configured prefix, the type abbreviation (CHG for CRs) and the UUID body.

## Preconditions

A config-schema-2 repository whose types have unique 3-5 character abbreviations and whose prefix is RE.

## Steps

Create documents of at least two types and one change request; inspect their sidecars and filenames; run gregraph validate; change one type abbreviation in config.toml and run validate again.

## Expected result

Every ID matches RE-<ABBREV>-<BODY>, filenames equal the sidecar id, the first validate run reports no identifier errors, and the changed abbreviation produces E-TYPE-ABBREVIATION-CHANGED for existing documents.

## Notes

*Add supporting notes, links, or open questions.*
