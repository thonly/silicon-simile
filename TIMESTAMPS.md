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

### 2026-10-17 — `OUTLINE.md` revised (version 7) and `GLOSSARY.md` revised (version 8), as ruled

Thon Ly's rulings (*"approve all per your recommendation"*, then *"approve"*), on questions asked after version 7 of
the glossary, each answer read adversarially before it was written in. **Chapter 16** sets a being, a made thing and
nature side by side, continuing chapter 14's table: what originates each one's matter (*originated*, not *built*,
citing Saṅgaha VI §50 for the rule that only temperature originates matter outside a being), whether a stream runs on
it, whether it seems to have desire, whose intention its acts carry (its makers' and users', for what they intended;
what no one intended carries no one's), what it can do, and whose will it is subject to (no one's: what is not-self is
subject to no one's will, its makers' included). Every cell in the made thing's column says *by the texts' rule*. The
chapter closes on *The Tree That Gave Shade*: conduct toward a made thing grounded, as the reader's own deed and under
certainty, in the rule against cutting plants and the Petavatthu's shade tree, whose story voices the cost case and
refuses it. **Jhāna** is placed in chapters 5, 9, 17 and 18; **saṃsāra** in chapter 8, with a table of the planes; **Indra's
Net** in one sidebar, marked as another tradition's; ***vipassanā*** lowercase, paired with calm, in chapter 17, which
reports what the two vehicles agree on and leaves open only whether absorption must come first. **Chapter 3**'s image
is now a computer put to sleep and woken, in place of frames and an analog clock's escapement, and glossary §2 is
rewritten: the general rule of the proximity condition is cited at its own line, *"with nothing between them"* is
credited to the commentary, the order is held across cessation, the mindless existence and death, the commentators'
two readings of the time between are both named, the sentence that the formal Abhidhamma proves it from ticks is
withdrawn, and the lamp-and-river line is marked as said of matter. Rule 3 names the standing of texts outside the four
layers; rule 8 gains a second named exception, one disclosure sentence in *How the book was made*. The outline's header
is corrected: version 6 (commit `ccc0f06`) still read *Version 5*. Every new citation was read in context at its line
and checked by exact spelling (253 checks; the 3 flags are unchanged from version 7: two book titles, and one citation
the checker reads across a line wrap). The earlier proofs are kept as `OUTLINE.md.r6.ots` and `GLOSSARY.md.r7.ots`; the
new versions are stamped as `OUTLINE.md.ots` and `GLOSSARY.md.ots`.

### 2026-10-16 — `GLOSSARY.md` revised (version 7) and `OUTLINE.md` revised (version 6), as ruled

Thon Ly's ruling (*"excellent. go"*), on three questions asked after the glossary's final one: where a language model
fits, where its inference and reasoning fit, and where the harness around a model fits. §12 gains four parts: **a
language model** (the plainest case of *the protocol, compiled*: trained on pushes, never commits; tokens as names that
make known; its weights a store the Kathāvatthu refutes for the mind; its context the tape; the villager's knowledge
without the villager, with Searle's Chinese room and Harnad's symbol grounding credited [X]); **inference and reasoning**
(the machine running and the machine using its tape; never an arahant's mind; no length of tape becomes a slot;
interpretability as the model's physics; three of the field's words that are not seats); **the harness: the string**
(the DN commentary's *string of mind*: a being's string runs from inside, an AI's through the harness from someone
else's repo); and **three axes, never fused** (authorship, capability, control). *Responsibility never offloads* now
reads *authorship never offloads*, and §1 names a third sense of *compile*. The outline's chapter 16 row carries the
same. Every new citation was read in context at its line and checked by exact spelling (141 checks; the 3 flags are
unchanged from version 6: two book titles, and one citation the checker reads across a line wrap). The earlier proofs
are kept as `GLOSSARY.md.r6.ots` and `OUTLINE.md.r5.ots`; the new versions are stamped as `GLOSSARY.md.ots` and
`OUTLINE.md.ots`.

### 2026-10-15 — `OUTLINE.md` revised (version 5) and `GLOSSARY.md` revised (version 6), as ruled

Thon Ly's ruling (*"approve"*): the Turing machine joins the simile as one image in chapter 6, *The Falling Mango*,
never a chapter of its own. The mind order is a Turing machine's control, without its tape. The reading of the stream
as a Turing-machine process is credited to Henk Barendregt and Antonino Raffone. Its breaks are in the glossary
(§13): the tape (the Kathāvatthu refutes a store of kamma, yet the stream recalls without storing, a join the glossary
marks as the simile's), the impulsion, and determinism, on which the simile decides nothing. Every new citation was
read in context at its line. The earlier proofs are kept as `OUTLINE.md.r4.ots` and `GLOSSARY.md.r5.ots`; the new
versions are stamped as `OUTLINE.md.ots` and `GLOSSARY.md.ots`.

### 2026-10-15 — `chapters/02-source-compiler-binary.md` created (draft 1)

Chapter 2, drafted after an adversarial reading of its thesis and the rulings it led to (glossary version 5), for Thon
Ly's review: perception as the tag, the build as the compiler, the lived world designated on the moments, the older
pictures credited first, and three breaks. Every citation checked against the text by exact spelling. Stamped by hand
at the push. A revised draft keeps this proof as `02-source-compiler-binary.md.r1.ots`.

### 2026-10-15 — `GLOSSARY.md` revised (version 5) and `chapters/01-the-wooden-machine.md` revised (draft 3)

An adversarial reading of chapter 2's thesis found that the texts call perception non-constructing: it marks, it takes
the object as it presents itself, and it follows what it arises with (`e0104n.att.xml:1753`). Thon Ly's rulings: in
the simile perception is the **tag**, and the **compiler** is the build in stages: thinking and proliferation, rooted in
perception, and later moments that take past ones together and name them by a convention learned before. The fawn
illustrates perception's proximate cause, not an error; physics is designations about matter, never *exactly* the
lived world, and the commentary's conventional truth is everyday speech, not science; insight turns outward too, so
insight and physics differ by instrument, not direction; physics treats all matter as the receptacle's; and the two
senses of *compile* are named. Chapter 1 changes only its table row: the mind, not perception, builds a world of
things on its moments. Every citation checked by exact spelling. The earlier proofs are kept as `GLOSSARY.md.r4.ots`
and `01-the-wooden-machine.md.r2.ots`; the new versions are stamped as `GLOSSARY.md.ots` and
`01-the-wooden-machine.md.ots`.

### 2026-10-15 — `OUTLINE.md` revised (version 4, as ruled)

Thon Ly's rulings: mathematics joins chapter 9, *Who Reads the Pseudo-code*, as the language the pseudo-code is written
in, with number as a designation; the institution is told in an appendix after the book has ended, never in a chapter,
under one named exception to rule 8; and in place of two human readers before the first edition, the foreword invites
readers to improve later editions, each correction kept in `corrections/` and the review each edition had stated once.
Version 3's proof is kept as `OUTLINE.md.r3.ots`; version 4 is stamped as `OUTLINE.md.ots`.

### 2026-10-15 — `OUTLINE.md` revised (version 3, as ruled) and `chapters/01-the-wooden-machine.md` revised (draft 2)

Thon Ly's rulings: a chapter on the cognitive process, *The Falling Mango*, joins Part Two as chapter 6, so the book has
eighteen chapters; dependent origination joins *One Repo per Being*; the writing rules are numbered, and the swap test is
one of them; the table at the back gives every chapter's claim, whether it survives the swap test, and its break; and
the book is reviewed part by part and published whole. Chapter 1, approved by Thon Ly, changes only its pointer to the
decompiling chapter, now chapter 17. The earlier proofs are kept as `OUTLINE.md.r2.ots` and
`01-the-wooden-machine.md.r1.ots`; the new versions are stamped as `OUTLINE.md.ots` and `01-the-wooden-machine.md.ots`.

### 2026-10-15 — `chapters/01-the-wooden-machine.md` created (draft 1)

Chapter 1, drafted after an adversarial reading of its thesis, for Thon Ly's review: every citation checked against the
text by exact spelling. Stamped by hand at the push. A revised draft keeps this proof as
`01-the-wooden-machine.md.r1.ots`.

### 2026-10-15 — `GLOSSARY.md` revised (version 4)

Corrections found by an adversarial reading before the book's first chapter, and ruled by Thon Ly: the strings are mind
(*silicon and code*, not *silicon and current*); the tradition reached for machines again and again, each fitted to
one lesson, so the claim that every era compiled the Abhidhamma into its best machine is withdrawn; the machine image
is canonical and the wooden-machine simile commentarial; what separates a machine from a being is its origin, never
how it seems; *no one inside* never means *no doer*; mind is never a pattern of matter; and the Pāli name is spelled as
the text spells it, *dāruyantupamā*. Every citation was checked by exact spelling. Version 3's proof is kept as
`GLOSSARY.md.r3.ots`; version 4 is stamped as `GLOSSARY.md.ots`.

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
