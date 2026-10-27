# Standard sync — the update ledger

This is the one file that says how this brain relates to the `parker-brain` factory: which release it runs, what posture it holds toward updates, and every offer the team has already answered. `/update-brain` owns it from here; `/disconnect-factory` flips the posture; nothing else edits the header block.

## Where this brain stands

- **Factory remote:** https://github.com/real-simple-labs/parker-brain (per `.gitmodules`)
- **Posture:** `follow`
- **Pinned release:** v22 — `parker-system/` submodule checked out at tag v22 (commit 65a2691, tagged 2026-09-15)
- **Migrations applied through:** v22 (fresh build on v22; no migration needed)
- **Last compared:** 2026-10-27 against v22 (newest tag seen locally; not checked against the remote)
- **Repo management:** local repo, no git remote set as of 2026-10-27; not yet provisioned through `setup_parker_brain` (Parker MCP not connected for this brand)

## Offer history

Append one line per offer, newest first: date — item — taken / declined (why, if given) / deferred. A declined item stays quiet until the factory version of that item moves again.

No offers yet — first /update-brain run fills this in.
