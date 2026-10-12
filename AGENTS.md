# AGENTS.md

sahcore is unassigned. This repository is documentation so the name stays reserved.

Suite contract: `~/development/systemapi.io/docs/sah-suite.md`.

## Do this

1. Read this file before adding anything.
2. Documentation edits stay inside README, `docs/`, `AGENTS.md`, and `CLAUDE.md`. Done when `git status` shows no source files.

## Rules

- Do not add a Go module, a binary, a server, or a client. A program would invent a product that has no role.
- Do not rename `adssh` into sahcore. adssh stays the execution shell (`github.com/afterdarksys/adssh`).
- Do not describe sahcore as the control plane or the compute catalog. Those are systemapi.io and computeapi.io.
- When a role is assigned, update opensah's catalog, sahapi's suite JSON, and the suite contract in the same change as the new program.

## Next

Do not scaffold code.
