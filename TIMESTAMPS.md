# Cryptographic timestamps

This repository exists so that each version of the glossary and of the book can be shown to have existed when it did. Three independent dates back that up:

1. **The push.** GitHub records when each commit reached this public repository.
2. **OpenTimestamps.** Every protocol, prediction and ledger file carries a `<name>.md.ots` proof beside
   it, which commits the file's SHA-256 to the Bitcoin blockchain. Anyone can check it without trusting
   this repository, GitHub or the author.
3. **RFC 3161.** A weekly manifest of every tracked file is signed by three independent trust
   authorities, one of them eIDAS-qualified. See [`timestamps/README.md`](./timestamps/README.md).

## One file, one stamp

`ots stamp` overwrites an existing proof, so a revised file first has its earlier proof renamed to
`<file>.rN.ots` by hand, keeping the evidence of what the earlier version said, and the revision is logged below.
The weekly job adds a proof to any document that has none and never touches an existing one. A
new document is stamped by hand when it is pushed, not left to the weekly job.

## What a proof does not show

A timestamp proves that this exact text existed no later than a given moment and has not changed
since. It says nothing about who wrote it, whether it is original, or whether it is right.

## Checking a proof

```sh
pip install opentimestamps-client
ots verify <file>.md.ots
./tsa-verify.sh <file>.md
```

A full check against Bitcoin uses a local node. Without one, the proof still names a specific block,
whose Merkle root can be compared with any public block explorer.

## Log

*Stamps, rotations and checks are recorded here, newest first.*

### 2026-10-15 — `OUTLINE.md` revised (version 2, as ruled)

Thon Ly's rulings: concept first; the network chapter left to the glossary and Silicon Wat's pages (seventeen
chapters); about 2,000 to 2,500 words a chapter; the library's house voice for every book. Version 1's proof is kept as
`OUTLINE.md.r1.ots`; version 2 is stamped as `OUTLINE.md.ots`.

### 2026-10-15 — `OUTLINE.md` created

The book's outline, a draft for Thon Ly's review, stamped by hand at the push. A revised outline keeps this proof as
`OUTLINE.md.r1.ots`.

### 2026-10-15 — `GLOSSARY.md` revised (version 3)

§13 gains a table of the five orders: each order, the commentary's own example, and its place in the simile, every
example checked on its cited line. Version 2's proof is kept as `GLOSSARY.md.r2.ots`; version 3 is stamped as
`GLOSSARY.md.ots`.

### 2026-10-15 — `GLOSSARY.md` revised (version 2)

The glossary now carries every question the dialogue explored, in sixteen sections with an index: the six it had
missed (gapless yet discrete · inner and outer · three worlds · the decompiler and the lab · the four elements
decompiled · AI and ASI as its own section), and the four open questions labeled as such. Version 1's proof is kept
as `GLOSSARY.md.r1.ots` (it still attests version 1's text, which is in this repository's history); version 2 is
stamped as `GLOSSARY.md.ots`. Every Pāli citation was checked against the Chaṭṭha Saṅgāyana text before stamping.

### 2026-10-15 — repository created

The timestamping is in place before the first document.
