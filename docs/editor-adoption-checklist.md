# Editor adoption checklist

Use this checklist before adding or migrating editor functionality in a Good-Unity repository.

## Audit
- Search for old editor packages.
- Search for duplicated editor config.
- Search for inline toolbar definitions.
- Search for repeated upload logic.
- Search for page-level style overrides.

## Required outputs
- src/editor or packages/editor structure
- central config file
- central toolbar file
- central upload adapter
- scoped styles
- subsystem README
- migration note if replacing existing editor logic

## Verification
- render test passes
- build passes
- upload flow verified
- custom features verified
- no duplicated config remains

## Review questions
- Is the editor modular?
- Is the plugin list explicit?
- Can another repo reuse this subsystem?
- Will future upgrades be straightforward?
