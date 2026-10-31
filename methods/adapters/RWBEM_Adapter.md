# RWBEM Adapter (M-0b)
**Status:** Proposed v0.1, 2026-10-21. Plug-in map for running the Real-World Basis Extrapolation Method unchanged
on a non-human race. Original: `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Real-World_Basis_Extrapolation_Method.md`.
Nothing here edits the original (`CLAUDE.md` rule 8).

**Register this maps:** `Human_Assumptions_Register/HAR_RWBEM.md` (18 entries: 5 Blocking, 9 Adjust, 4
Cosmetic). It also maps HAR-ULM-48, which sweeps the ULM's copy of RWBEM.
**Line references.** `RWBEM:` cites the original (417 lines). `RWBEM-copy:` cites
`Universal_Location_Methodology/Disciplines/Real-World_Basis_Extrapolation_Method.md` (469 lines, restructured,
not yet swept line by line; `HAR_RWBEM.md` note 4). Line numbers are from the 2026-10-21 sweep.

---

## When this adapter applies (and D-2 note: which parts are usable now vs. deferred to L4)
**RWBEM researches real human places. For a non-human race's biology, its role passes to M-2.**

**Handed off to M-2 (EBEM): everything about the race itself.** Behavior, signals, social structure, life
history, senses, diet, and locomotion are researched from real animal populations by M-2 (or derived by M-5 for
a race with no animal base), resolved by M-1, and written to L1. M-2 already carries RWBEM's discipline, adapted
step by step (`HAR_RWBEM.md`, "Carry-over into M-2"). A RWBEM run never sources a trait of the race.

**Where RWBEM still applies:**
1. **L4 location work (Phase 7; deferred under D-2).** Once a location exists, RWBEM runs corpus-wide after the
   ULM (`DR-14`), on real human places, for the **built environment, artifacts, institutions, and role
   placeholders** a place inhabited by these races would probably also have (`DR-15`). Each derived item is
   then checked against this race's body before it enters (rows HAR-RWBEM-01 and -12). The GPS law applies
   unchanged.
2. **Now, through M-5: real physical facts.** RWBEM's admissible category, "pure physical/geographic facts"
   (`RWBEM:143-146`), is the category M-5 Step 1 uses for the real Alpha Centauri / Proxima system (D-6). LAW
   0-R governs that research. D-2 still bars building a specific world from it.
3. **H-lineage inherited stock: by default, no role** (`HAR_RWBEM.md` note 2). An H-lineage's starting culture
   is a *Tepenian* creator culture, downstream of the Inner Tepenia city corpus (`MASTER_PLAN.md` §10). That
   culture is read from its own corpus, not re-researched from real places. The one conditional case: if an L0
   frame names a creator society whose stock is itself a real-world human culture, the "other half" sequencing
   rule (`RWBEM:150-198`) admits that stock only after L0 rules on it, and the GPS law still bars the creators'
   site or nation as a cause of any trait. Whether that case can arise is a developer question (see the last
   section).

## Read before a pass
1. **The race's L1 document, in full, general before narrow** (ULM `03` §0.2 Mechanic 9), and its **parameter
   sheet**, especially P-1, P-4, P-7, P-9, and P-10 (the body a real-place item must fit).
2. **`HANDWAVES.md`** and **D-7.** A real-place item enters only through this body. One worn whole is the
   "California college student" failure.
3. **The race's M-2 files:** `races/<Race>/research_log/Ethological_Picks.md` and the research log. A RWBEM run
   doesn't add to them. New biology goes M-2 → M-1 → L1.
4. **The L0 frame and M-4 charter of each lineage present**, before any H-lineage stock question.
5. **For an L4 run:** the finished ULM pass and CST run for the location (`ULM_Adapter.md`, `CST_Adapter.md`).

## Plug-in table — ordered by RWBEM's own step sequence
| Where in RWBEM (step/phase, file:line) | HAR entry (code · name) | Severity | What the pass does instead | Supplied by (P-/L-/M-/doc) |
|---|---|---|---|---|
| **LAW 0-R** · what "fully" means, angles (`RWBEM:59-60`) | HAR-RWBEM-08 · Research angles are angles on a settlement | Adjust | Biology: hand off to M-2's angle set. `[L4]` Human-place picks keep the settlement angles unchanged | M-2 Step B (angles) |
| **Purpose** · the output (`RWBEM:85-95`) | HAR-RWBEM-01 · The output is a catalog item for a human place | Blocking | Biology: the product is a mechanism, via M-2 → M-1 → L1, never a catalog item. `[L4]` The catalog-item product resumes, and each item passes the body check at Step C before entry | M-2; M-1; L1 |
| **The two source files** (`RWBEM:99-105`) | HAR-RWBEM-02 · Picks are real human places, filed per location | Blocking | Biology: a per-race pick list, filled only after Q-4 rules on the base (M-2 Step A). `[L4]` New per-location human-place picks will be needed; "doesn't require generating new picks" doesn't hold | M-2 Step A; `races/<Race>/research_log/Ethological_Picks.md`; GAP — no pick file exists for any location these races inhabit (D-2; none can until worlds exist) |
| **GPS law** (`RWBEM:109-124`) | HAR-RWBEM-03 · GPS law covers only human national operators | Adjust | Biology: M-2 Step 0's analog: a study population's human management regime is a coordinate, never a cause, with its swap test and sequencing exception. `[L4]` On human places the GPS law runs unchanged | M-2 Step 0; `CLAUDE.md` rules 2–3 |
| **GPS law** · the named-site trap (`RWBEM:126-141`) | HAR-RWBEM-04 · The named-site trap has a folk-meaning twin | Adjust | Biology: M-2 Step 0, "folk meaning is not a source." Silence, not a disclaimer. `[L4]` On human places, also leave out the base animal's folk symbolism wherever a site's history carries it | M-2 Step 0; `CLAUDE.md` rule 2 |
| **Other half of the law** · stock, unlock, Acts (`RWBEM:150-198`) | HAR-RWBEM-06 · The unlock and the Acts are framed on human ethnicity | Adjust | `[Now]` The stock is each lineage's L3 (charter, M-6 Mode A for collaborations). The Acts run in the race's generations. Same handling as HAR-CST-06 and -09 in `CST_Adapter.md` | L3; M-4 charter; M-6; P-5; M-7 Step 7 |
| **Other half** · divergence operator (`RWBEM:186-187`) | HAR-RWBEM-07 · The divergence operator lacks embodiment | Blocking | `[Now]` Add Embodiment Fit exactly as in `CST_Adapter.md`, row HAR-CST-07 | M-6 Mode A Step 4; GAP — no L3 method or template carries it for single-creator lineages (see the CST row) |
| **Step A** · tier value (`RWBEM:226-229, 410-411`) | HAR-RWBEM-10 · The tier-value finding was measured on human places | Adjust | Biology: M-2 Step A tiering, with "lower tiers hold the unspent value" treated as a hypothesis. Measure it in the Phase 3 pilot and record the result in `methodology-observations/`. `[L4]` On human places the finding stands as measured | M-2 Step A |
| **Step B** · research each pick (`RWBEM:241-247`; `RWBEM-copy:312-318`) | HAR-RWBEM-11 · Step B's inventory lists human cultural artifacts · **and** HAR-ULM-48 · RWBEM Step B researches only real human places | Blocking (RWBEM) / Adjust (ULM copy) | Biology: M-2 Step B's inventory (behaviors, signals, social structure, life history, senses, activity, diet, habitat use and locomotion), from primary literature, using the literature's operational definitions. `[L4]` Human-place Step B runs unchanged, except that role nouns are never applied to the race | M-2 Step B |
| **Step C** · the fusion question (`RWBEM:249-254`) | HAR-RWBEM-12 · The fusion question is an analogy between human places | Blocking | Biology: M-2 Step C, "does this race's resolved physiology keep the mechanism?", answered with M-1 tags, never yes/no. `[L4]` Human places: ask the fusion question, then the body check: can this race's body use or inhabit the item (scale, reach, senses, hours, diet)? Record keep / bend / drop | M-2 Step C; M-1 tags; P-1; P-4; P-7; P-10 |
| **Step C** · read-against map (`RWBEM:256-286`) | HAR-RWBEM-13 · The read-against map points to location phase files | Adjust | Biology: M-2 Step C's map from detail type to L1 domain and parameter (habitat and locomotion now read against P-10). `[L4]` The location phase-file map is unchanged | M-2 Step C; P-10 |
| **Step D** · cross-check (`RWBEM:288-338`) | HAR-RWBEM-14 · The cross-check canon is human-city data | Adjust | Biology: M-2 Step D's tiers (`CANON.md` and D-rulings > developer vision > L1 > derived notes), plus the four-question canon check. `[L4]` The location's own canon tiers, with the race's L1 and L2 ranked above any derived note about it | M-2 Step D; `CANON.md`; `DECISIONS.md`; L1; L2 |
| **Step F** · the research log (`RWBEM:358-362`) | HAR-RWBEM-16 · The research-log schema lacks study-population fields | Adjust | Biology: M-2 Step F, which adds the study-identity fields. `[L4]` The human-place log schema is unchanged | M-2 Step F |
| **Standing rule** · demographic-matching ban (`RWBEM:374-381`) | HAR-RWBEM-17 · The demographic-matching ban is framed on nations | Adjust | Biology: M-2 Step A's ban on picking a population for its image or setting. `[L4]` The ban runs unchanged, plus: never pick a human place because it matches the race's image or its base animal | M-2 Step A; `CLAUDE.md` rule 2; Q-4 |

**14 rows.** That covers all 14 Blocking and Adjust entries in `HAR_RWBEM.md` (5 Blocking, 9 Adjust), and
HAR-ULM-48.

## Rules that apply unchanged
On human places at L4, all of RWBEM runs as written, including the GPS law. The following also carry into M-2
with only nouns renamed (`HAR_RWBEM.md`, "Generalizes cleanly"), so they bind any research this repo does:
- **All of LAW 0-R** (`RWBEM:5-82`): a recalled fact is not input data; a wrong fact is worse than a missing
  one; no time limit and no search budget; the "change a finding, or ornament one?" check.
- **Chasing threads** (`RWBEM:231-239`), with unchased threads logged.
- **"Omit it entirely, not reframe it"** (`RWBEM:145-146`) and **"the fix is silence, not a disclaimer"**
  (`RWBEM:133-135`).
- **The "neither extreme" table** (`RWBEM:180-184`): too little gives "humans with ears," too much gives
  "animals in clothes."
- **No Forced Fit and One Location on Its Own Terms** (`RWBEM:203-222`), read as "one race on its own terms."
- **"A blocked check is not an absence"** (`RWBEM:284-286`). In M-2: an `UNRESOLVED` tag is not a negative.
- **Step D's ordering principle** (`RWBEM:303-333`) and **all of Step F** (`RWBEM:345-370`).
- **Lessons 2 and 4** (`RWBEM:412-417`) and **"Working from memory looks like the method and is not the
  method"** (`RWBEM:394`).

## Open items needing an Inner Tepenia ruling (point to Q-27; do not resolve)
1. **Embodiment Fit in the divergence operator** (HAR-RWBEM-07): the same Q-27 item as in `CST_Adapter.md`.
2. **The ULM copy of RWBEM hasn't been swept line by line** (`HAR_RWBEM.md` note 4). It is restructured and
   states the GPS law in a universe-agnostic form. This is a sweep task, not a ruling, but no L4 run should
   rely on the copy until it's done.

Not Inner Tepenia rulings, recorded here so they aren't lost:
- **H-lineage stock from real places** (the conditional case in "When this adapter applies"): a developer
  question for this repo (L0, Q-14). It isn't filed yet.
- `HAR_RWBEM.md` note 1 (D-2 vs. M-5) has been answered by **D-6**. Note 3 (EBEM admissibility depends on M-4)
  stays with Q-2 / Q-4.

## Cosmetic entries (closing note)
- HAR-RWBEM-05 · The admissible facts are about the land → M-5 Step 1 under D-6 (see "When this adapter
  applies," item 2)
- HAR-RWBEM-09 · The sub-part rule is phrased for places → M-2 Step A ("a population is not its species")
- HAR-RWBEM-15 · People entries as human role placeholders → the rule transfers; archetypes come from P-6
- HAR-RWBEM-18 · The worked example uses human places and human reach → M-2 needs its own worked example after
  the pilot
