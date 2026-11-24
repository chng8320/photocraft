# This fork: PhotoCraft for the Dataverse

This is the Dataverse's fork of [PhotoCraft](https://github.com/storytold/photocraft) by the ArtCraft team
(MIT OR Apache-2.0). The Dataverse runs its command line on the main server, headless, as the `pdfcraft`
package.

## Branches

| Branch | What it is |
|---|---|
| `main` | Exactly ArtCraft's `main`. Never commit here; it is only updated from them. |
| `dataverse` | `main` plus our own commits on top. This is what the Dataverse builds. |

Each of our changes is one commit on `dataverse`, following the app's own guide to adding a command,
so it replays cleanly on every new PhotoCraft and can be offered back as a pull request. PhotoCraft's rules for
contributors (`AGENTS.md`) apply to our commits too: in particular, no code read from GPL, LGPL or AGPL
programs.

## Keeping up with PhotoCraft

`.github/workflows/dataverse.yml` runs every Monday (and on demand from the Actions tab): it updates `main`
from ArtCraft, replays our commits on `dataverse` (opening an issue when one no longer applies), builds the
command line, runs the automation tests and attaches the program as `dataverse-photo-cli` (Linux x86-64).

## Our changes

| Commit | What | Offered upstream? |
|---|---|---|
| (none yet) | | |

## Name

The ArtCraft name and logos are trademarks, not covered by the code licence; modified versions must not use
them. Our build is called `dataverse-photo-cli` and is described as "based on PhotoCraft by the ArtCraft team".
