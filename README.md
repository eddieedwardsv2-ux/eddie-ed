# Eddie-Ed transcript archive

Portable raw-transcript vault for Charlie's AI research.

This repository is deliberately separate from the active AI-OS implementation. It preserves source evidence so a future AI-OS can start clean and re-ingest the corpus without depending on today's `Test-environment-` architecture.

## Archive policy

- Raw transcripts are preserved as source evidence.
- Active AI-OS repos may read/import them but should not rewrite the archived originals.
- Derived brains, summaries, rules, skills and system architecture should live elsewhere.
- Filenames retain a human-readable title and stable YouTube ID.
- Future transcript backups should be additive.
- This repository is public, matching Charlie's requested visibility.

## Snapshot

Source repository: `eddieedwardsv2-ux/Test-environment-`  
Source branch: `main`  
Raw transcripts archived: **111**

- andrej-karpathy: 4
- nate-herk: 73
- nick-saraev: 10
- the-next-new-thing: 24

Integrity check on 12 October 2026: **PASS**  
Missing: 0  
Unexpected extras: 0  
Empty files: 0  
Blob mismatches: 0

See `manifest.json` for the machine-readable inventory and `manifest.md` for the human-readable list.

## Latest transfer check

Four zero-byte archive files were restored from their source originals on 12 October 2026 (three Nate courses and one Nick video). All 111 raw transcripts now match source blob hashes and byte sizes. No additional raw-transcript video IDs were found across Test-environment's 14 branches or Kit-v1 main. AI Impact currently retains derived notes, not raw scripts.

See [transfer receipt](transfers/2026-10-12.md) for the exact repair and scope.
