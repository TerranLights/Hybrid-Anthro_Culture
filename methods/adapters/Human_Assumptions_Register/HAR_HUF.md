# Human-Assumptions Register — Human Universals Framework (HUF)

**Status:** Proposed, 2026-10-21 sweep. Part of M-0.

**Files swept:**
- `InnerTepeniaGDD/Neo-Races-and-Cultures/_Method/Human_Universals_Culture_Framework.md` (650 lines). Cited as
  `HUF:<line>`.
- `InnerTepeniaGDD/Neo-Races-and-Cultures/_Method/Human_Universals_Extraction.md` (605 lines). Cited as
  `HUX:<line>`.
- Consulted for robot verdicts, not swept line by line: `Robot_Culture_Toolkit_Status_Reference.md` (cited as
  `RTSR:<line>`); `TepenianUniverseTimeline/Reference/Robot_Universals/` Part II ch. 07–10 and Part IV
  ch. 18–19 (cited as `RU ch.N`), with spot checks of ch. 04, 11, 12, 13, and 16.

**Scope:** this register covers the HUF *method*: its sorting question, outcome types, robot verdicts, and the
analytic tools it borrows from Brown. The universals *content*, item by item, is in
`source_reference/Universals_Checklist.md`.

---

## Summary

HUF was built to answer one question: *what carries over from evolved humans to engineered robots that have no
biology at all?* Nearly every human-bound assumption in it follows from that two-population frame. The method
assumes that one population has all the biology and the other has none. The races in this repo break that
assumption three ways:

1. **They have biology,** so the reproduction, kinship, aging, disease, and innate-drive verdicts the robot pass
   reached (mostly Non-Transfer or New Universal) are **not** defaults here. Each must be re-run from L1.
2. **Most of them were engineered and then reproduced naturally.** Brown's own boundary example for a
   "universal of essence" is genetic engineering (HUX:532-546). Anthros and elves *are* that example, but only
   at their founding. After that, ordinary evolutionary mechanisms apply again. HUF's heuristic, "essence
   universals most likely don't transfer," does not hold for them.
3. **Their biology has more than one source:** human, base animal, creator design, and post-engineering
   drift. HUF's four outcomes have no slot for an animal-side or creator-side universal. M-3 adds these.

The sweep also found **five parameter gaps** that P-1 through P-9 don't cover:
- sex differences and dimorphism;
- cognitive profile and temperament;
- lineage or engineering program of origin;
- engineered-versus-born cohort status;
- population-level biological divergence.

**Totals:** 42 entries. 19 Blocking, 21 Adjust, 2 Cosmetic.

---

## Register

### A. The frame and the sorting question

| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| HAR-HUF-01 · Two-population frame | HUF:130, HUF:147-150 | The framework compares exactly two populations: evolved humans and engineered robots. The sorting question pairs "evolved under biological pressure" with essence and "general conditions of group living" with accident. | The split only works when one side has all the biology and the other has none. A biological race has evolved pressures of its own, and its accident-type universals can still depend on its biology. | All biological races. Worst for anthros, which have three trait sources (human, animal, creator). | M-1 (three-source resolution) feeding M-3; L1 | Blocking |
| HAR-HUF-02 · Engineering read as a permanent exemption | HUX:532-546; HUF:134-145 | Brown defines universals of essence as removable only by "unnatural intervention," and his example is genetic engineering. HUF treats robot existence as that intervention, so essence universals are expected not to transfer. | For anthros and elves, engineering was a **one-time founding event**, followed by generations of natural reproduction. Essence universals can come back through the human genome, the animal genome, or creator design, and post-engineering selection acts on all three. | Anthros, elves | M-3 (Animal-Inherited and Engineered outcomes); M-1 outcome tags; M-4 | Blocking |
| HAR-HUF-03 · Direct Transfer limited to accident-type items | HUF:176 | "Direct Transfer — an accident-type universal whose cause fully applies." | A human essence universal can transfer *directly* to an anthro if L1 resolves the underlying trait as Human-dominant. The mechanism is inherited, not substituted. Under HUF's definition this case has no outcome. | Anthros; elves if Q-5 gives them a human base | M-3: redefine Direct Transfer as "the cause is fully present in L1, whatever its essence/accident type." Consider a sub-outcome, *Direct Transfer, re-parameterized*, for the same mechanism on different numbers (for example, parental investment with litters). | Blocking |
| HAR-HUF-04 · Essence assumed to mean human-specific | HUF:152-155 | Essence universals "are the ones most likely to need a wholly different … treatment (or no equivalent at all)." | For a hybrid, the heuristic runs backward. The base animal has essence universals of its own, which HUF never asks about, and human essence universals can arrive intact through human DNA. | Anthros | M-3 Animal-Inherited Universal; M-2 (EBEM) | Blocking |
| HAR-HUF-05 · Outcome set has no animal or creator source | HUF:175-184 | Four outcomes: Direct Transfer, Structural Analog, Non-Transfer, New Universal. | "New Universal" means "no human precedent, arising from the new population's own conditions." That wrongly lumps three different things together: an animal-side pattern, a creator-installed trait, and an emergent cultural trait. | Anthros, elves | M-3 (adds Animal-Inherited Universal and Engineered Universal) | Blocking |

### B. Robot verdicts that must NOT be copied across

The master plan already warns about this reversal (§5 M-3). This section lists each robot verdict separately so
none slips through by default.

| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| HAR-HUF-06 · Parental investment "zero referent" | HUF:164-169; RU ch.8 | Parental investment theory "has zero robot-side referent, full stop." It is the method's own worked example of a Non-Transfer. | The example is written into the *method steps* (Step 2), not just the robot walkthrough, so it reads like a general rule. A biological race has differential parental investment, though litter size, gestation, lactation, and paternal care change the numbers. | All biological races | P-2; M-3 (re-run fresh) | Blocking |
| HAR-HUF-07 · Reproduction and kinship cluster Non-Transfer | HUF:313-322; RU ch.8 | Kinship terminology, incest avoidance, the mother-infant bond, sexual jealousy, and parental investment all trace to one cause, and robots lack it. | The cause (sexual reproduction plus genetic relatedness) comes back for biological races. Its *form* changes (litters, induced ovulation, scent-based kin recognition; all to verify per race under LAW 0-R). | All biological races | P-2; M-3 | Blocking |
| HAR-HUF-08 · Jealousy as trust-currency New Universal | HUF:323-334; RU ch.10 | Robot jealousy has no paternity-uncertainty root, so sex becomes "the highest available expression of trust." | Paternity uncertainty comes back. It may even be sharper in species where one litter can have more than one sire (verify per base animal). The robot answer is a robot cultural invention, not a template. | All biological races | P-2; M-3 | Blocking |
| HAR-HUF-09 · Sexuality sub-facets derived by reading the human template | HUF:335-359 | The robot pleasure layer is justified by robots' own reasoning about human evolutionary success. Sub-facet (E) puts human-on-human sex out of scope. | For a biological race, the pleasure layer is inherited or designed (M-1, M-4), not chosen by the race. It is also unknown whether (E)'s scope ruling extends to anthro-on-anthro or elf-on-elf sex. | Anthros, elves | M-4 (creator intent); scope goes to the developer as a question | Adjust |
| HAR-HUF-10 · Maker/made "holds no weight" | HUF:360-372; RU ch.11 | A robot is made by infrastructure (the Cradle), so a "who made you" parent-analog carries no weight. | Engineered races have **identifiable creators**: humans, aliens, robots, or collaborations, with legal and political standing (Q-13). Maker/made may be one of the heaviest relationships these races have. | Anthros, elves | M-4 (Design Charter); Q-13 | Blocking |
| HAR-HUF-11 · Tribalism has only two bases | HUF:367-372 | Robots have two of the three human bases of tribalism (geography and ideas/experience) and lack genetics. | Genetics comes back as a basis. In mixed settlements, *species* may become a fourth candidate basis. | All biological races | P-2 (kin recognition); M-6 | Adjust |
| HAR-HUF-12 · Mentor/mentee as the default kinship analog | HUF:360-365; RU ch.11 | Mentor/mentee is the real robot kin-like institution. | Real kin exist for biological races, so a mentor default would repeat the master plan's documented over-convergence failure (§8). | All biological races | M-3; P-2 | Adjust |
| HAR-HUF-13 · No innate drives beyond the modules | HUF:299-311; RU ch.7 | "Nothing is innate for a robot except the Personality Module and … the Language Module," so the cognitive imperative is absent and religion is a New Universal. | Biological brains carry innate drives from both parent lineages and may carry engineered ones. The cognitive imperative may Direct Transfer if L1 keeps a human-type cognitive architecture. | All biological races | L1 cognition (M-1 / M-5); new cognitive-profile parameter (HAR-HUF-21) | Blocking |
| HAR-HUF-14 · Cooperation and morality "emergent, not designed in" | HUF:424-434; RU ch.12 | Nothing about cooperation, morality, or social convention is built in. | Engineered races may have **designed-in** temperament (docility, loyalty, or deference to creators are obvious candidates; all are M-4 questions, not assumptions). They also carry *evolved* social instincts from the animal side. | Anthros, elves | M-3 Engineered Universal; M-4; P-3 | Blocking |
| HAR-HUF-15 · Cooperation cluster independent of origin | HUF:411-417 | Cooperation, reciprocity, government, and law come from general group-living pressure: "Nothing about *how* a population came into existence bears directly" on them. | Brown roots reciprocity in evolved psychology (HUX:419-424) and says group living itself needs explaining (HUX:425-428). A race from a facultatively social or solitary base may lack the evolved substrate the cluster rests on. | Cat-people; any solitary-base race; aliens | P-3; M-2; M-3 | Blocking |
| HAR-HUF-16 · Mortality as integrity; disease Non-Transfer | HUF:378-409; RU ch.4 | Death means irreversible architecture loss, and there is no disease analog. | Biological races age, sicken, and die. Mixed settlements also add *cross-species* disease, with no human-only precedent. | All biological races | P-5; L1; M-6 (cross-species disease) | Adjust |
| HAR-HUF-17 · No biological aging, age-grade OPEN | HUF:200-206, HUF:395-400; RU ch.9 | Robots don't age, so age-grades don't transfer directly. | Biological races do age, so this verdict must not be copied. The *human* child, adolescent, adult, elder shape must not be assumed either. Maturation speed, a post-reproductive stage (or none), and lifespan all vary. | All biological races | P-5; P-6; M-7 | Adjust |
| HAR-HUF-18 · Robot substrate list replaces eating | HUF:196-199 | "Any universal Brown traces to eating/hunger/thirst pressure should get re-derived from thermal/engine-power pressure." | Eating comes back, but with a different diet class (obligate carnivore, hindgut fermenter; verify per base). Respiration and atmosphere come back too. | All biological races | P-7; P-9 | Adjust |
| HAR-HUF-19 · Language independent of the organism; human phonemic limits kept | HUF:436-440, HUF:460-471; RTSR:39-42 | Language structure is "substantially independent of the specific biology." Robots keep human phonemic and vocal-tract limits. | Robots got that verdict because they were *designed* with human-style voices. Anthro muzzles, larynges, and hearing ranges differ. Phoneme inventory, prosody, and the ~3-second poetic line are biology-bound. | Anthros, aliens; elves pending Q-5 | P-8; Q-12 | Adjust |

### C. Brown's human givens, and parameter gaps

| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| HAR-HUF-20 · The mode-3 givens list | HUX:337-340 | Universals follow "more or less directly" from humans being large-brained, slow-maturing, sexually reproducing, group-living, terrestrial, omnivorous, moderately sexually dimorphic, quarrelsome, and without estrus. | Every item is a human premise, and M-3's L1 root-cause check needs a slot for each. Mapping: slow-maturing → P-5; sexual reproduction and estrus → P-2; group-living → P-3; terrestrial → P-9; omnivorous → P-7. **No slot** for large-brained, dimorphic, or quarrelsome (see 21–22). | All races | P-2, P-3, P-5, P-7, P-9, plus the new parameters in HAR-HUF-21 and 22. The checklist's Givens table (G-01…G-10) runs this per race. | Blocking |
| HAR-HUF-21 · No cognition or temperament parameter | HUF:219-229 (gel brain as the mode-7 anchor); HUX:353-356; HUX:339 ("quarrelsome") | Mode 7 ("the nature of the human organism, emphasis on the brain") needs a concrete brain description. For robots that was the gel brain. | L1 lists cognition and social instinct, but P-1 to P-9 don't. Every cognitive and emotional item in M-3 needs it: innate drives, critical periods, temperament baseline, and prey or predator stress reactivity. | All races | **NEW PARAMETER NEEDED: Cognitive profile & temperament** (innate drives, critical periods, aggression/fear baseline) | Blocking |
| HAR-HUF-22 · No sex-differences parameter | HUX:337-340, HUX:395-409; HUF:116 | Sex differences in aggression, political dominance, childcare, attractiveness, and age at marriage trace to human dimorphism and parental investment. | The size and direction of dimorphism vary by species (verify per base). For aliens, even the number of sexes is open. Many checklist items (U-076–U-081, U-145–U-146, U-150) can't be checked without it. | All races | **NEW PARAMETER NEEDED: Sex-differences & dimorphism profile** (incl. number of sexes) | Blocking |
| HAR-HUF-23 · One species, one mind | HUX:251-254 | The human mind is "fundamentally the same across all human populations," with only minor racial variation. | One species name may cover several **engineering programs** (by humans, aliens, robots, or collaborations) and several base lineages (dog breed groups, Q-4). That variation may not be minor. | Anthros, especially dog-people; any race made more than once | **NEW PARAMETER NEEDED: Lineage / engineering program of origin** (incl. intraspecies morph or breed variation); L0; Q-4 | Blocking |
| HAR-HUF-24 · Differences between peoples are cultural only | HUF:28-38; HUX:265-268 | The divergence operator's inputs are time, separation, environment, struggles, goals, and sensibilities, all of them cultural or environmental. | Brown himself says nature can explain differences between populations (HUX:265-268). With short generations and small founder populations, peoples of one species may diverge *biologically* within centuries. Rule 3 allows a mechanism-plus-condition chain, but no parameter carries it. This touches the no-stereotype law, so it needs a ruling, not a default. | Fast-breeding anthros; isolated colonies | **NEW PARAMETER NEEDED: Population-level biological divergence rate**; M-1 Step 5; M-7 | Blocking |
| HAR-HUF-25 · Acts measured in human generations | HUF:40-47 | Act 1 → Act 2 takes roughly a century and a half, which is a handful of human generations. | A fast-breeding race lives through many more generations in the same span. A long-lived race's individuals may witness both Acts personally. | All races | P-5; M-7 | Adjust |
| HAR-HUF-26 · Single ancestral environment | HUX:378-383 | Human nature was shaped in one Paleolithic environment, and today's mismatch with it is informative. | A hybrid has several ancestral environments: the human Paleolithic, the base animal's wild **and** domestication history, the creators' lab, and the post-engineering selective environment. | Anthros, elves | M-1; M-2 (domestication caution) | Adjust |
| HAR-HUF-27 · No "designed function" status | HUX:384-390, HUX:440-444 | A trait is explained by its evolved function, its side effects, or its proximate mechanism. | An engineered trait has a fourth status: **designed purpose**. It can differ from both evolved function and side effect, and it can drift. | Anthros, elves | M-4 (Design Charter and Drift Ledger); M-1 Engineered-novel | Adjust |
| HAR-HUF-28 · Phylogenetic constraint binds | HUX:434-439 | Evolutionary history limits which designs are available (e.g., primate smell). | Engineering can **bypass** this constraint at founding, and natural reproduction then brings it back going forward. The engineered state can also be partly undone over generations. | Anthros, elves | M-1 (Engineered-novel; Suppressed-but-latent; Step 5 drift) | Adjust |
| HAR-HUF-29 · Kin selection's "close kin" is the human family | HUX:410-418 | Kin-selected sentiment covers a narrow, human-shaped set. **Corrected 2026-10-21 from the PDF:** Brown's three (p. 107) are incest avoidance, *male sexual jealousy*, and the *mother*-infant bond. HUX's "parent-infant bond… sibling defense" misstates him (`Brown_Supplementary_Extraction.md`, merge-back note 3). | Same-age litter-mates and large broods change who counts as "close kin." Kin recognition may be olfactory (verify). | Litter species | P-2 | Adjust |
| HAR-HUF-30 · "In mammals, almost always the female" | HUX:400-404 | Parental investment theory as stated assumes mammalian gestation and lactation. | This holds for mammalian anthros, with different numbers. It may not hold for aliens or for an elf base stock (Q-5). | Aliens; elves pending Q-5 | P-2; the sex-differences parameter (HAR-HUF-22) | Adjust |
| HAR-HUF-31 · Experiential universals assume human senses | HUX:521-524 | "Blood is red" is a shared embodied experience that seeds symbolism. | Experiential universals pass through each race's sense organs. Color vision, smell acuity, and hearing range all differ (verify per base). | All races | P-4 | Adjust |

### D. Parts 1 and 3, and the extraction's coverage

| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| HAR-HUF-32 · Part 1 floor presumed present | HUF:96-105, HUF:107-118 | No catalog entry ever needed to establish that a population has kinship terms, food taboos, or music, "because all humans do." | That presumption is exactly what can't be made for a non-human race. Several rows in the table are also biology-bound: facial expressions, tone of voice, the ~3-second poetic line, toilet training, incest avoidance, the age-grade system, and the youth/health attractiveness preference. | All races | M-3 output: the per-race L2 floor replaces the Part 1 table. Rows feed P-2, P-4, P-6, P-8. | Blocking |
| HAR-HUF-33 · Robot differentiation axes | HUF:185-188, HUF:522-547 | The floor is "true of every robot population regardless of city, faction, build, or Gen." Part 3's axes are build, Gen/Mark, Arcanet connectivity, and the human-robot mix. | All of these are robot-only. Biological candidates include lineage or breed, engineered-versus-born cohort, sex, generation, and species mix. | All races | M-0a parameter sheet; M-4; M-6 | Adjust |
| HAR-HUF-34 · Guadalajara: the body carries no identity weight | HUF:577-590; RU ch.13, ch.19 | Peoplehood follows locality decisively, and body type carries essentially no identity weight. | This holds *within* a species. *Between* species, bodies differ in heritable, sensory-salient ways (scent, size, diet, activity cycle). Copying the ruling would decide M-6's central question before M-6 runs. | Mixed-species settlements | M-6 | Blocking |
| HAR-HUF-35 · Body type follows the local economy | HUF:608-621 | Robot builds are commissioned to fit local economic needs. | A reproducing species *inherits* body type. Any "locality shapes bodies" claim needs a selection, drift, or plasticity mechanism. Designed-to-purpose bodies apply only at the engineering event (M-4). A community-selection analog would be eugenics and must never enter as a default. | Anthros | M-1 Step 5; M-4; developer ruling | Adjust |
| HAR-HUF-36 · Personality spec limited by egalitarian law | HUF:233-246 | A fully designed mind is barred as a political safeguard, so randomization is mandatory. | That law governs robot fabrication in Tepenia. Nothing says a comparable limit applied to whoever engineered anthros or elves, or in which era. | Anthros, elves | M-4 (Design Charter); Q-13 | Adjust |
| HAR-HUF-37 · Gen/Mark cohort is never a hierarchy | HUF:265-275, HUF:562-575 | Fabrication generations are real but carry no status, by developer ruling. | Engineered races may have engineered founders versus naturally born descendants, and successive engineering programs. Whether "made" versus "born" stays non-hierarchical is an open M-4 question, and the robot ruling doesn't settle it. | Anthros, elves | **NEW PARAMETER NEEDED: Engineered-vs-born cohort status**; M-4 Drift Ledger | Adjust |
| HAR-HUF-38 · First-generation production mode | HUF:319-322, HUF:505-510 | Artificial wombs are mentioned only as a human demographic precedent. | An engineered race's founding cohort may have been produced by a different method (artificial gestation, surrogacy, cloning) than its later generations. P-2 has no slot for the founding method. | Anthros, elves | P-2 (add a founding-generation field); M-4 | Adjust |
| HAR-HUF-39 · Vernacular via a Language Module | HUF:256-264, HUF:441-459 | Language arrives partly through a module installed at build time, then follows the surrounding community. | The "follows the community" half generalizes (it is L3 culture-by-immersion). The module half is robot-only. An engineered race could have a designed language capacity, which would be an Engineered Universal to test, not assume. | Anthros, elves | L3; M-4 | Cosmetic |
| HAR-HUF-40 · Station-builder ≠ exile-origin rule | HUF:12-21 | The builder of a place is "GPS only" and must never characterize the people. | The analogy splits. For an engineered race, the creators are *both* the "builder" (who made the body) and, for anthros, the source of the inherited stock (L3). The rule's spirit, "characterize a people by who they are, not by who made them," still holds. The clean split doesn't. | Anthros, elves | Rule 3; M-4 vs. L3 boundary | Cosmetic |
| HAR-HUF-41 · Universality shown by sampling many societies | HUX:493-498, HUX:574-598 | Statistical universals and Brown's demonstration methods need many independent societies. | A new race may have one founder population or only a few. Its "universals" can't be *observed*, only *derived*, and founder culture can be mistaken for a species universal. | All new races, especially early anthros | Rule 1; M-3 (label each item *derived* vs. *observed*); M-7 | Adjust |
| HAR-HUF-42 · Incest-avoidance chapter not extracted | HUX:602-605 | Ch. 5 (Brown's full incest-avoidance treatment) and Ch. 1 and Ch. 3 are unextracted. | Incest avoidance was a Non-Transfer for robots and comes back for every biological race. The chapter with Brown's fullest argument on it is missing. | All biological races | M-3: extract Ch. 5 before running checklist item U-069 (log as an RQ) | Adjust |

**Severity tally:**
- Blocking (19): 01, 02, 03, 04, 05, 06, 07, 08, 10, 13, 14, 15, 20, 21, 22, 23, 24, 32, 34.
- Adjust (21): 09, 11, 12, 16, 17, 18, 19, 25, 26, 27, 28, 29, 30, 31, 33, 35, 36, 37, 38, 41, 42.
- Cosmetic (2): 39, 40.

---

## Generalizes cleanly

These parts of HUF and Brown's apparatus carry over to any sentient biological race with little or no change.
Some become *more* useful here than they were for robots.

- **Root-cause check, not surface resemblance** (HUF:170-174). This is the core of M-3 Step 2 and works
  unchanged.
- **Non-Transfer and "no distinct variant" as honest outcomes** (HUF:179-182, HUF:597-598; RU ch.18). These
  are already repo rule 4.
- **Condition, never essentialism** (HUF:544-547; RU ch.18). This is already repo rule 3, with the species
  wording added.
- **Formal/process vs. substantive split** (HUF:185-188; HUX:487-492). It carries over once robot axes are
  replaced (HAR-HUF-33).
- **Universal pool** (HUX:509-515; HUF:556-560). The question "same pool, a different pool, or an overlap?"
  fits biological races even better than robots. Note that pool membership itself can be biology-bound
  (phonemes).
- **Implicational and statistical universals** (HUX:499-508). "If A then B" is the natural form for
  species-conditional items, such as "if a litter species, then…."
- **Innate vs. manifest universals** (HUX:516-520). These map directly onto M-1's Suppressed-but-latent tag.
- **Obligate vs. facultative adaptations** (HUX:391-394). These are a ready-made vocabulary for retained
  animal traits that only show up under triggering conditions.
- **Clues to evolved origin** (HUX:429-433): unusual ease of learning, critical periods, emotion that runs
  against one's own ideals. These double as M-1 tests for whether an animal-side mechanism was retained.
- **Interspecific comparison, mode 9** (HUX:358-360). For anthros it becomes the *primary* mode, because the
  "nearest relative" is the base animal itself.
- **Ontogeny, mode 10** (HUX:361-365, HUX:446-465). Spiro's "remove the triggering configuration and the
  trait doesn't develop" framing is exactly how M-3 should handle rearing-dependent items.
- **Emic vs. etic** (HUX:525-531), **universals of classification vs. content** (HUX:567-572), and
  **negative universals** (HUX:563-566). These are pure method.
- **New and former universals** (HUF:492-510; HUX:547-562). "Former universal" is a ready-made label for
  human traits the creators designed out.
- **Brown's interactionism** (HUX:286-290). Explaining a trait means placing it on the nature-culture spectrum
  case by case, never by assumption. This is the stance M-1 and M-3 need.
- **Divergence-operator inputs** (HUF:28-31). They carry over as cultural inputs, with HAR-HUF-24's biological
  input added.
- **The statistical-universal nuance** (HUF:120-126). Treat the floor as "practically every population," not
  as exceptionless.

---

## Notes for the developer

1. **The robot verdicts are not neutral defaults.** Part B lists 14 robot verdicts. A drafter could pick up any
   of them by habit, because the HUF and Robot Universals texts state them confidently and in general terms.
   HAR-HUF-06 is the most dangerous: "parental investment has zero referent" sits in the *method steps*, not
   just the robot walkthrough. Proposed handling: the M-3 file opens with a "do not inherit" list that points
   here.

2. **Five proposed new parameters.** These are names only; whether to add them is your call.
   - Cognitive profile & temperament (HAR-HUF-21)
   - Sex-differences & dimorphism profile (HAR-HUF-22)
   - Lineage / engineering program of origin (HAR-HUF-23)
   - Population-level biological divergence rate (HAR-HUF-24)
   - Engineered-vs-born cohort status (HAR-HUF-37)

   If accepted, these would be P-10 to P-14. HAR-HUF-38 suggests a field inside P-2 rather than a new
   parameter.

3. **HAR-HUF-24 needs an explicit ruling.** It touches the no-stereotype law. Brown says biology *can* explain
   differences between populations, and short-generation races could really diverge biologically between
   settlements. Rule 3 allows a mechanism-plus-condition chain, but nothing yet says whether L4 peoples within
   one species may differ *heritably*, or how fast. A default either way would be a design decision made
   silently.

4. **Brief vs. canon on creators.** *(Resolved, 2026-10-21: D-1 supersedes the canon file's "by humans," and
   `MASTER_PLAN.md` §1 has been revised. The HAR-HUF-10 point below stands.)* This sweep's brief describes anthros as engineered "by aliens, humans,
   and/or robots — sometimes collaborations." The master plan's canon anchor (§1, from
   `Doll_Representation_Categories.md`) says humans spliced them. This needs reconciling under Q-2 and
   Phase 0 canon intake. If robots ever act as engineers, maker/made comes back in a form the robot pass never
   considered: robots as *creators* of a biological race (HAR-HUF-10).

5. **HAR-HUF-35 has an ethical edge.** The robot "bodies fit the local economy" logic, carried over to a
   reproducing species, becomes communities selecting bodies. It must never enter as a default. Raise it only
   if you want that theme.

6. **Coverage of the source.** The extraction holds Brown's Ch. 6 composite plus the analytic chapters (2, 4,
   7). It does **not** contain the bulleted list reprinted in Pinker's *The Blank Slate* (HUX:18-24), and
   Ch. 1, 3, and 5 are unextracted (HUX:602-605). The checklist therefore covers what the extraction holds. A
   later RQ could add the Pinker-appendix list and Ch. 5 to raise the item count and give incest avoidance
   proper grounding.

7. **Animal facts in this register are prompts, not findings.** Every base-animal claim here (litters with
   more than one sire, female-larger dimorphism, olfactory kin recognition, dichromatic vision, and so on) is
   marked "verify" for a reason. Under LAW 0-R, a recalled biological fact is a guess until M-2 sources it.
