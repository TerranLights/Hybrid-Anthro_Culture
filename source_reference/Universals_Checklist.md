# Universals Checklist (input to M-3)

**Status:** Working input, 2026-10-21. Item names derived from the developer's extraction of Brown (1991), `Neo-Races-and-Cultures/_Method/Human_Universals_Extraction.md`. Short item names and paraphrases only — no bulk reproduction of Brown's text.

**PDF audit (2026-10-21).** Every item was checked against the scanned book itself: Ch. 6 (pp. 130–141) read
page by page, plus Ch. 1–5 and 7.
- **Page references.** Each item's source cell now ends with "· p. N", Brown's printed page, with supporting
  pages in parentheses. From Ch. 1 on, PDF page = printed page + 9. The extraction's "+10" holds only for the
  front matter.
- **New items.** 36 Ch. 6 universals missing from the extraction were added as U-164 to U-199. Two Ch. 2 items
  it omitted were added as U-200 and U-201. One missing given was added as G-11.
- **Corrections.** "†A-n" marks an item where the extraction's paraphrase misstates or omits part of Brown. See
  "PDF audit corrections" below.
- **Further reading.** Ch. 1, 3, and 5, and the book's biology and animal passages, are in
  `source_reference/Brown_Supplementary_Extraction.md`.

**What the source contains:** the extraction states (HUX:18-24) that Brown's 1991 book does **not** contain the
famous bulleted "List of Human Universals." That list is a later Brown contribution, reprinted as an appendix to
Pinker's *The Blank Slate* (2002). The extraction instead paraphrases the book's Ch. 6 composite, "The Universal
People," by topic. This checklist follows the extraction:
- **U-001 to U-144:** Ch. 6, split into single items, under the extraction's own topic headings.
- **U-145 to U-159:** universals the extraction names only in its Ch. 2 and Ch. 4 notes.
- **U-160 to U-163:** items that appear in the HUF Part 1 baseline table but not in the extraction. The PDF
  audit found U-160 to U-162 in Ch. 6 itself; U-163 is not in Ch. 6.
- **U-164 to U-199:** Ch. 6 items the extraction omitted (added 2026-10-21 from PDF audit).
- **U-200 to U-201:** Ch. 2 items the extraction omitted (added 2026-10-21 from PDF audit).

The Pinker-appendix list is not covered. Brown's Ch. 1, 3, and 5 were unextracted in HUX (HUX:602-605) and are
now in `Brown_Supplementary_Extraction.md` (resolves HAR-HUF-42 once accepted).

---

## How to use

- **One row per universal.** For each race, M-3 copies the row and fills four fields:
  1. **Essence / Accident.** Use HUX:532-546. Remember that an engineered race is Brown's own
     "unnatural intervention" case only at founding (HAR-HUF-02).
  2. **Root-cause mode.** Pick one or more of Brown's 11 modes (HUX:330-371). Where the extraction states a mode,
     it is pre-filled in column 3; otherwise the column shows "—" and M-3 assigns one.
  3. **L1 check.** Does this race's L1 document keep the *cause*, not just the surface? Record Yes, Null, N/A,
     or Uncertain (master plan §8). Cite the L1 line or P-x field.
  4. **Outcome.** One of: Direct Transfer · Structural Analog · Non-Transfer · New Universal · Animal-Inherited
     Universal · Engineered Universal. Then sort survivors into Formal/Process (L2 floor) or Substantive (L4).
- **"Biology-dependent?" column:**
  - **Y** means the item is rooted in a specific human biological trait: senses, reproduction, life history,
    diet, anatomy, or emotional expression.
  - **N** means a formal or process item likely to transfer to any sentient social species. Even N items
    assume a language-capable mind and some sociality, so check P-3 and the cognitive profile (HAR-HUF-21).
  - **Partly** means the item's structure is general but its form, timing, or content depends on biology.
- **"Robot verdict" column:** shown only where the robot pass actually classified the item. Robot verdicts
  are **evidence of how the method was used, never a default for a biological race** (master plan §5 M-3;
  `HAR_HUF.md` Part B).
- **"Flag" column:** a prompt for M-2 and M-1, **not a finding**. Any animal fact in a flag is a recalled
  guess until sourced under LAW 0-R; those are marked "(verify)."
- **Citations:**
  - `HUX:<line>` → `Human_Universals_Extraction.md`
  - `HUF:<line>` → `Human_Universals_Culture_Framework.md`
  - `RTSR:<line>` → `Robot_Culture_Toolkit_Status_Reference.md`
  - `RU ch.N` → `TepenianUniverseTimeline/Reference/Robot_Universals/`
  - "Mode N" → Brown's explanatory mode N (HUX:330-371).
  - `p. N` → Brown (1991), printed page N (PDF audit). `†A-n` → entry A-n in "PDF audit corrections."
  - `BSE §N` → `Brown_Supplementary_Extraction.md`, "Implications" section N.
- **Run the Givens table first.** Brown's mode-3 givens (HUX:337-340) are the human premises many items rest
  on. Filling G-01 to G-11 for a race before the items makes most L1 checks quick.

---

## Root-cause givens (run first; not counted as items)

| Code · Given | HUX source | Parameter | Flag for non-human races |
|---|---|---|---|
| G-01 · Large-brained | HUX:338 | NEW: cognitive profile (HAR-HUF-21) | Engineered cognition may not track brain size; L1 decides |
| G-02 · Slow-maturing | HUX:338 | P-5 | Fast-maturing species compress childhood and socialization |
| G-03 · Sexually reproducing | HUX:338 | P-2 | Founding cohort may have been produced differently (HAR-HUF-38) |
| G-04 · Group-living | HUX:338-339 | P-3 | Facultatively social base (cat); solitary base |
| G-05 · Terrestrial | HUX:339 | P-9 | Burrowing; arboreal; off-world gravity |
| G-06 · Omnivorous | HUX:339 | P-7 | Obligate carnivore; strict herbivore / hindgut fermenter (verify) |
| G-07 · Moderately sexually dimorphic | HUX:339 | NEW: sex-differences profile (HAR-HUF-22) | Female-larger or monomorphic species (verify); number of sexes (aliens) |
| G-08 · Quarrelsome | HUX:339 | NEW: cognitive profile / temperament | Prey vs. predator stress reactivity |
| G-09 · Without estrus | HUX:339-340 | P-2 | Estrus species; induced ovulators. **Rabbit (2026-10-21):** an induced ovulator with **no regular estrous cycle**, so "estrus species" is wrong for rabbits (`races/Rabbit/research_log/EBEM_Log_02_Body_LifeHistory_Diet_Health.md`) |
| G-10 · Menopause (sharp female reproductive cap) | HUX:407-408 | P-6 | Many mammals lack a clear post-reproductive stage (verify per base) |
| G-11 · Mammalian (added 2026-10-21 from PDF audit) | — · p. 94 (HUX:337-340 omits it) | P-2 | Gestation and lactation underlie parental-investment items (p. 109); not a given for aliens, and for elves only pending Q-5 |

*PDF audit note on the givens:* Brown's list (p. 94) reads "large-brained, slow-maturing, sexually reproducing,
group-living, terrestrial, omnivorous, and often quarrelsome mammals with moderate sexual dimorphism and no
estrus." So G-08 is "*often* quarrelsome." Brown also calls this explanatory mode "inherently weak or limited"
because its causal chain is not traced (pp. 94, 117). A given never settles an item on its own.

---

## Items

### Language (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-001 · Phonemes (closed contrastive sound set) | HUX:40-41 · p. 131 | Universal pool (HUX:509-512) | **Y** — produced by the vocal tract, perceived by the ear | Language transfers within human phonemic limits (HUF:460-471; RTSR:39-42) | Muzzle and larynx anatomy; hearing range (P-8) |
| U-002 · Phoneme inventory bounded (~10 to ~70) | HUX:40-41 · p. 131 | — | **Y** — the bounds are a human vocal-tract figure | Same as U-001 | Re-derive the bounds from P-8; don't copy the numbers |
| U-003 · Grammar with nouns and verbs | HUX:42 · p. 132 | Mode 10, innate deep structure (HUX:456-460) | **N** — formal; assumes a language faculty | Transfers (HUF:436-440) | Confirm the language faculty in L1 cognition |
| U-004 · Possessive, with inalienable vs. alienable possession | HUX:42-43 · p. 132 | — | **N** — formal | — | — |
| U-005 · Language changes over generations | HUX:44 · p. 131 | — | **Partly** — the rate is tied to generation turnover | — | Generation length (P-5) sets the drift pace |
| U-006 · Redundant encoding (e.g., number marked twice) | HUX:45 · p. 132 | — | **N** — formal | — | — |
| U-007 · Figurative speech (metaphor, metonymy) | HUX:46 · p. 132 | Mode 10, cross-sensory transfer possibly underlying metaphor (HUX:452-455) | **Partly** — metaphor draws on the body and the senses | — | Scent-channel source domains |
| U-008 · Onomatopoeia | HUX:47 · p. 132 | — | **Partly** — limited by what can be heard and produced | — | Hearing range; producible sounds (P-8) |
| U-009 · Poetry with ~3-second lines, repetition with variation | HUX:47-48 · p. 132 (cause: p. 116) †A-1 | — | **Y** — the ~3-second figure is a human timing constant; Brown ties it to brain information processing (p. 116; A-1) | — | Breath cycle and auditory memory span differ; re-derive |
| U-010 · Translation always imperfect but possible | HUX:49-50 · p. 132 | — | **Partly** — fails where sensory vocabularies don't overlap | — | Interspecies untranslatables (smell, ultrasound) |
| U-011 · Universal semantic categories (body parts, inner states, flora, fauna, weather, tools, space, motion…) | HUX:51-53 · p. 133 | — | **Partly** — the category set is general; its contents depend on the body | — | Body-part lexicon includes tail, ears, whiskers |
| U-012 · Polysemy | HUX:54 · p. 133 | — | **N** — formal | — | — |
| U-013 · Frequent words shorter (marking) | HUX:54-55 · p. 133 (mode 6: p. 98) | Mode 6, conservation of energy (HUX:350-352) | **Partly** — rests on articulatory cost | — | Articulatory cost profile differs (P-8) |
| U-014 · Proper names | HUX:56 · p. 133 | — | **N** | — | — |
| U-015 · Pronouns with at least 3 persons and 2 numbers | HUX:56-57 · p. 133 | — | **N** | — | — |
| U-016 · Numerals (even if minimal) | HUX:57-58 · p. 133 | — | **N** | — | — |
| U-017 · Logical notions (not, and, same, equivalent, opposite, general/particular, part/whole) | HUX:58-59 · p. 134 | — | **N** | — | — |
| U-018 · Overestimating the objectivity of one's own thought, especially about out-groups | HUX:60 · p. 134 | — | **N** — cognitive bias, general | — | Interspecies out-groups (M-6) |
| U-019 · Conjectural reasoning from indirect evidence | HUX:61-62 · p. 134 | — | **N** | — | Evidence channels differ (tracking by scent) |
| U-020 · Gesture (especially hand and arm) | HUX:63 · p. 134 | — | **Y** — hand and arm anatomy | — | Ear, tail, and posture channels (P-8) |
| U-021 · Some signals sent unconsciously, received consciously (e.g., an infant's fear cry) | HUX:63-64 · p. 134 | — | **Y** — rests on vocal and emotional physiology | — | ~~Prey species may suppress young's distress calls~~ **Rabbit: CORRECTED 2026-10-21.** Rabbit pups do call, and mothers return (`races/Rabbit/research_log/EBEM_Log_01_Senses_Communication_Cognition_Social.md`) |
| U-022 · Universal facial expressions (happiness, sadness, anger, fear, surprise, disgust, contempt) | HUX:65-66 · p. 134 (Ch. 1: pp. 23–27) | Modes 9 and 10, innate component (HUX:447-451) | **Y** — facial musculature | — | Muzzle face; ear and whisker displays; verify per base |
| U-023 · Some expressions voluntarily masked or mimicked | HUX:66 · p. 134 | — | **Partly** — voluntary control varies by channel | — | Involuntary channels (piloerection, scent) can't be masked |

### Cognition and Personhood (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-024 · Self vs. others; self as subject and object | HUX:69 · p. 135 | — | **N** | Well-grounded transfer (HUF:279-283; RTSR:17-19) | — |
| U-025 · Self as partly responsible (neither wholly passive nor autonomous) | HUX:69-70 · p. 135 | — | **N** | — | — |
| U-026 · Controlled vs. uncontrolled action | HUX:71 · p. 135 | — | **N** | — | Retained instinctive reflexes may blur the line |
| U-027 · Intention understood | HUX:71 · p. 135 | — | **N** | Well-grounded transfer (HUF:279-283) | — |
| U-028 · Others have a private inner life | HUX:71-72 · p. 135 | — | **N** | — | — |
| U-029 · Normal vs. abnormal mental states | HUX:72-73 · p. 135 | — | **Partly** — "normal" is defined against the species baseline | — | Cyclical states (estrus, seasonal) count as normal |
| U-030 · Naive personality theory | HUX:74-76 · p. 135 | — | **N** | Well-grounded transfer (HUF:279-283) | — |
| U-031 · Theory of mind (intuitive) | HUX:76-77 · p. 135 | — | **N** — assumes social cognition | Well-grounded transfer (HUF:279-283; RTSR:17-19) | Confirm in the cognitive profile |
| U-032 · Kin terms mark sex and generation | HUX:78 · p. 133 (p. 93) | Mode 2, cultural reflection of physical fact (HUX:467-477) | **Y** — tracks sexual reproduction | Non-Transfer (RU ch.8) — **do not copy** | Litter-mates as a kin category; overlapping generations (P-2) |
| U-033 · Units of time (day, month, season, year) | HUX:79 · p. 133 | — | **Partly** — anchored on the sky and on body cycles | — | Non-Earth sky at Centauri; "month" has no anchor off Earth |
| U-034 · Past, present, future; time as durational | HUX:79-80 · p. 133 | — | **N** | — | — |
| U-035 · Cyclicity and rhythm of life | HUX:80 · p. 133 | — | **Partly** — set by activity and breeding cycles | — | Non-diurnal (P-1); seasonal breeding (P-2) |
| U-036 · Binary discrimination (good/bad, male/female) | HUX:81-82 · p. 134 | Mode 1, dualistic thought (HUX:331-333) | **Partly** — the male/female pole assumes two sexes | — | Number of sexes (aliens); HAR-HUF-22 |
| U-037 · Ordered continua (gradations between poles) | HUX:82-83 · p. 134 | — | **N** | — | — |

### Emotion (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-038 · Sexual attraction | HUX:86 · p. 135 | — | **Y** — reproductive physiology | New Universal shape; physical pleasure layer (RU ch.17; HUF:335-359) — **do not copy** | Estrus species: attraction cyclic vs. continuous. **Rabbit:** no regular estrous cycle; receptivity varies without one (`races/Rabbit/research_log/EBEM_Log_02_Body_LifeHistory_Diet_Health.md`) |
| U-039 · Sexual jealousy | HUX:86 · p. 135 | Mode 8, parental investment / paternity confidence (HUX:404-406) | **Y** — paternity uncertainty | Root Non-Transfer; New Universal as a trust bond (HUF:323-334; RU ch.10) — **do not copy** | Multiple-sire litters change the paternity math (verify) |
| U-040 · Childhood fear of loud noises | HUX:87 · p. 135 | — | **Y** — auditory startle | — | Hearing range; prey startle response |
| U-041 · Stranger fear peaking near the end of year one | HUX:87-89 · p. 135 | — | **Y** — keyed to the human developmental timeline | — | Timing follows P-5; socialization windows in base animals (verify) |
| U-042 · Strong caretaker attachment at the same age | HUX:88-89 · p. 135 | — | **Y** — rearing physiology | Mother-infant bond Non-Transfer (RU ch.8) — **do not copy** | Low-contact maternal care in some bases (verify); P-2 |
| U-043 · Fear of snakes, effortfully surmountable | HUX:90 · p. 135 (p. 115) †A-2 | Mode 11, innate snake-wariness feeding iconography (HUX:369) | **Y** — primate predator history | — | Base animal's own predator template (raptors? canids?); M-2 |
| U-044 · Oedipal dynamic (narrow form) | HUX:91-94 · p. 135 (Ch. 1: pp. 32–37) | Mode 10, ontogeny (Spiro; HUX:461-465) | **Y** — depends on a specific rearing configuration | — | Litter rearing and father absence may remove the trigger |
| U-045 · Envy, with symbolic means of coping | HUX:95 · p. 139 | — | **Partly** | — | — |
| U-046 · Affection expressed and recognized | HUX:96 · p. 134 | — | **Partly** — the expression channel is bodily | — | Allogrooming; scent exchange; vocal affiliative signals |

### Tool Use and Material Culture (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-047 · Toolmakers, highly tool-dependent | HUX:99-101 · p. 135 | — | **Partly** — requires manipulation | Tool and cooperation cluster transfers (HUF:411-417) | Hand and paw dexterity (P-4) |
| U-048 · Cutters (improving on teeth and hands) | HUX:102 · p. 135 | — | **Partly** — the baseline is human teeth | — | Carnassial dentition; claws change the need |
| U-049 · Pounders | HUX:102-103 · p. 135 | — | **Partly** | — | — |
| U-050 · Containers | HUX:103 · p. 135 | — | **N** | — | — |
| U-051 · Binding materials (cord, sinew, wire) | HUX:103-104 · p. 135 | — | **N** | — | — |
| U-052 · The lever | HUX:104 · p. 135 | — | **N** | — | — |
| U-053 · Weapons, including the spear | HUX:104 · p. 135 | — | **Partly** | — | Natural weapons (claws, teeth) shift the weapon's role |
| U-054 · Reusable tools in recognizable, lasting styles | HUX:105-107 · p. 135–136 | — | **N** | — | Lifespan affects how long a style outlives its maker |
| U-055 · Population-level right-handedness | HUX:108 · p. 136 (pp. 89–91) | Mode 1, symbolic right-preference (HUX:331-333) | **Y** — brain lateralization | — | Paw preference may not be population-level (verify) |
| U-056 · Fire used for cooking and comfort, though not always made | HUX:109-110 · p. 136 (p. 95) †A-3 | Mode 4, age plus utility; a universal of *accident* (HUX:341-344, HUX:535-537) | **Partly** — the utility depends on diet and thermal needs | — | Obligate-carnivore or herbivore cooking utility; fur and cold tolerance |
| U-057 · Mood-altering substances | HUX:111 · p. 136 | — | **Y** — neurochemistry | Consumption culture on robot substrate (RU ch.16; HUF:473-482) — **do not copy** | Species-specific psychoactives and toxicities (verify) |
| U-058 · Shelter from the elements | HUX:112 · p. 136 | — | **Partly** — needs set by tolerances | — | Burrow or warren building (P-9) |

### Reproduction, Family, Kinship (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-059 · Patterned birth preparation, birth, and postnatal care | HUX:115-116 · p. 136 | — | **Y** — gestation and birth | Non-Transfer: fabricated, not born (HUF:319-322) — **do not copy** | Litter birth; nest-building (P-2) |
| U-060 · Weaning, with a roughly standard duration | HUX:115-116 · p. 136 | — | **Y** — lactation | — | Duration varies widely by base (verify); P-5 |
| U-061 · Group living; the family as one key group | HUX:117-118 · p. 136 (pp. 111–112) †A-4 | Mode 8, group-living factors (HUX:425-428) | **Y** — evolved sociality | Group living transfers (HUF:411-417) — **do not copy** | Facultatively social cat base; P-3 |
| U-062 · Territoriality (locality or claimed range) | HUX:119-121 · p. 136 | — | **Partly** | — | Warren territory; scent-marked boundaries |
| U-063 · Sense of peoplehood | HUX:122-123 · p. 136 | — | **N** | Transfers via shared experience; tracks city (HUF:577-590; RU ch.13) | Species boundary may compete with locality (M-6; HAR-HUF-34) |
| U-064 · Mother and child(ren) as the family core | HUX:124-127 · p. 136 | — | **Y** — gestation and lactation | Non-Transfer (RU ch.8) — **do not copy** | Mother-infant dyad becomes mother-litter |
| U-065 · Marriage (public right of sexual access) | HUX:128-130 · p. 136 | — | **Y** — rests on the human mating system | Not classified; cf. the trust bond (RU ch.10, ch.17) | Base mating system (verify); induced ovulation |
| U-066 · Active socialization by senior kin; learning by imitation and trial | HUX:131-133 · p. 136–137 | — | **Partly** — childhood length and form | Mentor/mentee institution (RU ch.11) — **do not copy** | Short juvenile period (P-5) |
| U-067 · Toilet training | HUX:133 · p. 137 | — | **Y** — elimination behavior | — | Spontaneous latrine use in some bases may make training moot (verify) |
| U-068 · Close kin distinguished and favored | HUX:134-135 · p. 137 (pp. 105, 107) †A-5 | Mode 8, kin selection (HUX:410-418) | **Y** | Genetics axis absent; clan from shared experience (HUF:367-372) — **do not copy** | Kin recognition by scent (verify); genetics axis comes back |
| U-069 · Incest avoidance (mother-son unthinkable) | HUX:136-137 · p. 137 (Ch. 5: pp. 118–129) †A-6 | Mode 8, kin selection (HUX:416-417) | **Y** | Non-Transfer (RU ch.8) — **do not copy** | Co-reared litter-mates; Ch. 5 now extracted (`Brown_Supplementary_Extraction.md`); split avoidance vs. taboo (A-6) |
| U-070 · Sex as a topic of great interest, with contexts of silence | HUX:137-138 · p. 137 | — | **Partly** | — | Seasonal breeders: salience is cyclical |

### Social Structure, Status, and Economy (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-071 · Social differentiation by kinship, sex, and age | HUX:141 · p. 137 | — | **Y** — all three axes are biological | — | Number of sexes; life stages (P-6) |
| U-072 · Statuses beyond those; ascribed, achieved, and succession rules | HUX:141-143 · p. 137 | — | **N** | — | Engineered-vs-born cohort as an ascribed status (HAR-HUF-37) |
| U-073 · Corporate social personhood ("the government") | HUX:144-145 · p. 137 | — | **N** | — | — |
| U-074 · Unequal prestige | HUX:146 · p. 137 | — | **N** | — | — |
| U-075 · Economic inequality | HUX:146-147 · p. 137 | — | **N** | — | — |
| U-076 · Division of labor by sex and age | HUX:148 · p. 137 | — | **Y** | — | Sex-differences profile (HAR-HUF-22) |
| U-077 · Women do more direct childcare | HUX:148-149 · p. 137 (p. 109) | Mode 8, parental investment (HUX:400-402) | **Y** | — | Paternal or alloparental care in some bases (verify) |
| U-078 · Children not expected to do adult work | HUX:149 · p. 137 | — | **Partly** — maturation speed | — | Fast-maturing species compress childhood (P-5) |
| U-079 · Sexes and ages seen as having different natures | HUX:150 · p. 137 | — | **Partly** | — | — |
| U-080 · Men more physically aggressive and lethal | HUX:151-152 · p. 137 (pp. 109–110) | Mode 8, sexual selection (HUX:395-399); proximate hormones (HUX:440-444) | **Y** | — | Dimorphism direction varies (verify); HAR-HUF-22 |
| U-081 · Men dominate the public political sphere | HUX:152-153 · p. 137 (pp. 91, 110) | — (a Ch. 4 running example, HUX:321) | **Y** | — | Dimorphism; see U-150 |
| U-082 · Cooperative labor | HUX:154 · p. 138 | — | **N** | Direct Transfer, emergent (HUF:411-434; RU ch.12) | — |
| U-083 · Reciprocal exchange, including revenge | HUX:155 · p. 138 | Mode 8, reciprocal altruism (HUX:419-424) | **Partly** — evolved psychology in humans | Transfers, emergent (RU ch.12) — **do not copy** | Social vs. solitary base (P-3) |
| U-084 · Non-reciprocal trade | HUX:155-156 · p. 138 †A-7 | — | **N** | — | — |
| U-085 · Food sharing in some contexts | HUX:156 · p. 138 | — | **Partly** — depends on how food comes packaged | — | Carnivore kill-sharing vs. grazer with no shareable packet (P-7) |
| U-086 · Planning for and predicting the future | HUX:157 · p. 138 | — | **N** | — | — |
| U-087 · Triangular awareness (others' relationships to each other) | HUX:158-159 · p. 138 (p. 111) | Mode 9, interspecific comparison (chimpanzees; HUX:359-360) | **N** — but also found in some animals | — | May be retained from a social base |

### Governance, Law, Conflict (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-088 · Government (regulated public affairs, binding decisions, corporate statuses) | HUX:162-163 · p. 138 | — | **N** | Transfers (HUF:411-417; RTSR:20-22) | — |
| U-089 · Leaders, even if situational | HUX:164 · p. 138 | — | **N** | — | — |
| U-090 · Generosity admired in leaders | HUX:164-165 · p. 138 | — | **N** | — | — |
| U-091 · No leader holds unchecked power (de facto oligarchy) | HUX:165-166 · p. 138 | — | **N** | — | Engineered Universal risk: designed deference to creators (M-4) |
| U-092 · Law: rights and obligations attached to persons or statuses | HUX:167-168 · p. 138 | — | **N** | Transfers (HUF:411-417) | — |
| U-093 · Murder and rape proscribed (with in-group-sanctioned exceptions) | HUX:168-170 · p. 138 | — | **Partly** — depends on mating system and receptivity | — | Handle through P-2 with care |
| U-094 · Sanctions: expulsion, incarceration, ostracism, execution | HUX:170 · p. 138 | — | **N** | — | How severe ostracism is depends on sociality (P-3) |
| U-095 · Conflict is familiar, with customary resolution and mediation | HUX:171-172 · p. 138 | — | **N** | — | — |
| U-096 · Violence never fully eliminated | HUX:172-173 · p. 138 | — ("quarrelsome" given, HUX:339) | **Partly** | — | Temperament baseline (G-08) |
| U-097 · Conflict structured by in-group vs. out-group | HUX:174-175 · p. 138–139 | — | **Partly** | — | Species as an out-group line (M-6) |
| U-098 · Ethical dualism (different standards for insiders and outsiders) | HUX:175-176 · p. 139 | — | **N** | — | Interspecies application (M-6) |

### Morality (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-099 · Right vs. wrong | HUX:179 · p. 139 | — | **N** | Emergent transfer (RU ch.12) | Engineered Universal risk (M-4) |
| U-100 · Responsibility and intentionality recognized morally | HUX:179-180 · p. 139 | — | **N** | — | — |
| U-101 · Promises | HUX:180 · p. 139 | — | **N** | — | — |
| U-102 · Reciprocity as a moral principle | HUX:180 · p. 139 (pp. 107–108) | Mode 8, reciprocal altruism (HUX:421-424) | **Partly** | Emergent transfer (RU ch.12) — **do not copy** | Social vs. solitary base |
| U-103 · Empathy (a thread across communication, morality, personhood) | HUX:181-183 · p. 135, 139, 141 †A-17 | — | **Partly** — depends on readable signals | — | Cross-species signal legibility (M-6) |

### Etiquette, Ritual, Belief (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-104 · Etiquette and hospitality ideals | HUX:186 · p. 139 | — | **N** | — | — |
| U-105 · Customary greetings | HUX:186-187 · p. 139 | — | **Partly** — the greeting channel is bodily | — | Scent channel (sniff greetings) |
| U-106 · Customs for visiting kin and others | HUX:187 · p. 139 | — | **N** | — | — |
| U-107 · Standard meal times and occasions (cf. feasts, HUF:111) | HUX:187 · p. 139 | — | **Y** — feeding pattern | — | Grazing or caecotrophy patterns (verify); P-7 |
| U-108 · Normal daily routines | HUX:188 · p. 139 | — | **N** | — | — |
| U-109 · Diurnal (day-active) | HUX:188 · p. 139 | — | **Y** — circadian biology | — | Non-diurnal: crepuscular or nocturnal (P-1) |
| U-110 · Sexual modesty standards | HUX:189 · p. 139 | — | **Partly** | — | Visible estrus signals |
| U-111 · Public copulation avoided | HUX:189-190 · p. 139 | — | **Partly** | — | — |
| U-112 · Public defecation avoided | HUX:190 · p. 139 | — | **Y** — elimination behavior | — | Scent-marking with waste reverses the privacy logic (verify) |
| U-113 · Food taboos | HUX:191 · p. 139 | — | **Partly** — content is set by diet | — | Diet class (P-7) |
| U-114 · Tabooed utterances | HUX:191 · p. 139 | — | **N** | — | — |
| U-115 · Sweets relished | HUX:191-192 · p. 139 (p. 111) | — | **Y** — taste receptors | — | Carnivore palate: sweet taste may be absent (verify for cats) |
| U-116 · Religious and supernatural belief | HUX:193-194 · p. 139 (pp. 99, 114–115) | Mode 7, cognitive imperative (HUX:353-356); Mode 11, partial explanations (HUX:366-371) | **Partly** — brain-based drive plus a bundle of causes | New Universal; no innate drive (HUF:299-311; RU ch.7, ch.15) — **do not copy** | The cognitive imperative may Direct Transfer if L1 keeps it |
| U-117 · Anthropomorphizing non-human things and forces | HUX:194-195 · p. 139 | — | **Partly** | — | The race projects *its own* form, not a human one |
| U-118 · Magic (sustaining life; attracting the opposite sex) | HUX:196-197 · p. 139 | — | **Partly** — "opposite sex" assumes two sexes | — | Number of sexes; seasonal mating |
| U-119 · Beliefs about fortune and misfortune | HUX:197-198 · p. 139 | — | **N** | — | — |
| U-120 · Beliefs about the causes of disease and death | HUX:198 · p. 139 | — | **Partly** | Disease Non-Transfer (HUF:401-409; RU ch.4) — **do not copy** | Cross-species disease in mixed settlements |
| U-121 · Medicine (attempts to heal the sick) | HUX:198-199 · p. 139 | — | **Partly** | Disease Non-Transfer (same) — **do not copy** | Prey species may hide illness (verify) |
| U-122 · Attempts to control the weather | HUX:199 · p. 139 | — | **N** | — | Off-Earth or enclosed habitats |
| U-123 · Divination | HUX:199 · p. 139 | — | **N** | — | — |
| U-124 · Ritual | HUX:200 · p. 139 | — | **N** | — | — |
| U-125 · Rites of passage | HUX:200-201 · p. 139 | — | **Partly** — the stages marked are life history | — | Life-stage map (P-6) |
| U-126 · Mourning for the dead | HUX:201 · p. 139 | — | **Partly** — mortality profile | Death as irreversible architecture loss, a structural analog (HUF:383-394; RTSR:26-30) — **do not copy** | Litter and infant loss rates; lifespan (P-5) |
| U-127 · Worldview | HUX:202-203 · p. 139 | — | **N** | — | — |
| U-128 · World perceived as unified across senses (cross-modal transfer) | HUX:203-206 · p. 139 (p. 113) | Mode 10, ontogeny (HUX:452-455) | **Partly** — the sense set differs | — | Sensory channel list (P-4) |
| U-129 · Mythology and folklore | HUX:205-206 · p. 139 | — | **N** | — | — |
| U-130 · Dreaming and dream interpretation | HUX:206 · p. 139 | — | **Y** — sleep physiology | — | Polyphasic sleep; prey vigilance (verify) |

### Property, Aesthetics, Play (Ch. 6)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-131 · Property (individual, group, others') | HUX:209-210 · p. 139–140 | — | **N** | — | Scent-marked ownership |
| U-132 · Rules for inheriting property | HUX:210 · p. 140 | — | **Partly** — heir count and timing follow life history | — | Litter size multiplies heirs; lifespan (P-2, P-5) |
| U-133 · Aesthetic standards beyond utility | HUX:211 · p. 140 | Mode 11 (HUX:366-367) | **N** | Aesthetics transfers (HUF:473-482) | Sensory filter (P-4) |
| U-134 · Personal adornment and hairstyling | HUX:212 · p. 140 | — | **Y** — the human hair and skin surface | Glow ruled not an aesthetic domain (HUF:483-490) | Full pelage: coat grooming replaces hairstyling |
| U-135 · Standards of sexual attractiveness | HUX:212-213 · p. 140 | — | **Y** | — | Signal channels (scent, coat) |
| U-136 · Preference for youth cues over post-menopausal ones | HUX:213-214 · p. 140 †A-8 | Mode 8, parental investment plus menopause (HUX:406-409) | **Y** | — | No menopause in many mammals (G-10; verify) |
| U-137 · Hygienic grooming distinct from aesthetic grooming | HUX:214 · p. 140 | — | **Y** — body surface | — | Self- and allogrooming instinct |
| U-138 · Dance | HUX:215 · p. 140 | — | **Partly** — body plan | — | Locomotor anatomy (P-4) |
| U-139 · Music (melody, rhythm, repetition, purposeful variation) | HUX:215-217 · p. 140 | Mode 11, rhythmic effects on the brain (HUX:370) | **Partly** — hearing range | Wider sound perception led to Cymatics (HUF:215-218) | Ultrasonic or infrasonic hearing (verify) |
| U-140 · Music understood as a created art | HUX:217-218 · p. 140 | — | **N** | — | — |
| U-141 · Some dance and religious activity music-accompanied | HUX:216 · p. 140 | — | **N** | — | — |
| U-142 · Vocal music, including sung poetry | HUX:218 · p. 140 | — | **Y** — vocal anatomy | — | Vocal range (P-8) |
| U-143 · Children's music | HUX:218 · p. 140 | — | **Partly** — childhood length | — | Compressed childhood (P-5) |
| U-144 · Play (fun and skill training), especially by the young | HUX:219-220 · p. 140 †A-9 | — | **Partly** | — | Predatory vs. prey play forms |

### Universals named only in the Ch. 4 and Ch. 2 extraction notes

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-145 · Male jealousy typically more violent | HUX:405-406 · p. 109 | Mode 8, parental investment | **Y** | Root Non-Transfer (RU ch.10) — **do not copy** | Sex-differences profile (HAR-HUF-22) |
| U-146 · Husband on average older than wife | HUX:409 · p. 109 n. 10 | Mode 8, parental investment | **Y** | — | Lifespan; reproductive window (P-5, G-10) |
| U-147 · Critical period for first-language acquisition | HUX:362-363, HUX:456-460 · p. 113 (pp. 77–78, 85) | Mode 10, ontogeny | **Y** | — | Maturation timeline (P-5); cognitive profile |
| U-148 · Early infant face recognition (innate component) | HUX:447-451 · p. 112 | Modes 10 and 9 | **Y** | — | Newborn vision; altricial young born blind (verify) |
| U-149 · Red linked with blood and life (experiential universal) | HUX:521-524 · p. 47 | Experiential universal | **Y** — color vision | — | Dichromatic vision (verify per base); P-4 |
| U-150 · No society is a matriarchy (negative universal) | HUX:564, HUX:589-592 · p. 50 (pp. 22–23, 91 n. 3) | — | **Partly** — tied to dimorphism | — | Dimorphism direction (HAR-HUF-22) |
| U-151 · No music made only of equal-length notes (negative universal) | HUX:564-565 · p. 50 | — | **Partly** | — | Rhythm perception (P-4) |
| U-152 · Capital punishment (near-universal, included cautiously) | HUX:227-229 · p. 140–141 †A-10 | — | **N** | — | — |

### Former universals (once universal, now not; Ch. 2)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-153 · High infant mortality | HUX:557-558 · p. 50 | Former universal | **Y** | — | Litter species: high per-offspring loss may be the baseline |
| U-154 · Near-continuous childbearing and nursing for most women | HUX:558 · p. 50 | Former universal | **Y** | Human precedent noted via artificial wombs (HUF:505-510) | Fecundity (P-2); founding production mode (HAR-HUF-38) |
| U-155 · Transport by foot only | HUX:558-559 · p. 50 | Former universal | **Partly** | — | Locomotion (P-4) |
| U-156 · Near-absence of stranger relationships | HUX:559 · p. 50 †A-11 | Former universal | **Partly** | — | Stranger tolerance (P-3) |

### New universals (became universal recently; Ch. 2)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-157 · Tobacco | HUX:548-549 · p. 50 †A-12 | New universal | **Y** — nicotine physiology | — | Species toxicity (verify) |
| U-158 · Metal tools | HUX:548-549 · p. 50 †A-12 | New universal | **N** | — | — |
| U-159 · Predicted: plastic containers, machine-made clothing | HUX:549-550 · p. 50 †A-12 | New universal (predicted) | **Partly** — clothing assumes a bare body | — | Pelage reduces clothing's function |

### Items in the HUF Part 1 table but not in the extraction

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-160 · Tone-of-voice signaling | — (HUF:114) · p. 131 †A-13 | — | **Y** — vocal anatomy | — | Vocal range (P-8) |
| U-161 · Capacity to lie or mislead | — (HUF:114) · p. 131 | — | **N** | — | Involuntary channels (scent) may limit deception |
| U-162 · Some age-grade system | — (HUF:117) · p. 133 †A-14 | — | **Y** — life history | No direct transfer; OPEN (HUF:395-400; RU ch.9) — **do not copy** | Life-stage map (P-6) |
| U-163 · Competitive or cooperative games | — (HUF:113) · not in Ch. 6 (pp. 43, 69) †A-15 | — | **N** | — | — |


### Ch. 6 items missing from the extraction (added 2026-10-21 from PDF audit)

Brown's own wording is paraphrased. Codes continue the sequence; topic order follows Ch. 6.

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-164 · Culture: learned patterns passed within and between generations (humans not unique in having it, unique in extent) | — (PDF audit 2026-10-21) · p. 130 (pp. 40, 63) | — | **Partly** — social-learning capacity is biological; its extent varies | — | Base animals may have social-learning traditions (verify); Murdock's ape "fads" (p. 63) |
| U-165 · Distinction drawn between "our way" (culture) and the way of nature | — (PDF audit 2026-10-21) · p. 130 | — | **N** | — | For engineered races, "made vs. born" may enter the nature/culture boundary (M-4) |
| U-166 · Language used for abstractions and for things not present | — (PDF audit 2026-10-21) · p. 131 | — | **N** — assumes a language faculty | — | Cognitive profile (HAR-HUF-21) |
| U-167 · Language used to manipulate others; verbal skill brings prestige (especially for a male) | — (PDF audit 2026-10-21) · p. 131 | — | **Partly** — the male skew is a sex-difference claim | — | Sex-differences profile (HAR-HUF-22) |
| U-168 · Gossip | — (PDF audit 2026-10-21) · p. 131 | — | **N** | — | Group size and stranger tolerance (P-3) |
| U-169 · Ways to be funny and ways to insult | — (PDF audit 2026-10-21) · p. 131 | — | **N** | — | — |
| U-170 · Speech symbolic: sound-meaning link arbitrary, unlike species-typical animal calls | — (PDF audit 2026-10-21) · p. 131 (p. 77 n. 12) | — | **Partly** — humans keep call-like cries of fright alongside arbitrary words | — | Retained species-typical calls (alarm, distress) may coexist with language as a second layer (P-8; verify); BSE §7 |
| U-171 · Phonemic contrasts: vocalic vs. nonvocalic, vowel contrasts, stops vs. nonstops | — (PDF audit 2026-10-21) · p. 131 | — | **Y** — vocal tract | — | Muzzle and larynx anatomy (P-8); see U-001 |
| U-172 · Marking: "good," "wide," "deep" never obligatorily expressed as negated opposites | — (PDF audit 2026-10-21) · p. 132 (pp. 78–79) | Mode 6, conservation of energy (p. 98) | **N** — formal | — | — |
| U-173 · Special speech forms for special occasions; poetic and rhetorical standards | — (PDF audit 2026-10-21) · p. 132 | — | **N** | — | — |
| U-174 · Narrative: telling stories, explaining how things came to be | — (PDF audit 2026-10-21) · p. 132 | — | **N** | — | Origin narratives meet documented creators (M-4) |
| U-175 · Words for black and white (dark/light), and for face and hand | — (PDF audit 2026-10-21) · p. 133 (Ch. 1: pp. 11–14) | Mode 2/7, uniform color perception (p. 14) | **Y** — vision; body plan | — | Color vision (P-4; verify per base); body-part salience (muzzle, paw, ear) |
| U-176 · Antonyms and synonyms | — (PDF audit 2026-10-21) · p. 133 | — | **N** | — | — |
| U-177 · Separate terms for mother and father (never obligatorily lumped) | — (PDF audit 2026-10-21) · p. 133 (p. 79) | — | **Y** — two-parent sexual reproduction | — | Number of sexes; paternal recognition (P-2) |
| U-178 · Kin terms translatable via procreative relations (mother, father, son, daughter) | — (PDF audit 2026-10-21) · p. 133 (p. 93) | Mode 2, cultural reflection of physical fact | **Y** | — | Litter-mates; multiple-sire litters (verify); P-2 |
| U-179 · Sex terminology fundamentally dualistic, even with three or four categories | — (PDF audit 2026-10-21) · pp. 133–134 | — | **Y** — two-sex reproduction | — | Aliens with more than two sexes: UNCERTAIN until L1 (HAR-HUF-22) |
| U-180 · Naming and taxonomy fundamental to cognition | — (PDF audit 2026-10-21) · p. 134 (p. 86) | — | **N** | — | — |
| U-181 · Measuring things and distances (not necessarily in uniform units) | — (PDF audit 2026-10-21) · p. 134 | — | **N** | — | Body-based units (reach, stride) follow P-4 |
| U-182 · Smiling in greeting signals friendly intent | — (PDF audit 2026-10-21) · p. 134 (p. 26) | Modes 9/10 (p. 83) | **Y** — facial musculature | — | Muzzle face; ear and tail intention signals as ANALOG (BSE §7) |
| U-183 · Crying when unhappy or in pain | — (PDF audit 2026-10-21) · p. 134 (p. 83) | — | **Y** — tears and vocal distress | — | Prey species may suppress distress signals. **Rabbit: CORRECTED 2026-10-21 for pups**; adults unverified (`races/Rabbit/research_log/EBEM_Log_01_Senses_Communication_Cognition_Social.md`) |
| U-184 · Coy or flirting display with the eyes, recognizable everywhere | — (PDF audit 2026-10-21) · p. 134 (pp. 52, 83, 101) | Mode 9, ethology (Eibl-Eibesfeldt) | **Y** — one of the few human fixed patterns (p. 101) | — | Eye and face display anatomy (P-8) |
| U-185 · Individuals recognized by their faces (and in other ways); implicit concept of the individual | — (PDF audit 2026-10-21) · p. 135 (p. 112) | Mode 10, ontogeny (p. 112) | **Y** — recognition channel | — | Kin recognition rests on this (p. 112); scent or voice channel = ANALOG (P-4, P-8); BSE §2 |
| U-186 · Tools used to make tools | — (PDF audit 2026-10-21) · p. 135 | — | **Partly** — manipulation | — | Hand and paw dexterity (P-4) |
| U-187 · Interlaced materials | — (PDF audit 2026-10-21) · p. 135 | — | **Partly** — manipulation | — | Dexterity (P-4) |
| U-188 · Group unity maintained even when members are dispersed | — (PDF audit 2026-10-21) · p. 136 | — | **N** | — | Stranger tolerance and range (P-3) |
| U-189 · A man (or men) attached to the mother-child unit, giving the children community status and/or acting as consort | — (PDF audit 2026-10-21) · p. 136 | — | **Y** — the human pair-bond and paternal role | — | Paternal role in the base (verify); P-2; founders' rearing arrangement (BSE §10) |
| U-190 · Gift giving, reciprocal or not | — (PDF audit 2026-10-21) · p. 138 | — | **N** | — | — |
| U-191 · Coalitions (enabled by triangular awareness) | — (PDF audit 2026-10-21) · p. 138 (p. 111) | Mode 9 (chimpanzees, p. 111) | **Partly** — social cognition | — | Social vs. solitary base (P-3) |
| U-192 · Leaders go beyond the limits of the group's reason and morality | — (PDF audit 2026-10-21) · p. 138 | — | **N** | — | — |
| U-193 · Censure or punishment of acts that threaten the group (or are alleged to) | — (PDF audit 2026-10-21) · p. 138 | — | **N** | — | — |
| U-194 · Wronged parties may seek redress | — (PDF audit 2026-10-21) · p. 138 | — | **N** | — | — |
| U-195 · Feasting occasions | — (PDF audit 2026-10-21) · p. 139 | — | **Partly** — feeding pattern | — | Diet class and feeding rhythm (P-7); see U-107 |
| U-196 · Decorative art applied to artifacts, not only to the body | — (PDF audit 2026-10-21) · p. 140 | Mode 11 (p. 116) | **N** | — | Sensory filter (P-4) |
| U-197 · Signs of good health count in sexual attractiveness | — (PDF audit 2026-10-21) · p. 140 | — | **Y** | — | Health cues via coat, scent, movement (verify) |
| U-198 · Playfighting, especially by the young | — (PDF audit 2026-10-21) · p. 140 (p. 148 n. 3) | Innate basis with conditional expression (p. 148 n. 3) | **Partly** — innate basis, facultative form | — | Predator vs. prey play forms (verify); write as a drive (BSE §4) |
| U-199 · Abortion (near-universal; Brown left it out of the composite) | — (PDF audit 2026-10-21) · pp. 140–141 | Near-universal | **Y** — pregnancy | — | Litter species; base-animal resorption (verify); P-2 |

### Ch. 2 items missing from the extraction (added 2026-10-21 from PDF audit)

| Code · Item | HUX source | Brown's explanatory mode(s) if stated | Biology-dependent? (Y / N / Partly — why) | Robot verdict (if the robot pass classified it; cite) | Flag for non-human races |
|---|---|---|---|---|---|
| U-200 · Former universal: relatively rare experiences of menstruation | — (PDF audit 2026-10-21) · p. 50 | Former universal | **Y** | — | Estrous species may not menstruate at all (verify); G-09 |
| U-201 · New-universal candidate: the domestic dog (absent from under 5% of known cultures) | — (PDF audit 2026-10-21) · pp. 44, 50 | New universal (candidate) | **Partly** — a human-animal relationship | — | For a dog-derived race this is a canon and ethics question for the developer, not an item to transfer; never infer from the word (rule 2) |

---

## PDF audit corrections

Where the extraction's paraphrase (and so the checklist row built on it) misstates or omits part of Brown.
Inner Tepenia's HUX is **not** edited; these go to the developer through `Brown_Supplementary_Extraction.md`,
"Proposed merge-back note."

| Code | Item(s) | Extraction says | Brown says (printed page) |
|---|---|---|---|
| A-1 | U-009 | The ~3-second line has no stated cause | Explained by information-processing features of the human brain (Turner and Pöppel; pp. 116, 150) |
| A-2 | U-043 | Snake fear "effortfully surmountable" | Ch. 6 says "with effort, the UP can overcome *some* of their fears," in general (p. 135); snake wariness is shared with other primates (p. 115), which adds Mode 9 |
| A-3 | U-056 | Fire-making ~40,000 years | 40,000–100,000 years; uses include illumination and purification; no counterparts "outside the hominid line" (p. 95) |
| A-4 | U-061 | Three co-equal factors for group living | Predator protection is the *primary* factor for primates, including humans (pp. 111–112) |
| A-5 | U-068 (and HAR-HUF-29) | Narrow kin range: parent-infant bond, incest avoidance, sibling defense | Incest avoidance, *male sexual jealousy*, *mother*-infant bond (p. 107) |
| A-6 | U-069 | Incest avoidance as one item | Taboo "clearly is not universal" (a statistical universal); *avoidance* "may be universal" (p. 128). Three mechanisms: prohibition, prevention, inhibition (p. 124). Proposed split: BSE §1 |
| A-7 | U-084 | "Non-reciprocal trade" | Trade defined as "nonreciprocal exchanges," meaning one kind of good or service for another (p. 138); gifts "whether reciprocally or not" are separate (now U-190) |
| A-8 | U-136 | Near-universal preference for youth cues | "A clear *male* preference" for signs of early nubility; attractiveness also includes "signs of good health" (p. 140; now U-197) |
| A-9 | U-144 | Play | "Play *and playfight*" (p. 140; now U-198) |
| A-10 | U-152 | Capital punishment "included cautiously" | Not in the composite: Brown accepted the cautious near-universal judgment (p. 141). Execution appears only among sanctions (p. 138). Abortion was treated the same way (now U-199) |
| A-11 | U-153 to U-156 | Four former universals | Brown also lists "relatively rare experiences of menstruation" (now U-200), and notes many former universals "were part of the environment in which human nature evolved" (p. 50) |
| A-12 | U-157 to U-159 | Tobacco and metal tools became universal | These are *candidates*: tobacco "a very likely candidate," "the dog and metal tools" equally likely (now U-201); phosphorus matches sit with plastic containers and machine clothing "far behind" (p. 50) |
| A-13 | U-160 | Tone of voice (HUF only) | A Ch. 6 item: shifts in tone, timing, and other speech features signal turn-taking (p. 131) |
| A-14 | U-162 | Age grades (HUF only) | A Ch. 6 item: an age terminology with age grades in a linear sequence. Brown notes that a non-linear scheme is possible (p. 133) |
| A-15 | U-163 | Games (HUF only) | Not in Ch. 6. Brown discusses games only as a reporting problem (p. 43); they are on Murdock's 1945 list (p. 69) |
| A-16 | G-08, G-11 | Givens include "quarrelsome" | "Often quarrelsome *mammals*" (p. 94); G-11 added |
| A-17 | U-103 | Empathy as a thread across categories | Also: Brown counted empathy as universal *despite* contrary ethnographic testimony (Zapotec, Kaluli), judging that testimony emically correct but not etically (p. 140) |
| A-18 | All | PDF page = printed + 10 | Printed + 10 only for the front matter and Introduction; printed + 9 from Ch. 1 (p. 9) onward |

---

## Counts

- **Total items:** 201 (U-001 to U-201).
  - 144 from the extraction's Ch. 6 paraphrase (U-001 to U-144).
  - 15 named only in the extraction's Ch. 2 and Ch. 4 notes (U-145 to U-159), of which 4 are former and 3 are
    new universals.
  - 4 from the HUF Part 1 table (U-160 to U-163). The PDF audit found that 3 of them (U-160 to U-162) are also
    Ch. 6 items.
  - 36 Ch. 6 items added from the PDF audit (U-164 to U-199).
  - 2 Ch. 2 items added from the PDF audit (U-200 to U-201): 1 former universal and 1 new-universal candidate.
  - The 11 root-cause givens (G-01 to G-11) are not counted. G-11 was added from the PDF audit.
- **Biology-dependent:**
  - **Y:** 62 (49 original + 13 added)
  - **N:** 77 (61 original + 16 added)
  - **Partly:** 62 (53 original + 9 added)
- **PDF audit:**
  - all 201 items carry a printed page reference, or are marked "not in Ch. 6";
  - 18 correction entries (A-1 to A-18) cover 21 items, plus the givens and the page offset.
- **Robot pass classified:** 37 items carry a robot verdict. 19 of those are marked **do not copy**: the robot
  verdict depended on robots lacking a biology this repo's races have. None of the added items has a robot
  verdict.
