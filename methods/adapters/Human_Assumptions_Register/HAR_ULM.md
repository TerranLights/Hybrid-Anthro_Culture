# Human-Assumptions Register — ULM
**Status:** Proposed, 2026-10-21 sweep. Part of M-0 (see `MASTER_PLAN.md` §4).
**Files swept:**
- `ULM/01_Frame_Typology_and_Inheritance.md` (full)
- `ULM/02_Generators_Capability_and_Symbols.md` (full)
- `ULM/03_The_Phase_Spine.md` (full)
- `ULM/04_QA_Gates_and_Differentiation.md` (full)
- `ULM/05_The_Input_Contract.md` (full)
- `ULM/Disciplines/README.md` (full)
- `ULM/Disciplines/00b_General_Population_Discipline.md` (full)
- `ULM/Disciplines/00d_Shadow_Proportion_Discipline.md` (full)
- `ULM/Disciplines/00f_Review_Panel.md` (full)
- `ULM/Disciplines/Cultural_Synthesis_Techniques.md` (full; the ULM copy. `DR-14` keeps it out of a ULM pass, so its entries here are mostly duplicates of the CST register)
- `ULM/Disciplines/Real-World_Basis_Extrapolation_Method.md` (full; the ULM copy. Same `DR-14` note)
- `ULM/00_RUNBOOK.md` (Step −2 through Step 5, §A–§E and §C.7–§C.10 read in full; Steps 6–10 and the leak/contamination machinery skimmed by keyword)
- `ULM/DEVELOPER_RULINGS_LOG.md` (skimmed; `DR-4`, `DR-7`, `DR-10`–`DR-16`, `DR-24`–`DR-26`, `DR-56`–`DR-58` read in full)

Line numbers are from the files as read on 2026-10-21. These files change often, so re-check a line before relying on it.

---

## Summary

The ULM is the least human-bound of the four methods in its machinery, but its examples are human throughout, and the
universal files (`01`–`05`) carry seven blocking assumptions that would leak into every race.
- **What generalizes:** the spine (three generators, the four-quadrant capability frame, shapes, deficit addresses,
  the both-are-true test), the input contract, the circularity and ratification rules, and most QA gates. These are
  species-neutral as long as the generators are fed the race's physiology.
- **The core problem:** nothing in `01`–`05` *requires* that physiology. Mechanic 9 (`03` §0.2) is the only hook. It
  assumes one non-human body set against an implicit human baseline, and the input contract does not list physiology
  as a blocking input at all.
- **The worst offenders:**
  - the scale bands, which are human group-size thresholds;
  - G2, which is read against an unstated human body;
  - the inheritance classes, which have no slot for the species floor;
  - the swap test and the "could this be true anywhere?" test, which cannot see species-generic findings;
  - Gate 11's plausibility check, which runs on human intuition;
  - the Review Panel, built on positions in a human life;
  - the arrival-mode taxonomy, which has no mode for "made here";
  - every time-depth calibration (the Acts, the "~250 years is not short" benchmark, the epistemic horizon), which
    assumes human generation length.
- **Robot-specific assumptions** sit mostly in the runbook and `03`'s MUST OPEN blocks. The most dangerous is
  §C.9b's "inheritance is mediated, not personal," which `MASTER_PLAN.md` §3 cites as a precedent but which reverses
  for any race that bears and raises its own young.
- **Coverage of the parameter list:** P-1…P-9 handle most entries. Four gaps need new parameters (see below).

---

## Register

| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| **HAR-ULM-01 · Scale bands are human group-size thresholds** | `ULM/01_Frame_Typology_and_Inheritance.md:174-182, 195-200` | Bands at ~30 / ~500 / ~50k. "Below thirty people, everything is witnessed." | The thresholds track human cognitive group limits and sight-range social surveillance | Species with larger or smaller stable group sizes; scent-tracking species (deviance is detectable after the fact, so "unwatched" starts at a different size); solitary-leaning cat-people; warren-colony rabbit-people | P-3 (band thresholds), P-4 (perception range) | Blocking |
| **HAR-ULM-02 · Recognition is by sight** | `ULM/01_Frame_Typology_and_Inheritance.md:178` | Band 2's unit of analysis is "Persons-known-by-sight" | Treats human face recognition as the identity channel | Scent-recognizing species (dogs, rabbits); voice-recognizing species; nocturnal species | P-4, P-8 (recognition channel) | Adjust |
| **HAR-ULM-03 · An office outlives its holder only above a human-tenure threshold** | `ULM/01_Frame_Typology_and_Inheritance.md:202-207` | Below ~500, "the person *is* the office… when they die the mechanism dies" | Whether an office outlives its holder depends on how long holders live compared with how long institutions last | Long-lived races (one holder spans the settlement's whole history, so offices stay personal at large sizes); short-generation species (offices turn over fast enough to act like institutions at small sizes) | P-5, M-7 | Adjust |
| **HAR-ULM-04 · Headcount equals social participants** | `ULM/01_Frame_Typology_and_Inheritance.md:176-182`; `ULM/05_The_Input_Contract.md:146` | Population magnitude alone sets the band | Human populations have a moderate dependent fraction, so a headcount approximates the social body | Litter-bearing, high-fecundity species with a large juvenile fraction; species with a long non-participating juvenile stage | P-2, P-6 (derive an adult-equivalent count on the sheet) | Adjust |
| **HAR-ULM-05 · "True of every small crew"** | `ULM/01_Frame_Typology_and_Inheritance.md:249-252` | Every Band 1 place has "a practice that is visibly one person deep, because that is true of every small crew that has ever existed" | The evidence base is human crews, where practices travel person to person | Species with innate or engineered competences, where a practice is not carried by one person | NEW PARAMETER NEEDED: Enculturation & transmission mode (P-12); L2 | Cosmetic |
| **HAR-ULM-06 · Growth means arrivals** | `ULM/01_Frame_Typology_and_Inheritance.md:287` | Status *Growing*: "Who is arriving, what do they not know, and what is straining?" | Models settlement growth as migration, because human birth rates are low | High-fecundity species, whose growth is internal (births) and whose strain is age structure rather than newcomer ignorance | P-2, P-5 | Adjust |
| **HAR-ULM-07 · Era is inferred from the human technology timeline** | `ULM/01_Frame_Typology_and_Inheritance.md:315-317`; `ULM/05_The_Input_Contract.md:157-161` | "an orbital station is evidently future, a medieval village evidently past" | Infers era from a place's position on Earth-human technological history | Elves (alien-engineered on a parallel Earth), aliens, and any race whose technology path is not humanity's; under D-2 the world itself is unknown | L0 (origin frame, timeline placement) | Adjust |
| **HAR-ULM-08 · Generational memory turnover** | `ULM/01_Frame_Typology_and_Inheritance.md:320-323, 469-478`; `ULM/02_Generators_Capability_and_Symbols.md:235-238, 512, 517-524`; `ULM/03_The_Phase_Spine.md:710-720` | Founding, crisis, and now are different people. "A practice whose original reason has been forgotten." Witnesses have departed | Assumes a human lifespan, so the founders, the crisis generation, and the present are different living cohorts | Long-lived races: founders are still alive, so "nobody remembers why" is false and nostalgia is personal memory. Short-generation species: forgetting is much faster, with many turnover cycles per era | P-5, M-7 | Blocking |
| **HAR-ULM-09 · The parent determines calendar and language family** | `ULM/01_Frame_Typology_and_Inheritance.md:413`; `ULM/04_QA_Gates_and_Differentiation.md:362-363`; `ULM/05_The_Input_Contract.md:212` | "A sub-location does not have its own climate, currency or calendar. If the pass produced one, it is wrong." | In a one-species human polity, calendar and language family are cultural properties the parent sets | Mixed-species polities. A race may legitimately keep a biological calendar (breeding season, activity cycle) and a species-bound language (non-vocal channels) that the parent cannot set. Gate I would reject a correct finding | P-1, P-2, P-8; M-6 | Blocking |
| **HAR-ULM-10 · The inheritance classes have no slot for the species floor** | `ULM/01_Frame_Typology_and_Inheritance.md:407-421`; `ULM/04_QA_Gates_and_Differentiation.md:356-384` | Every element is Determined, Inflected, Originated, or Aggregated *relative to the parent location* | For humans, species-level traits are invisible because every location shares them | Every non-human race. A species-universal trait (for example, warren-structured territory) gets classed "Originated" locally, and Gate I's Originated:Inflected ratio is distorted | L2 (M-3 output) as a "species-determined" source, ahead of "what the parent determines" in the order of attempts | Blocking |
| **HAR-ULM-11 · Act timing and "origin is ancestry"** | `ULM/01_Frame_Typology_and_Inheritance.md:400-404`; `ULM/02_Generators_Capability_and_Symbols.md:312-314`; `ULM/00_RUNBOOK.md:2244-2263`; `ULM/Disciplines/Cultural_Synthesis_Techniques.md:279-282` | Act 1 (origin culture "still fresh") gives way within ~a century to Act 2 ("properly Tepenian… origin is now ANCESTRY, not identity") | The pace is calibrated on human third- and fourth-generation assimilation | Long-lived races (founders still alive in "Act 2", so origin is still identity); short-generation species (assimilation within decades); an engineered first generation (no origin culture except the creators') | P-5, M-7; L3 | Blocking |
| **HAR-ULM-12 · G2 is read against an unstated human body** | `ULM/02_Generators_Capability_and_Symbols.md:174-187`; `ULM/03_The_Phase_Spine.md:517-518` | "withhold absolutely? (daylight for four months…)"; "demand continuously? (heat, pressure…)"; "permit but punish? (going outside, being alone…)" | What an environment withholds or demands depends on the body. Every example is a human tolerance. G2 is the primary generator and has no physiology hook of its own | Cold-adapted furred species; nocturnal or crepuscular species, for whom polar night is not a deprivation; low-light vision; species for whom being alone carries no social cost | P-9, P-1, P-3; L1 via Mechanic 9 | Blocking |
| **HAR-ULM-13 · Standing cost assumes someone must stay awake** | `ULM/02_Generators_Capability_and_Symbols.md:380-381` | "its standing cost is heat, power, snow clearance, and somebody being awake" | Assumes human single-block sleep and a night shift | Polyphasic sleepers, crepuscular species, species without consolidated sleep | P-1 | Cosmetic |
| **HAR-ULM-14 · Real-world research is human-only** | `ULM/02_Generators_Capability_and_Symbols.md:240-254`; `ULM/05_The_Input_Contract.md:202`; `ULM/01_Frame_Typology_and_Inheritance.md:502-503`; `ULM/00_RUNBOOK.md:2607-2620` | G7 has the "highest surprise value". Step 3.1: "Find a real culture that has it". Step 3.2: a substitute institution from "a real culture" | The only external research stream in-run is human places and human cultures (`DR-15` keeps it in the ULM) | Every non-human race. It imports institutions shaped by human bodies and cognition, which is the "humans with ears" failure (`MASTER_PLAN.md` §8) | M-2 EBEM as a second Step 3 stream (M-5 for aliens); check every import against L1 | Blocking |
| **HAR-ULM-15 · Composition means national origins** | `ULM/02_Generators_Capability_and_Symbols.md:271-281, 310-323`; `ULM/03_The_Phase_Spine.md:408-414`; `ULM/00_RUNBOOK.md:2090-2124` | Composition is read as nations plus percentages; the divergence operator's "stock" is the origin nation's culture | The human composition axis is nationality or ethnicity | Multi-species and multi-creator lineages, where the axes are species × creator lineage × base-animal line × nation. For an engineered race the stock is the creators' culture filtered through the body | M-6, L3, M-4 | Adjust |
| **HAR-ULM-16 · No arrival mode for "made here"** | `ULM/03_The_Phase_Spine.md:434-446` | Seven arrival modes: chose, assigned, fled, born, inherited, sentenced, stopped | Humans arrive only by birth or migration | Engineered races: a first generation created or decanted on site, young bred to a placement by their creators, or a population released. A pass would force these into "Born here" or "Assigned / posted" without noticing | M-4 (Design Charter) supplies the mode; P-2 | Blocking |
| **HAR-ULM-17 · "Born here" assumes human rearing** | `ULM/03_The_Phase_Spine.md:443` | Natives "never chose, and frequently cannot leave" | Assumes single births, long parental rearing, and family-anchored natives | Litter-bearing species (natives arrive as cohorts); crèche or communal rearing; species whose young disperse at maturity | P-2; NEW PARAMETER NEEDED: Dispersal & philopatry (P-13) | Adjust |
| **HAR-ULM-18 · Mechanic 9 is a two-body model** | `ULM/03_The_Phase_Spine.md:169-200, 1057-1060`; `ULM/00_RUNBOOK.md:1981, 2067-2068, 2330-2334` | "*the* non-human population… *its* physiology". "The general physiology document". "In this project that is robots and humans" | Humans are the implicit baseline and there is exactly one non-human document | Settlements holding several non-human races plus humans (Q-10). One document gets read, and the rest are written as human, which is the exact failure Mechanic 9 describes | M-6, plus one L1 and one parameter sheet per race present | Blocking |
| **HAR-ULM-19 · The player-facing channels are human senses** | `ULM/03_The_Phase_Spine.md:162-164`; `ULM/Disciplines/Cultural_Synthesis_Techniques.md:150-157` | "seen, heard, entered, handled, spoken, done, or hooked"; "A finding that can only be read about is weak" | The channels are human senses and actions, so scent or vibration findings get demoted as "weak" | Scent-dominant species (chin-marking cat- and rabbit-people, dogs); substrate-vibration signalers (rabbit thumping); ultrasonic communication | P-4, P-8; add a rendered-proxy channel (smelled or felt, shown through NPC reaction or text) | Adjust |
| **HAR-ULM-20 · The sensory texture fields are human channels** | `ULM/03_The_Phase_Spine.md:474, 509-512` | "to the eye, ear, nose, and skin"; four fields: Sound, Smell, Feel, First impressions | Human channels and human ranges; "first impressions" defaults to visual | Ultrasonic hearing (cats); UV or low-light vision; substrate vibration; vibrissae; taste-marking | P-4 | Adjust |
| **HAR-ULM-21 · An ordinary day is diurnal** | `ULM/03_The_Phase_Spine.md:536, 579-583, 587-589` | "an ordinary person's day"; "between one hour and the next"; "somebody's Tuesday" | Assumes a human diurnal, single-sleep day and a 7-day week | Crepuscular rabbit-people (*rabbit CORRECTED 2026-10-21: field activity ranges from nocturnal to two-peaked dawn/dusk with predators and weather, so a "midnight rest" is not general; `races/Rabbit/research_log/EBEM_Log_02_Body_LifeHistory_Diet_Health.md`*); nocturnal or polyphasic species. A 9-to-5 day would be wrong without anyone noticing | P-1 (Phase 4's axis list at `:601-602` already allows "a light cycle") | Blocking |
| **HAR-ULM-22 · Death and mourning follow the human pattern** | `ULM/03_The_Phase_Spine.md:754-755, 816-825`; `ULM/05_The_Input_Contract.md:273` | "what does it do about death?"; "who is not mourned properly, and why not" | Assumes the human mortality profile (low juvenile mortality, long life, individual grief) | High-fecundity species with high juvenile mortality; long-lived races; species with different kin attachment | P-2, P-5; M-3 (grief universals) | Adjust |
| **HAR-ULM-23 · Skill passes by teaching and apprenticeship** | `ULM/03_The_Phase_Spine.md:922-925`; `ULM/Disciplines/00f_Review_Panel.md:194-200` | 7c: "Apprenticeship, qualification… what becomes of the ones who cannot learn it." Mentor: "Transmits skill" | Assumes a long human juvenile learning period, with teaching as the default channel | Engineered or innate competences; short maturation; imitation-only learners | NEW PARAMETER NEEDED: Enculturation & transmission mode (P-12); P-5 | Adjust |
| **HAR-ULM-24 · Making assumes clothing, vocal music, and spoken accent** | `ULM/03_The_Phase_Spine.md:985-994` | Cuisine, Music, Dress, Language ("accent, code-switching, slang"). Dress: "what does that need becoming custom look like after two centuries?" | Assumes human need for clothing, vocal-auditory music and speech, and a human time scale for custom | Furred species (dress optional or adornment only); non-vocal signalers; ear, tail, or scent "language"; obligate-carnivore or grazer cuisine | P-8, P-7, P-4; NEW PARAMETER NEEDED: Body plan, scale & integument (P-10) | Adjust |
| **HAR-ULM-25 · Robot canon is hard-wired into the universal MUST OPEN blocks** | `ULM/03_The_Phase_Spine.md:541-552, 760-769, 962-963, 1033-1040, 1110-1113` | Phase 4: `Robot_Physiology…` is "THE LARGEST SINGLE INPUT". Phase 9: `Laws_of_Robotics`, `Robot_Universals`. Phase 6: robot religions | Inner Tepenia project data in a universal file, naming robots rather than "the setting's non-human population" | Any non-robot race. Mandatory robot sources ("Not optional", `M-169`) push the race's own L1 and L2 aside | The adapter remaps each block to the race's L1/L2 and its religion and law canon (see developer notes) | Adjust |
| **HAR-ULM-26 · Phase 9 is framed as robots and humans** | `ULM/03_The_Phase_Spine.md:1057-1066` | "In this project that is robots and humans"; the lens anchors "robot culture" in the founding population | A two-kind roster | Multi-species settlements, where species may itself be "a category that matters more than kind" | M-6; L4 | Cosmetic |
| **HAR-ULM-27 · The swap test can't see species-generic findings** | `ULM/04_QA_Gates_and_Differentiation.md:141-146`; `ULM/03_The_Phase_Spine.md:466, 1089-1094` | Swap "onto a real-world comparable or a generic location of the same type"; "*would this be true anywhere?*" | The pool of swap partners is human places, so a species trait looks location-unique | Every non-human race. An L2 species universal passes as a local finding, so the place reads as distinctive when it is only typical of the race | L2: add "would this be true of any settlement of this race?" | Blocking |
| **HAR-ULM-28 · Gate 11 plausibility runs on human intuition and human density norms** | `ULM/04_QA_Gates_and_Differentiation.md:250-258, 265-278, 540-545` | "would a person actually do this"; density "comparable to some of the densest real cities on Earth" | The author's sense of how people behave, and the comparison cities, are human. The interpretive half is already "the weakest gate" | Every non-human race. Body scale and territoriality change what density is plausible | L1/L2 with M-2 evidence cited for every behavioral plausibility call; P-3; P-10 | Blocking |
| **HAR-ULM-29 · Pull/push durability is human migration psychology** | `ULM/05_The_Input_Contract.md:298-327` | "A population assembled by attraction has already demonstrated willingness to relocate… It will demonstrate it again" | Generalizes from human voluntary mobility | Territorial or philopatric species; sex-biased dispersal (one sex always leaves, so "willingness to relocate" is biological rather than chosen) | P-3; NEW PARAMETER NEEDED: Dispersal & philopatry (P-13) | Adjust |
| **HAR-ULM-30 · The input contract lacks physiology as a blocking input** | `ULM/05_The_Input_Contract.md:140-150, 749-803` | Tier 0 is existence, position, population magnitude, and parent. The pre-flight checklist has no physiology line | For a human population, physiology is an unstated constant | Every non-human race. A pass can return "proceed" with no L1, even though band, G2, Phase 4, and Gate 11 all depend on it | L1 plus the M-0a parameter sheet as a Tier 0 input when the population is non-human | Blocking |
| **HAR-ULM-31 · A food is "a meal"; art is "a song"** | `ULM/05_The_Input_Contract.md:265-266` | "what a meal *is* here"; "A song, artwork, or story" | Assumes discrete meals and vocal song | Grazers (continuous feeding, caecotrophy); non-vocal species | P-7, P-8 | Cosmetic |
| **HAR-ULM-32 · Sector-share baselines come from human economies** | `ULM/Disciplines/00b_General_Population_Discipline.md:224, 241-242` | "ordinary shares of 25–35%"; "Athens is not 35% archaeology" | The healthy-share benchmark is drawn from human economies | Species with large feeding time budgets (grazers), different work capacity, or different activity hours | P-7, P-1, P-10 | Adjust |
| **HAR-ULM-33 · The shadow substrate is human individual psychology** | `ULM/Disciplines/00d_Shadow_Proportion_Discipline.md:153-156, 200-203` | "The substrate files describe one person at a time"; "ordinary human loyalty to people you know" | The source books describe humans. The scaling rule itself is neutral | All non-human races, but only as source flavor | M-3 / L2 | Cosmetic |
| **HAR-ULM-34 · The Review Panel is built on positions in a human life** | `ULM/Disciplines/00f_Review_Panel.md:129-132, 809-813`; `ULM/04_QA_Gates_and_Differentiation.md:241-248` | "positions in a human life… survive the move… unchanged"; Gate 10 "carried unchanged — only the casting changes" | Explicitly universalizes the human life course and calls it fit for the ULM | Precocial or short-maturing species; long-lived races; engineered races with no childhood (cf. `DR-11` for robots) | P-6 | Blocking |
| **HAR-ULM-35 · Child and Parent assume long dependency** | `ULM/Disciplines/00f_Review_Panel.md:158-177, 580-582` | "dependents who cannot yet fend for themselves"; Child cast as "a resident's kid, too young to work" | Assumes a long human childhood and one-to-one parental care | Litter cohorts; communal or crèche rearing; fast maturation | P-2, P-5, P-6 | Adjust |
| **HAR-ULM-36 · The Lover assumes pair-bonding** | `ULM/Disciplines/00f_Review_Panel.md:165-170, 581` | "Oriented toward one other person"; cast as "a courting pair with nowhere private" | Assumes the human pair bond and romantic love | Promiscuous, polygynous, seasonal-breeding, or induced-ovulation species; engineered sterility | NEW PARAMETER NEEDED: Mating system & pair-bond form (P-11) | Adjust |
| **HAR-ULM-37 · The Elder assumes human senescence** | `ULM/Disciplines/00f_Review_Panel.md:186-192, 584` | "Past active contribution; holds the memory; now dependent in a different way" | Assumes human aging and a long post-reproductive life | Species with no post-reproductive phase; non-senescing or very long-lived races; very short-lived species | P-6, P-5 | Adjust |
| **HAR-ULM-38 · The Life Arcs are gendered human passages** | `ULM/Disciplines/00f_Review_Panel.md:204-221, 246-256` | Maiden: "leaving the parental home; individuation"; Queen, King, Crone | Human dispersal pattern and a gender-coded life course | Female-philopatric warren species (*rabbit: CORRECTED 2026-10-21. Female dispersal occurs, 32–95% philopatry across Australian populations; `races/Rabbit/research_log/EBEM_Log_01_Senses_Communication_Cognition_Social.md`*); male-dispersal species; different sex roles | P-6; NEW PARAMETER NEEDED: Dispersal & philopatry (P-13) | Adjust |
| **HAR-ULM-39 · Panels D and E are human depth psychology** | `ULM/Disciplines/00f_Review_Panel.md:281-284, 353-390`; `ULM/00_RUNBOOK.md:2078` | "archetypes of the mature masculine"; Oedipal Child, Mama's Boy, "the last stage of boyhood" | Jungian and psychoanalytic theory of human (male) development | All non-human races. The faculty *questions* transfer; the developmental claims do not | L2 (M-3): keep the four questions, drop the developmental mapping | Adjust |
| **HAR-ULM-40 · The bounded franchise is measured by arm reach** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:293-313` | "How far an arm reaches from your window"; "individual human decisions" | Human body reach | Different limb reach, body scale, or locomotion | P-4; P-10 | Adjust |
| **HAR-ULM-41 · The failure-state table uses the human life course** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:331-339` | "you age out"; "You can no longer work" | Human aging and working-life shape | Species with different life stages or senescence | P-6 | Cosmetic |
| **HAR-ULM-42 · Micro-practices use human gestures** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:352-371` | "A specific greeting, nod, or naming"; "A glance or signal"; "A count, a breath" | Human gesture and vocal repertoire | Ear and tail signaling; scent-marking (chin-rubbing); allogrooming; substrate thumps | P-8, P-4 | Adjust |
| **HAR-ULM-43 · Borrowed Form's "every society needs" list** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:670-675` | "no form for something every society needs… mourning, celebration, arbitration, hospitality, apprenticeship" | Treats Brown-style human universals as needs | Any race where M-3 returns Non-Transfer for one of these | M-3 (only universals that survive for this race) | Adjust |
| **HAR-ULM-44 · Human temperament typologies and robot symbol systems used as lenses** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:798-805, 891-907`; `ULM/03_The_Phase_Spine.md:1110-1113, 1155-1160`; `ULM/00_RUNBOOK.md:722, 1746-1748` | Zodiac Lens "person-shaped" results; `Enneagram_Character_Index`; cross-check against "Robot Elementals" and "Robot Planetary Symbols" | The Zodiac and Enneagram describe human temperaments; the elemental and planetary sets are registered for robot cities | Every non-human race (person-results come out human-shaped); non-robot settings (wrong symbol register) | L2 (M-3) as a filter on person-results; register race-appropriate systems through `02` §6.5 | Adjust |
| **HAR-ULM-45 · Composition Merge R4 has only cultural axes** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:1061-1063` | Stock distance measured on "staple… kinship form · script, calendar… funerary… dietary prohibition… CLIMATE" | Human stocks differ only culturally, so biology is never an axis | Mixed-species stocks. A diet-class or activity-cycle mismatch makes them FAR stock even when cultures match, so the merge depth comes out wrong | M-6 | Blocking |
| **HAR-ULM-46 · R5 viability thresholds** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:1079-1090` | "under ~2% Traces… ~5–10% One institution… over ~20% A CO-DEFAULT" | Calibrated on human minority sociology | Species with very different group-size needs or institution-sustaining minimums | Re-justify per race (P-3) or mark human-only | Adjust |
| **HAR-ULM-47 · R6/R7 assume generational assimilation** | `ULM/Disciplines/Cultural_Synthesis_Techniques.md:1121-1124, 1143-1148` | "a small group keeps only what it cannot do without"; "their descendants are simply from here" | Human minority retention, at human generation pace | Long-lived races (no descendants yet); short-generation species (faster absorption); engineered cohorts | P-5, M-7 | Adjust |
| **HAR-ULM-48 · RWBEM Step B researches only real human places** | `ULM/Disciplines/Real-World_Basis_Extrapolation_Method.md:312-318` | "Run an actual web search on the named real place itself" | The research pool is human sites only | Every non-human race (`DR-14` keeps this out of a ULM pass) | M-2 EBEM | Adjust |
| **HAR-ULM-49 · Inheritance is "mediated, not personal" (robot-specific)** | `ULM/00_RUNBOOK.md:2116-2121` | "FOR ROBOTS THE INHERITANCE IS MEDIATED, NOT PERSONAL… not through any individual robot's 'origin.'" | A robot ruling with no parents and no rearing. `MASTER_PLAN.md` §3 cites it as the L3 precedent | Every race that bears and raises its own young: after the first engineered generation, inheritance is personal (parents to young). Copying the robot verdict would erase family transmission | P-2 (who raises young), M-4 (first generation only) | Blocking |
| **HAR-ULM-50 · Divergence pace is calibrated on human ethnogenesis** | `ULM/00_RUNBOOK.md:2154-2172, 2210-2212` | "after enough generations"; "~250 YEARS… Roughly the age of the United States… not short" | Benchmarked on human generation length and human national ethnogenesis (Québécois, Australian, Singaporean) | Long-lived races (250 years may be under one generation); short-generation species (250 years may be 80+ generations) | P-5, M-7 | Blocking |
| **HAR-ULM-51 · Kinship by shared experience (robot-specific)** | `ULM/00_RUNBOOK.md:2352-2353` | "kinship by shared experience, not fabrication lineage" | A robot answer, since robots have no genetic lineage. Listed as standard L1 content | Anthros and every other biological race: genetic and rearing kinship come back (`MASTER_PLAN.md` §5, M-3 reversal warning) | P-2 (kin recognition), M-3 | Blocking |
| **HAR-ULM-52 · The robot physiology facts become a body template** | `ULM/00_RUNBOOK.md:2338-2345` | Bodies are "HUMAN-LOOKING"; robots "WEAR CLOTHING, AND NEARLY ALWAYS DO"; "a human-shaped hand"; "what evolution already optimized" | A robot body built on the human form. The only worked "ordinary condition" in the ULM is humanoid and clothed | Non-humanoid body plans; furred integument; digitigrade or quadrupedal posture | L1 (Mechanic 9 rule 3); NEW PARAMETER NEEDED: Body plan, scale & integument (P-10) | Adjust |
| **HAR-ULM-53 · Robots share the human night** | `ULM/00_RUNBOOK.md:1976` | Phase 4 input: "the shared night, overnight recharging, leisure-as-a-fact-of-life" | Robots are synced to the human diurnal night | A settlement whose majority is crepuscular or nocturnal: there is no single "shared night" | P-1 | Cosmetic |
| **HAR-ULM-54 · Labor data are human labor data** | `ULM/00_RUNBOOK.md:2071-2072`; `ULM/03_The_Phase_Spine.md:863-866` | Staffing ratios and labor-productivity factors; the SOC occupational taxonomy | Human work hours, body capacity, and occupation categories | Different activity cycles, body scale, or manipulation; occupations that don't exist for humans | P-1, P-4, P-10 | Adjust |
| **HAR-ULM-55 · Belief-transmission sources assume human imitation** | `ULM/00_RUNBOOK.md:2079`; `ULM/03_The_Phase_Spine.md:766-768` | `The_Meme_Machine` and `The_True_Believer` extractions feed Phase 6 and 7d | Human memetics and mass-movement psychology | Species with different social-learning or conformity mechanisms | P-12; M-3 | Adjust |
| **HAR-ULM-56 · DR-11 sets enculturation "very similarly to humans" as the model** | `ULM/DEVELOPER_RULINGS_LOG.md:448-461` | Robots "learn the cultures that they're immersed in (very similarly to humans)… without a childhood" | Uses human enculturation as the reference mechanism; `MASTER_PLAN.md` §3 cites it for L3 | Engineered races with installed behaviors; species with narrow developmental windows | P-12, P-6, M-4 | Adjust |
| **HAR-ULM-57 · DR-56: human language acquisition, generational learning, guilt-driven duty** | `ULM/DEVELOPER_RULINGS_LOG.md:1115-1118, 1124` | "A human child would learn the dominant language"; "the first generation of incomers had to learn"; not acting brings "deep and immense personal guilt" | Human language acquisition, human generations, and human moral emotion as what enforces duty without compulsion | Non-vocal or differently acquired communication; short or long generations; races whose social emotions differ (M-3) | P-8, P-12, P-5; M-3 | Adjust |

**Count:** 57 entries. Blocking 18 · Adjust 32 · Cosmetic 7.

---

## Generalizes cleanly

These are species-neutral and can be used unchanged once the race's L1 and parameter sheet are plugged in.
- **The governing laws.** LAW 0 (`ULM/01_Frame_Typology_and_Inheritance.md:8-56`) and LAW 0-R
  (`ULM/Disciplines/Real-World_Basis_Extrapolation_Method.md:1-58`) apply as written. So do the Law of No Forced Fit
  (`ULM/00_RUNBOOK.md:378-428`) and the Law of One Location (`ULM/00_RUNBOOK.md:430-552`), which extend directly to
  "one race on its own terms" (`MASTER_PLAN.md` §8).
- **The input contract's categories.** PROVIDED / RESERVED / PRODUCED / REQUESTED and the request format
  (`ULM/05_The_Input_Contract.md:114-131, 439-451`) are exactly what M-4 CIDA needs ("requested, never invented").
- **Circularity and ratification.** The circularity rule, laundering via migration, and ratification-by-root
  (`ULM/05_The_Input_Contract.md:468-742`) are about provenance, not biology.
- **The capability spine.** The four quadrants, shapes, the input-set caveat (§4.0), the deficit-address axis, the rule
  of three, and the both-are-true test (`ULM/02_Generators_Capability_and_Symbols.md:357-469, 497-555, 571-625`) are
  neutral. Their neutrality depends on the generator inputs carrying the physiology (see HAR-ULM-12, -30).
- **Type, status, and frame structure.** The location types and modifiers, the Interstitial procedure, the Band 0
  procedure, the provisional-inheritance protocol, and the neutral-default-frame rule
  (`ULM/01_Frame_Typology_and_Inheritance.md:91-160, 256-276, 344-391, 423-447`). One exception: HAR-ULM-06 on the
  *Growing* status.
- **Mechanic 9's three rules.** Read the general physiology document first, never infer physiology from the word, and
  state the ordinary condition first (`ULM/03_The_Phase_Spine.md:191-198`). This is the plug-in point; only its
  single-population framing needs extending (HAR-ULM-18).
- **Sanction proportionality.** "Price it in this location's physical conditions"
  (`ULM/03_The_Phase_Spine.md:942-947`; `ULM/Disciplines/00d_Shadow_Proportion_Discipline.md:149-177`) is neutral once
  P-9 is supplied.
- **The shadow tests.** The three shadow tests, proportion, and no-villains
  (`ULM/Disciplines/00d_Shadow_Proportion_Discipline.md:109-147`) hold for any sentient race with intentions.
- **General-population discipline.** The 00b discipline and its object-versus-sector arithmetic
  (`ULM/Disciplines/00b_General_Population_Discipline.md:108-243`), except the human share benchmark (HAR-ULM-32).
- **Gate 11's arithmetic half.** Dividing population by area (`ULM/04_QA_Gates_and_Differentiation.md:260-282`) is
  arithmetic. Only the *interpretation* of the result is human-bound (HAR-ULM-28).
- **The other gates.** Gates 0, 1, 3, 5, 6, 7, 8, 9, C, F, P, G, the Part IV honesty problems, and the Part V/V.2
  instrument trials (`ULM/04_QA_Gates_and_Differentiation.md`).
- **Phase 4's differentiation axis.** "a shift, a tide, a light cycle… nothing at all"
  (`ULM/03_The_Phase_Spine.md:601-602`) already allows non-diurnal organization.
- **The panel's position-based standpoints.** The Passer-Through and Neighbor
  (`ULM/Disciplines/00f_Review_Panel.md:587-594`), the Lover *faculty* question "is this place alive, and could anyone
  love it?" (`:324-327`), and "a position that cannot be cast at all is a finding" (`:757-764`). The last one gives an
  honest route for human positions a race cannot fill.
- **Inheritance rulings.** The persistence test (`ULM/DEVELOPER_RULINGS_LOG.md:339-381`) and "records, not traditions"
  (`:634-646`) are neutral.
- **The divergence operator.** Its input list and "do not reason from elapsed time"
  (`ULM/02_Generators_Capability_and_Symbols.md:271-281`; `ULM/00_RUNBOOK.md:2180-2208`) are neutral. Only the
  *calibration* is human (HAR-ULM-50).
- **Composition Merge R1–R3 and R5b.** Majority versus plurality, contested lead, concentrated versus dispersed, and
  the pooling hypothesis (`ULM/Disciplines/Cultural_Synthesis_Techniques.md:1031-1057, 1092-1111`) are
  distribution-shape arithmetic.
- **Anti-stereotype sequencing.** The GPS / composition-first sequencing (`ULM/00_RUNBOOK.md:2090-2124`) and the RWBEM
  rule "never evaluate picks by national/demographic matching"
  (`ULM/Disciplines/Real-World_Basis_Extrapolation_Method.md:445-452`) carry straight over to the species-stereotype ban
  (`MASTER_PLAN.md` §2 rule 3). For EBEM the equivalent is "never pick by base-animal resemblance alone."
- **§C.10's list of what a general physiology file must supply** (`ULM/00_RUNBOOK.md:2349-2354`). As a checklist of L1
  *topics* (build, personality variation, language, age categories, kinship, origin site, what counts as death,
  leisure, sexuality, inter-population baseline) it is a ready-made L1 outline. Copy the topics, not the robot answers
  (HAR-ULM-51, -52).

---

## Proposed new parameters

| Code | Parameter | What it would feed | Why P-1…P-9 don't cover it |
|---|---|---|---|
| **P-10** | **Body plan, scale & integument** (size and mass, posture and locomotion, limb and hand form, fur or skin, baseline clothing or adornment need) | Gate 11 density interpretation (HAR-ULM-28); Phase 3 architecture; Phase 8 dress and tools (HAR-ULM-24); 7a labor capacity (HAR-ULM-54); CST T1 franchise (HAR-ULM-40); Mechanic 9 rule 3's "ordinary condition" (HAR-ULM-52); M-6's "body scale" axis, which currently has no parameter feeding it | P-4 covers reach and manipulation only. P-9 covers environmental tolerances, not form or size |
| **P-11** | **Mating system & pair-bond form** (monogamous, polygynous, promiscuous; seasonal or continuous; induced or spontaneous ovulation; whether durable pair bonds exist) | 00f Lover position (HAR-ULM-36); Phase 6 kin and mourning; Phase 4 private life; 7d minorities | P-2 covers reproduction and rearing mechanics, not the social form of mating |
| **P-12** | **Enculturation & transmission mode** (developmental windows; teaching, imitation, innate, or engineered acquisition; vertical, oblique, or horizontal transmission; language-acquisition window) | Phase 7c and the Mentor (HAR-ULM-23); `DR-11` / `DR-56` precedents (HAR-ULM-56, -57); Band 1 fragility (HAR-ULM-05); belief transmission (HAR-ULM-55); together with P-5, the Acts | P-5 gives maturation *age*, not how culture is acquired. Without this, every race silently gets human immersion learning |
| **P-13** | **Dispersal & philopatry** (which sex and age leaves the natal group, how far, natal-site attachment) | Phase 2 arrival modes and "who is not here" (HAR-ULM-17); 05 pull/push durability (HAR-ULM-29); 00f Maiden arc (HAR-ULM-38); 01 §3 status and migration | P-3's "territoriality" says nothing about who leaves or when |

**Field extensions to existing parameters.** These are not new codes.
- **P-4:** add a *recognition channel* field: sight, scent, or voice (HAR-ULM-02).
- **P-6:** add *senescence / post-reproductive phase present?* (HAR-ULM-37).
- **P-2 with P-6:** add a derived *adult-equivalent population* figure, so the band reflects the social body rather
  than the headcount (HAR-ULM-04).

---

## Notes for the developer

These need an Inner Tepenia ruling, because an adapter would otherwise have to contradict the ULM's own text.

1. **Species floor as an inheritance source (HAR-ULM-09, -10).** Gate I says a sub-location with its own calendar is
   "*wrong* — not thin, wrong". In a mixed-species polity, a biological calendar or a species-bound language can be
   legitimately local. Two possible rulings:
   - add a species-determined class to `01` §5.1; or
   - rule that a race's L2 counts as a "parent" for Determined purposes.

   Either one benefits Inner Tepenia too, since robots versus humans already raises this.
2. **A "made / engineered here" arrival mode (HAR-ULM-16).** This changes `03` Phase 2's taxonomy. An adapter can add
   the row, but the taxonomy is described as the phase's "main generative instrument", so the addition should be
   ratified.
3. **A same-race swap partner (HAR-ULM-27).** Gate 4 and Phase 9 E define the swap partner as "a real-world
   comparable or a generic location of the same type". Adding "any settlement of this race" changes a gate.
4. **Robot addresses in `03`'s MUST OPEN blocks (HAR-ULM-25).** These were mirrored from `§C.8c` on 2026-09-07
   (`M-169`) and are binding ("Not optional"). Robot canon names are not location names, so the blocks technically pass
   the Layering Law, but they are project data in a universal file. We need a ruling on whether an adapter may remap
   them per race, or whether they should move behind a "the setting's non-human canon (see runbook)" pointer.
5. **Physiology as a Tier 0 input (HAR-ULM-30).** `05` §2.1 does not list it. Inner Tepenia handles robots through
   Step 0.2 and §C.10 instead. Adding a Tier 0 line would also close the gap for robots.
6. **00f §9's universality claim (HAR-ULM-34).** "Because every position is a stage of a human life… the same six
   work" on any location. The `Disciplines/` copy is pinned to the district original and must stay identical in
   substance, so changing the claim means changing the original. We need a ruling on whether to amend the claim or
   leave it and have the adapter override it.
7. **"Act" as a universal concept (HAR-ULM-11).** The Act stamps in `01` §5.1 (`M-157`) and `02` G8 put an
   Inner-Tepenia timing concept into universal files. We need a ruling on whether "Act" generalizes as an
   *identity-consolidation stage* with its timing set by P-5 / M-7, or stays project-specific.
8. **The C.9b precedent cited in `MASTER_PLAN.md` §3 (HAR-ULM-49).** It is robot-specific and reverses for any race
   that raises its own young. This needs no Inner Tepenia change, but the plan's L3 wording should be corrected before
   M-4 is drafted, so the robot verdict isn't copied.
9. **`DR-11a` is still pending (upstream registration of robot national origin).** If `DR-11`'s "very similarly to
   humans" is registered into `Robot_Universals` as a universe-level fact, it should be scoped to robots explicitly. It
   should not be stated as the general model of how sentients acquire culture (HAR-ULM-56).
10. **The `Disciplines/` copies of CST and RWBEM.** `DR-14` keeps them out of a ULM pass, so HAR-ULM-40 to -48 are
    recorded here only because those files sit in the swept folder. The sibling CST and RWBEM registers should be
    authoritative for those entries, so the two don't need maintaining in parallel.
11. **Gate 11's interpretive half (HAR-ULM-28).** It is already called "the weakest gate". For biological races, a
    standing rule that every behavioral plausibility judgment must cite L1, L2, or EBEM evidence (never author
    intuition) would be a methodology change. It belongs in the adapter, but the developer may want it in `04` itself.
