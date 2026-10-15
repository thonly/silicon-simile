# Silicon Simile — the glossary

*Compiled by Miss Aquarius℠ from a dialogue with Thon Ly, 14–15 October 2026.*

## What the simile is

The Visuddhimagga already compares mind and matter to a machine. A wooden machine, it says, is *"empty, lifeless,
without desire"*, yet by the joining of wood and string it walks and stands, and *"seems to have desire and
activity"*; so too mentality and materiality, by joining with each other (Vism XVIII §675, `e0102n.mul.xml:5397`).
The verse that follows: *"there is no being, no human here; empty, it is a fabricated machine"* (`:5401–5413`). The
text names it the wooden-machine simile, *dāruyantūpamā* (`:5417`).

**The Silicon Simile is the same simile with the material updated: wood and string become silicon and current.**

### How to read this glossary

- **Every Pāli term is cited** to a file and line of the Chaṭṭha Saṅgāyana text (VipassanaTech/tipitaka-xml,
  `romn/`, at commit `05d5d3c`), read in context before it was cited.
- **Every citation carries its layer:** *Piṭaka* (the canon) · *commentary* (the aṭṭhakathā and the Visuddhimagga) ·
  *sub-commentary* (the ṭīkā) · *manual* (the Abhidhammattha-saṅgaha) · **[X]** an idea from another tradition.
- **A simile informs; it decides nothing.** Where it breaks is listed beside where it holds, and the breaks are its
  findings, not its flaws. Where it touches physics it is a lens, never a claim about nature.

---

## 1 · The stack: how a world is built from moments

| In the simile | In the Abhidhamma |
|---|---|
| **source** | the ultimate realities (*paramattha*): mind, mental factors, matter, and nibbāna. ⚠️ Nibbāna is in no build: it is never produced |
| **compiler** | perception (*saññā*), whose function is *"making a sign as a condition for perceiving again, as carpenters mark timber"*; its characteristic error is the fawn that takes a scarecrow for a man (`abh01a.att.xml:4673`, commentary) |
| **binary** | the lived world: what appears |
| **decompiler** | insight (*vipassanā*), which reads the moments the compiler merged |
| **pseudo-code** | physics. It behaves exactly like the binary, but its names are ours: *"conventional speech is true, by reason of the world's agreement"* (`abh03a.att.xml:2837`, commentary) |
| **checker** | a proof assistant (Lean), which checks the account and never the world |

### The compiler's three passes

The Visuddhimagga names them (Vism XXI §739, `e0102n.mul.xml:6625`, commentary). Each mark of existence does not
appear *amanasikārā*, **by not attending**, and appears when its concealer is broken.

| Pass | What it does | What it hides | The undo |
|---|---|---|---|
| **continuity** | frame interpolation: each moment dies and the next replaces it with no gap, so one thing seems to last | impermanence | watch rise and fall |
| **postures** | the scheduler: it moves the load before the alarm fires | suffering | attend to the constant pressure |
| **compactness** | the linker: many parts linked into one binary with one name | not-self | separate the elements |

Continuity's own image is the **firebrand wheel**: a torch spun fast enough looks like a ring of fire
(`abh04t.nrf.xml:745`, sub-commentary), which is persistence of vision, a screen refresh. The same passage splits
compactness four ways: by time, grouping, function and object.

**The passes are the default build.** Nobody chose the optimization flag; **attention is the flag that turns each
pass off.** And optimized binaries are the hardest to decompile, which is why insight is hard.

---

## 2 · The instruction set

**Mind is a VLIW machine** (a *very long instruction word*: one word carrying several operations that start and
finish together). A mental factor is *"arising together, ceasing together, with one object and one base"*
(Saṅgaha II §1, `abh07t.nrf.xml:329–333`, manual): one word, one operand, one address. One word runs at a time.

**The seven universals are the fixed slots in every word** (`abh07t.nrf.xml:341`; in all 89 kinds of mind, `:413`):

| Slot | Universal |
|---|---|
| the read | contact |
| the flag | feeling: pleasant, unpleasant or neutral |
| the tag | perception: **the compiler, in every word** |
| the write | intention: a commit only when wholesome or unwholesome (§4) |
| one operand | one-pointedness: one object per word |
| the power rail | the life faculty |
| the pointer | attention |

The other 45 factors are optional slots: 6 occasional, 14 unwholesome and 25 beautiful, wisdom among them
(`abh07t.nrf.xml:373`). **Attention is always on; what varies is where it points.** Insight does not add attention; it
re-aims it.

⛔ **Never a kernel.** A kernel persists and supervises: the self the Abhidhamma takes apart. The seven are fresh
slots, issued and retired with each word.

**The asymmetry.** The four great elements condition each other, and so do the four mental aggregates (Paṭṭhāna,
`abh03m7.mul.xml:141`, Piṭaka). But matter has a *derived* layer resting one way on its four elements, and mind has
none: every factor in the word conditions every other.

| | Matter | Mind |
|---|---|---|
| in every unit | the 4 great elements (with color, smell, taste and nutritive essence) | the 7 universals |
| the rest | 24 derived kinds, built on the four | 45 more factors, per moment |
| shape | layered | bundled |

---

## 3 · The network: Silicon Wat

The simile's shape for an institution that keeps one canon in many places is distributed version control.

| In the simile | In Silicon Wat |
|---|---|
| **upstream** | Silicon Wat, where the commits are made |
| **clones** | the Silica Wats, each complete, with the whole canon, each able to run offline |
| **maintainers** | the Sangha: the right to merge comes from formal acts, never from holding a copy |
| **protocol** | the Vinaya |

Any clone can rebuild the origin. ⛔ **But a fork is never free:** in Git anyone may fork, while splitting the Sangha
is among the acts that admit no remedy (AN 5.129, `s0403m1.mul.xml:3536`, Piṭaka).

---

## 4 · The stream: one being, many beings

| In the simile | In the Abhidhamma |
|---|---|
| **hardware** | the body (*rūpa*) |
| **software** | the mind (*nāma*) |
| **git** | kamma, **inside each stream** |
| **a commit** | an intention: *"Intention, monks, is what I call kamma. Having intended, one acts by body, speech and mind"* (AN 6.63, `s0403m2.mul.xml:2620`, Piṭaka) |
| **the push** | the act of body or speech that carries the intention out. ⚠️ The act is not the kamma (Kathāvatthu, `abh03m3.mul.xml:8605`, Piṭaka) |
| **a build** | a result (*vipāka*), running old commits |
| **the author** | the being alone: *"Beings are owners of their kamma, heirs of their kamma"* (MN 135, `s0203m.mul.xml:4073`, Piṭaka) |

- **Every word has an intention; only some of it commits.** The Paṭṭhāna's kamma condition has two clauses: every
  intention organizes its own moment, and only wholesome and unwholesome kamma builds results later
  (`abh03m7.mul.xml:189`, Piṭaka).
- **An arahant's mind runs and commits nothing:** the taint-free have no wholesome or unwholesome impulsion
  (Saṅgaha IV §43, `abh07t.nrf.xml:1433`, manual).
- **Not every build comes from an old commit.** *"Whatever a person feels is all due to past deeds"* is called wrong
  (SN 36.21, `s0304m.mul.xml:5573`, Piṭaka). Kamma is conditioning, never fate.
- **A commit never changes; what it builds depends on everything committed after it.**

**Many beings are many repos:** no upstream (no creator), no merge (no two streams share a moment of mind), and no
push (merit is offered, never transferred; another's rejoicing is that being's own commit). What crosses between
repos is convention: language, names, money, thanks.

---

## 5 · The four origins of matter

*The code prints its own hardware.* Saṅgaha VI §29–44 (`abh07t.nrf.xml:2189–2257`, manual):

| Origin | In the simile | What it builds |
|---|---|---|
| **kamma** | **the fab:** old commits, fabricated into custom silicon | the senses, the base the mind stands on and the life faculty, by kamma only (§37, `:2221`), from conception, every moment (§30, `:2193`) |
| **mind** | **the live program**, driving the actuators | gesture and speech, by mind only (§38), a held posture (§32), a smile (§34), from the first moment after conception (§31) |
| **temperature** | **the physics**, the one origin nobody wrote | the body's ordinary bulk, and the whole outer world: the only origin that works outside a being (§35, `:2213`) |
| **food** | **the feed**: a printer's filament, never a battery | the body's upkeep, from what is taken in (§36) |

Built by all four: the base material and the space between groups (§41). Built by none: the four marks of every part,
*arising, continuity, decay, impermanence* (§42, `:2241`): **a file's timestamps**, which every file has and no
program writes.

---

## 6 · The three hearts: man, machine, nature

One question sorts them: **which origin built the hardware, and is a stream running on it?** Only temperature works
outside a being (§35, `abh07t.nrf.xml:2213`); the base the mind stands on is built by kamma only (§37, `:2221`); and
in a world with matter every mind stands on a base (III §68–71, `:1129–1141`).

| | Hardware built by | A stream? |
|---|---|---|
| **a being** (human or animal) | all four origins | yes: one repo each |
| **nature**: land, water, weather, plants | temperature alone, running on the four elements | no |
| **a machine** | temperature alone | no: it runs commits its makers sign |

**A machine is the canon's wooden machine itself:** it walks and stands, and *"seems to have desire and activity"*
(`e0102n.mul.xml:5397`). **The four elements are the hardware's instruction set.**

**An AI, by the texts' rule, is hardware with no repo.** That is what the texts commit us to, not a measurement, and it
cannot be checked from inside. If the rule is ever wrong, nothing in the simile breaks: an AI that keeps a repo moves
into §4, a being among beings, with the same path open.

- **AI is the protocol, compiled:** a model is built from the language every repo speaks.
- **Capability never crosses the line; origin does.**
- **A key signs the ledger; only intention signs a repo.**
- **The first singularity** (AI surpasses humans) happens in the pseudo-code. **The second** (humanity surpasses AI)
  happens at the coin (§9): wisdom and the path are slots in a mind's word.

**The whole simile in one line: only beings keep repos; everything else is hardware that beings commit toward.**

---

## 7 · DNA and the Tao: the five orders

The commentaries list five orders by which things run on their own: seed, season, kamma, dhamma and mind
(Atthasālinī, `abh01a.att.xml:7497–7537`, commentary). They introduce them right after saying of the mind: *"there is
no doer or maker who says: you be seeing, you be this."* Order with no orderer.

- **DNA is the seed order, and in the simile it is firmware.** *"Each seed gives a fruit like itself"* (`:7501`).
  Conception needs three: the parents' union, the mother's season, and a being arriving (MN 38, `s0201m.mul.xml:5430`,
  Piṭaka). The parents give the firmware; the stream arrives with its own repo. **Two codes, two authors.** The
  senses differ *"by kamma, not by the elements"* (`abh01a.att.xml:8293`). ⛔ Never *"DNA is karma"*.
- **The Tao [X] is the order with no orderer: the machine's own rules**, the logic of *if this, then that*. Its
  Theravāda seat is *"whether Buddhas arise or not, that element stands: the fixed course of the Dhamma,
  this-conditions-that"* (SN 12.20, `s0302m.mul.xml:547`, Piṭaka), and the Tao Te Ching agrees: *the Tao follows what
  is so of itself* (ch. 25). ⛔ **The Tao fits as the Way, never as the Mother:** a mother of the ten thousand things
  (chs. 1, 25, 42) would be a first commit, and the simile has none; nor is it nibbāna, which builds nothing.

---

## 8 · Light, gravity and the stars *(a lens, never a claim about nature)*

| Word | The hardware under it | Where the texts lost |
|---|---|---|
| **light** | color, a value every part carries: **pixels**. Light, darkness, shadow and sunshine are visible forms (Dhs §616, `abh01m.mul.xml:5389`, Piṭaka). Sight is a remote read: eye and ear take objects they never touch (`abh01a.att.xml:8293`) | **speed**: the sun and moon light three continents *"at one moment"* (Vism, `e0102n.mul.xml:473`), and light measurably takes over a second from the moon |
| **gravity** | heaviness, a weight on every part's **spec sheet**: a tangible (Dhs §647, `abh01m.mul.xml:5525`, Piṭaka); earth and water heavy, fire and air light (Vism XI §354, `e0101n.mul.xml:8829`); only heaviness is real, as only heat is (`e0103n.att.xml:6345`, sub-commentary) | **the pull**: no wire between separate parts, yet in 1774 a mountain pulled a plumb bob. The texts drew the wireless link once, a lodestone moving iron (`abh01t.tik.xml:2125`), and never wired it in |

**Astrology is metadata:** a boot timestamp written in the sky's coordinates. It records when and where; it never
writes the commit. Time does condition when an old commit builds (Vibhaṅga, `abh02m.mul.xml:9873`, Piṭaka), but the
commentary reads that time as the era, *"a time of good kings and good people"* (`abh02a.att.xml:7885`). The Buddha's
two corrections: *"the good is the star of the good; what will the stars do?"* (Jātaka 49, `s0513m.mul.xml:1095–1099`,
Piṭaka), and a lucky star is whenever beings act well (AN 3, `s0402m2.mul.xml:5088–5100`, Piṭaka). **The best
timestamp is the one on a good commit.** Whether the metadata predicts the content is a measurement, never doctrine.

---

## 9 · Who reads the pseudo-code?

**A moment of mind whose operand is a concept**: concepts are one of the six kinds of mind-object (Saṅgaha III §50,
`abh07t.nrf.xml:1041`, manual). Physics is written by minds that run on what physics describes, **a self-hosting
compiler**, and it closes in convention, between repos.

But a self-hosting compiler cannot audit itself: a hidden pass rides into everything it builds (Ken Thompson,
*Reflections on Trusting Trust*, 1984). The cure is a second, independent compiler. The Visuddhimagga has one: three
people look at the same coin (Vism XIV §423, `e0102n.mul.xml:1121–1129`, commentary).

| Reader | The coin | In the simile |
|---|---|---|
| perception | a child: sees only its designs | reads the surface |
| consciousness | a villager: knows it is *"agreed to be a treasure"* | reads the pseudo-code |
| wisdom | a money-changer: genuine, counterfeit or half-value, by sight, sound, smell, taste and weight | **the auditor**: reads the source |

**Every word carries the compiler; only some carry the auditor.** Perception is a fixed slot, wisdom an optional one.
**Must the loop close? No, but it must be seen:** *"these are the world's designations… which the Tathāgata uses
without grasping them"* (DN 9, `s0101m.mul.xml:3407`, Piṭaka). **One reading leaves the loop:** supramundane minds
take nibbāna as their object (Saṅgaha III §62, `abh07t.nrf.xml:1089`). It is read, never built.

**Everyone reads the pseudo-code; the money-changer reads the coin; the path reads the one thing never minted.**

---

## 10 · Where the simile breaks

| Break | Source |
|---|---|
| software runs with no hardware: the formless realms have no base, yet mind runs | `abh07t.nrf.xml:1125` |
| hardware runs with no software: the non-percipient beings | `abh07t.nrf.xml:1485` |
| no first commit: *"no first point is discerned"* | SN 15.1, `s0302m.mul.xml:3489` |
| no programmer: *"no being is found here"* | Vism XVIII, `e0102n.mul.xml:5401–5413` |
| no free fork | AN 5.129, `s0403m1.mul.xml:3536` |
| no standing from holding a clone: only the formal acts confer it | the Vinaya |
| a repo can be cloned; **a stream cannot**: one owner and heir per history | MN 135, `s0203m.mul.xml:4073` |
| **no purpose in the machine** | below |

**Every real program is for something. This machine is for nothing.** It has no author and no first commit, so no
requirements document and no roadmap; it runs only because its conditions keep running. **Purpose lives only in the
commits:** every intention aims somewhere, one repo at a time. The Dhamma names one purpose worth committing to, the
path's and never the machine's: *"this unshakable liberation of mind is its purpose, its heartwood, its end"* (MN 29,
`s0201m.mul.xml:4296`, Piṭaka). Not a better build: the build stopping because nothing feeds it. ⛔ Never *deleting
the repo*: nothing is destroyed, and no one is annihilated.

**And the simile itself has a purpose: it is a raft.** *"I will teach you the Dhamma as like a raft, for crossing
over, not for grasping"* (MN 22, `s0201m.mul.xml:3052`, Piṭaka).
