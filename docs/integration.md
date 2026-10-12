# sahcore integration

Nothing in the suite calls sahcore. `opensah tools` reports it as `not_built` and `unassigned`. `sahapi` `/v1/suite` reports the same.

The suite contract is `~/development/systemapi.io/docs/sah-suite.md`.

When a role is assigned, add the program in a later change and update `opensah` `internal/suite/suite.go`, the sahapi suite JSON, and the suite contract in that same change.

## Next

Leave this directory as documentation.
