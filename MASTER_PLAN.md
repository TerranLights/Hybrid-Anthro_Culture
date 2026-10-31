# Master Plan — Developing Non-Human, Non-Robot Cultures

**Status:** Working approach (D-3, 2026-10-21). Individual items are still `Proposed:` and open to
revision.

**Revised 2026-10-21 for two developer rulings.** Both reshape the plan, and the sections below have been
updated to match:
- **D-1:** anthro creators are Aliens, Humans, and/or Robots, including collaborations. Origin is therefore
  per **creator lineage**, not per species.
- **D-2:** locations are known only in the vaguest terms, so L4 is deferred and environments are `[hazy]`
  archetypes.

**Scope:** every conscious, sentient, *biological*, non-human race in the Tepenian Multiverse. The current
roster comes from `README.md`: dog-, cat-, and rabbit-people (anthros), elves, orcs, and aliens.
More are expected. Robots are out of scope because they already have their floor in
`TepenianUniverseTimeline/Reference/Robot_Universals/`.

---

## 1. Where this plan comes from

Four pieces of prior art. This plan reuses all four and does not replace any of them.

| Code | Name | Location | What it gives us |
|---|---|---|---|
| ULM | Universal Location Methodology | `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Universal_Location_Methodology/` | The per-location derivation engine: 8 generators, spine, Phases 0–10, QA gates, Review Panel |
| CST | Cultural Synthesis Techniques | `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Cultural_Synthesis_Techniques.md` | About 18 question-shaped techniques run on a finished pass, plus Composition Merge (R1–R7) |
| RWBEM | Real-World Basis Extrapolation Method | `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Real-World_Basis_Extrapolation_Method.md` | Research named real places, then ask "does this location produce its own version?" |
| HUF | Human Universals Culture Framework | `InnerTepeniaGDD/Neo-Races-and-Cultures/_Method/Human_Universals_Culture_Framework.md`, polished as `TepenianUniverseTimeline/Reference/Robot_Universals/` | Brown's *Human Universals* turned into a divergence procedure: essence vs. accident, then Direct Transfer / Structural Analog / Non-Transfer / New Universal, then the Differentiation Engine |

**Existing hooks for non-human populations:**
- **ULM Phase Spine, Mechanic 9** (`03_The_Phase_Spine.md`): "Where the setting has a non-human population,
  its physiology is a standing input to every phase."
  - Read the general physiology document early and in full.
  - Never infer physiology from the word for it.
  - State the population's ordinary condition before any environmental claim.
- **ULM Phase 9:** applies to "whatever population categories the setting actually contains."
- **ULM Layering Law:** method files `01`–`05` must work in any universe. Project data lives only in the runbook's §C.

**What was never tested:** the ULM was tested against a different *body* (robots). It was never tested
against a different *biology*: senses, reproduction, lifespan, social instinct. That gap is what this plan
closes.

**Canon anchor:** `TepenianUniverseTimeline/Reference/Doll_Representation_Categories.md`.
- **Anthros:** spliced human and animal DNA into hybrids, which later became full races through natural
  reproduction. The canon file says "by humans." **D-1 supersedes that:** creators are Aliens, Humans,
  and/or Robots, including collaborations. The canon file itself is unedited (Q-18).
- **Elves:** engineered by aliens on a parallel Earth.
- **Aliens:** origin unknown.
- **Orcs:** not in the file (see Q-1).

---

## 2. Standing rules

**Adopted into `CLAUDE.md` (D-3).** That file is the single authoritative copy; this plan no longer
repeats the rules. The rules most relevant to the method:
- derive, don't invent;
- never infer physiology from the word;
- condition, never essentialism (creator type included);
- no forced fit;
- LAW 0 and LAW 0-R;
- hazy locations only (D-2);
- parameterize, don't fork.

---

## 3. The core architecture: five layers per race

Inner Tepenia's own lesson applies here: "**Composition names the stock; time and place produce the
culture.**" For a biological race this splits into five layers. Each layer is built only from the layers
above it.

```
L0  ORIGIN FRAME           PER CREATOR LINEAGE (D-1): creator set (A / H / R / combinations), when,
        │                  where [hazy], why, from what; canon/timeline placement
        │                  (mostly developer decisions — this repo asks, it doesn't decide)
        ▼
L1  PHYSIOLOGY & LIFE      SPECIES BASELINE + LINEAGE DELTAS: body plan, senses, diet, activity cycle,
    HISTORY                reproduction, maturation, lifespan, communication, cognition, social instinct
        │                  ← the "general physiology document" Mechanic 9 requires
        ▼
L2  SPECIES UNIVERSALS     the floor: what is true of every population of this race, derived from
        │                  Brown via the expanded classification (§5, M-3)
        ▼
L3  INHERITED STOCK +      PER LINEAGE: the culture the lineage STARTED with (its creators' culture,
    DIVERGENCE             lived in a non-human body) and the mechanism/pace of divergence over time
        │                  ← species-level parameters for the divergence operator
        ▼
L4  POPULATIONS            DEFERRED (D-2). Specific peoples in specific places — ULM passes with L1 as
                           a standing input, then CST + RWBEM/EBEM corpus-wide — once worlds exist
```

**The creator lineage (D-1).** A **creator lineage** (`CL-`) is one engineering program by one creator set.
- **The seven creator sets** are A, H, R, A+H, A+R, H+R, and A+H+R. "Mostly" leaves room for other origins
  (Q-16).
- **How lineages map to species is open** (Q-14). A species might have a single lineage, or several
  independent ones. Where it has several, whether they interbreed (Q-15) decides whether L1 is one baseline
  with lineage deltas or effectively separate peoples sharing an animal base.
- **Creator type is a condition, never an essence** (`CLAUDE.md` rule 3). It acts only through two channels:
  - the lineage's **design charter** (M-4), which feeds L1;
  - its **inherited stock**, which feeds L3.

**Why L3 matters.** These races don't begin culture-less. Each lineage's culture on day one is its creators'
culture, lived in a non-human body.
- **H-lineages** inherit human culture, possibly from the Inner Tepenia city lineage (§10).
- **R-lineages** inherit the robot meta-culture. `Robot_Universals` is that stock's floor. This would be the
  first time the robots' "absence of genetic relatedness" (Robot Universals ch. 8) meets a biological
  offspring population. That is a real seam to examine, not to assume.
- **A-lineages** inherit an alien culture, which is not yet developed (Q-6). The stock is unknown and stays
  explicitly unknown until it is developed.
- **Collaborations** inherit a composite stock. CST Composition Merge (R1–R7) is the existing tool for
  composites, extended by M-6.
- **The mechanism has two stages.** *(Corrected 2026-10-21 per `HAR_ULM.md` HAR-ULM-49. The first draft
  cited §C.9b as the precedent for all of L3, but §C.9b is a robot-only ruling.)*
  - **First generation: mediated.** The founders weren't born to their creators. They took in the creators'
    culture through immersion or through a managed facility. This is where the robot precedent applies:
    the ULM's §C.9b "inheritance is mediated, not personal," and DR-11's culture-by-immersion model. Whether
    the founders were raised *inside* their creators' society or apart from it is a key L0 question.
  - **Later generations: personal.** Once the race bears and raises its own young, culture also passes down
    through families. §C.9b's ruling *reverses* here. How the two channels combine (family transmission,
    plus whatever creator-society contact continues) is set by the race's enculturation mode, a proposed new
    parameter.
- **So L3 asks:** *which parts of the inherited stock does this body keep, bend, or drop, and how fast?*
- **Elves** likely have the same structure, with alien creators as the mediating culture (Q-5).

**Two levels of "race."** In Inner Tepenia, "neo-race" means human ethnogenesis: new peoples forming
in new places, like Québécois or Taiwanese. Here there are two distinct levels.
- **Species** (rabbit-people): set by L1 and L2. It is biological.
- **Peoples within a species** (the rabbit-people of one Proxima settlement versus another): set by L3 and L4.
  This is ethnogenesis, and the existing Neo-Races Iceberg method applies here almost unchanged.

**What lives where.**
- **Robot Universals precedent:** the floor and the method go in a shared reference, and each specific
  population's culture goes in its own game's repo.
- **Proposed:** L0–L3 and all method files live here. L4 population catalogs live here while their games have
  no GDD, then move or get mirrored once a game repo exists. Confirm this under Q-7. (Under D-2, L4 is
  deferred anyway.)

---

## 4. Adapting the existing methods (ULM, CST, RWBEM, HUF)

**Approach: parameterize, don't fork.** The originals are universe-agnostic by design under the Layering Law,
and Inner Tepenia is still revising them. A forked copy here would drift. This repo instead holds:

### M-0 · Human-Assumptions Register (`methods/adapters/Human_Assumptions_Register.md`)

**What it is:** a line-cited list of every place the four methods assume human biology. The first sweep is
already done (2026-10-21 research). Each entry records:
- source file and line;
- the assumption;
- which layer (L1–L3) supplies the replacement;
- which adapter or parameter handles it.

**Starting entries:**

| Method | Assumption | Replaced by |
|---|---|---|
| RWBEM Step B | Researches real human places only | Second research stream, EBEM (M-2) |
| RWBEM | National-stereotype / GPS rule covers human nations only | Rule 3 above (species stereotype ban) |
| CST §0b; ULM Phase 3 | Human sensory channels: seen, heard, felt, and so on | Per-race sensory channel list (P-4) |
| CST Technique 1 | "How far an arm reaches" | Per-race reach and perception range (P-4) |
| CST Composition Merge R4 | Stock-distance axes (diet, kinship, script, calendar, funerary, prohibition, climate) | Add biological axes (M-6) |
| CST Composition Merge R5 | Thresholds (<2% trace, 5–10% institution) calibrated on human minority sociology | Re-justify per race, or mark as human-only |
| ULM `01` scale bands | ~30 / ~500 / ~50k, "below thirty everything is witnessed" (human group sizes) | Per-race social-cognition bands (P-3) |
| ULM Phase 2 | "Born here" arrival mode | Per-race reproduction and rearing model (P-2) |
| ULM Phase 4 | "An ordinary person's day," which is diurnal | Per-race activity cycle (P-1) |
| ULM Phase 6 | Human death, mourning, and kin | Per-race mortality and kin model (P-2) |
| ULM Acts; divergence operator | "After enough generations" at human generation length | Per-race generation length (P-5) |
| ULM Review Panel (`00f`) | Archetypes are positions in a human life (Maiden, Crone, Elder; King, Warrior…) | Per-race life-stage map (P-6) |
| HUF / Brown | Facial expressions, phoneme range, snake fear, "without estrus," menopause, sweets relished… | M-3, run item by item |

### M-0a · Species Parameter Sheet (`methods/templates/Species_Parameter_Sheet_TEMPLATE.md`)

**What it is:** one sheet per race. It is the plug-in that lets the unchanged ULM, CST, and RWBEM run against that race,
much as runbook §C does for Inner Tepenia's project data. Each field cites its L1 source.

| Code | Parameter | Feeds |
|---|---|---|
| P-1 | Activity cycle (diurnal / crepuscular / nocturnal / flexible) | ULM Phase 4, CST timing techniques |
| P-2 | Reproduction and rearing (litter size, cycle type, gestation, who raises young, kin recognition) | ULM Phases 2 and 6, HUF kinship items |
| P-3 | Social-cognition scale bands (stable group size, stranger tolerance, territoriality) | ULM `01` scale bands |
| P-4 | Sensory channels and ranges, plus body reach and manipulation | CST §0b, Technique 1; ULM Phase 3 |
| P-5 | Maturation age, generation length, lifespan | Divergence operator, Acts, CST R5 timing |
| P-6 | Life-stage map (what stages exist and what marks each one) | Review Panel archetype replacement |
| P-7 | Diet class and food constraints | CST R4, ULM Phase 8 cuisine |
| P-8 | Communication channels (vocal range, body signals, scent) | Phase 8 language; future language-repo work |
| P-9 | Physical environmental tolerances (temperature, light, gravity, atmosphere) | ULM G2 / spine capability profile |

### M-0b · Adapter notes (`methods/adapters/ULM_Adapter.md`, `CST_Adapter.md`, `RWBEM_Adapter.md`)

**What they are:** short files that say *where* in each method a parameter or a new method plugs in. They are
patch notes, not rewrites. If an adapter finds a change that belongs in the original method, it goes to the
developer as a proposed Inner Tepenia ruling, not as a silent fork.

---

## 5. New methodologies to write

Each is written to the Layering Law: no race named in the method file itself, and race data lives in that race's
folder.

### M-1 · Hybrid Trait Resolution Method (HTRM)
**For:** anthros. Possibly elves, depending on Q-5.

**Problem:** a spliced species has three possible sources for every trait, and nothing tells you which
one wins.

**Procedure, per trait domain** (senses, diet, reproduction, maturation, lifespan, social instinct,
communication, thermoregulation, locomotion, cognition):
1. **Human baseline:** what human biology does, from sourced data.
2. **Animal baseline:** what the base species does, from sourced data via M-2.
3. **Creator intent:** what the engineers wanted, from M-4. If intent is unknown, it is *requested*, never
   invented (ULM input-contract rule).
4. **Resolve** to one outcome:
   - **Human-dominant**
   - **Animal-dominant**
   - **Blended** (state the mechanism)
   - **Engineered-novel** (in neither parent)
   - **Suppressed-but-latent** (designed out, but can resurface)
   - **Unresolved** (a valid result; log it as a `Q-`)
5. **Post-engineering drift:** the race then reproduced naturally for generations. Ask what selection,
   drift, or founder effects did to the engineered state. This uses P-5 to set the pace.

**Output:** the L1 Physiology & Life History document. Every trait carries its outcome tag and source chain.

### M-2 · Ethological Basis Extrapolation Method (EBEM)
**For:** any race with a real-animal base.

**What it is:** RWBEM's biological counterpart. It keeps RWBEM's step shape.
- **Step A:** pick real, *named* animal populations, not generic animals. The base itself may need a ruling
  first (see Q-4). For example, wild *Oryctolagus cuniculus* warrens in Iberia versus feral Australian
  populations, and domestic rabbits.
- **Step B:** research the concrete behavior and biology of each pick from primary ethology and biology literature,
  under LAW 0-R. Inventory behaviors, signals, social structure, life history, and senses.
- **Step C:** for each detail, ask: *does this race's resolved physiology (M-1) keep the mechanism that
  produces it?* Never ask "does the animal do this?" The answer is checked against L1.
- **Step D:** canon cross-check.
- **Step E:** write into L1 or L2.
- **Step F:** a per-race research log, which also serves as the provenance record.

**Two binding cautions:**
- **Domestication:** dogs co-evolved with humans, cats are semi-domesticated, and rabbits were domesticated
  late and as prey. Which population counts as "the animal" changes the answers a great deal.
- **Pop ethology is not a source:** for example, the dominance/"alpha wolf" model, which researchers have since
  revised.

### M-3 · Species Universals Differentiation (SUD)
**For:** every race.

**What it is:** HUF Part 2 and Robot Universals Part II, with two new outcome types. Run Brown's
universals item by item, using the Ch. 6 composite as extracted in
`Neo-Races-and-Cultures/_Method/Human_Universals_Extraction.md`.
1. **Essence vs. accident.** Use Brown's 11 explanatory modes to find the root cause of each universal.
2. **Root-cause check against L1.** Does this race have the cause, not just the surface resemblance?
3. **Classify** the universal:
   - **Direct Transfer**
   - **Structural Analog**
   - **Non-Transfer**
   - **New Universal**
   - **NEW: Animal-Inherited Universal.** A species-wide pattern rooted in the animal side, such as
     warren-structured territory, if L1 keeps the mechanism.
   - **NEW: Engineered Universal.** Installed by the creators, not by evolution or culture.
4. **Sort the survivors:**
   - **Formal/Process** items go on the species-wide floor (L2).
   - **Substantive** items are free to vary and go to the Differentiation Engine (L4).

**Watch for this reversal:** for robots, genetics, kinship, and parental investment were all **Non-Transfer**.
For anthros they come back, on different biology. Do not copy robot verdicts across.

**Output:** a "*[Race]* Universals" volume, structured like Robot Universals:
- Part I: Fundamentals
- Part II: Differentiation
- Part III: Cultural Universals
- Part IV: Applying, with worked examples

### M-4 · Creator Intent & Drift Analysis (CIDA)
**For:** anthros and elves, and any race that was *made*.

**What it is:** the designers' purpose is an input, much as the Fundamental Laws are for robots or G4 (founding)
is for a location. **It runs once per creator lineage (D-1).** A collaboration lineage has one charter, but the
charter records which creator contributed what (Q-14, and the L0 questionnaire). CIDA has two outputs:
- **Design Charter:** what the creators intended. Purpose (labor? companionship? environment-specific
  colonists? research?), what they designed in or out, the legal and social status they assigned, and
  their own culture (which feeds L3).
- **Drift Ledger:** how natural reproduction, time, separation, and the race's own goals eroded or rewrote the
  charter.

**Note:** almost every charter field is a developer decision. CIDA's first job is to *structure the
questions*, not answer them. There is an obvious thematic link to the robots' own history, made by humans
and later exiled. The method should make that comparison available for the developer to use or reject, never
assume it.

### M-5 · Xenobiology First-Principles Method (XFP)
**For:** aliens. Also orcs, if Q-1 places them outside every existing category.

**Problem:** there is no Earth animal to research, and canon says "origin unknown."

**Chain:** environment, then biochemistry, then body plan, then senses, then life history, then cognition, then sociality, then
culture floor.
- **Environment:** research the real Alpha Centauri / Proxima system (stellar type, flares, tidal locking,
  known exoplanets) under LAW 0-R. The aliens may or may not be native there (see Q-6).
- **Each link** cites real astrobiology or comparative biology where possible. Unavoidable speculation is
  labeled as speculation.
- **Output:** the same L1 document format as M-1, so M-3 runs unchanged afterward.
- **"Origin unknown"** can stay true *in-world* and still need an internal answer for consistency (see Q-6).

### M-6 · Interspecies Composition (ISC)
**For:** two jobs.
- **Collaboration lineages, usable now (D-1).** It merges the creators' cultures (for example robot + human
  stock) into one inherited stock for L3. This is CST Composition Merge applied to *creators* rather than
  settlers.
- **Mixed settlements, deferred (D-2).** Centauri probably has several races together (see Q-10).

**What it is:** it extends CST Composition Merge's R4 stock-distance axes with biological axes:
- diet class
- activity cycle
- reproduction and kin model
- lifespan ratio
- sensory mismatch (for example, scent-dominant and vision-dominant neighbors)
- body scale

**Inherited predator/prey history** (cat-people beside rabbit-people) counts *only* if both races' L1
documents keep the relevant mechanisms. Rule 2 applies with extra force here.

### M-7 · Life-History Calibration
**What it is:** a short method for filling in P-3, P-5, and P-6 from L1 data, and for showing their effects
downstream:
- how a 3-year versus a 25-year versus a 200-year generation changes divergence pace;
- the Acts timing;
- how much history one individual witnesses;
- the memory and oral-history depth of a people.

The robot precedent (`00_RUNBOOK.md` §C.9d, "For robots specifically": "a given individual spans more of the divergence") is the
starting point.

---

## 6. Per-race notes

| Race | Origin (canon) | Primary methods | Blocked on | Notes |
|---|---|---|---|---|
| Rabbit-people | Splice; creator lineages per Q-14 (D-1) | M-1, M-2, M-3, M-4, M-6 | Q-2, Q-4, Q-14 | Most distant from humans: prey species, crepuscular, induced ovulation, high fecundity, warren sociality. Every human assumption gets stress-tested |
| Dog-people | Splice; creator lineages per Q-14 (D-1) | M-1, M-2, M-3, M-4, M-6 | Q-2, Q-4, Q-14 | Long co-evolution with humans makes this the hardest base to choose (wolf vs. dog vs. specific breed groups). Their kinship and social cognition may land closest to human |
| Cat-people | Splice; creator lineages per Q-14 (D-1) | M-1, M-2, M-3, M-4, M-6 | Q-2, Q-4, Q-14 | Facultatively social carnivore. The diet class (obligate carnivore) is a strong M-6 axis |
| Shared Anthro floor | — | M-3 consolidation | Three species done | Written **after** the three species, by finding what they share. Not written first and inherited down, because that would force convergence (see the kinship over-convergence lesson, §8) |
| Elves | Engineered by aliens, parallel Earth | M-1 or M-5, M-3, M-4 | Q-5, Q-11 | Base stock unknown. "Long-lived" and similar fantasy defaults are **not** assumed (rule 2) |
| Orcs | **Not in canon** | TBD | Q-1 | Can't start until categorized |
| Aliens | Origin unknown | M-5, M-3 | Q-6 | First-principles only |

---

## 7. Phased sequence

**Progress (2026-10-21):**
- **Phase 0 (foundation):** done, apart from the developer's answers to the blocking questions.
- **Phase 1 (adapter layer):** register swept (156 entries); the adapter notes wait on Q-23.
- **Phase 2 (method drafts):** M-1 to M-7 are all at v0.1.
- **Next:** the Phase 3 pilot, once Q-4 and Q-14 are answered for the pilot species.

Each phase finishes and gets a developer review before the next one starts. This follows the Inner Tepenia
pattern: test runs on one location, then a retrospective, then rollout.

**Phase 0 — Foundation and blocking questions**
- Write the repo skeleton: `CLAUDE.md`, `DECISIONS.md`, `OPEN_QUESTIONS.md`, `CANON.md`, `RESEARCH_QUEUE.md`,
  `methodology-observations/`, `source_reference/`, `to-be-integrated/`.
- **Canon intake:** collect every existing mention of these races and their tech into `CANON.md` with
  sources:
  - `Doll_Representation_Categories.md`
  - the timeline repo's Era 4 / Centauri notes
  - Outer Tepenia 1's DNA-as-tech thread
  - Inner Tepenia's Vostok genetics program, the only in-world precedent for biological engineering
- Present the blocking questions (§9) to the developer.

**Phase 1 — Adapter layer**
- Finish M-0: a full sweep of the four methods, extending the 2026-10-21 first pass.
- Write the M-0a template and the M-0b adapter notes.

**Phase 2 — Draft the new methods**
- Draft M-1 through M-7 as method files only, with no race content.
- Draft M-5 even though aliens come last. It is the method most likely to need several rounds of revision.

**Phase 3 — Pilot one race end to end**
- **Recommended pilot: rabbit-people.** They are the furthest from human, so the pilot exercises every
  adapter and every new outcome type.
- **Alternative: dog-people,** the closest to human, which would test whether the method avoids just
  re-deriving humans.
- **Run order:**
  1. **L0 lineage questionnaire** to the developer (Q-14 and the per-lineage questions).
  2. **M-2 on the base animal.** This does not depend on creators, so it can start as soon as Q-4 is answered
     or the proposed default is accepted.
  3. **M-1**, which produces the L1 baseline plus lineage deltas.
  4. **The parameter sheet.**
  5. **M-4**, once per lineage.
  6. **M-3**, which produces the Universals volume.
  7. **The L3 inherited-stock analysis**, once per lineage, with M-6 for collaborations.
- **No L4 populations** (D-2).

**Phase 4 — Retrospective**
- Write up what broke, what produced generic output, and which outcome tags were never used, in
  `methodology-observations/`.
- Revise the methods. Send any finding that affects the original Inner Tepenia methods to the developer as a
  proposed ruling.

**Phase 5 — Remaining anthros, then the shared Anthro floor**
- Dog-people and cat-people.
- Then consolidate the shared Anthro Universals from all three.

**Phase 6 — Elves, orcs, aliens**
- Each starts once its blocking question is answered.
- Aliens may run earlier if Q-6 is answered early, since M-5 doesn't depend on the anthro work.

**Phase 7 — Populations (L4): DEFERRED (D-2)**
- Starts only once *Outer Tepenia: New Centauri* or *Elven Steel* has locations.
- Uses ULM passes with the race's L1 as the Mechanic 9 standing input and its parameter sheet as the plug-in,
  breadth-first, one location on its own terms.
- Then CST, RWBEM, and EBEM run corpus-wide afterward (DR-14 ordering).
- Then the Neo-Races Iceberg method for peoples within a species.

**Phase 8 — Interfaces and registration**
- Register accepted floors to `TepenianUniverseTimeline` (following the Robot Universals precedent).
- Add the category field the Doll intake process is missing.
- Make any Outer Tepenia 1 or 2 seeding decisions (§10).
- Hand off to the language repos (anthro vocal anatomy into phonology; see P-8).

---

## 8. Inner Tepenia lessons applied here

- **Cross-reference synthesis gives the best findings, and single-input passes give generic ones.**
  - In M-1, every trait resolution reads all three sources together, not each in turn.
- **Separate "checked and found nothing" from "never applied."**
  - The four-outcome triage (Yes / Null / N/A / Uncertain) is used in M-3 and M-0.
- **Over-convergence is the main risk.**
  - All of the first 10 robot cities' kinship findings came out as mentor/mentee. The developer ruled that the
    root was "shared ongoing life experience" and that mentorship was only one form of it.
  - The equivalent risk here is every anthro species turning into "humans with ears."
  - This is why the shared Anthro floor comes *last*, and why the pilot is the most divergent race.
- **Check canon before inventing.**
  - Missed canon (symbol pairs, glitch-coolant) forced corrections to three cities.
  - Here, Phase 0 canon intake comes before any trait.
- **Depth standard.**
  - The thin first drafts of the Neo-Races catalogs forced a re-audit of 17 cities. Here, the pilot sets
    the depth bar before rollout.
- **One race on its own terms.**
  - Do not develop rabbit-people by contrast with dog-people during a pass.
  - Differentiation is a check on the finished corpus, never a way to generate content (CLAUDE.md
    "never compare locations during a pass," extended here to races).

---

## 9. Open questions

Moved to **`OPEN_QUESTIONS.md`**, the single authoritative list. It includes the questions D-1 raised:
- Q-14 · Lineage map
- Q-15 · Cross-lineage compatibility
- Q-16 · Other origins
- Q-17 · Alien access to Earth DNA
- Q-18 · Update the categories canon
- Q-19 · Robots as makers of biological life

---

## 10. Interfaces with Outer Tepenia 1

None of these races appear in Outer Tepenia 1, but two threads touch it. **Neither moves without a
developer decision (rule 8).**
- **DNA-as-tech:** Outer Tepenia 1 has DNA-as-tech as a core *story* thread, and anthros are a product of genetic
  engineering by humans, robots, and/or aliens (D-1). Depending on Q-2, Outer Tepenia 1 (or 2) could plant the early stages of that
  capability, or deliberately not.
- **Inherited stock:** `ULM/WHY_CITIES_ARE_THE_ROOT.md` records that the cultures of the Outer Tepenia era
  derive from Inner Tepenia's 38 cities. If an H- or R-lineage's creators descend from that corpus, their L3 inherited
  stock traces back to that corpus, which isn't finished yet. L3 work for anthros may have to wait on, or stay
  provisional against, that chain. This is the same sequential dependency the factions already follow.

---

## 11. Proposed repo layout

```
Hybrid-Anthro_Culture/
  README.md                     (existing)
  MASTER_PLAN.md                (this file)
  CLAUDE.md                     standing rules (adopted, D-3)
  DECISIONS.md                  D- codes
  OPEN_QUESTIONS.md             Q- codes
  CANON.md                      C- codes — canon intake with sources
  RESEARCH_QUEUE.md             RQ- codes
  methods/
    00_Method_Index.md
    templates/                  Origin Frame (lineage questionnaire), Parameter Sheet, L1 doc
    adapters/                   M-0 register, M-0b ULM/CST/RWBEM adapters
    M-1_Hybrid_Trait_Resolution.md
    M-2_Ethological_Basis_Extrapolation.md
    M-3_Species_Universals_Differentiation.md
    M-4_Creator_Intent_and_Drift.md
    M-5_Xenobiology_First_Principles.md
    M-6_Interspecies_Composition.md
    M-7_Life_History_Calibration.md
  races/
    _Shared_Anthro/             floor consolidated after the three species
    Rabbit/                     01_Physiology_and_Life_History (baseline + lineage deltas) ·
                                02_Parameter_Sheet · 04_Universals/ · research_log/ ·
                                lineages/CL-xx_<name>/ → 00_Origin_Frame ·
                                03_Design_Charter_and_Drift · 05_Inherited_Stock   (D-1)
    Dog/  Cat/  Elf/  Orc/  Alien/
  methodology-observations/
  source_reference/
  to-be-integrated/
```
