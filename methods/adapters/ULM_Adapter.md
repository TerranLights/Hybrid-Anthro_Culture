# ULM Adapter (M-0b)
**Status:** Proposed v0.1, 2026-10-21. Plug-in map for running the Universal Location Methodology unchanged on a
non-human race. Original: `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Universal_Location_Methodology/`
(entry point `00_RUNBOOK.md`). Nothing here edits the original (`CLAUDE.md` rule 8).

**Register this maps:** `Human_Assumptions_Register/HAR_ULM.md` (57 entries: 18 Blocking, 32 Adjust, 7 Cosmetic).
**What this file is:** patch notes. For every Blocking and Adjust entry, it says what a ULM pass does differently
when the population includes a race from this repo, and what supplies the substitute. It never restates or
replaces ULM text. Where an entry would need the ULM's own text changed, the row gives a `Proposed interim`
handling and the change goes to the developer (see the last section).

**File keys used in the table** (all under `Universal_Location_Methodology/`):
`RB` = `00_RUNBOOK.md` · `01` = `01_Frame_Typology_and_Inheritance.md` · `02` =
`02_Generators_Capability_and_Symbols.md` · `03` = `03_The_Phase_Spine.md` · `04` =
`04_QA_Gates_and_Differentiation.md` · `05` = `05_The_Input_Contract.md` · `00b`, `00f` = the `Disciplines/`
files of those names · `DRL` = `DEVELOPER_RULINGS_LOG.md`.
Line numbers are from the 2026-10-21 HAR sweep (spot-checked the same day). The ULM changes often, so re-check a
line before relying on it.

**Race-document keys:** L0 = `races/<Species>/lineages/CL-<nn>_<Name>/00_Origin_Frame.md` · M-4 charter =
`…/CL-<nn>_<Name>/03_Design_Charter_and_Drift.md` · L1 = `races/<Species>/01_Physiology_and_Life_History.md` ·
sheet = `races/<Species>/02_Parameter_Sheet.md` · L2 = `races/<Species>/04_Universals/` · L3 =
`…/CL-<nn>_<Name>/05_Inherited_Stock.md`.

---

## When this adapter applies (and D-2 note: which parts are usable now vs. deferred to L4)
**Applies to:** any ULM location pass whose population includes one or more races from this repo, alongside or
instead of the humans and robots the ULM was built for. Humans and robots present in the same place keep their
ordinary Inner Tepenia inputs. This adapter adds to them; it doesn't remove them.

**D-2: the ULM is an L4 tool, and L4 is deferred.** No location pass runs on these races until their worlds
exist (Phase 7). Each row below is tagged:
- `[L4]`: applies only inside a location pass. That is most rows.
- `[Now]`: the ULM element also governs location-independent work that is in scope today. These are the
  divergence-pace, Act, and inheritance-mechanism rules that shape L3 (HAR-ULM-08, -11, -49, -50, -56). Under
  D-2 they are written as mechanism and pace only, never as a local outcome.

One more part of the ULM is usable now and needs no row: `RB` §C.10's list of what a general physiology file
must supply (`RB:2349-2354`) works as a checklist of L1 *topics*. Copy the topics, never the robot answers
(HAR-ULM-51, -52).

## Read before a pass
Read these at **Step 0.2**, once, early, and in full, alongside the disciplines. They stay open for every phase
(`03` §0.2 Mechanic 9). Do the reading for **every** race present, not only the majority.
1. **The race's L1 document, in full, general before narrow** (Mechanic 9 rules 1–3). Start with its
   ordinary-condition summary. Never infer anything from the race's name (Mechanic 9 rule 2; `CLAUDE.md` rule 2).
2. **The race's parameter sheet**, with P-1 to P-15, the D-8 field extensions, and the derived values. A value
   marked `Unresolved` is a REQUESTED input (`05` §5). It is never estimated in-pass.
3. **The L0 Origin Frame and M-4 Design Charter for each creator lineage present.** Under D-5 a species
   usually has more than one, so the pass must state which lineages live here and apply each one's L1 deltas.
4. **The race's L2 Universals volume** (M-3 output). Several rows below use it as the species floor.
5. **Each lineage's L3 inherited stock** (with M-6 Mode A for collaboration lineages).
6. **`HANDWAVES.md`.** Anything not on it obeys known biology and physics.
7. **D-7, the plausibility standard.** The animal side stays in behavior, with believable variance. Human
   culture reaches the race only through its body. A pass that writes the race as a human persona with animal
   cosmetics has failed, however well each finding is argued.
8. **M-3's "Do not inherit" list** (robot verdicts). The ULM's robot inputs state these confidently; none is a
   default for a biological race.

## Plug-in table — ordered by the ULM's own step/phase sequence
| Where in ULM (step/phase, file:line) | HAR entry (code · name) | Severity | What the pass does instead | Supplied by (P-/L-/M-/doc) |
|---|---|---|---|---|
| **Step −1** · `05` §2.1 Tier 0 (`05:140-150`); §7 pre-flight (`05:749-803`) | HAR-ULM-30 · The input contract lacks physiology as a blocking input | Blocking | `[L4]` For each non-human race in the population, the L1 document and a filled parameter sheet are Tier 0: without them the pass stops and requests them (`05`'s own rule for a missing Tier 0 input). Add a pre-flight line on the adapter side: "L1 + sheet present for every race; `Unresolved` parameters filed as requests." `05` itself is not edited | L1; M-0a sheet; Q-27 (whether to add the line upstream) |
| **Step −1** · `05` §2.4 Tier 3 catalog, pull/push durability (`05:298-327`); consumed at Phase 2 | HAR-ULM-29 · Pull/push durability is human migration psychology | Adjust | `[L4]` Before reading an attraction-assembled population as "willing to relocate again," read P-13. Movement by the dispersing sex or age class is a dispersal fact, not a choice, and doesn't predict re-relocation. Philopatric classes get the opposite reading. P-3 territoriality qualifies both | P-13; P-3 |
| **Step 0.1** · band declaration, `01` §2.1–2.2 (`01:174-182, 195-200`) | HAR-ULM-01 · Scale bands are human group-size thresholds | Blocking | `[L4]` Declare both bands using the race's P-3 thresholds (stable group size, the "everyone is witnessed" threshold), never ~30 / ~500 / ~50k. Adjust "witnessed" for P-4 perception range: a scent-tracking race detects deviance after the fact, so "unwatched" starts at a different size. If P-3 is `Unresolved`, the band is declared `Unresolved` and requested. In a mixed place, declare a band per race | P-3 (M-7 Step 6); P-4 |
| **Step 0.1** · Band 2 unit of analysis (`01:178`) | HAR-ULM-02 · Recognition is by sight | Adjust | `[L4]` Read Band 2's unit as "persons known by [the race's recognition channel]," not "by sight" | P-4 recognition channel (D-8 field extension); P-8 |
| **Step 0.1** · Threshold 2→3 (`01:202-207`) | HAR-ULM-03 · An office outlives its holder only above a human-tenure threshold | Adjust | `[L4]` Decide whether offices are personal or institutional by comparing holder tenure with institution age, in the race's generations, not by headcount alone. A long witness span keeps offices personal at larger sizes; short generations make them institutional sooner | P-5; M-7 Steps 2–3 (witness span) |
| **Step 0.1** · band sizing (`01:176-182`); Tier 0 population magnitude (`05:146`) | HAR-ULM-04 · Headcount equals social participants | Adjust | `[L4]` Enter the band with the adult-equivalent population, not raw headcount. Record both figures | P-2 adult-equivalent population (D-8 field extension, derived with P-6) |
| **Step 0.1** · status *Growing*, `01` §3 (`01:287`) | HAR-ULM-06 · Growth means arrivals | Adjust | `[L4]` Ask first whether growth is internal (births) and read the strain as age structure (the juvenile fraction) before newcomer ignorance. Arrivals remain one possible source, not the default | P-2; P-5; P-6 |
| **Step 0.1** · temporal frame, `01` §4 (`01:315-317`); `05` §2.1b (`05:157-161`) | HAR-ULM-07 · Era is inferred from the human technology timeline | Adjust | `[L4]` Take the era from each lineage's L0 timeline placement and the setting's declared frame, never from resemblance to Earth's technological history. A missing era is requested, not inferred. Under D-2 the world's era stays `[hazy]` | L0 §2 (When); Q-11 (*Elven Steel* era) |
| **Step 0.1** · temporal frame and the default one-location set, `01` §4, §5.3a (`01:320-323, 469-478`); `02:235-238, 512, 517-524`; Phase 5 (`03:710-720`) | HAR-ULM-08 · Generational memory turnover | Blocking | `[Now]` for L3; `[L4]` for location claims. Before any "nobody remembers why," "the witnesses have gone," or "founders, crisis generation, and present are different people," compute how many of the race's generations separate those eras and whether founders can still be alive. Write the claim in generations and witness span. Long-lived: memory is personal. Short-generation: many turnover cycles per era | P-5; M-7 Steps 2–4 (witness span, oral-history depth) |
| **Step 0** · Act stamps, `01` §5.1 (`01:400-404`); G8 (`02:312-314`); `RB` §C.9e (`RB:2244-2263`) | HAR-ULM-11 · Act timing and "origin is ancestry" | Blocking | `[Now]` for L3 pace. Express Act 1 → Act 2 in the race's generations, per lineage where P-5 differs. For an engineered first generation, the "origin culture" is the creators' stock (L3), and "origin is ancestry, not identity" is tested on witness span, not years. Never write "after N years, X" (Q-25) | P-5; M-7 Step 7; L3; Q-25; Q-27 |
| **Step 0** · inheritance classes, `01` §5.1 (`01:407-421`); Gate I (`04:356-384`) | HAR-ULM-10 · The inheritance classes have no slot for the species floor | Blocking | `[L4]` `Proposed interim`, pending a ruling: before trying "what the parent determines," check L2. An element that matches an L2 floor item is tagged `species-floor (L2, U-code)` beside its ULM class. It is not counted as Originated, and it stays out of Gate I's Originated:Inflected ratio | L2 (M-3); Q-27 |
| **Step 0** · parent-determined calendar and language family (`01:413`); Gate I (`04:362-363`); `05:212` | HAR-ULM-09 · The parent determines calendar and language family | Blocking | `[L4]` `Proposed interim`, pending a ruling: a biological calendar (activity cycle, breeding season) or a species-bound signal channel found at sub-location level is recorded as species-determined (row above), not as a sub-location calendar or language that Gate I rejects. The cultural calendar and language family still come from the parent. In a mixed place, M-6 Mode B axes B2 and B6 describe the overlap | P-1; P-2; P-11; P-8; M-6 Mode B; Q-27 |
| **Step 0.2** · Mechanic 9 (`03:169-200, 1057-1060`); `RB:1981, 2067-2068, 2330-2334` | HAR-ULM-18 · Mechanic 9 is a two-body model | Blocking | `[L4]` Read one L1 document and one parameter sheet **per race present**, each general before narrow, at Step 0.2. State each race's ordinary condition before any environmental claim about it. How the races affect each other is M-6 Mode B, not a merged reading of their files | L1 and sheet per race; M-6 Mode B (deferred) |
| **Step 0.2** · `RB` §C.10 facts table (`RB:2338-2345`) | HAR-ULM-52 · The robot physiology facts become a body template | Adjust | `[L4]` The race's ordinary condition (posture, hand form, integument, clothed or not) comes from L1 and P-10, never from §C.10's humanoid, clothed robot. P-10's clothing/adornment need answers Mechanic 9 rule 3's "clothed or not" | P-10; L1 domains 1, 2, 9 |
| **Step 0.2** · `RB` §C.10 "what the general file supplies" (`RB:2352-2353`) | HAR-ULM-51 · Kinship by shared experience (robot-specific) | Blocking | `[L4]` Use §C.10's list as topics only. Kinship comes from the race's own rearing and kin-recognition data and from M-3's re-derived kinship items. The robot answer is never copied | P-2; P-11; L2 (M-3 "Do not inherit") |
| **Step 2** · G2 (`02:174-187`); applied at Phase 3 (`03:517-518`) | HAR-ULM-12 · G2 is read against an unstated human body | Blocking | `[L4]` Profile G2's "withhold / demand / permit but punish" against this body. Tolerances come from P-9, light-regime deprivation from P-1, the social cost of isolation from P-3, and cover from P-10. State the ordinary condition first (Mechanic 9 rule 3). The human examples in `02` are prompts, never values | P-9; P-1; P-3; P-10; L1 via Mechanic 9 |
| **Step 2** · G8 composition (`02:271-281, 310-323`); Phase 2 (`03:408-414`); `RB` §C.9b (`RB:2090-2124`) | HAR-ULM-15 · Composition means national origins | Adjust | `[L4]` Read composition on the axes species × creator lineage (`CL-`) × base-animal line × origin. Each lineage's "stock" is its L3 inherited stock. Shares come from the developer (Q-10) and are never estimated | L3; M-4; M-6 Mode B; Q-10 |
| **Step 2** · `RB` §C.9b, "mediated, not personal" (`RB:2116-2121`), read with G8 and Phase 2 | HAR-ULM-49 · Inheritance is "mediated, not personal" (robot-specific) | Blocking | `[Now]` Apply the mediated reading only to the engineered founder cohort. From the first born generation on, inheritance is also personal (parents to young), through the rearing unit and the transmission mode. The charter's rearing plan sets how mediated the founders' intake was. (`MASTER_PLAN.md` §3 already carries this two-stage correction) | P-2; P-12 (engineered-founder vs. born cohort split); M-4 charter §6 |
| **Step 2** · divergence operator calibration, `RB` §C.9d (`RB:2154-2172, 2210-2212`) | HAR-ULM-50 · Divergence pace is calibrated on human ethnogenesis | Blocking | `[Now]` Replace the "~250 years … not short" benchmark with M-7's conversion: state the span in the race's generations and witness spans, per lineage. The operator's inputs and its "do not reason from elapsed time" rule are unchanged (Q-25). The missing body term is handled in `CST_Adapter.md` (HAR-CST-07) | P-5; M-7 Steps 2, 3, 7 |
| **Step 3** · research (`RB:2607-2620`); G7 (`02:240-254`); `05:202`; `01:502-503` | HAR-ULM-14 · Real-world research is human-only | Blocking | `[L4]` Two streams. (1) Human real-world comparables still run in Step 3 for built environment, artifacts, and institutions, but each import is checked against L1 and the sheet before use (keep / bend / drop, D-7). (2) The race's behavior and biology are never sourced in-pass: they come from L1 (built from M-2, or M-5 for aliens). A Step 3 deficit that needs new biology is filed as an `RQ-` and routed M-2 → M-1 → L1 | L1; M-2; M-5; `RWBEM_Adapter.md` |
| **Step 4** · `03` §0.2 Mechanic 7, player-facing test (`03:162-164`) | HAR-ULM-19 · The player-facing channels are human senses | Adjust | `[L4]` The race's sense and signal channels are the list of physical expressions. A scent-, vibration-, or ultrasound-borne finding is physical for residents and is not demoted to "read about." How the player meets it is a separate question, answered per game (see `CST_Adapter.md`, HAR-CST-02 and -03) | P-4; P-8; GAP — the per-game Channel-Rendering Map exists in no game GDD yet |
| **Phase 2** · arrival-mode taxonomy (`03:434-446`) | HAR-ULM-16 · No arrival mode for "made here" | Blocking | `[L4]` `Proposed interim`, pending ratification: add an eighth mode, "made / placed here." It covers a first generation created or decanted on site, young bred to a placement, and a released population. The lineage's charter and L0 say which applies. Don't force these into "Born here" or "Assigned / posted" | M-4 charter §1, §2, §6, §7; L0 §3; P-2; Q-27 |
| **Phase 2** · "Born here" (`03:443`) | HAR-ULM-17 · "Born here" assumes human rearing | Adjust | `[L4]` Natives may arrive as litter cohorts and be raised by a crèche or communal unit. "Cannot leave" is read against dispersal: the dispersing class leaves at maturity and the philopatric class stays | P-2; P-13 |
| **Phase 3** · texture fields (`03:474, 509-512`) | HAR-ULM-20 · The sensory texture fields are human channels | Adjust | `[L4]` Answer the texture fields per sense channel the race has, at its ranges. Add fields for channels it has and humans lack (vibration, vibrissae); mark fields for channels it lacks. "First impressions" uses the dominant channel | P-4; L1 domains 3–6 |
| **Phase 4** · ordinary day (`03:536, 579-583, 587-589`) | HAR-ULM-21 · An ordinary day is diurnal | Blocking | `[L4]` Build the day on the race's activity cycle and sleep architecture (two peaks, polyphasic sleep, and so on), using Phase 4's own axis "a light cycle" (`03:601-602`). In a mixed place, write the day per race | P-1; M-6 Mode B axis B2 |
| **Phase 4** · MUST OPEN blocks (`03:541-552`); also Phase 6 (`03:760-769`), Phase 8 (`03:962-963`), Phase 9 (`03:1033-1040`), Phase 10 (`03:1110-1113`) | HAR-ULM-25 · Robot canon is hard-wired into the universal MUST OPEN blocks | Adjust | `[L4]` `Proposed interim`, pending a ruling. Where a block names robot physiology as "THE LARGEST SINGLE INPUT," open the race's L1 and sheet in its place. Where it names the Laws of Robotics, Robot Universals, or robot religions, open the race's L2, each lineage's charter (§5 status, §8 controls), and the race's law and religion canon. Open the robot sources as well only where robots live in the place. Record each remap in the run receipt | L1; sheet; L2; M-4 charter; `CANON.md`; Q-27 |
| **Phase 6** · death and the dead (`03:754-755, 816-825`); `05:273` | HAR-ULM-22 · Death and mourning follow the human pattern | Adjust | `[L4]` Write death against the race's lifespan and mortality, juvenile survival and litter size (who dies young, how often), its life stages, and M-3's verdicts on grief and mourning, which may be `ANALOG` or `NON-TRANSFER`. Ask "who is not mourned properly" after those | P-2; P-5; P-6; L2 |
| **Phase 6 / 7d** · belief-transmission sources (`03:766-768`; `RB:2079`) | HAR-ULM-55 · Belief-transmission sources assume human imitation | Adjust | `[L4]` Treat *The Meme Machine* and *The True Believer* extractions as human-calibrated prompts. Transmission claims route through the race's acquisition mode and transmission direction, and through M-3's social-learning and conformity items. Any temperament claim needs a mechanism chain | P-12; P-15; L2 |
| **Phase 7a** · labor data (`03:863-866`; `RB:2071-2072`) | HAR-ULM-54 · Labor data are human labor data | Adjust | `[L4]` Adjust staffing and productivity figures for active hours, body scale and manipulation, and feeding time budget. SOC categories are prompts; occupations with no human counterpart may exist | P-1; P-4; P-7; P-10 |
| **Phase 7a / Gate 2** · `00b` share benchmark (`00b:224, 241-242`) | HAR-ULM-32 · Sector-share baselines come from human economies | Adjust | `[L4]` Treat the "ordinary 25–35%" benchmark as human-calibrated. Don't fail a sector share on it alone; read it against feeding time budget, active hours, and body capacity | P-7; P-1; P-10; GAP — no method derives a per-race sector-share benchmark (M-7 doesn't cover it) |
| **Phase 7c** · knowledge and transmission (`03:922-925`); Mentor (`00f:194-200`) | HAR-ULM-23 · Skill passes by teaching and apprenticeship | Adjust | `[L4]` Write 7c from the race's acquisition mode (teaching, imitation, innate, engineered) and developmental windows, with maturation age. Ask "the ones who cannot learn it" within the race's window. Cast the Mentor accordingly | P-12; P-5 |
| **Phase 7c** precedent · `DR-11` (`DRL:448-461`) | HAR-ULM-56 · DR-11 sets enculturation "very similarly to humans" as the model | Adjust | `[Now]` for L3. `DR-11` is the robot model; never cite it as this race's. Use the race's transmission mode, including the engineered-founder vs. born split, its developmental stages, and the charter's installed behaviors and rearing plan | P-12; P-6; M-4 charter §3, §6 |
| **Phase 8** · cuisine, music, dress, language (`03:985-994`) | HAR-ULM-24 · Making assumes clothing, vocal music, and spoken accent | Adjust | `[L4]` Cuisine from diet class and feeding pattern. Music and language from the race's signal channels and hearing range. Dress from the body plan's clothing or adornment need. Convert "after two centuries" into the race's generations | P-7; P-8; P-4; P-10; M-7 Step 2 |
| **Phase 8** language · `DR-56` (`DRL:1115-1118, 1124`) | HAR-ULM-57 · DR-56: human language acquisition, generational learning, guilt-driven duty | Adjust | `[L4]` Language acquisition comes from the race's acquisition window and channels. "The first generation of incomers" is counted in its generations. The duty-enforcing emotion (guilt) is checked against M-3's social-emotion items and the race's mechanism-chained temperament values, never assumed | P-8; P-12; P-5; P-15; L2; Q-12 |
| **Step 7** · Gate 4 swap test (`04:141-146`); also Phase 2 (`03:466`) and Phase 9 E (`03:1089-1094`) | HAR-ULM-27 · The swap test can't see species-generic findings | Blocking | `[L4]` `Proposed interim`: Gate 4 runs unchanged, plus an adapter check beside it: "would this be true of any settlement of this race?", answered against L2. A finding that passes is a species-floor item, not a location distinction, and the weakest-finding report says so | L2; Q-27 |
| **Step 7** · Gate 11 plausibility (`04:250-258, 265-278, 540-545`) | HAR-ULM-28 · Gate 11 plausibility runs on human intuition and human density norms | Blocking | `[L4]` Every behavioral plausibility call cites an L1 domain, an L2 item, or an M-2 log entry, never author intuition. Run the D-7 test: the animal side is visible in behavior, and no human persona is worn whole. Interpret density against body scale, built-environment needs, and territoriality. The arithmetic half of the gate is unchanged | L1; L2; M-2 log; P-3; P-10; P-15; D-7; Q-27 |
| **Step 8** · Review Panel base (`00f:129-132`), §9 universality claim (`00f:809-813`); Gate 10 (`04:241-248`) | HAR-ULM-34 · The Review Panel is built on positions in a human life | Blocking | `[L4]` Cast the panel from the race's life-stage map. Replace the archetypes; don't relabel them. A human position the race lacks is recorded as uncastable, which `00f` already treats as a finding (`00f:757-764`). Stages the race has and humans lack are added. The Passer-Through, the Neighbor, and the Lover faculty question are unchanged | P-6 (M-7 Step 5); Q-27 |
| **Step 8** · Child and Parent (`00f:158-177, 580-582`) | HAR-ULM-35 · Child and Parent assume long dependency | Adjust | `[L4]` Cast from the race's litter structure, rearing unit, maturation age, and dependency stage. A litter cohort or a crèche may be the cast unit | P-2; P-5; P-6 |
| **Step 8** · the Lover (`00f:165-170, 581`) | HAR-ULM-36 · The Lover assumes pair-bonding | Adjust | `[L4]` Cast from the mating system and pair-bond form. If durable pair bonds don't exist, cast a seasonal or courtship position, or record the position as uncastable. The Lover *faculty* question is kept | P-11 |
| **Step 8** · the Elder (`00f:186-192, 584`) | HAR-ULM-37 · The Elder assumes human senescence | Adjust | `[L4]` If the race has no senescent or post-reproductive stage, the Elder as written is uncastable (a finding), or is recast to the oldest active stage. Very long or very short lifespans change what "holds the memory" means | P-6 senescent/post-reproductive field (D-8); P-5 |
| **Step 8** · Life Arcs (`00f:204-221, 246-256`) | HAR-ULM-38 · The Life Arcs are gendered human passages | Adjust | `[L4]` Key the arcs to which sex and age class disperses, and to the race's mechanism-chained sex differences. "Leaving the parental home" applies only to a class that actually disperses | P-6; P-13; P-14 |
| **Step 8** · Panels D and E (`00f:281-284, 353-390`; `RB:2078`) | HAR-ULM-39 · Panels D and E are human depth psychology | Adjust | `[L4]` Keep the four faculty questions. Drop the Jungian and psychoanalytic developmental mapping. Any developmental claim routes through the race's stages, developmental windows, and L2 | L2 (M-3); P-6; P-12 |

**42 rows.** That covers 17 Blocking and 25 Adjust entries.

**Cross-referenced, not repeated here.** HAR-ULM-40 to -48 sweep the CST and RWBEM copies in `Disciplines/`.
`DR-14` keeps those copies out of a ULM pass, and their twins in the CST and RWBEM registers are authoritative
(HAR_ULM note 10). Each one appears in exactly one row elsewhere:
- **In `CST_Adapter.md`:** HAR-ULM-40 (with HAR-CST-10), -42 (with HAR-CST-14), -43 (with HAR-CST-26), -44
  (with HAR-CST-28), -45 (with HAR-CST-32), -46 (with HAR-CST-34), and -47 (its own row, at R6/R7). HAR-ULM-44
  also cites ULM-proper lines (`03:1110-1113, 1155-1160`; `RB:722, 1746-1748`). Its CST row also governs the
  Zodiac Lens and symbol cross-check when Phase 10 runs them.
- **In `RWBEM_Adapter.md`:** HAR-ULM-48 (with HAR-RWBEM-11).
- HAR-ULM-41 is Cosmetic (see the closing note).

## Rules that apply unchanged
These carry over as written once the L1 document and sheet are plugged in (`HAR_ULM.md`, "Generalizes cleanly"):
- **LAW 0, LAW 0-R, the Law of No Forced Fit, and the Law of One Location** (`01:8-56`; `RB:378-428, 430-552`).
  Read the last as "one race on its own terms" too (`CLAUDE.md` rule 10).
- **The input contract's categories** PROVIDED / RESERVED / PRODUCED / REQUESTED, and the request format
  (`05:114-131, 439-451`). Charter answers the developer hasn't given are REQUESTED, never invented.
- **Circularity, laundering via migration, and ratification** (`05:468-742`).
- **The capability spine:** the four quadrants, shapes, the deficit-address axis, the rule of three, and the
  both-are-true test (`02:357-469, 497-555, 571-625`). These are neutral only while the generators carry the
  physiology (rows HAR-ULM-12 and -30).
- **Type, modifier, Interstitial, Band 0, provisional-inheritance, and neutral-default-frame procedures**
  (`01:91-160, 256-276, 344-391, 423-447`). The one exception is the *Growing* status (HAR-ULM-06).
- **Mechanic 9's three rules** (`03:191-198`). Only its single-population framing is extended (HAR-ULM-18).
- **Sanction proportionality** (`03:942-947`; `00d:149-177`), once P-9 is supplied.
- **The shadow tests, proportion, and no-villains** (`00d:109-147`).
- **The 00b discipline and its object-vs-sector arithmetic** (`00b:108-243`), except the share benchmark
  (HAR-ULM-32).
- **Gate 11's arithmetic half** (`04:260-282`) and **Gates 0, 1, 3, 5, 6, 7, 8, 9, C, F, P, G**, the Part IV
  honesty problems, and the Part V / V.2 trials.
- **Phase 4's differentiation axis** "a shift, a tide, a light cycle… nothing at all" (`03:601-602`).
- **The panel's position-based standpoints** (Passer-Through, Neighbor; `00f:587-594`), the Lover faculty
  question (`00f:324-327`), and "a position that cannot be cast at all is a finding" (`00f:757-764`).
- **The persistence test and "records, not traditions"** (`DRL:339-381, 634-646`).
- **The divergence operator's inputs and its "do not reason from elapsed time" rule** (`02:271-281`;
  `RB:2180-2208`). Only the calibration changes (HAR-ULM-50).
- **Anti-stereotype sequencing** (`RB:2090-2124`). It carries straight over to the species-stereotype ban
  (`CLAUDE.md` rule 3).

## Open items needing an Inner Tepenia ruling (point to Q-27; do not resolve)
All of these are filed under **Q-27** (`OPEN_QUESTIONS.md`), from `HAR_ULM.md` "Notes for the developer." The
rows above give a `Proposed interim` handling only so a Phase 7 pass isn't blocked. None of them is a ruling.
1. **The species floor as an inheritance source** (HAR-ULM-09, -10; note 1): add a species-determined class to
   `01` §5.1, or count L2 as a "parent" for Determined purposes?
2. **A "made / engineered here" arrival mode** (HAR-ULM-16; note 2): Phase 2's main generative instrument would
   change.
3. **A same-race swap partner** (HAR-ULM-27; note 3): changes Gate 4 and Phase 9 E.
4. **The robot addresses in `03`'s MUST OPEN blocks** (HAR-ULM-25; note 4): may an adapter remap them per race,
   or should they move behind a "the setting's non-human canon" pointer?
5. **Physiology as a Tier 0 input** (HAR-ULM-30; note 5). Adding it upstream would close the gap for robots too.
6. **`00f` §9's universality claim** (HAR-ULM-34; note 6): amend the claim, or leave it and let the adapter
   override it?
7. **"Act" as a universal concept** (HAR-ULM-11; note 7): does it generalize as an identity-consolidation stage
   timed by P-5 / M-7, or stay project-specific? Related: Q-25 (the elapsed-time ban vs. M-7).
8. **`DR-11a` scoping** (HAR-ULM-56; note 9): if `DR-11` is registered into `Robot_Universals`, scope it to
   robots explicitly.
9. **Gate 11's interpretive half** (HAR-ULM-28; note 11): does the "cite L1, L2, or EBEM evidence" rule belong in
   `04` itself, or only here?

HAR_ULM note 8 (the §C.9b precedent) needed no Inner Tepenia change and is already corrected in
`MASTER_PLAN.md` §3. Note 10 (which register is authoritative for the `Disciplines/` copies) is handled by the
cross-references above.

## Cosmetic entries (closing note)
These are wording or worked-instance issues. A pass reads through them using the parameter named:
- HAR-ULM-05 · "True of every small crew" → P-12
- HAR-ULM-13 · Standing cost assumes someone must stay awake → P-1
- HAR-ULM-26 · Phase 9 is framed as robots and humans → M-6 Mode B; L4
- HAR-ULM-31 · A food is "a meal"; art is "a song" → P-7, P-8
- HAR-ULM-33 · The shadow substrate is human individual psychology → L2
- HAR-ULM-41 · The failure-state table uses the human life course → P-6. Its CST twin, HAR-CST-13, is Adjust
  and has a row in `CST_Adapter.md`.
- HAR-ULM-53 · Robots share the human night → P-1
