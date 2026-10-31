# CST Adapter (M-0b)
**Status:** Proposed v0.1, 2026-10-21. Plug-in map for running the Cultural Synthesis Techniques unchanged on a
non-human race. Original: `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Cultural_Synthesis_Techniques.md`.
Nothing here edits the original (`CLAUDE.md` rule 8).

**Register this maps:** `Human_Assumptions_Register/HAR_CST.md` (39 entries: 7 Blocking, 27 Adjust, 5 Cosmetic).
It also maps the CST entries of `HAR_ULM.md` (HAR-ULM-40 to -47), which sweep the ULM's copy of CST.
**What this file is:** patch notes. For every Blocking and Adjust entry, it says what a CST run does differently
when its subject population includes a race from this repo, and what supplies the substitute. It never restates
or replaces CST text.

**Line references.** `CST:` cites the original (1,194 lines). `CST-copy:` cites the ULM copy,
`Universal_Location_Methodology/Disciplines/Cultural_Synthesis_Techniques.md`. Its offset from the original is
about +95 lines through Technique 1 and +21 in the Composition Merge (`HAR_CST.md` header). Both copies carry the
same human assumptions, so one row covers an entry and its twin. Line numbers are from the 2026-10-21 sweep;
re-check before relying on one.

**Race-document keys:** as in `ULM_Adapter.md` (L0, M-4 charter, L1, sheet, L2, L3 under `races/<Species>/`).

---

## When this adapter applies (and D-2 note: which parts are usable now vs. deferred to L4)
**Applies to:** any CST run on a location whose population includes one or more races from this repo, and the
parts of CST that this repo reuses for L3.

**D-2: CST is mostly an L4 tool.** Every technique reads a finished ULM location pass (the source map,
`CST:83-101`), and CST runs corpus-wide only after the ULM (`DR-14`). No location exists for these races, so
most rows wait for Phase 7. Each row is tagged:
- `[Now]`: in scope today, for L3 inherited stock. This covers the "other half" of the GPS law (stock = the
  creators' culture), the divergence operator's missing body term (Embodiment Fit), the Acts and elapsed-time
  rules as pace, and the Composition Merge as reused by **M-6 Mode A** (creator-stock merge for collaboration
  lineages).
- `[L4]`: applies only once a location pass exists. This includes M-6 Mode B (settlement merge).
- **R5 is usable in neither mode** until M-7 produces per-race bands (row HAR-CST-34).

## Read before a pass
1. **The race's L1 document, in full, general before narrow** (ULM `03` §0.2 Mechanic 9). Never infer from the
   race's name (`CLAUDE.md` rule 2).
2. **The race's parameter sheet** (P-1 to P-15, the D-8 field extensions, and the derived values, including
   Culture-Bearing Weight). `Unresolved` values are never estimated here.
3. **`HANDWAVES.md`.** Anything not listed obeys known biology and physics.
4. **D-7.** The animal side stays in behavior. Human culture arrives through the body (Embodiment Fit), never
   worn whole.
5. **The race's L2 volume** (M-3), the **L0 frame and M-4 charter of each lineage present**, and **each
   lineage's L3 inherited stock**.
6. **M-6** (both modes) before any Composition Merge rule.
7. **For an L4 run:** the finished ULM pass for the location, run with `ULM_Adapter.md`. CST's own source map
   still governs which phase file each technique reads.

## Plug-in table — ordered by CST's own section sequence
| Where in CST (step/phase, file:line) | HAR entry (code · name) | Severity | What the pass does instead | Supplied by (P-/L-/M-/doc) |
|---|---|---|---|---|
| **§0** Characteristic Plausibility (`CST:37-39, 43-45`) | HAR-CST-01 · Human common-sense plausibility baseline | Adjust | `[L4]` "Characteristic" means consistent with L1 + L2 + this place, never with a human default. Check each "of course this is here" against when the race is active, how it gathers and tolerates strangers, and what it eats and can tolerate. In a setting with engineered animal-people, the giraffe line is not a test | L1; L2; P-1; P-3; P-7 |
| **§0b** channel list (`CST:56-60`; `CST-copy:150-157`) | HAR-CST-02 · Sensory channel set fixed to the human sensorium | Blocking | `[L4]` Replace the fixed seven with the race's channels: its senses at their ranges, and its signal channels. Keep "entered," "done," and "hooked" as actions, read through this body. A custom expressed by scent or substrate counts as physical. (The ULM's Mechanic 7 copy of this list is HAR-ULM-19, in `ULM_Adapter.md`) | P-4; P-8; P-10 |
| **§0b** player = resident (`CST:8-9, 56, 62`) | HAR-CST-03 · Resident perception treated as player perception | Blocking | `[L4]` Split the test. (a) How residents express it: the race's channels (row above). (b) How the player meets it: the game's map of each channel as rendered directly, rendered by proxy (NPC reaction, visible residue, item text, UI cue, companion comment), or not rendered. A rendered proxy counts as a physical expression | P-4; P-8; GAP — the Channel-Rendering Map is per game (README "Not parameters") and no game GDD has one; whose senses the player character has is open; a non-interactive medium needs a §0b variant (Q-11) |
| **§0b** "handled" (`CST:58`) | HAR-CST-04 · "Handled" presumes human hands | Adjust | `[L4]` Read "handled" through the race's manipulation ability and hand form | P-4; P-10; Q-9 |
| **§0b** "spoken" (`CST:59`) | HAR-CST-05 · "Spoken" presumes vocal-verbal language | Adjust | `[L4]` Read "spoken" as "communicated" on whichever channels carry language for this race. Vocal ranges outside human hearing go through the rendering map (row above) | P-8; Q-12 |
| **Other half of the law** · stock and the GPS law (`CST:150-176, 984`) | HAR-CST-06 · Starting stock is a human nation or ethnicity | Adjust | `[Now]` The starting stock is each lineage's L3 inherited stock: its creators' culture, lived in this body. A collaboration's stock is M-6 Mode A's composite. Mixed places add a species axis (M-6 Mode B). The species analog of the national-stereotype ban is `CLAUDE.md` rules 2 and 3 | L3; M-4 charter; M-6; `CLAUDE.md` rules 2–3 |
| **Other half** · divergence operator (`CST:178-179`, restated `CST:1146-1148`) | HAR-CST-07 · Divergence operator has no embodiment term | Blocking | `[Now]` Run the six operator terms unchanged, then add **Embodiment Fit** on the adapter side: for each inherited practice, record keep / bend / drop and the L1 mechanism behind it (activity cycle, rearing, senses and reach, diet, signals, body plan). D-7 point 3 binds: human culture is bent by this body, never worn whole. (Its RWBEM twin, HAR-RWBEM-07, points here) | M-6 Mode A Step 4 (collaboration lineages); P-1; P-2; P-4; P-7; P-8; P-10; GAP — no L3 method or template states Embodiment Fit for single-creator lineages (A, H, or R alone); M-6 is the only written form; promotion into the operator is Q-27 |
| **Other half** · elapsed-time ban (`CST:181-182, 1150`) | HAR-CST-08 · Elapsed-time ban conflicts with generation-length calibration | Adjust | `[Now]` Use the proposed Q-25 reading provisionally. Years are converted to generations and witness depth, and reasoning proceeds on those. Never write "after N years, X" | P-5; M-7 Steps 2–3; Q-25 |
| **Other half** · the Acts (`CST:185-187`) | HAR-CST-09 · The Acts are timed to human generations | Adjust | `[Now]` Express Act 1 → Act 2 in the race's generations, per lineage. The dates and Antarctica are Inner Tepenia project data and don't carry over. (Same rule as HAR-ULM-11 in `ULM_Adapter.md`) | P-5; M-7 Step 7 |
| **T1** Bounded Personal Franchise, limits table (`CST:200-203, 207, 212, 220-221`; `CST-copy:293-313`) | HAR-CST-10 · Franchise limit measured by human reach · **and** HAR-ULM-40 · The bounded franchise is measured by arm reach | Adjust (both) | `[L4]` Set reach, travel, and carrying limits from the race's reach, manipulation, stature, and locomotion (climbing, burrowing). Where its senses reach far, add a perceptual franchise row: what you can smell or hear as yours | P-4; P-10 |
| **T1** franchise holder (`CST:198-203`) | HAR-CST-11 · Franchise holder is an individual adult | Adjust | `[L4]` The unit that holds control (individual, pair, group, one sex, one life stage) comes from the race's territoriality, rearing unit, stages, and sex differences, as L1 establishes them. Never presume it from the animal | P-3; P-2; P-6; P-14 |
| **T2** Failure State of the Core Value (`CST:239, 241, 244`) | HAR-CST-13 · Failure states keyed to human aging and working life | Adjust | `[L4]` Key "you age out," "you can no longer work," and successor turnover to the race's stages (including whether a post-reproductive stage exists), lifespan, and generation length. (The ULM-copy twin, HAR-ULM-41, is Cosmetic) | P-6; P-5; M-7 |
| **T3** Universal Micro-Practice (`CST:264-279`; `CST-copy:352-371`) | HAR-CST-14 · Micro-practices use human gestures and timing · **and** HAR-ULM-42 · Micro-practices use human gestures | Adjust (both) | `[L4]` Draw the repertoire from the race's signal channels (ears, tail, posture, scent-marking, allogrooming, substrate) and its perceptual time scales. Only a **voluntary or trainable** signal can be a micro-practice. An involuntary signal is biology (L1), never a custom; M-3 decides reflex vs. culture | P-8 signal control (D-8 field extension); P-4; L2 |
| **T4** Ambiguous Universal Object (`CST:292-297, 312-313`) | HAR-CST-16 · Carried object presumes clothing and private meaning | Adjust | `[L4]` If L1 keeps olfactory acuity, an object carries its owner's scent and history, so the etiquette moves from "not asking" to "not remarking on what you smelled." Whether objects are worn or carried follows the body plan and the inherited clothing norms | P-4; P-8; P-10; L3; Q-9 |
| **T5** Retroactive Mechanism, hunting list (`CST:329-331`) | HAR-CST-17 · Unexplained effects listed in order of human salience | Adjust | `[L4]` Build the list from the race's channels and ranges, including those beyond human range (ultrasound, infrasound, UV, substrate vibration). Drop effects it can't perceive. "Anomaly" is relative to its tolerances | P-4; P-9 |
| **T6** Necessity Before Meaning (`CST:355-356, 361-362`) | HAR-CST-18 · Forcing constraints leave out the body | Adjust | `[L4]` Add the constraint family "what the body required" (diet, light and activity regime, nesting and rearing, tolerances, built-environment scale) and test it first | P-1; P-2; P-7; P-9; P-10 |
| **T8** Asymmetric Record-Keeping (`CST:395-405`) | HAR-CST-20 · Record-keeping presumes writing and human lineage | Adjust | `[L4]` "Lineage" follows the race's kin recognition and litter structure, so it may not be linear. The record medium follows its channels and whether L3 inherited writing | P-2; P-8; L3 |
| **T10** Membership by Unremarked Persistence (`CST:441-452`) | HAR-CST-21 · Membership timescales assume a human lifespan and default stranger tolerance | Adjust | `[L4]` State each conversion timescale as a share of adult life. Default newcomer tolerance comes from stranger tolerance. If group identity is recognized physiologically (by scent, say), membership may be biological as well as economic; M-3 decides whether group recognition is `ANIMAL-INHERITED` | P-3; P-4 recognition channel; P-5; P-8; L2 |
| **T11** Negative Image (`CST:469-482`) | HAR-CST-22 · Counterculture from misfit ignores biological misfit | Adjust | `[L4]` A species-shaped counterculture must name its mechanism **and** record the members of that species who comply (`CLAUDE.md` rule 3). Composition is the developer's (Q-10) | M-6 Mode B; `CLAUDE.md` rule 3; Q-10 |
| **T12** Native Before Transplanted (`CST:495-500`) | HAR-CST-23 · "Native vs. transplanted" has only two layers | Adjust | `[L4]` Develop four layers separately: creator-installed (charter; `ENGINEERED`), animal-inherited (L2 `ANIMAL-INHERITED`), inherited creator culture (L3), and locally grown | M-4 charter; L2; L3 |
| **T13** Unused-Tier Mine (`CST:509-514, 536-537, 560`) | HAR-CST-24 · The research stream is real human places only | Adjust | `[L4]` Two streams. Human places (RWBEM, via `RWBEM_Adapter.md`) for built and cultural material; the race's M-2 research log for anything biological. The spend record covers both | M-2; `RWBEM_Adapter.md` |
| **T14** Population Share Check (`CST:543-552`) | HAR-CST-25 · Population Share Check misses sex and life-stage narrowing | Adjust | `[L4]` Add the biological narrowings: one sex, one life stage, the breeding season, a captive or lab sample. Read them from each source's study-identity fields | M-2 Step F; P-6; P-2; P-14 |
| **Borrowed Form** (`CST:589-590`; `CST-copy:670-675`) | HAR-CST-26 · "Forms every society needs" is the human list · **and** HAR-ULM-43 · Borrowed Form's "every society needs" list | Adjust (both) | `[L4]` The "every society needs" list is the race's L2 floor. A need M-3 returned `NON-TRANSFER` doesn't fire Borrowed Form; an `ANALOG` need fires in its analog form | L2 (M-3) |
| **Zodiac Lens** (`CST:718-745`, esp. `731-740`) and its Elemental/Planetary cross-check (`CST:865` onward); `CST-copy:798-805, 891-907`; also ULM Phase 10 (`ULM/03_The_Phase_Spine.md:1110-1113, 1155-1160`) and `ULM/00_RUNBOOK.md:722, 1746-1748` | HAR-CST-28 · The Zodiac Lens reads human personality archetypes · **and** HAR-ULM-44 · Human temperament typologies and robot symbol systems used as lenses | Adjust (both) | `[L4]` Run the lens as prompts only. Before the §0 filter, check every person-shaped result against L1, L2, and the race's mechanism-chained temperament values. Registers tied to life stages go through the stage map. Hold the robot symbol cross-checks pending Q-28. Race-appropriate systems may be registered through ULM `02` §6.5, by the developer | L1; L2; P-6; P-15; Q-28 |
| **§18 Composition Merge** · input contract (`CST:1001-1003`, consumed `CST:1058-1065`) | HAR-CST-29 · Composition counts every head as an equal culture-bearer | Blocking (for M-6) | `[L4]` Across species, convert each headcount share into a transmission share with Culture-Bearing Weight before applying R1–R7. Shares themselves are never estimated (`CST:1003`) | Culture-Bearing Weight (D-8 derived value; template row); GAP — M-7 v0.1 has no step that computes it |
| **R1–R3** (`CST:984, 1010-1036`) | HAR-CST-30 · R1–R3 read a single composition axis | Blocking (for M-6) | `[Now]` Mode A: run R1–R3 on the creator stocks, weighted by exposure, not credit (M-6 Mode A Step 1). `[L4]` Mode B: run R1–R3 on each axis (origin, species, creator lineage), then cross them | M-6 |
| **R1** majority default (`CST:1016-1017`) | HAR-CST-31 · R1's default is treated as purely cultural | Adjust | `[L4]` The majority species' default includes the physical plant: body scale, hours, food, and interior climate. A minority's mismatch with those is physical, and can't be "optional" (M-6 Mode B rule 6) | P-10; P-1; P-7; P-9; M-6 axes B7, B2, B1, B9 |
| **R4** stock-distance axes (`CST:1040-1042`; `CST-copy:1061-1063`) | HAR-CST-32 · R4's stock-distance axes are cultural only · **and** HAR-ULM-45 · Composition Merge R4 has only cultural axes | Blocking (both) | `[Now]` Mode A Step 2: read cultural distance on the six axes, and note where creator stocks rest on different bodies. `[L4]` Mode B: keep the six cultural axes, split off each one's biological "can't" (staple → diet class; household → reproduction and rearing; calendar → activity cycle and breeding season; climate → tolerance), measure the biological axes B1–B10 as overlap, and read cultural distance against bodily overlap as a 2×2, never averaged | M-6 (Mode A Step 2; Mode B axes and rule 2); P-1; P-2; P-7; P-9; P-11 |
| **R4** built commons (`CST:1049-1054`) | HAR-CST-33 · R4's "built commons" assumes everything can be negotiated | Adjust | `[L4]` A built commons forms only on axes where the races' L1s overlap. A biological incompatibility produces parallel infrastructure with a minimal commons in the overlap zone | M-6 Mode B rule 2 |
| **R5** threshold viability (`CST:1056-1069`; `CST-copy:1079-1090`) | HAR-CST-34 · R5's thresholds are uncited and human-calibrated · **and** HAR-ULM-46 · R5 viability thresholds | Blocking (CST) / Adjust (ULM copy) | Neither mode: mark R5 "human-calibrated, unverified" and don't apply it to any non-human population. When M-7 bands exist: on the species axis, use the biological floor (R5-B: accommodate from the first resident, at any share); on the origin axis within one species, restate the bands as absolute adult counts relative to the race's P-3 band, with a fecundity growth note | M-6 Mode B rule 7; P-3; P-2; Culture-Bearing Weight; GAP — M-7 has no step that produces per-race R5 bands; the missing human source is Q-27 |
| **R5** "the non-negotiable one" (`CST:1062`) | HAR-CST-35 · R5's "non-negotiable" set is cultural | Adjust | `[L4]` A biological minority's first non-negotiables are physical (diet, light and activity regime, rearing, tolerances). They need accommodation at any share (R5-B). The cultural non-negotiables (funerary, dietary, devotional) follow under the restated R5 | P-7; P-1; P-2; P-9; M-6 Mode B rule 7 |
| **R6** share × necessity (`CST:1093-1103`) | HAR-CST-36 · R6's "goes universal" crosses a biological boundary | Adjust | `[L4]` Across species, what goes universal is the accommodation (schedule, venue, etiquette), never the physical practice | M-6 Mode B rule 4; L1 overlap |
| **R6 / R7** retention and absorption (`CST:1100-1103, 1122-1127`; `CST-copy:1121-1124, 1143-1148`) | HAR-ULM-47 · R6/R7 assume generational assimilation | Adjust | `[Now]` for L3 pace; `[L4]` for settlements. State retention and absorption in the race's generations and witness span. Long-lived: founders may still be present and "descendants" may not exist yet. Short-generation: absorption is faster. Engineered founder cohorts follow the founder-vs-born split | P-5; P-12; M-7 Steps 2–3 |
| **R7** most of the roster shows up nowhere (`CST:1111-1127`) | HAR-CST-37 · R7's end state assumes the body disappears | Adjust | `[L4]` Apply R7 on the origin axis only. On the species axis, the integrated end state is accommodation nobody remarks on, never invisibility | M-6 Mode B rule 5 |
| **Guards** · sequencing gate (`CST:1144-1145`) | HAR-CST-38 · The sequencing gate names nationality, not species | Adjust | `[L4]` Never infer which species lives somewhere from the environment ("burrow-friendly ground") or a folk image. Composition is a developer decision | `CLAUDE.md` rules 2–3; Q-10 |

**35 rows.** That covers all 34 Blocking and Adjust entries in `HAR_CST.md` (7 Blocking, 27 Adjust), and
HAR-ULM-40, -42, -43, -44, -45, -46, and -47.

## Rules that apply unchanged
These carry over as written once the parameter sheet feeds them (`HAR_CST.md`, "Generalizes cleanly"):
- **The self-check against copying** (`CST:15-23`). "Similar shape means at least one is wrong" is the CST form
  of "one race on its own terms."
- **§0's two failure modes** (`CST:35-50`). Only the baseline changes (HAR-CST-01).
- **"The violation is usually the gameplay"** (`CST:64-65`).
- **The source-map discipline** (`CST:69-135`). Every technique names its input.
- **The question shapes of Techniques 2, 5, 6, 7, 8, 9, 11, and 14.** Only the example rows carry human scale.
  For T9 food exports in a mixed place, diet-class compatibility (P-7) is a filter, not a rewrite.
- **The Unrecognized Instrument**, complete (`CST:643-695`).
- **The Zodiac Lens process discipline:** the stopping criterion (`CST:768-780`) and the per-hit contradiction
  check (`CST:832-863`). The ULM copy dropped both (open item 2 below), so a run should read them from the
  original.
- **Composition Merge, species-neutral parts:** R2 and R3 as arithmetic on any one axis; the ban on estimating
  shares (`CST:1003`); R5b "pooling is a hypothesis, not an entitlement" (`CST:1086-1090`), applied per axis;
  R6's core claim, survival as share × necessity; Guard 1 (structure, never character), Guard 5, and Guards 6
  and 7; and "listed is not represented" (`CST:1111`) on the origin axis.

## Open items needing an Inner Tepenia ruling (point to Q-27; do not resolve)
Filed under **Q-27** (`OPEN_QUESTIONS.md`) unless another code is named. None is decided here.
1. **R5's thresholds cite no source, even for humans** (HAR-CST-34; `HAR_CST.md` Composition Merge §4). This is a
   finding about the original. Until it's settled, R5 stays "human-calibrated, unverified" in this adapter.
2. **The ULM copy of CST differs in substance** (`HAR_CST.md` note 1). It drops Zodiac Lens step 7 (the per-hit
   contradiction check, `CST:832-863`) and two related paragraphs. Its pin looks stale, and the two files
   disagree on counts ("eighteen"/"216" vs. "nineteen"/"228"; "fourteen" vs. "eighteen").
3. **Embodiment Fit in the divergence operator** (HAR-CST-07): should it become a seventh operator term in the
   Inner Tepenia originals? Until then it is adapter-only.
4. **Related, filed separately:** the elapsed-time ban vs. M-7 (HAR-CST-08, **Q-25**); robot symbol systems on
   biological races (`HAR_CST.md` note 5, **Q-28**); §0b's CRPG assumption for a non-interactive medium
   (`HAR_CST.md` note 4, **Q-11**); and the cross-species disease axis B10, which needs an M-1 immunology domain
   (**Q-29**).

## Cosmetic entries (closing note)
- HAR-CST-12 · Time limits assume a diurnal work schedule → P-1
- HAR-CST-15 · Rank signaling presumes a human status hierarchy → P-3. Don't fill the row from pop ethology (the
  M-2 revised-model watch)
- HAR-CST-19 · Testifying media assume human records and human generation length → P-4, P-8, P-5
- HAR-CST-27 · The shared meal is assumed to be available → P-7, P-1; M-6 axis B1
- HAR-CST-39 · Player value is phrased as "human decisions" → wording only
- HAR-ULM-41 (the ULM-copy twin of HAR-CST-13) is Cosmetic in `HAR_ULM.md`. The HAR-CST-13 row above covers its
  substance.
