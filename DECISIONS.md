# Decisions Log

Developer rulings for this repo. Each entry has a short code (`D-`) and a plain name. Entries are never
silently edited: a later ruling supersedes an earlier one by citing it, and the earlier entry stays.

Anything not recorded here is `Proposed:` (see `CLAUDE.md` rule 6).

---

## D-1 · Anthro creators are Aliens, Humans, and/or Robots
**Date:** 2026-10-21 · **Source:** developer, in session.

> "The anthros were mostly created by either Aliens, Humans, or Robots (sometimes, possibly a collaboration
> of two, sometimes possibly all, of the above)."

**Consequences for method** (recorded so they aren't re-derived):
- **The creator is a variable, not a species-wide constant.** The unit of origin is the **creator lineage**:
  one engineering program by one creator set. There are seven possible creator sets: A, H, R, A+H, A+R, H+R,
  and A+H+R. "Mostly" leaves room for other origins (Q-16).
- **L0 (Origin Frame) is written per lineage,** not per species.
- **L1 (Physiology) becomes a species baseline plus per-lineage deltas,** because each creator set made its own
  engineering choices.
- **L3 (Inherited Stock) is per lineage.** A lineage's starting culture is its creators' culture:
  - human culture for H;
  - the robot meta-culture (`Robot_Universals`) for R;
  - alien culture for A, unknown so far;
  - for collaborations, a composite. CST Composition Merge is the existing tool for composites.
- **M-4 (Creator Intent & Drift) runs per lineage.**
- **Creator type is a *condition*, never an essence.** "Robot-made rabbit-people do X because robots made them"
  is not an answer. "…because the robot design charter specified Y" or "…because their inherited robot stock
  carries Z" is.

**Supersedes:** the phrase "genetically engineered by humans" in
`TepenianUniverseTimeline/Reference/Doll_Representation_Categories.md` (Category 2). That file has **not**
been edited. Updating it needs a separate go-ahead (`CLAUDE.md` rule 8; tracked as Q-18).

**Does not change:** elves (still engineered by aliens on a parallel Earth, per canon) and aliens (origin
still unknown).

---

## D-2 · Locations are known only in the vaguest, most generalized terms
**Date:** 2026-10-21 · **Source:** developer, in session.

> "The 'locations' can only be assumed in the vaguest, haziest, most generalized terms, because I haven't
> figured out those worlds yet."

**Consequences for method:**
- **L4 (Populations) is deferred** until worlds exist. No ULM location passes and no location-level CST or
  RWBEM runs until then.
- **Environmental claims use generic archetypes only** (for example "orbital habitat," "planetary surface,
  unspecified," "the parallel Earth"). Each must be marked `[hazy]` and written as conditional: "*if* the
  habitat is X, then…". No planet, settlement, climate, or geography is to be invented.
- **Physiological environmental tolerances (P-9)** are still in scope. They are properties of the body, not
  the world.
- **L3 divergence** can be described as mechanism and pace (P-5, M-7), never as a specific local outcome.
- **The current work focus is the location-independent layers:** L0 questions, L1, L2, L3 stock, and the
  method drafts.

---

## D-3 · Proceed with `MASTER_PLAN.md` as the working approach
**Date:** 2026-10-21 · **Source:** developer, in session ("go ahead and start piecing through the process").

The plan's architecture, sequence, and proposed standing rules are adopted as the **working** approach.
They are written into `CLAUDE.md` so sessions follow them. Individual items stay open to revision. Open
questions in `OPEN_QUESTIONS.md` are **not** answered by this decision, including Q-8 (fork vs.
parameterize), whose proposed default is used provisionally.

---

## D-4 · Pilot base animal: the European rabbit (*Oryctolagus cuniculus*)
**Date:** 2026-10-21 · **Source:** developer, in session ("as a test run, I suppose we can start with that").

The rabbit-people pilot uses *Oryctolagus cuniculus* as its base species. **Scope:** accepted *as a test
run*. It answers Q-4 for rabbit-people at the species level only. Which populations within the species count
(wild, feral, domestic) is still decided by M-2's sequencing rule and each lineage's charter. Q-4 for
dog-people and cat-people stays open.

---

## D-5 · Hybridized races will very likely have multiple lineages
**Date:** 2026-10-21 · **Source:** developer, in session.

> "In terms of all of the hybridized races, in all likelihood, probably, there will very likely be some
> degree of multiple lineages."

**Consequences for method:**
- **Every hybrid species is built for more than one creator lineage by default.** L1 is a species baseline
  plus lineage deltas, and L0, M-4, and L3 are per lineage.
- **The species floor (L2) is what survives the M-3 Step 7 lineage test.** Anything true of only some lineages
  is lineage-level, not floor.
- **Still open:** which lineages exist for each species, their creator sets (Q-14), and whether lineages
  interbreed (Q-15). Until those are answered, pilot lineage work uses placeholder lineages, marked
  `[Proposed]`. They are sketches for exercising the method, not canon.

Partly answers Q-14.

---

## D-6 · Research the real Alpha Centauri system
**Date:** 2026-10-21 · **Source:** developer, in session ("Absolutely, you definitely should").

M-5 may research the real Alpha Centauri / Proxima system from published astronomy, under LAW 0-R. Answers
Q-26. **D-2 still applies to *worlds*:** real astronomical data is in scope, but no specific settled planet,
habitat, or geography is to be built from it without a ruling.

---

## D-7 · The plausibility standard: "a humanized lizard, never a California college student"
**Date:** 2026-10-21 · **Source:** developer, in session. **Binding on every race.**

> "There will always be some degree of hand-waving, to some extent or another, but I do want to maintain as
> much realism as possible, while still being entertaining to the audience. For example, if a lizard that has
> been anthropomorphized into an anthro-hybrid form will act like a humanized lizard, and some degree of
> variance will be believable. She will always have some aspect, some degree, some variance, some extent of
> lizard about her. However, if that anthropomorphized lizard behaves like a coffee shop-dwelling college
> student from California, that would be completely preposterous. So, hand-waving within the realm of
> plausibility is acceptable. Hand-waving that's completely fantastical is not."

**What it means for method:**
1. **The animal side always remains.** Every hybrid race keeps *some* degree of its animal side in how it
   behaves, not only in how it looks. A race that resolves to human behavior with animal cosmetics fails this
   standard, however well each individual trait was argued.
2. **Variance is believable and expected.** Individuals and lineages vary in *how much* and *which* animal
   traits show. L1 records a range, not a single point.
3. **The failure case is a specific human persona transplanted whole.** Human culture can legitimately reach a
   race (for example, an H-lineage raised inside human society). But it always arrives *through this body*
   (Embodiment Fit, M-6 Step A4), so it is bent by that body. Human culture worn with no animal residue is
   the "California college student" failure.
4. **Handwaves are allowed within plausibility.** Every handwave is logged in `HANDWAVES.md` with what is
   waved and what is **not** waved, following the Inner Tepenia handwave-register precedent. A handwave that
   no real mechanism could approach is "completely fantastical" and is rejected.
5. **Entertainment is a real goal.** Among plausible options, the audience must be able to *read* the animal
   side. Choosing the more legible plausible option is legitimate; choosing an implausible one for effect
   is not.

**Supersedes:** M-1's "humans with ears" alarm was a soft review trigger. It is now a binding check (M-1
guards).

---

## D-8 · Six new settings-sheet parameters (P-10 to P-15) and four field extensions
**Date:** 2026-10-21 · **Source:** developer, in session ("in that case, yes"), after a plain-language
explanation of Q-23.

The consolidated proposal in `methods/adapters/Human_Assumptions_Register/README.md` is accepted into the
parameter-sheet template:
- **New parameters:**
  - P-10 · Body plan, scale, locomotion, and integument
  - P-11 · Mating system and pair-bond form
  - P-12 · Enculturation and transmission mode
  - P-13 · Dispersal and philopatry
  - P-14 · Sex differences and dimorphism
  - P-15 · Cognitive profile and temperament (every value needs a mechanism chain, per `CLAUDE.md` rule 3)
- **Field extensions:**
  - P-2: adult-equivalent population
  - P-4: recognition channel
  - P-6: whether a senescent or post-reproductive stage exists
  - P-8: signal control
- **Derived value (M-7):** Culture-Bearing Weight.
- **Housekeeping, same day:** two fields named in the registers were added as sub-fields, with no new codes. They are the founding-generation production mode in P-2 (HAR-HUF-38) and the number of sexes in P-14 (HAR-HUF-22). The recognition channel sits in P-4, as accepted, not in P-8 as HAR-ULM-02 suggested.

Answers Q-23 and unblocks the M-0b adapter notes. The rabbit pilot tests every parameter. Any that prove
unneeded are flagged at the Phase 4 retrospective.
