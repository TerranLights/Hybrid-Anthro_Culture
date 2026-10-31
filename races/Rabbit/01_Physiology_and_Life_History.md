# Rabbit-People — L1 Physiology & Life History (species baseline)

**Status:** `Proposed:` draft v0.1, 2026-10-21 (`CLAUDE.md` rule 6). First pass of M-1 (Hybrid Trait Resolution),
the rabbit-people pilot. **Species baseline only.** No creator lineage exists yet (Q-14), so no Design Charter
exists (M-4 not run), and creator intent is open everywhere.
**Produced by:** M-1 Steps 1–8, using `methods/templates/L1_Physiology_TEMPLATE.md`.
**Companion files:** `Charter_Decision_Points.md` (the `CD-n` decisions this document cites) and
`methodology-observations/2026-10-21_M-1_Pilot_Rabbit.md` (what the method did and didn't handle).
**Not done in this pass:** the parameter sheet (`02_Parameter_Sheet.md`, pilot step 4). A readiness note is at the
end.

This is the race's general physiology document (ULM Phase Spine Mechanic 9). In its present state it is mostly a
map of **what real biology settles, what it rules out, and what only the developer can decide.**

---

## How to read this document

**Citation codes.** Every claim traces to one of these. Nothing is from memory.

| Code | Source |
|---|---|
| `HB-S##` | `source_reference/Human_Baseline.md` (RQ-4) |
| `Log01:S-##` | `research_log/EBEM_Log_01_Senses_Communication_Cognition_Social.md` |
| `Log02:S-##` | `research_log/EBEM_Log_02_Body_LifeHistory_Diet_Health.md` (its S-codes restart at S-01, so the log prefix is always given) |
| `Log0n #n` | a row in that log's search log |
| `PI-S##`, `PI §n` | `source_reference/Plausibility_Inputs.md` (RQ-5, RQ-6, RQ-8) |
| `C-##` · `D-#` · `Q-##` | `CANON.md` · `DECISIONS.md` · `OPEN_QUESTIONS.md` |
| `HW-#` · `HWC-#` | `HANDWAVES.md` (accepted · candidate) |
| `pHWC-#` | a **new** handwave candidate proposed by this pass (see "Proposed handwave candidates"; not registered) |
| `CD-#` | a charter decision point in `Charter_Decision_Points.md` |
| `[derived]` | this document's own arithmetic or inference from sourced values; never a source claim |

Each animal citation names the population and its management status (wild, wild-encl, wild-pen, feral, domestic,
lab, captive), as the logs record them. Under M-2's sequencing rule, domestic and lab findings are used only as
**mechanisms**, never as reasons for a race trait, until a charter names the stock (CD-5).

**Outcome tags** (M-1 Step 3): `HUMAN-DOM` · `ANIMAL-DOM` · `BLENDED` · `ENG-NOVEL` · `SUPPRESSED-LATENT` ·
`UNRESOLVED`. Two marks are added by this pass and explained in the methodology observations:
- `SHARED*`: **both** baselines have the same mechanism, so there is nothing to resolve and no default is taken.
  M-1 has no tag for this; using `HUMAN-DOM` or `ANIMAL-DOM` would misstate the chain. Counted separately.
- `ENG-NOVEL*`: in neither source, and required by **canon plus an accepted handwave** (C-7 and HW-1), not by a
  lineage Design Charter item. M-1 says `ENG-NOVEL` needs a charter item; whether species-level canon counts is a
  method question.

**Resolution is per mechanism** (M-1 Step 3). Each domain has a mechanism table; the domain-level tag is the
summary. Where biology narrows the options without picking one, the table says **"Excluded by biology"**:
combinations that real biology rules out, or that would need a bend handwave.

**Worked branch.** Several consequences depend on adult size (CD-1). Where they do, this draft states them for
**CD-1 option A (adult mass in the human range, about 50–80 kg)**, because that is the range the allometry inputs
were worked for (PI §6.3). This is a reading aid, **not a resolution**. One derived result makes it less
consequential than it looks: across 30–80 kg, the rabbit-line allometric predictions barely move (gestation about
40–64 days, maximum lifespan about 20–27 years, conception-to-maturity about 0.8–1.1 years) `[derived from the
PI §6.1 exponents and PI-S58 base values]`. **For life history, pace (CD-2) matters far more than size (CD-1).**

**Behavior-bearing domains** (D-7; M-1 guards): 7, 8, 10, 13, 14, 15, 16.

---

## Ordinary condition (summary) — PROVISIONAL

*Written last, assembled only from the domains below. Almost all of it rests on open charter decisions; the
settled part is short, and it is stated first.*

**Settled whatever the developer decides** (each item cites its domain):
- A rabbit-person belongs to a **new species built on one engineered genome**. They cannot have children with
  rabbits. They cannot have children with humans unless the developer rules for an engineered exception, which
  real biology treats as a bend (Domain 0, G-1; O-1, O-2; Q-31).
- They are **far larger than any rabbit or any lagomorph that has ever lived**, because the only sourced kind of
  language-capable brain is the human one, and a rabbit-sized body cannot carry it (1.1).
- They **think and communicate in a full language** (spoken or signed) and can take on a creator culture
  (13.1, 15.1).
- Their body grows on **one schedule**. How fast they mature, how long they live, how many children they have,
  and how helpless their newborns are move together as one package. A rabbit's breeding pace in a human-range
  body is ruled out (G-3; O-4, O-5).
- Their newborns receive maternal antibodies **before birth**, whichever placental design is chosen (10.10).
- Their dim-light (rod) vision peaks at the same wavelength as both parent species' (3.5).

**Decided by the developer's charter choices** (nothing below is fixed yet):
- whether their eyes sweep a near-panoramic horizon or fix forward, and whether their ears are large, mobile
  sound horns that also shed heat (CD-7);
- whether, under threat, the body slows the heart and freezes, with vigilance and alarm patterns from the base
  animal, and how strongly (CD-4, CD-5);
- whether their scent announces identity and rank without their choosing (CD-10);
- whether they are night- or day-clocked (CD-11);
- whether they eat as fiber-dependent grazers with ever-growing teeth or as omnivores (CD-8);
- how pregnancy, birth, nursing, and rearing work, inside the pace set by CD-2 (CD-3);
- how their hands and posture work (CD-6).

**D-7 note.** At this stage **no part of the animal side in their behavior is fixed by biology.** It lives
entirely in the choices above. D-7 requires that some of it stays; see the plausibility check.

---

## Domain 0 · Genome architecture and developmental program *(not in the template)*

**Why this section exists.** RQ-5 shows that several properties of a self-reproducing splice are **single,
genome-wide settings**: one karyotype, one imprinting map, one placental program, one developmental tempo, one
mitochondrial lineage, one immune system (PI §5.7). Each binds several domains at once, and none can be split
half-human, half-rabbit. The template has no slot for them, so they are resolved here once and cross-referenced
below instead of being re-tagged in each domain.

- **Human baseline:** 2n = 46 (PI-S01); hemochorial, hemomonochorial placenta with deep invasion (PI-S28);
  prenatal IgG through the placenta via FcRn (PI-S34); slow developmental tempo, with a segmentation clock of
  about 5–6 h against 2–3 h in mouse, set by slower biochemical reactions including protein degradation (PI-S32).
- **Animal baseline:** *O. cuniculus* 2n = 44 (PI-S02, secondary: genome-size database, lab-strain meiosis
  study); hemochorial, **hemodichorial**, labyrinthine placenta (PI-S28, PI-S29); prenatal IgG across the **yolk
  sac**, not the trophoblast (PI-S35, lab); a fast life history: gestation ~30 days, maturity in months (Log02:S-02,
  Bayreuth wild-origin field enclosure, wild-encl; Log02:S-04, introduced Australasian populations, wild).
- **Divergence:** human and rabbit split about 91 Myr ago (PI-S13); mammals lose the ability to form viable
  hybrids after about 2–4 Myr (PI-S12, numbers via citing papers).
- **Creator intent:** no charter; `[Q-14]`, `[Q-2]`. Decisions: CD-2, CD-14, CD-15, CD-17.

| # | Mechanism | Human | Rabbit | Tag | Reasoning | Binds domains |
|---|---|---|---|---|---|---|
| G-1 | Karyotype and meiotic pairing | 2n = 46 | 2n = 44 | `ENG-NOVEL*` | Canon says the race "later developed into full races via natural reproduction" (C-7). HW-1 (accepted) waves that the splice works. Real meiosis needs **sequence-compatible homologs**: asynapsis tracks the heterospecific status of a chromosome pair, not chromosome number (PI-S08), and nothing in real biology pairs across ~90 Myr (PI §5.3). So the race's karyotype is in neither source: a unified engineered karyotype (HWC-1). Its design is CD-14 | 10, 17 |
| G-2 | Imprinting map | species-specific (PI-S27) | species-specific | `ENG-NOVEL*` | Both parental genomes are required for development (PI-S25); hybrid imprinting breaks down into placental and fetal growth disorders (PI-S26); human and rodent maps already differ at single loci (PI-S27). A working splice must carry one coherent map (HWC-2) | 10, 11, 17 |
| G-3 | Developmental tempo | slow | fast | `UNRESOLVED` (CD-2) | Tempo behaves as a **genome-wide** property, not a switch (PI-S32). **Excluded by biology:** an organ-by-organ mosaic, such as a rabbit-tempo gut with a human-tempo brain (PI §5.6 [repo analysis]). One tempo must be chosen, and it then has to pass RQ-6 (HWC-4) | 1, 10, 11, 12, 15 |
| G-4 | Placental family | hemochorial | hemochorial | `SHARED*` | Both baselines are hemochorial (PI-S28). Nothing to resolve | 10, 11 |
| G-5 | Placental subtype, and the prenatal IgG route | monochorial; placental FcRn | dichorial; yolk sac | `UNRESOLVED` (CD-17) | **Excluded by biology:** an average of two programs. "A splice therefore chooses a placental program; it cannot average two" (PI §5.6, on PI-S28). Either choice still gives prenatal IgG (10.10) (HWC-3) | 10, 11 |
| G-6 | Mitochondrial lineage with matched nuclear respiratory genes | human mtDNA | rabbit mtDNA | `UNRESOLVED` (CD-17) | Human cells are rescued by chimpanzee or gorilla mtDNA but not by more distant primates' (PI-S33). **Excluded by biology:** unmatched mixing. One maternal lineage per design (HWC-5) | 17 |
| G-7 | Immune self-tolerance (one MHC and complement system across a mixed proteome) | — | — | `ENG-NOVEL*` | A body of two proteomes must tolerate both. In the closest real case, glycan knockouts alone failed and seven human transgenes were needed (PI-S23). HW-1 requires it to work (HWC-6); any residue goes to 17 | 17 |
| G-8 | Founder number and diversity | — | — | `UNRESOLVED` (CD-15) | Required for long-term reproduction, but not sourced (PI Gaps 6; HWC-8). Canon already treats drift in a closed pool as a real problem (C-54) | 17, all drift |
| G-9 | Sex determination and number of sexes | two sexes; XY males (HB-S32; PI-S07) | two sexes; mammalian XY males (PI-S07, which finds Haldane's rule in all 26 mammal species considered) | `SHARED*` | Both baselines. Feeds P-14's "number of sexes" sub-field (D-8). Under HWC-1, the heterogametic (male) sex is the one that fails first if any chromosome pairing is imperfect (PI-S07) | 10, 17 |

### Biology-forced outcomes (results, not mechanisms; not counted as tags)

| # | Outcome | Chain |
|---|---|---|
| O-1 | **No interfertility with *O. cuniculus*.** | ~91 Myr divergence against a 2–4 Myr window (PI-S12, PI-S13); asynapsis from sequence divergence (PI-S08); PI §5.7 |
| O-2 | **No interfertility with humans**, unless the developer rules for HWC-9 (bend): a lineage built on a human chromosome scaffold with sequence-compatible homologs, and even then reduced fertility, males failing first (Haldane's rule: PI-S07) | PI §5.1–5.3; Q-31 → CD-12 |
| O-3 | **Lineages built to different karyotype designs are partly or wholly isolated from each other.** Simple differences cost about half of fertility (PI-S09); complex ones give multiple pairing failures (PI-S10) | PI §5.7; HWC-12; Q-15 → CD-14 |
| O-4 | **Life history moves as one package.** Development time predicts lifespan (PI-S48); short gestation goes with altricial young and long gestation with precocial young (PI §6.4) | G-3; Domains 10–12 |
| O-5 | **A rabbit's breeding pace in a human-range body is excluded** (30-day gestation, frequent large litters, maturity in months). Mass-specific production must fall to about 0.37–0.47× the rabbit's at 65 kg (PI-S51; PI §6.3), and to about 0.35–0.56× across 30–80 kg `[derived]` | HWC-10 (recommended reject) |
| O-6 | **Lifespan above a longevity quotient of about 5 is excluded**, and long life is available only with slow maturation and low reproduction (PI-S48, PI-S54, PI-S56) | HWC-11 |
| O-7 | **Newborns receive maternal IgG before birth** under either placental program (PI-S34, PI-S35) | 10.10 |
| O-8 | **Generation zero cannot be carried by an unmodified human or rabbit mother:** xenogeneic rejection (donkey-in-horse loses 70–80%, PI-S30) and maternal size bounding fetal size (PI-S31) | HWC-7; Q-32 → CD-13 |
| O-9 | **The adult body is far beyond lagomorph scale** | 1.1 |

- **Coherence links:** every domain below; especially 10, 11, 12, 17.
- **Post-engineering drift:** founder effects run from G-8. Under HWC-1, any imperfectly paired chromosome would
  show first as male subfertility (PI-S07, PI-S08); direction only.
- **Lineage deltas:** pending Q-14. **G-1 is the delta that decides whether the others can blend:** lineages
  sharing one karyotype design can interbreed; lineages that don't, can't (O-3). G-5 and G-6 can differ by lineage
  with no effect on interbreeding that any source shows.
- **Handwaves used:** HW-1; HWC-1 to HWC-8.
- **Confidence:** Derived (G-1, G-2, G-7 requirements; O-1 to O-9); Charter (G-3, G-5, G-6, G-8).
- **Canon check:** (1) C-7 establishes the splice and natural reproduction; nothing in canon gives a karyotype or
  tempo. (2) No contradiction: O-1/O-2 are consistent with C-7, which never claims human interfertility. (3) O-2
  binds human canon (family and romance storylines; Q-31). O-3 binds every other rabbit lineage (Q-15). (4)
  Register Q-31 and Q-15 rulings in `DECISIONS.md`; the karyotype design is a per-lineage M-4 item.

---

## 1 · Body plan, scale, and locomotion

- **Ordinary condition (provisional):** *Settled:* an adult is far larger than any rabbit or any lagomorph known,
  and the body grows on one schedule (G-3). *Open:* how large (CD-1), what posture and gait, and how the legs and
  feet are built (CD-6).
- **Human baseline:** an obligate biped; an extended hip and long hindlimb make walking about 75% cheaper than in
  chimpanzees (HB-S30); preferred walking speed 1.3–1.4 m/s (HB-S31); endurance-running anatomy (narrow pelvis,
  short toes, large gluteus, large semicircular canals), its selective story contested (HB-S29). World mean adult
  mass about 62 kg, regional means 58–81 kg (HB-S28); stature strongly plastic, with cohort means moving up to
  ~20 cm with living conditions (HB-S27). Men ~7% taller and 12–25% heavier (HB-S32).
- **Animal baseline:**
  - *Size:* wild adults about 1.0–1.5 kg (Log02:S-122, a statement in a genetics paper on domestic dwarfism;
    [FT*]). In four introduced Australian populations (wild), animals over ~1,250 g had dispersed into adult
    groups and kittens under ~600 g were still on the birth warren (Log02:S-07). *O. c. algirus* is lighter, with
    shorter ears and hind feet, than *O. c. cuniculus* across 999 adults at 27 native Iberian sites (Log02:S-123,
    wild). Sexual size dimorphism: **direction unresolved** (Log02:S-123, no direction in abstract; Log02:S-127,
    introduced Neuquén population, females heavier, [SN]). The largest lagomorph ever recorded was about 8–12 kg
    (PI-S59, the fossil *Nuralagus rex*).
  - *Gait:* rabbits "almost exclusively" bound or half-bound; in six New Zealand White lab rabbits, plantar
    contact covered 70 ± 11% of a plantigrade foot, shifted toward the toes (a digitigrade gait), with peak vertical
    force 44 ± 11% of body weight (Log02:S-115, lab). Rabbits saltate more, hares run more (Log02:S-116, ~40
    *O. cuniculus* from introduced Australian populations, CT).
  - *Shape:* leporids have elongated hind shanks and feet (Log02:S-125, [SN]); across 40 lagomorph species, body
    size best predicts body shape: larger species have stouter bodies with longer, more gracile forelimbs
    (Log02:S-117, museum). Leporids have an intracranial joint, hypothesized to absorb locomotor energy
    (Log02:S-118, museum). Skeleton about 7–8% of body mass (Log02:S-126, `[LEAD]` only).
  - *Digging:* warrens and female-dug breeding "stops" (Log02:S-02, Bayreuth, wild-encl; Log02:S-120, Doñana,
    wild native); domestic does given soil still dig (Log02:S-124, domestic).
- **Creator intent:** no charter; `[Q-14]`. Scale → **CD-1**; posture, limbs, feet → **CD-6**. Related: Q-9
  (whether a real doll's form constrains the body plan; C-2).

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 1.1 | Adult scale (growth target) | ~62 kg (HB-S28) | ~1.0–1.5 kg (Log02:S-122) | `UNRESOLVED` (CD-1) | Biology sets a **floor**, not a value. The only sourced language-capable brain is human (HB-S46), at about 2% of body mass (HB-S45), which is about 1.2 kg at 62 kg `[derived]`. A rabbit-scale body cannot carry it, and 15.1 requires that capacity. A human-range body is about 36× a wild rabbit's mass and 5–8× the largest lagomorph ever recorded `[derived on PI-S59]`. Whether a smaller-than-human brain could be language-capable is unsourced (proposed RQ). **How size is reached matters too:** size reached by accelerated growth predicts the large-dog-breed aging pattern (PI-S57; HWC-14) |
| 1.2 | Posture and primary locomotor mode | obligate biped | quadrupedal bounding | `UNRESOLVED` (CD-6) | No source decides. A bounding lagomorph at human mass has no precedent (PI-S59) |
| 1.3 | Hind-limb segment proportions and foot use | long hindlimb, arched plantigrade foot (HB-S30) | long shank and foot; toe-weighted use of a plantigrade foot (Log02:S-115, S-125) | `UNRESOLVED` (CD-6) | A biped built with rabbit-derived hind-limb proportions is conceivable, but that would be a blend whose mechanism only a charter can supply |
| 1.4 | Body-shape allometry | — | larger lagomorphs: stouter body, longer forelimbs (Log02:S-117) | `UNRESOLVED` | Direction only: *if* a lagomorph-proportioned plan were scaled up, the within-order trend points to a stouter trunk and longer forelimbs. A human-range body lies far outside the sampled sizes (the largest living leporid in the inputs is a 4.2 kg hare, PI §6.3), so this is extrapolation |
| 1.5 | Skeletal mass fraction | not in HB | 7–8% (`[LEAD]`) | `UNRESOLVED` (proposed RQ) | No skeletal scaling source in the inputs; the rabbit figure is lead-level |
| 1.6 | Cranial kinesis (intracranial joint) | not in HB | present (Log02:S-118) | `UNRESOLVED` (CD-7) | Depends on the head plan; its function is a hypothesis |
| 1.7 | Sexual size dimorphism | males larger (HB-S32) | direction unresolved | `UNRESOLVED` (proposed RQ; CD-3) | The rabbit direction is open in the sources; the human mechanism (sexual selection on males, natural selection on females) is partly contested (HB-S32) |

- **Coherence links:** 2 (whether forelimbs carry locomotion); 9 (surface-to-volume; ears); 10 and 11 (maternal
  size bounds neonate size, PI-S31; multiple births through an upright pelvis are unresearched, PI Gaps 11);
  12 (HWC-14); 15 (brain floor).
- **Post-engineering drift (Step 5):** *Founder effect:* body-size alleles ride on the founders (CD-15). If a
  charter names domestic stock (CD-5), the dwarfing *HMGA2* deletion is a coordinate to check: recessive lethal in
  homozygotes, about two-thirds size in heterozygotes (Log02:S-122, domestic). *New selection `[hazy]`:* if a
  lineage lives in a reduced- or spun-gravity habitat archetype, the only data are human bone loss in microgravity
  (HB-S72), and mammalian gestation there is untested (C-56, proposed); direction unknown. Pace: per generation
  (CD-2).
- **Lineage deltas:** pending Q-14. **Charter choices that would create deltas:** CD-1 (scale), CD-6 (posture),
  CD-5 (stock: *algirus* is smaller than *cuniculus*, Log02:S-123; domestic stock spans < 1 to > 5 kg,
  Log02:S-122, S-132). If lineages of different scale interbreed (Q-15), maternal size bounds neonate size
  (PI-S31), so crosses would be asymmetric by direction `[derived]`.
- **Individual variance range:** not behavior-bearing. The base shows large heritable size variance (domestic
  < 1 to > 5 kg, Log02:S-132) and the human side strong environmental plasticity (HB-S27).
- **Handwaves used:** HW-1; HWC-4; HWC-14 (if growth is accelerated).
- **Confidence:** Derived (scale floor); Unresolved (scale value, posture, limbs).
- **Canon check:** (1) No canon gives anthro size or posture; C-2 (every character is a real doll) may constrain
  it (Q-9). C-47 (robots keep the human form by choice) bears on robot-made lineages only by implication.
  (2) No contradiction. (3) Binds the doll mapping and character intake (C-2, C-4). (4) A ruling on CD-1 or CD-6
  should be registered with Q-9.

---

## 2 · Manipulation

- **Ordinary condition (provisional):** *Open.* Whether hands grip and turn objects the way human hands do is a
  charter choice (CD-6). *Settled conditionally:* if the forearm is rabbit-type, it cannot turn palm-up
  (Log02:S-119).
- **Human baseline:** an opposable thumb with forceful precision and power grips; eight derived hand features,
  three already in *Australopithecus afarensis* (HB-S33); dense fingertip afferents in four classes that feed fast
  grip-force control (HB-S24); left-handedness ~10.6% (9.3–18.1% by definition) (HB-S34). The human value for
  forearm rotation is **not stated** in the baseline (gap).
- **Animal baseline:** in 20 domestic rabbit forearms, the radius and ulna are curved and bound along their length
  by a short interosseous ligament, with a flattened olecranon head; the forearm is "fixed in pronation" and its
  job is support and locomotion; no supination (Log02:S-119, domestic, osteology; the same source records about 80° of
  supination in another domestic mammal). Forepaws dig warrens and stops (Log02:S-02, wild-encl; Log02:S-120, wild native) and climb shrubs for
  moist leaves in drought (Log02:S-97, introduced wild, arid South Australia). **No study of rabbit grasping, food
  handling, or paw preference was found** (Log02 gap 3; Log01 #78–79). The rabbit's touch map is dominated by the
  muzzle, not the paw (Log01:S-31, lab; see 6).
- **Creator intent:** no charter; `[Q-14]` → **CD-6**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 2.1 | Forearm rotation | (not stated in HB) | locked in pronation (Log02:S-119) | `UNRESOLVED` (CD-6) | Partial rotation is anatomically possible in mammals (another species in the same source rotates ~80°), so a lock is not all-or-nothing, but any intermediate needs a charter mechanism |
| 2.2 | Thumb opposition and precision grip | HB-S33 | no data | `UNRESOLVED` (CD-6) | — |
| 2.3 | Fingertip mechanoreceptor density | HB-S24 | not sourced for forepaws | `UNRESOLVED` (CD-6) | Travels with 2.2 |
| 2.4 | Limb laterality | ~10.6% left (HB-S34) | unstudied | `UNRESOLVED` (proposed RQ) | No rabbit data (Log01 #78–79; Log02 #78) |

- **Coherence links:** 1.2 (if forelimbs carry locomotion, the pronation lock keeps its job; in a biped it has
  none); 13.2 (sign language needs hands: coherence row CM-10); 6 (touch); 10.14 (nest-building movements; the body
  part used is unsourced, Log02 #22).
- **Post-engineering drift:** no sourced mechanism; not traced.
- **Lineage deltas:** CD-6 can differ by lineage.
- **Handwaves used:** HW-1.
- **Confidence:** Unresolved.
- **Canon check:** (1) None. C-47 is an implied bearing for robot creators only. (2) No. (3) Binds tool and
  equipment design for any character (game asset level). (4) With Q-9.

---

## 3 · Senses: vision

- **Ordinary condition (provisional):** *Open* on eye placement, field of view, and color. *Settled because both
  sources agree:* dim-light (rod) vision peaks near 498 nm, and a short-wavelength ("blue") cone class exists.
- **Human baseline:** trichromat, cones near 420, 530–534, and 560–564 nm (HB-S06); fovea ~199,000 cones/mm²
  (HB-S01); field about 200° horizontal with ~120° binocular overlap (HB-S02; HB-S03, secondary); 20/20 is the
  *lower* normal limit (HB-S04); rods peak ~498 nm, dark adaptation slow (HB-S09); X-linked red-green deficiency up
  to ~8% of males in some samples (HB-S07); myopia is environment-driven (HB-S10). A diurnal, fovea-dominant visual
  system.
- **Animal baseline** (almost all from albino New Zealand White lab rabbits; pigmented wild retinas not found,
  Log01 gap 3):
  - two cone classes near 425 and 523 nm, rods near 498 nm (Log01:S-01, [SN]; Log01:S-03, lab; Log01:S-09, lab);
  - a horizontal **visual streak** with cone density peaking near 18,000/mm² (Log01:S-03, lab); the superior
    colliculus magnifies the band 15° above and below the horizon (Log01:S-04, domestic, n = 7, [FT]);
  - short-wavelength cones concentrated in a far-ventral band (Log01:S-03);
  - laterally directed eyes and a near-360° field (Log01:S-06, `[LEAD]`), with a narrow frontal binocular strip;
    overlap degrees unresolved (Log01:S-04, S-07);
  - acuity unresolved; no tapetum (Log01:S-06, `[LEAD]`); rod-rich retina, rods peaking near 300,000/mm²
    (Log02:S-108, lab);
  - eyelids open on postnatal days 10–12 (Log01:S-10, lab).
- **Creator intent:** no charter → **CD-7** (head and senses), **CD-11** (clock).

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 3.1 | Orbit orientation and field geometry | frontal; ~120° binocular | lateral; near-panoramic | `UNRESOLVED` (CD-7) | No source decides |
| 3.2 | Retinal topography and collicular map | fovea | horizon streak plus collicular horizon magnification | `UNRESOLVED` (CD-7) | In the base, streak and lateral geometry come together; no source shows them separated |
| 3.3 | Middle/long-wave cone opsins (color dimensionality) | trichromat | dichromat | `UNRESOLVED` (CD-7) | If human opsin genes are used, their X-linked variation comes with them (HB-S07) `[derived]` |
| 3.4 | Short-wave cone class | ~420 nm | ~425 nm | `SHARED*` | Both present (HB-S06; Log01:S-01). Its retinal *distribution* follows 3.2 |
| 3.5 | Rod photopigment | ~498 nm | ~498 nm | `SHARED*` | Same peak (HB-S09; Log01:S-01) |
| 3.6 | Rod-to-cone weighting (dim-light design) | diurnal, fovea-dominant | rod-rich (Log02:S-108) | `UNRESOLVED` (CD-11) | Must agree with the activity cycle (coherence row CM-2) |
| 3.7 | Timing of eye opening | — | postnatal days 10–12 | `UNRESOLVED` (CD-2, CD-3) | Follows the neonatal state (11.2) |

- **Coherence links:** 4 (across species, sound-localization acuity falls as the field of best vision widens,
  because hearing's job is to point the eyes; Log01:S-12, domestic, [AB]); 8 (rod-rich retina ↔ dim-light
  activity; Log02:S-108); 15.2 (horizon scanning versus fixation).
- **Post-engineering drift `[hazy]`:** if a lineage lives under a different star's light, spectral tuning could
  come under selection; vision under red-dwarf light is a logged research gap (RQ-10). Direction unknown.
- **Lineage deltas:** CD-7 per lineage. Visible, so legible to the audience.
- **Handwaves used:** HW-1.
- **Confidence:** Sourced (3.4, 3.5); Unresolved (the rest).
- **Canon check:** (1) None. (2) No. (3) No. (4) No.

---

## 4 · Senses: hearing

- **Ordinary condition (provisional):** *Settled:* either ear can hear the speech band, so spoken language is not
  blocked by the hearing choice. *Open:* how high they hear, how big and mobile the outer ears are, and how
  precisely they localize sound (CD-7).
- **Human baseline:** about 20 Hz–20 kHz in young listeners, often 15–17 kHz in adults (HB-S11); most sensitive
  near 2–5 kHz from ear-canal resonance (HB-S13, secondary); extended-high-frequency loss with age (HB-S12). Human
  localization thresholds are not given in the baseline (gap).
- **Animal baseline:** upper limit 49 kHz at 60 dB (Log01:S-11, domestic, behavioral audiogram); lower limit about
  96 Hz only from a secondary table, unverified (Log01:S-11, [SN]). Left/right localization about 22°; ITD
  threshold 50–60 µs (Log01:S-13, lab). The pinna is the main spectral and high-frequency directional filter: gain
  peak at 2.6 kHz (+12–23 dB), notch at 7.6 kHz, interaural level differences up to ±31 dB; removing the pinnae
  removed the spectral cues (Log01:S-14, lab, n = 9). Orienting with head and pinna from about postnatal day 10
  (Log01:S-16, lab). Pinna mobility range and musculature: **not found** (Log01 gap 4). In an owner survey, lop-eared
  pet rabbits had more ear disease (~25% vs ~10%) (Log01:S-17, domestic, owner-reported).
- **Creator intent:** no charter → **CD-7**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 4.1 | Cochlear upper frequency limit | ~20 kHz | 49 kHz | `UNRESOLVED` (CD-7) | — |
| 4.2 | Audibility of the speech band | yes | yes | `SHARED*` | The human speech-sensitive band (2–5 kHz, HB-S13) lies inside the rabbit's audible range (Log01:S-11), near the rabbit pinna's gain peak (Log01:S-14) `[derived]`. Relative sensitivity is unsourced |
| 4.3 | Outer ear as acoustic horn and directional filter | human pinna | large pinna | `UNRESOLVED` (CD-7) | If large pinnae are chosen, the filtering follows from their physics (Log01:S-14) |
| 4.4 | Localization acuity | (not in HB) | coarse, ~22° | `UNRESOLVED` | Must agree with vision (Log01:S-12; coherence row CM-11) |
| 4.5 | Pinna mobility | — | unsourced | `UNRESOLVED` (proposed RQ; CD-7) | Ear posture as a signal (13, 14) depends on it |

- **Coherence links:** 3; 9 (the same ear is a heat radiator, Log02:S-110 to S-112); 13 and 14 (ear posture);
  17 (if domestic lop alleles came with the stock, ear disease follows: Log01:S-17; Log02:S-62, domestic;
  coordinate until CD-5).
- **Post-engineering drift:** none sourced beyond stock alleles.
- **Lineage deltas:** CD-7; CD-5 (lop conformation exists only in domestic stock).
- **Handwaves used:** HW-1.
- **Confidence:** Derived (4.2); Unresolved (the rest).
- **Canon check:** (1)–(4) none.

---

## 5 · Senses: smell and taste

- **Ordinary condition (provisional):** *Settled by the revised human model:* a human-type nose is not "poor";
  humans can scent-track (HB-S14, HB-S20). A larger receptor-gene count would not, by itself, mean finer smell
  (Log01:S-18 caveat; HB-S19). *Open:* the receptor repertoire, the vomeronasal organ, the newborn's
  pheromone-released nursing response, and the taste profile.
- **Human baseline:** about 400 intact olfactory-receptor loci; personalized repertoires, with 66% of loci
  carrying loss-of-function or copy-number variants in the population (HB-S18); the "poor human smell" claim traces
  to 19th-century anatomy, not testing (HB-S14); threshold data across mammals are thin (HB-S19); no human pheromone
  is demonstrated (HB-S21); five taste qualities, fat proposed (HB-S22, HB-S23). Human prenatal flavor learning and
  vomeronasal status are **not in the baseline** (gaps).
- **Animal baseline:** 768 intact OR genes, 24.5% pseudogenes (Log01:S-18, the reference genome, domestic origin);
  no adult threshold study found. Lactating females emit 2-methylbut-2-enal (the mammary pheromone, MP), which
  releases stereotyped nipple search through the **main** olfactory system, not the VNO (Log01:S-19, S-21,
  lab/domestic). The MP also gates one-trial odor learning; this window declines by postnatal day 5 (Log01:S-20,
  S-22). Fetuses learn dietary odors in the womb (Log01:S-23). The VNO is present with a pumping anatomy, plastic
  expression, and a sexually dimorphic pathway, but its adult social function is untested (Log01:S-24 to S-26).
  Scent glands: chin, anal, inguinal, Harderian, lacrimal, preputial, mammary (Log01:S-27, S-28). Taste: sugar
  thresholds from maltose 30 mM to lactose 175 mM, suggesting a starch-sensitive channel (Log01:S-29, captive,
  n = 12); domestic rabbits have more taste buds than wild ones (Log01:S-30, wild and domestic).
- **Creator intent:** no charter → **CD-7** (repertoire), **CD-3** (newborn response), **CD-8** (taste),
  **CD-10** (VNO and glands).

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 5.1 | OR gene repertoire | ~400 | 768 | `UNRESOLVED` (CD-7) | Gene count is not acuity (Log01:S-18; HB-S19) |
| 5.2 | Main olfactory system | present | present | `SHARED*` | Structure shared; acuity unsourced on both sides |
| 5.3 | Vomeronasal organ | not in HB | present; adult function unknown | `UNRESOLVED` (CD-10; proposed RQ) | — |
| 5.4 | Newborn MP response (innate release of nipple search) | none sourced | Log01:S-19, S-21 | `UNRESOLVED` (CD-3) | Packaged with rabbit-type nursing (10.15). If kept, any rearing without a lactating mother must supply the MP (pHWC-7; Q-32) |
| 5.5 | MP-gated one-trial learning window | none sourced | Log01:S-20, S-22 | `UNRESOLVED` (CD-3) | — |
| 5.6 | Prenatal flavor learning | not in HB | Log01:S-23 | `UNRESOLVED` (proposed RQ) | The human side is unsourced, so Step 1 is incomplete |
| 5.7 | Taste-receptor set and sugar preferences | HB-S22 | Log01:S-29, S-30 | `UNRESOLVED` (CD-8) | Travels with diet |

- **Coherence links:** 7.8 (perinatal diet learning); 10 and 11 (MP and nursing); 13 (receiving chemical
  signals needs a working olfactory channel); 16 (odor-based identity).
- **Post-engineering drift:** taste-bud numbers differ between wild and domestic rabbits (Log01:S-30), so the
  stock choice (CD-5) sets the starting point. No drift mechanism beyond that is sourced.
- **Lineage deltas:** CD-3, CD-7, CD-10, CD-5.
- **Handwaves used:** HW-1; pHWC-7 (if 5.4 is kept with artificial rearing).
- **Confidence:** Sourced (5.2); Unresolved (the rest).
- **Canon check:** (1)–(4) none.

---

## 6 · Senses: touch and others

- **Ordinary condition (provisional):** *Open.* The base's touch specialist is the face (lips, nose, whiskers);
  the human's is the fingertip. Which comes along depends on the head and hand choices (CD-6, CD-7).
- **Human baseline:** four classes of fingertip afferents carry contact, force direction, and shape (HB-S24); the
  two-point test is a criticized measure (HB-S25); the Pacinian channel handles ~250 Hz vibration (HB-S26,
  secondary). **No vibrissae.** Vestibular, proprioceptive, and interoceptive baselines are **not sourced** (HB gap 1).
- **Animal baseline:** circumoral surfaces take ~86.4% of the primary somatosensory map, and the pinna has its own
  representation (Log01:S-31, lab); whisker barrels are mapped in awake rabbits (Log01, Song 2010); whisker
  movements were filmed in captive domestic rabbits for the first time in 2023, with active whisking not
  established (Log01:S-32, captive). **Substrate-vibration sensing: no source** (Log01 #52). Pups settle using
  tactile and thermal cues (Log01, Pacheco-Cobos 2003, [TI]).
- **Creator intent:** no charter → **CD-6**, **CD-7**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 6.1 | Somatosensory weighting (face vs hand) | fingertip-specialized (HB-S24) | muzzle ~86% of map (Log01:S-31) | `UNRESOLVED` (CD-6, CD-7) | — |
| 6.2 | Vibrissae | absent | present; whisking unknown (Log01:S-32) | `UNRESOLVED` (CD-7) | An additive mechanism: nothing human competes with it, so the question is presence, not which wins (method observation) |
| 6.3 | Substrate-vibration sensing | not sourced | not sourced | `UNRESOLVED` (proposed RQ) | Bears on whether foot-thumping (13.7) is a ground signal |
| 6.4 | Vestibular and proprioceptive systems | not sourced | not sourced | `UNRESOLVED` (proposed RQ) | Both baselines empty |

- **Coherence links:** 2; 13.7 (thumping); 3 and 4 (head plan).
- **Post-engineering drift:** none sourced.
- **Lineage deltas:** CD-7.
- **Handwaves used:** HW-1.
- **Confidence:** Unresolved.
- **Canon check:** (1)–(4) none.

---

## 7 · Diet, dentition, and digestion *(behavior-bearing)*

- **Ordinary condition (provisional):** *Settled:* the rabbit's own digestive solution cannot be carried into a
  human-range body unchanged. Cecotrophy (re-eating soft cecal pellets as the main route to hindgut nutrients) has a
  published **small-body** rationale, and no animal near human size is known to rely on it (Log02:S-87, S-88;
  HWC-16). Teeth that never stop growing would require an abrasive, fibrous diet for life (Log02:S-63). *Open:*
  whether the gut is a human-type omnivore gut or a rabbit-derived fermenter redesigned for size (CD-8); feeding
  rhythm and food choice follow from that.
- **Human baseline:** flexible omnivory; forager plant-to-animal ratios vary widely and fixed "ancestral"
  macronutrient ratios are refuted (HB-S37, contested); heavy dependence on cooking and processing, since strict
  raw diets cut weight and menstrual function (HB-S36), with the origin's timing contested (HB-S35); 32 rooted
  permanent teeth, third molars absent in ~22.6% (HB-S44); no vitamin C synthesis (HB-S41); no functional uricase
  (HB-S42); adult lactose tolerance varies by population (HB-S38); the brain uses ~20% of resting energy (HB-S45);
  the gut-for-brain trade-off is contested (HB-S43). Meal frequency, fiber requirement, emesis, and prenatal flavor
  learning are **not in the baseline** (gaps).
- **Animal baseline:**
  - *Diet:* a generalist grazer that selects; it switches between grasses and broad-leaved plants by habitat and
    season, eats seeds heavily in late spring and summer, and takes high-water plants in summer (Log02:S-96,
    introduced wild, south-western Australia). Wild native gastric contents: 25.5% crude protein, 40.4% neutral
    detergent fiber (Log02:S-92, wild, Mediterranean Spain, n = 80); adult females carry 85% more gastric content
    than males (Log02:S-93, n = 70).
  - *Learned preferences:* pups prefer at weaning what the mother ate, learned equally through the womb, through
    nursing, and through fecal pellets she leaves in the nest; this works even for a toxic plant and for a diet eaten
    a month before pregnancy (Log02:S-51, lab; Log02:S-52, domestic; Log01:S-73, S-74).
  - *Teeth:* all teeth grow continuously and never form roots; eruption matches wear, and soft diets break the
    match and cause dental disease (Log02:S-63, domestic Dutch breed, n = 32, 17 months).
  - *Gut:* a hindgut fermenter whose proximal colon sorts digesta (the colonic separation mechanism), with the
    *fusus coli* as pacemaker (Log02:S-84, S-86, lab/domestic). Soft pellets are about half bacteria, mucus-coated,
    and carry vitamins and protein; cecal fatty acids supply ~40% of maintenance energy; cecotrophy begins at ~3
    weeks and is established by ~6 (Log02:S-01, farm; Log02:S-84). Whole-tract transit 18–30 h (Log02:S-01). Pups
    eat the mother's nest pellets and are colonized from day 3 (Log02:S-50, domestic).
  - *Feeding pattern:* 34–40 small meals a day, more in the dark (Log02:S-01, domestic). Indigestible fiber below
    ~10% of the ration risks lethal diarrhea (Log02:S-01).
  - *Water:* captive wild-caught rabbits cannot reduce water needs below ~55% of food-plus-water intake
    (Log02:S-98); free-living turnover tracks plant water content (Log02:S-99, introduced wild, arid Australia).
  - *Size and cecotrophy:* a separation mechanism plus coprophagy is argued to be **necessary below a body-size
    threshold** (Log02:S-88, meta-analysis); leporids are already the largest reingesting species apart from the
    coypu (Log02:S-87, [SN]); small herbivores' high requirement-to-capacity ratio forces fast passage (Log02:S-89,
    [SN], qualified by later work).
  - *Other:* "cannot vomit" is not demonstrated (Log02:S-77, review; revised model); avocado persin is cardiotoxic
    (Log02:S-79, domestic outbreak) and *Allium* causes hemolytic anemia (Log02:S-80); a serum atropinesterase that
    breaks down atropine is present in some rabbits and not others (Log02:S-78, [SN]).
- **Creator intent:** no charter → **CD-8**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 7.1 | Gut architecture | simple stomach, omnivore gut | cecum-centered hindgut fermenter with colonic separation (Log02:S-84) | `UNRESOLVED` (CD-8) | No source decides |
| 7.2 | Cecotrophy as the main hindgut-nutrient route | absent | present | `UNRESOLVED` (CD-8) | **Excluded by biology as an *obligate* mechanism at human-range size**, unless the HWC-16 bend is accepted: its published reason is a small-body constraint (Log02:S-88, S-89) and the largest known reingesters are far smaller (Log02:S-87) `[derived on scale]`. A rabbit-derived fermenter redesigned to work without it would be `ENG-NOVEL` and needs a charter item |
| 7.3 | Dentition: continuously growing vs rooted | rooted (HB-S44) | continuously growing (Log02:S-63) | `UNRESOLVED` (CD-8) | **Coupled:** continuously growing teeth require abrasive food; with soft or processed food, dental disease is a standing vulnerability (Log02:S-63; pet data Log02:S-60, S-61, coordinate only) (pHWC-9) |
| 7.4 | Feeding pattern (many small meals) | not in HB | 34–40/day | `UNRESOLVED` | Follows 7.1 |
| 7.5 | Fiber floor | not in HB | ~10% indigestible fiber | `UNRESOLVED` | Follows 7.1 |
| 7.6 | Vitamin C synthesis | absent (HB-S41) | rabbit status not sourced | `UNRESOLVED` (proposed RQ; CD-8) | The log does not cover it, so no assumption is made |
| 7.7 | Uricase | absent (HB-S42) | not sourced | `UNRESOLVED` (proposed RQ) | — |
| 7.8 | Perinatal diet-preference learning (womb, milk, nest pellets) | not in HB | Log02:S-51, S-52; Log01:S-73, S-74 | `UNRESOLVED` (proposed RQ) | The human side is unsourced. The nest-pellet route also depends on 7.2 and on nest rearing (CD-3). This is a chemosensory mechanism, not a gut one, so it could be kept under either gut |
| 7.9 | Toxin sensitivities and detox polymorphisms | vitamin C, uric acid (HB-S41, S-42) | persin, *Allium*, atropinesterase (Log02:S-78 to S-80) | `UNRESOLVED` | Follows which genes are kept (CD-8) |
| 7.10 | Emesis | not in HB | not demonstrated (Log02:S-77) | `UNRESOLVED` (proposed RQ) | Bears on poisoning risk (17) |
| 7.11 | Water economy | not in HB | high water dependence (Log02:S-97 to S-99) | `UNRESOLVED` | Follows 7.1 and 9 |

- **Coherence links:** 8 (rabbits feed mostly in the dark, Log02:S-01, and produce soft pellets in quiet periods,
  Log02:S-84); 11 (cecotrophy starts at weaning, when enteritis risk peaks, Log02:S-84); 15 (brain energy: ~20%
  of resting energy in humans, HB-S45, against cecal fatty acids supplying ~40% of maintenance in the rabbit,
  Log02:S-84; whether a fermenting gut can fuel a human-scale brain is unsourced, pHWC-8); 17 (dental disease, gut
  stasis, toxins); 10 (lactating farm does drink 200–250 g per kg per day, Log02:S-01).
- **Post-engineering drift:** *Relaxed selection:* any engineered gut redesign (7.2) is maintained only if it keeps
  paying; direction only. *Condition `[hazy]`:* if a lineage with continuously growing teeth lives on soft or
  processed food (for example in a managed habitat archetype), dental disease recurs every generation as a
  condition, not as selection. No domestication-type effect on diet is sourced.
- **Lineage deltas:** CD-8 can differ by lineage. If lineages with different gut designs interbreed (Q-15), the
  outcome has no source; flag.
- **Individual variance range** (D-7): in the base, females eat more and use nutrients better than males, and the
  young eat a higher-protein diet (Log02:S-93); diet tracks season and habitat (Log02:S-96); each litter's food
  preferences are set by what its mother ate (Log02:S-51, S-52), so preferences vary by family `[derived]`. On the
  human side, lactase persistence and amylase copy number vary as population distributions, not identities
  (HB-S38, S-40). **Range for the race:** from a human-type omnivore whose enzyme profile varies by family line, to a
  selective, fiber-dependent grazer feeding in many small bouts whose favorite foods are inherited from the mother's
  diet. The learned-preference mechanism (7.8) can persist at either end, so it is the most portable piece of the
  animal side in this domain.
- **Handwaves used:** HW-1; HWC-16 (only if 7.2 is kept); pHWC-8, pHWC-9.
- **Confidence:** Sourced (baselines); Derived (7.2 exclusion, 7.3 coupling); Unresolved (resolution).
- **Canon check:** (1) No canon on anthro diet. C-31 (Tepenian proposals to engineer livestock and grasses) and C-30
  (genetically adapted ecosystems) show engineered food chains exist; they don't bind this. (2) No. (3) Binds food
  supply, cuisine, and CST R4 for any settlement (L4, deferred under D-2). (4) No.

---

## 8 · Activity cycle and sleep *(behavior-bearing)*

- **Ordinary condition (provisional):** *Open:* whether the internal clock is the human diurnal type or the
  rabbit's nocturnal type (CD-11). *Settled by the base data:* if the rabbit clock is kept, the **timing** of
  activity is not fixed. It shifts between nocturnal and twilight-peaked patterns with predation risk, weather, and
  season (Log02:S-101 to S-103), so "crepuscular" is one outcome under one set of conditions, not a trait.
- **Human baseline:** diurnal; intrinsic period ~24.18 h (HB-S52); chronotypes roughly normally distributed and
  latest near age 19 (HB-S53, S-54); a week of natural light shifts the clock ~2 h earlier (HB-S55); foragers sleep
  5.7–7.1 h, with onset ~3.3 h after sunset (HB-S56); among Hadza, everyone was asleep at once for only 18 minutes
  in 20 days, because chronotypes differ (HB-S57); adults are advised ≥ 7 h (HB-S58, S-59); segmented sleep is
  contested (HB-S60). Sleep architecture is **not sourced** (HB gap 2).
- **Animal baseline:**
  - *Clock:* phase response to light matches predominantly nocturnal mammals (Log02:S-33, lab, n = 12).
  - *Expressed activity, condition-dependent* (all recorded, none averaged): one nocturnal block (Log02:S-101,
    introduced wild, Dutch dunes, [SN]); an evening peak (Log02:S-104, enclosure under artificial light); peak in
    the last 4–5 h before dawn (Log02:S-02, citing); two peaks at sunrise and sunset, with males more active and
    less activity at temperature extremes, humidity, and wind (Log02:S-102, wild-pen, León); nocturnal under one
    predator community and twilight-peaked under another (Log02:S-103, native translocated, central Spain).
  - Feeding and nursing sit in the dark phase (Log02:S-01; 84–86% of nursing visits at night, Log02:S-32).
  - *Winter:* food shortage lowered heart rate ~30% while body temperature stayed stable (Log02:S-100,
    semi-natural).
  - *Sleep (lab only):* 11.4 h/day, 64.5% slow-wave, 9.6% REM, with more waking and less REM in the dark
    (Log02:S-105, lab males); a light-phase sleep preference (Log02:S-106); sleep with eyes open (Log02:S-107, lab,
    n = 3). No wild sleep data (Log02 gap 2).
- **Creator intent:** no charter → **CD-11**; the risk-timing part travels with **CD-4**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 8.1 | Circadian clock phase type | diurnal (HB-S52) | nocturnal-type (Log02:S-33) | `UNRESOLVED` (CD-11) | **Excluded:** nothing; but a "blended" clock has no source mechanism |
| 8.2 | Risk-sensitive shifting of activity timing (predators, weather, season) | different mechanism: group vigilance from chronotype spread (HB-S57) | Log02:S-102, S-103 | `UNRESOLVED` (CD-4) | The neural mechanism is not identified in the source; it belongs with the vigilance package |
| 8.3 | Daily sleep amount and architecture | 5.7–7.1 h (HB-S56); architecture unsourced | 11.4 h (lab) | `UNRESOLVED` (proposed RQ; CD-11) | Neither side gives a usable architecture comparison |
| 8.4 | Sleep with eyes open | not in HB | Log02:S-107 (n = 3) | `UNRESOLVED` (CD-7, CD-11) | Thin evidence |
| 8.5 | Winter metabolic depression without hypothermia | not in HB | Log02:S-100 | `UNRESOLVED` | Also bears on 9 |

- **Coherence links:** 3.6 (rod-rich retina); 7 (feeding in the dark); 10 (night nursing, Log02:S-32; light-linked
  breeding season, Log02:S-01); 16 (who is awake when, in a group); 9 (less activity at temperature extremes,
  Log02:S-102).
- **Post-engineering drift `[hazy]`:** *If a lineage lives under an artificial light–dark cycle* (for example an
  orbital habitat archetype), human data show light environment moves the clock (HB-S55), and in domestic does 16 h
  of light abolishes breeding seasonality (Log02:S-01), a knock-on to 10. *If the habitat archetype is free of
  predators,* the base data say only that activity windows track predator regimes (Log02:S-103); urban rabbits are
  reported to extend activity (Log01, Ziege 2016, [TI], low). Direction otherwise unknown.
- **Lineage deltas:** CD-11. CD-5 also creates timing deltas: wild rabbits are more nocturnal than domestic
  (Log02:S-101, [SN]), and wild-stock does nurse later at night (peak 01:00–02:00) than domestic does (peak
  19:00–21:00) (Log02:S-32).
- **Individual variance range** (D-7): human chronotype spread by age and sex (HB-S53, S-54); in the base, sex (males
  more active, Log02:S-102), season, and predator regime. **Range for the race:** under a rabbit-type clock, from
  strictly nocturnal to twilight-peaked by condition, with individuals spread by sex and age; under a human-type
  clock, diurnal with a chronotype spread. The **risk-sensitive timing shift (8.2) could be carried under either
  clock** if the vigilance package (CD-4) is kept, which would make it a visible animal trait even in a day-clocked
  lineage. That is an option, not a resolution.
- **Handwaves used:** none beyond HW-1.
- **Confidence:** Sourced (baselines); Unresolved (resolution).
- **Canon check:** (1) C-23 says Centauri planets restore an outdoor/indoor distinction; environment only, kept
  `[hazy]` (D-2). (2) No. (3) Binds settlement scheduling (L4, deferred). (4) No.

---

## 9 · Thermoregulation and environmental tolerance

- **Ordinary condition (provisional):** *Settled (conditional on size):* rabbit-type ear radiators lose relative
  effectiveness as the body gets larger, because heat loss through a surface falls with the surface-to-volume ratio
  (Log02 highlight 4, [derived from physics]). *Open:* fur or skin, sweat glands, the ear's role, and so the heat
  ceiling (CD-9). The base animal is heat-weak; the human is a heavy sweater.
- **Human baseline:** eccrine gland density ~10× chimpanzees' and macaques' (HB-S61); 61–133 functional glands/cm²
  (HB-S62); sweat can exceed 1 L/h (HB-S61, HB-S63). In mice, **EN1 dosage sets the ratio of eccrine glands to hair
  follicles**; but human hair and sweat-gland traits evolved partly independently (both HB-S61). Nude thermoneutral
  zone ~25.9–33.3 °C (HB-S66); measured critical wet-bulb ~30.6 °C humid, lower in hot-dry conditions (HB-S64);
  hypothermia below 35 °C core (HB-S67). Mechanisms include shivering and brown-fat thermogenesis (HB domain 9).
  Gravity: G-LOC near +4 Gz unprotected (HB-S71); microgravity bone loss ~1–1.5% per month (HB-S72).
- **Animal baseline:** the ears are radiators under central neural control: blood flow rises with core temperature
  (Log02:S-110), active vasodilation needs nitric oxide (Log02:S-111), a central NO donor triggers ear warming,
  faster panting, and more respiratory water loss (Log02:S-112), and cold constriction depends on medullary raphé
  neurons (Log02:S-109), all lab. **Heat is the weak side:** comfort around 18–21 °C, heat stress above ~30 °C,
  loss of control above ~35 °C; sweat glands described as non-functional (Log02 #82, #83, S-114; farm, [SN]);
  embryo mortality rises above 30–33 °C (Log02:S-01); heat stress harms immune and reproductive function
  (Log02:S-81). Arid survival needs succulent plants, water, or shaded warrens (Log02:S-97 to S-99; #87).
  Overwinter survival tracks autumn body mass (Log02:S-44, Bayreuth, wild-encl); wild rabbits are lean (Log02:S-130,
  [SN]). **Neonates** are near-poikilothermic for ~15 days and rely on the litter huddle; peripheral pups express
  more brown-fat UCP1; mothers don't brood (Log02:S-45, S-46, S-48, domestic lab); nest temperature tracks soil
  temperature (Log02:S-38, wild-encl).
- **Creator intent:** no charter → **CD-9**; the ear's form → **CD-7**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 9.1 | Integument: fur cover vs bare skin | largely hairless (HB-S61) | furred | `UNRESOLVED` (CD-9) | — |
| 9.2 | Eccrine sweating | dense, high output (HB-S61 to S-63) | described non-functional ([SN]) | `UNRESOLVED` (CD-9) | **Coupled, not locked, to 9.1:** a shared regulator sets the gland-to-hair ratio in mice, but in human evolution the two traits moved partly independently (HB-S61). Full fur plus full human sweating on the same skin is therefore unsourced, not excluded (proposed RQ; pHWC-5) |
| 9.3 | Ear radiator (arteriovenous anastomoses under NO and adrenergic control) | not in HB | Log02:S-109 to S-112 | `UNRESOLVED` (CD-7, CD-9) | If kept at human-range size, its share of total heat loss falls `[derived from physics]` |
| 9.4 | Respiratory evaporative cooling (panting) | not in HB | Log02:S-112 | `UNRESOLVED` (CD-9) | — |
| 9.5 | Brown-fat (non-shivering) thermogenesis | present (HB domain 9) | present (Log02:S-45) | `SHARED*` | Both baselines |
| 9.6 | Age at thermal independence of newborns | not in HB | ~15 days (Log02:S-48) | `UNRESOLVED` | Follows the neonatal state (11.2) |
| 9.7 | Winter metabolic depression | not in HB | Log02:S-100 | `UNRESOLVED` | Shared with 8.5 |
| 9.8 | Heat ceiling | ~30.6 °C wet-bulb (HB-S64) | heat stress above ~30 °C air (farm) | `UNRESOLVED` | Follows 9.1–9.4 |
| 9.9 | Water conservation (urine to 1.9 M urea) | not in HB | Log02:S-98 | `UNRESOLVED` | — |
| 9.10 | Gravity, pressure, radiation tolerance (P-9) | HB-S71, S-72 | not sourced | `UNRESOLVED` | No rabbit or race data; gestation in low or spun gravity is untested (C-56, proposed) |

- **Coherence links:** 1 (scale); 4 (the ear is both hearing organ and radiator); 8; 11 (neonatal huddle and nest);
  7 (water); 17 (heat harms immune and reproductive function, Log02:S-81; embryo loss, Log02:S-01).
- **Conflict (Step 4):** *rabbit-type fur + no functional sweating + human-range size* leaves heat loss to ears and
  panting, whose relative capacity falls with size `[derived]`, in a base animal that is already heat-weak.
  Resolved by (c), recorded as a **known vulnerability** in 17, and (d), sent to the developer as CD-9.
- **Post-engineering drift `[hazy]`:** *if a lineage lives on a hot planetary-surface archetype,* selection on heat
  dissipation is expected; *if cold,* the base data point to autumn body condition as the survival filter
  (Log02:S-44). Direction only.
- **Lineage deltas:** CD-9 by lineage.
- **Individual variance range:** not behavior-bearing. Human sweat rate and heat tolerance vary widely between
  individuals (HB-S63, S-64); in the base, heavier and centrally huddled pups reach thermal independence sooner
  (Log02:S-48).
- **Handwaves used:** HW-1; pHWC-5.
- **Confidence:** Derived (ear scaling); Unresolved (the rest).
- **Canon check:** (1) C-56 (proposed handwave: gestation in low or spun gravity untested). (2) No. (3) P-9 is a body
  property and stays in scope under D-2. (4) No.

---

## 10 · Reproduction (cycle type, mating system, gestation, litter) *(behavior-bearing)*

- **Ordinary condition (provisional):** *Settled by biology:* rabbit-people reproduce only among themselves (O-1;
  O-2 unless Q-31 rules otherwise), through one engineered karyotype (G-1). If adults are human-range in size, they
  **cannot breed at a rabbit's pace:** offspring output per unit of body mass must fall to roughly 35–50% of a
  rabbit's (O-5), and gestation length, litter size, and newborn state come as a matched set (O-4). Newborns get
  maternal antibodies before birth either way (10.10). *Open:* how ovulation and receptivity work, whether breeding
  is seasonal, litter size, nursing pattern, the nest-building drive, and the mating system (CD-3), all inside the
  pace set by CD-2.
- **Human baseline:** spontaneous ovulation, continuous breeding, a menstrual cycle averaging 29.3 days (most 25–30)
  (HB-S73); gestation ~268 days from ovulation, natural range ~37 days (HB-S74); singletons, with twins at roughly
  0.8–1.8% of births by population (HB-S75); forager interbirth interval ~3.1 years, first birth ~20, total
  fertility ~6.2 (HB-S82, secondary); generation time ~26.9 years (HB-S83). Ovulation is usually called concealed;
  why is contested (HB-S76, S-77). Pair bonds in all societies, mostly serial monogamy; polygyny widely permitted;
  polyandry rare; extra-pair paternity ~1–2% (HB-S78 to S-81).
- **Animal baseline:**
  - *Ovulation:* induced (reflex) ovulation with **no regular estrous cycle**; ovulation 10–12 h after mating
    (Log02:S-01, S-12, S-13). The trigger is disputed: a genital-neural route, seminal nerve growth factor, and
    possibly social mounting (Log02:S-09, S-10, S-11; revised-model watch). Receptivity is near-continuous but
    variable (~90% acceptance with a red vulva, ~10% otherwise; Log02:S-01, farm). Pseudopregnancy after sterile
    mating lasts 15–18 days (Log02:S-01, S-14).
  - *Season:* a photoperiod-linked fertility cycle overlain by a green-forage trigger, with the balance varying by
    climate (Log02:S-02, Bayreuth, wild-encl, season 207 ± 4 days; Log02:S-05, introduced wild, south-western
    Australia; Log02:S-06, *algirus*, wild native, Portugal, November–June).
  - *Gestation and litter:* ~30 days (Log02:S-02); litter 4.83 ± 0.04, range 1–9, n = 1,575 litters (Log02:S-02);
    3.90 in *algirus* (Log02:S-06); farm 7–9 (coordinate). Litter mass rises with litter size while each pup's
    birth mass falls (Log02:S-02).
  - *Postpartum conception:* does conceive right after giving birth and carry pregnancy and lactation together;
    realized 3.18 litters per female per year (Log02:S-02). Superfetation is **not** documented in rabbits
    (Log02:S-15).
  - *Nest-building:* digging, then straw-carrying, then hair-pulling, driven by progesterone, estradiol, prolactin,
    and androgens (Log02:S-22 to S-25, lab); stress around birth delays nesting and raises kit loss (Log02:S-27,
    captive); a progesterone-receptor promoter variant is associated with when carrying begins, heritability 0.10
    (Log02:S-28, captive wild stock).
  - *Nursing:* ~3 minutes, about 1.1–1.3 visits a day (Log02:S-32, wild-pen and domestic), on a period near 23 h
    that may be an hourglass rather than a circadian process (Log02:S-30, S-31); concentrated milk, 13.5% protein,
    under 1% lactose (Log02:S-01, farm); oxytocin release proportional to the number of suckling young
    (Log02:S-01); weaning is triggered abruptly by the next pregnancy (Log02:S-21).
  - *Losses:* whole-litter intrauterine loss is common (~60% of litters in one British series, Log02:S-55, [SN]).
  - *Mating system:* small territorial groups with separate rank orders in each sex; called polygynous (Log02:S-08);
    within-litter paternity unstudied (Log02 gap 6).
  - *Reproductive aging:* cessation documented in rabbits (Log02:S-53).
- **Creator intent:** no charter → **CD-3** (system), **CD-2** (pace), **CD-12** (Q-31), **CD-13** (Q-32),
  **CD-17** (placental subtype).

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| — | Karyotype; placental family and subtype | see G-1, G-4, G-5 | | (tagged in Domain 0) | Not re-counted |
| 10.4 | Ovulation mode | spontaneous | induced | `UNRESOLVED` (CD-3) | **Not size-tied:** the source synthesis finds induced ovulation is not tied to small size (Log02 highlight 1, citing Log02:S-13), so biology leaves both open at any scale |
| 10.5 | Cycle and receptivity | menstrual cycle (HB-S73) | no regular cycle; variable receptivity (Log02:S-01, S-14) | `UNRESOLVED` (CD-3) | — |
| 10.6 | Seasonal gating (light and forage) | continuous | seasonal | `UNRESOLVED` (CD-3) | — |
| 10.7 | Postpartum conception with concurrent lactation | lactational suppression (general; not sourced in HB) | present (Log02:S-02, S-21) | `UNRESOLVED` (CD-3) | At human scale, untested: concurrent pregnancy and lactation already put farm does in negative energy balance (Log02 #16, [SN]) (pHWC-4) |
| 10.10 | Newborn passive immunity before birth | placental FcRn (PI-S34) | yolk sac (PI-S35) | `SHARED*` (outcome) | Either program delivers IgG before birth. **Rearing is not forced into early-nursing dependence for immunity.** Maternal IgG protected rabbit kittens to ~13 weeks against one virus strain (Log02:S-66) |
| 10.11 | Litter size | 1 | ~4–5 wild | `UNRESOLVED` (CD-3 inside CD-2) | Lagomorphs show no within-order litter shrinkage with mass (PI-S52), so a lineage could hold ~5; but the production cap (O-5) means litter × frequency × newborn size must fit. Multiple births through an upright pelvis are unresearched (PI Gaps 11; pHWC-3) |
| 10.12 | Gestation length | ~268 days | ~30 days | `UNRESOLVED` (CD-2) | Rabbit-line scaled: ~40–64 days across 30–80 kg `[derived]`. **Excluded:** the rabbit's ~30 days at human scale (HWC-10); under ~40 days with developed newborns (PI §6.4). 40–60 days with helpless newborns falls between PI's "plausible" floor and its "bend" line (pHWC-6) |
| 10.13 | Mating system and pair-bond mechanism | pair bonds, serial monogamy (HB-S80) | polygynous small groups (Log02:S-02, S-08) | `UNRESOLVED` (proposed RQ; CD-3) | Neither side's pair-bond neurobiology is sourced (HB gap 11; rabbit paternity gap) |
| 10.14 | Hormone-triggered nest-building drive (dig, carry, pluck) | none sourced | Log02:S-22 to S-25 | `UNRESOLVED` (CD-3) | Additive. Comes with the rabbit-type hormonal sequence of late pregnancy |
| 10.15 | Nursing economy (brief, infrequent nursing of concentrated milk; hourglass timing; weaning by next pregnancy) | breastfeeding to ~29 months (HB-S86) | Log02:S-01, S-21, S-30 to S-32 | `UNRESOLVED` (CD-3) | Tied to a small burrow-nesting body in the source synthesis (Log02 highlight 1, [derived]); scaling unsourced (pHWC-2) |
| 10.16 | Reproductive aging | menopause ~48.8 y (HB-S94) | cessation documented (Log02:S-53) | `UNRESOLVED` (CD-2) | See 12.3 |

- **Coherence links:** 1 (pelvis; maternal size bounds newborn size, PI-S31); 11 (newborn state); 12; 16 (in the
  base, female competition for nursery burrows drives infanticide, Log01:S-86); 14 (stress delays nesting,
  Log02:S-27); 8 (night nursing); 5 (MP); 17 (uterine cancer in intact pet does, Log02:S-64, domestic; the flea whose
  breeding is tied to the doe's pregnancy hormones, Log02:S-75).
- **Post-engineering drift:** *Founder effects* (G-8). *Reversion:* none unless a charter suppresses a rabbit trait
  such as seasonal gating (then it becomes `SUPPRESSED-LATENT`). *New selection `[hazy]`:* under artificial
  photoperiods, seasonality may lapse (Log02:S-01). *Domestication-type, under creator management (HWC-15):* the
  selected fox lines matured about a month earlier and some bred out of season (PI-S75), trait by trait, never as a
  package (PI §8.2). Pace: per generation (CD-2).
- **Lineage deltas:** CD-3 per lineage. **If lineages differ in karyotype (CD-14), they are partly or wholly
  isolated (O-3)**, and the "species" may be several peoples sharing an animal base; flagged, not decided (M-1
  Step 6). **If one lineage alone is built on a human scaffold (Q-31),** it alone would carry reduced fertility and
  male-first sterility risk (PI-S07), and would be less able to interbreed with the others `[derived]`.
- **Individual variance range** (D-7): in the base, fecundity tracks rank (Log02:S-02, S-03; Log01:S-90 conflicts),
  mother's age (Log02:S-37, S-39), season (Log02:S-41), population (Log02:S-02, S-04, S-06), and a heritable
  nest-timing variant (Log02:S-28); annual output varies three-fold or more between populations (15–53 young per
  female per year, Log02:S-04). On the human side, cycle length varies by age and BMI (HB-S73), twinning by
  population and maternal age (HB-S75), and total fertility from ~4.7 to over 9 (HB-S82). **Range for the race:**
  whichever system is chosen, both baselines make realized reproduction strongly condition-dependent (food, density,
  rank, stress), so individual output varies several-fold at any pace `[derived]`. Litter-based variance (sibling
  position, litter size effects) exists only if CD-3 gives litters.
- **Handwaves used:** HW-1; HWC-1, HWC-3, HWC-10 (excluded form), HWC-12, HWC-13; HWC-9 only if Q-31 rules yes;
  pHWC-2, pHWC-3, pHWC-4, pHWC-6.
- **Confidence:** Derived (exclusions, 10.10); Sourced (baselines); Unresolved (system).
- **Canon check:** (1) C-7 (natural reproduction) agrees. C-52 (artificial wombs are normal in Tepenia) bears on
  generation zero. C-57 (a robot as legal mother) is an idea, not canon. (2) No. (3) Q-31 binds human canon and
  family storylines; Q-15 binds every rabbit lineage. (4) Register the Q-31, Q-32, and Q-15 rulings in
  `DECISIONS.md`.

---

## 11 · Development and maturation (neonatal state, dependency period, juvenile stages)

- **Ordinary condition (provisional):** *Settled:* development runs on **one** genome-wide tempo (G-3). Gestation
  length and newborn state come together: short gestation means helpless newborns in a nest; long gestation means
  more developed newborns (O-4). Passive immunity arrives before birth (10.10). They acquire a full language, with a
  sensitive period for it (11.7). *Open:* the tempo itself (CD-2), and with it newborn state, weaning, age at
  maturity, and how long the learning period lasts.
- **Human baseline:** "secondarily altricial"; neonatal brain ~25–30% of adult size (HB-S84); brain ~80% of maximum
  by ~3 years, gray matter peaking ~5.9 years, white matter ~28.7 years (HB-S90); breastfeeding ~29 months in
  nonindustrial populations (HB-S86); childhood and adolescence as stages (HB-S85, contested in part); forager
  children are net consumers into their mid-to-late teens (HB-S87); US median menarche 12.43 years (HB-S89);
  allocare by fathers, grandmothers, siblings (HB-S88, framing contested). Language: phonology tuned in year 1,
  grammar-learning ability high to ~17.4 years, late first-language exposure causes lasting deficits (HB-S122,
  S-124).
- **Animal baseline:** born furless, eyes closed, in an underground nest (Log02:S-48, S-34); eyes open on days
  10–12 (Log01:S-10, lab); out of the burrow ~day 20, weaned ~day 30 (Log02:S-02, wild-encl); pups wake 1–2 h before
  nursing and their feeding clock entrains to it (Log02:S-29, S-34, S-35, lab). Heavier pups take central huddle
  places, stay warmer, and get more milk (Log02:S-36, wild-encl and lab; S-45); pups raised without littermates
  develop balance later and compete worse (Log02:S-49, domestic). Early life sets lifetime fitness (Log02:S-39,
  S-43, wild-encl). Puberty: few pregnancies before 19 weeks, the full rate ~27 weeks (Log02:S-04, introduced
  wild); no breeding until the next spring in Bavaria, mean "adult" age 304 days (Log02:S-02); farm 4–8 months at
  70–75% of adult weight (Log02:S-01). Developmental windows: conditioned fear bradycardia from day 18 (Log01:S-16);
  the first-week handling window around nursing sets fear of humans (Log01:S-71, S-72); the MP learning window
  closes by day 5 (Log01:S-22).
- **Creator intent:** no charter → **CD-2**, **CD-3**, **CD-4**, **CD-13**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| — | Developmental tempo | see G-3 | | (Domain 0) | — |
| 11.2 | Newborn state | secondarily altricial (HB-S84) | altricial, nest-born (Log02:S-48) | `UNRESOLVED` (CD-2) | Follows gestation (10.12) by the matched-set rule (PI §6.4) |
| 11.3 | Extent of postnatal brain growth | large (HB-S84, S-90) | not sourced | `UNRESOLVED` (CD-2) | **Coherence conflict (CM-8):** a language-capable brain (15.1) has to be grown somewhere in development. Under a rabbit-line tempo that growth and the whole language window would be compressed into about a year; no source shows that is possible (pHWC-1). Sent to the developer (d) |
| 11.4 | Weaning trigger and timing | ~29 months, varies (HB-S86) | the next pregnancy (Log02:S-21) | `UNRESOLVED` (CD-3) | — |
| 11.5 | Puberty trigger | endocrine, secular trend (HB-S89) | ~70–75% of adult mass, season-gated (Log02:S-01, S-02, S-05) | `UNRESOLVED` (CD-2, CD-3) | — |
| 11.6 | Arousal-gated early window that re-categorizes humans but not predators | not sourced | Log01:S-71, S-72 | `UNRESOLVED` (CD-4) | If kept, its timing rescales with tempo (M-7 Step 5b), and **who handles the infants inside it** matters (CD-13) |
| 11.7 | Language sensitive period | present (HB-S122, S-124) | — | `HUMAN-DOM` | Part of the language capacity (13.1, 15.1): late exposure causes lasting deficits (HB-S124). Its **duration** is open (CD-2) and must be re-derived by M-7 |
| 11.8 | Sibling-dependent development (huddle position, littermate competition) | singletons (twins rare) | Log02:S-36, S-45, S-49 | `UNRESOLVED` (CD-3) | Exists only if litters exist |
| 11.9 | Who rears: mother-only brief contact vs mother plus allocare | allocare (HB-S88) | mother only; no paternal care reported (Log02:S-20, S-31) | `UNRESOLVED` (CD-3) | Long dependency requires provisioning by others (HB-S87); see 16.9 |

- **Coherence links:** 10; 12 (late maturity predicts long life, PI-S48); 15 (learning period); 16 (rearing shapes
  groups); 9 (newborn thermoregulation); 5 (MP).
- **Post-engineering drift:** *Domestication-type (HWC-15):* earlier sexual maturity in selected fox lines (PI-S75),
  in rabbit-people generations. *Founder:* G-8.
- **Lineage deltas:** CD-2 per lineage gives different P-5 values. Crosses between lineages of different tempos have
  no source; flag (Step 6).
- **Individual variance range:** not behavior-bearing, but it feeds 14–16: in the base, body mass relative to
  littermates and huddle position produce consistent individual differences by days 12–17 (Log02:S-40; Log01:S-78,
  S-104).
- **Handwaves used:** HWC-4; HWC-13; HWC-14; pHWC-1.
- **Confidence:** Derived (couplings); Unresolved (values).
- **Canon check:** (1) C-52 (artificial wombs) and C-56 (gestation in low or spun gravity, proposed) bear on
  generation zero. (2) No. (3) The co-rearing window that underlies incest avoidance (L0 template §6, Brown) must be
  re-derived on this race's tempo; binds L3. (4) No.

---

## 12 · Lifespan and aging

- **Ordinary condition (provisional):** *Settled:* lifespan cannot be set separately from maturation. Long life
  needs slow development and low reproduction (O-6), and a life beyond about five times the size prediction is
  excluded (HWC-11). Size reached by fast growth predicts earlier aging (PI-S57; HWC-14). *Open:* where on that line
  the race sits (CD-2): about 20–27 years maximum on the rabbit-scaled line, up to a human-range lifespan on a slow
  line.
- **Human baseline:** forager life expectancy at birth 21–37 years, modal adult age at death ~72 (68–78) (HB-S91);
  modern global ~73 (HB-S92, secondary); validated maximum 122, contested (HB-S93); menopause ~48.8 (HB-S94); a long
  post-reproductive life is species-typical (HB-S91). Setting modifier: Tepenian human lifespans are only marginally
  longer than real-world (C-53).
- **Animal baseline:** most wild rabbits die young: ~40% nestling mortality to day 12, and 5.5% of newborns reach
  adulthood (Log02:S-02, wild-encl); survival to 24 weeks 20–55% (Log02:S-04, S-07, introduced wild). Mean
  reproductive lifespan 712 ± 37 days after adulthood; high-ranking females live ~50% longer (Log02:S-02, S-03).
  Maximum recorded wild lifespan 9.5 years (Log02:S-57, introduced wild, South Australia); AnAge maximum 13 years
  (PI-S58). Pets: median death 4.3 years (Log02:S-58, domestic coordinate). Reproductive cessation documented
  (Log02:S-53); tumor prevalence rises steeply with age in intact pet does (Log02:S-64, S-65, domestic). Longevity
  quotient ≈ 0.85 (PI §6.2).
- **Creator intent:** no charter → **CD-2**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 12.1 | Intrinsic senescence schedule | mortality doubling ~7–8 years (HB-S91) | not sourced | `UNRESOLVED` (CD-2) | Coupled to development time (PI-S48) |
| 12.2 | Maximum lifespan | 122 (contested) | 9.5 wild; 13 AnAge | `UNRESOLVED` (CD-2) | Rabbit-line scaled: ~20–27 years across 30–80 kg; pan-mammal line 24–28 years; ceiling at a longevity quotient of 5 ≈ 118–137 years, **only with a slow life history** `[derived from PI-S48, PI-S58]` |
| 12.3 | Post-reproductive stage | present | cessation documented; rarely reached in the wild (Log02:S-02) | `UNRESOLVED` (CD-2, CD-3) | P-6 needs this |
| 12.4 | Age-linked reproductive-tract cancer | not in HB | Log02:S-64, S-65, S-133 (domestic) | `UNRESOLVED` | Follows the hormonal system chosen in CD-3 |

- **Coherence links:** 11; 10; 1 (growth acceleration); 16 (high rank lengthens life in the base, Log02:S-03); 17.
- **Post-engineering drift:** if size was reached by accelerated growth, expect the large-dog-breed pattern of
  faster aging once senescence begins (PI-S57). **M-7 note:** witness span (lifespan ÷ generation time) is about 2.6
  on human values (~70 ÷ ~27; HB-S91, S-83) `[derived]`. On the rabbit-scaled line, with first breeding near one
  year and a maximum near 20–27 years, generation time would likely fall in single-digit years, so divergence per
  calendar century would be several times faster `[derived; survivorship unsourced; M-7 computes it]`.
- **Lineage deltas:** CD-2 per lineage; a shorter-lived lineage turns over generations faster, so the same span of
  years is more generations of drift (M-7 Step 2).
- **Handwaves used:** HWC-11 (excluded form); HWC-13; HWC-14.
- **Confidence:** Derived (couplings, ranges); Unresolved (value).
- **Canon check:** (1) C-53 is about humans only. C-51 (robots live for centuries) means robot creators could
  witness many generations (an M-4 drift-ledger matter). (2) No. (3) Generations elapsed between creation and
  *New Centauri* (C-25; Q-2 era) depend on CD-2. (4) No.

---

## 13 · Communication channels (vocal anatomy, body signals, chemical signals) *(behavior-bearing)*

- **Ordinary condition (provisional):** *Settled:* rabbit-people communicate in a **full language**, spoken or
  signed, because canon makes them a full race that inherits its creators' culture (C-7; D-1), and the only sourced
  mechanism for language is human (HB-S97, S-101, S-103). *Open:* whether language rides on a human-type voice or
  on sign (at least one must be kept: CM-10), and which of the base animal's non-verbal channels run alongside it:
  scent marks, identity odors, tail-flagging, foot-thumping, ear and body postures (CD-10, CD-7, CD-6, CD-4).
- **Human baseline:** language in every society, in speech or sign; sign languages are full languages, and Nicaraguan
  children built one from gesture within ~25 years (HB-S101). Humans lost the laryngeal air sacs and vocal membranes
  of other primates, giving a stable voice source (HB-S98); the decisive human difference is articulator and
  laryngeal **control**, not a descended larynx (HB-S97, contested); vocal learning is rare in mammals (HB-S103);
  ~39 bits/s across 17 languages (HB-S100); adult male voices about an octave below female (HB-S99); sclera-based gaze
  signaling contested (HB-S102); no demonstrated human pheromone (HB-S21); body odor carries ratable cues (HB-S76).
  Signal control: speech and sign voluntary and learned; pitch anatomical but trainable; body odor involuntary.
- **Animal baseline:**
  - *Chemical (best documented):* both sexes chin-mark; the gland and the marking pattern are androgen-dependent
    (Log01:S-28, [FT], citing secondary work). In dominant males a fixative, 2-phenoxyethanol, appears in the chin
    secretion; rabbits can't smell it, but it makes dominant marks last longer (Log01:S-38). Marks are placed at the
    group's center and boundaries, and dominants mark subordinates (Log01:S-36, introduced wild, Australia). Chin
    chemistry differs between sites over 100 km apart (Log01:S-37). Chinning is triggered by novel objects' visual and
    tactile features (Log01:S-39, S-40, domestic). **Inguinal odor carries group or individual identity:** penmates
    smeared with a stranger's inguinal secretion were attacked (Log01:S-34, wild-type in outdoor pens, Australia,
    n = 60 ♂, 120 ♀, 162 mixed). Pellet odor raises the owner's success in territorial contests (Log01:S-35).
    Latrines are signal sites whose layout shifts along a rural-to-urban gradient (Log01:S-42, 15 wild populations,
    Frankfurt); residents counter-mark strangers' pellets more than neighbors' (Log01:S-43, wild native, Spain).
    Urine spraying in courtship and aggression (Log01:S-45, lab ethogram).
  - *Acoustic (thin):* grunts; screams when injured or frightened; a male call at ejaculation (Log01:S-45); adults
    rarely vocalize to minor procedures (Log01:S-51); pregnant domestic does placed with a male vocalized (Log01:S-50,
    domestic, Algeria); **pup distress calls work:** 60.6% of mothers returned to playbacks (Log01:S-49, Bayreuth,
    wild-encl). No ultrasonic calls found; no acoustic analysis of the adult repertoire exists (Log01 #57).
  - *Percussive:* hind-foot thumping when alarmed, held in check by septal inhibition (Log01:S-45, S-58); its effect
    on receivers is untested (Log01:S-47, [TI]).
  - *Visual:* tail-flagging before flight was about three times as likely with young nearby (22% vs 7%), and never
    at an empty trolley (Log01:S-46, wild, UK, 2,169 escape events); ears erect when alert; crouching with ears
    flattened; nose lowered below an approaching rabbit's (Log01:S-45); ears pressed back tracks corticosterone
    (Log01:S-53).
  - *Tactile:* allogrooming, lying in contact (Log01:S-45).
  - *Signal control:* audience-sensitive (tail-flag with kin, Log01:S-46; pain face with an observer, Log01:S-52)
    versus physiologically fixed (status chemistry, androgen-dependent marking, identity odors; Log01:S-28, S-34,
    S-38).
- **Creator intent:** no charter → **CD-10** (scent and body signals), **CD-7** (voice, ears), **CD-6** (tail,
  hands), **CD-4** (alarm). Canon requirement for language: C-7, D-1.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 13.1 | Language capacity (neural) | present (HB-S101, S-103) | absent | `HUMAN-DOM` | **Not a silent default.** Canon makes the race a full people that inherits its creators' culture (C-7 "full races"; D-1, "a lineage's starting culture is its creators' culture"), and the repo's scope is conscious, sentient races (`CLAUDE.md`). That requires a symbolic communication system, and the only sourced mechanism for one is human; the rabbit side offers none (Log01 §13). Confidence: Derived |
| 13.2 | Speech apparatus (simplified larynx, fine laryngeal and articulator control) | HB-S97, S-98 | rabbit vocal anatomy not sourced | `UNRESOLVED` (CD-7) | **Constraint:** if 13.2 is not kept, hands capable of sign (2.2) must be; otherwise language has no channel (CM-10) |
| 13.3 | Identity odor (inguinal) | none (HB-S21) | Log01:S-34 | `UNRESOLVED` (CD-10) | Additive. If kept, it is involuntary (Log01:S-34) |
| 13.4 | Status-linked gland chemistry and androgen-dependent marking | none | Log01:S-28, S-38 | `UNRESOLVED` (CD-10) | If kept, rank is broadcast without the sender's control |
| 13.5 | Latrine and pellet marking | none | Log01:S-35, S-42, S-43 | `UNRESOLVED` (CD-10) | Sensitive for audience reception |
| 13.6 | Novelty-triggered chin-marking motor pattern | none | Log01:S-39, S-40 | `UNRESOLVED` (CD-10) | — |
| 13.7 | Alarm signals: tail-flag (audience-dependent) and thumping | none | Log01:S-45, S-46, S-58 | `UNRESOLVED` (CD-6 tail; CD-4) | Thumping as a ground signal also needs 6.3 |
| 13.8 | Species-typical nonverbal calls (scream when caught; grunt; infant distress calls) | human nonverbal vocalizations (HB-S109) | Log01:S-45, S-49 | `UNRESOLVED` (CD-4, CD-7) | Infant distress calls are effective in the base (Log01:S-49) |
| 13.9 | Ear and postural signals | human posture and face | Log01:S-45, S-53 | `UNRESOLVED` (CD-7) | See 14.7 |
| 13.10 | Tactile affiliative signals (grooming, contact lying) | touch (HB domain 14) | Log01:S-45 | `UNRESOLVED` (proposed RQ) | Human affiliation neurobiology is not sourced (HB gap 11) |

- **Coherence links:** 4 (hearing); 2 (sign); 5 (receiving chemical signals); 16 (identity and status); 14.
- **Post-engineering drift:** *conditional:* if the chemical channel is kept, the base shows site-level chemical
  differences in chin secretion (Log01:S-37), so local differences in scent profile could arise between settlements;
  mechanism not identified in the source. Latrine layout shifts with density (Log01:S-42), a condition effect. Pace:
  per generation.
- **Lineage deltas:** CD-10 per lineage: one lineage might carry identity and status odors and another none. Within
  one species, the base's attack response to foreign identity odor (Log01:S-34) is a mechanism to watch if such
  lineages share space; whether it would fire across lineages is untested.
- **Individual variance range** (D-7): in the base, marking intensity rises with dominance and in the breeding
  season (Log01:S-28, S-33); males chin more overall but females more around days 30–50 (Log01:S-28); tail-flag rates
  depend on whether young are near (Log01:S-46). On the human side, speech rate and pitch vary with sex, age, and
  language (HB-S99, S-100). **Range for the race:** from members who signal almost entirely through language and
  voluntary posture (if CD-10 drops the glands), to members whose identity and rank are continuously broadcast in
  scent beyond their control while they talk.
- **Handwaves used:** HW-1.
- **Confidence:** Derived (13.1, CM-10); Unresolved (the rest).
- **Canon check:** (1) Q-12 (whether languages go through the language repos) is downstream. (2) No. (3) Language
  modality binds dialogue, voice casting, and the doll's face (C-2). (4) No.

---

## 14 · Emotion expression (face, ears, tail, posture, voice) *(behavior-bearing)*

- **Ordinary condition (provisional):** *Open* in nearly every visible part. The base animal offers a **prey-type
  fear architecture:** fear expressed by a conditioned slowing of the heart and freezing, run through the central
  amygdala; tonic immobility as a last resort; pain displays that drop when an observer is present (Log01:S-57,
  S-54, S-52). Whether rabbit-people carry it, and how strongly (the wild form or the reduced domestic form), is the
  developer's largest behavioral lever (CD-4, CD-5). Human expressive machinery (facial muscles under dual control,
  nonverbal vocalizations) is the other source, and how faces map to emotions is debated (HB-S104 to S-110).
- **Human baseline:** expression through face, voice, posture, touch; voluntary (pyramidal) and spontaneous
  (extrapyramidal) facial routes, with upper-face muscles harder to move at will (HB-S110, secondary). Universality
  is contested: recognition above chance across cultures and shared expression contexts (HB-S105, S-107, S-109),
  against culture-specific representations and weak face-to-emotion coherence (HB-S104, S-106, S-108). **Fear and
  stress physiology (freezing, heart-rate responses, stress hormones) is not in the human baseline** (gap), so Step 1
  is incomplete for this domain's core mechanism.
- **Animal baseline:**
  - *Fear output:* conditioned bradycardia via the amygdala's central nucleus; lesions there block its acquisition
    (Log01:S-57, lab); it first appears ~day 18 (Log01:S-16).
  - *Tonic immobility:* heart rate falls (Log01:S-54, lab); a "trancing" study reports raised heart rate and stress
    hormones instead (Log01:S-55, [SN]); recorded as variation, not averaged. Septal lesions raise emotionality and
    immobility (Log01:S-58).
  - *Stress hormones:* fecal corticosterone tracks the local carnivore index across 20 Doñana populations (Log01:S-60,
    wild native); fox odor raises it (Log01:S-61); subordinates carry more (Log01:S-83, Bayreuth); ten minutes on an
    unfamiliar lap raised it 214% (Log01:S-53, domestic, n = 7).
  - *Pain face:* the Rabbit Grimace Scale uses orbital tightening, cheek flattening, nose shape, whisker change, and
    ear position (Log01:S-51, lab, n = 8); with an observer present, peak-pain scores were lower (Log01:S-52, lab,
    n = 28).
  - *Positive states:* food and nursing are rewarding (Log01:S-75); an anxiolytic raised play and lowered vigilance
    (Log01:S-101, lab, n = 8).
  - *Individual styles:* not domain-general (Log01:S-62, Bayreuth); pups differ consistently by relative body mass
    (Log01:S-78) and sibling relations (Log01:S-104).
  - *Domestication changed fear circuitry:* smaller amygdala, larger medial prefrontal cortex (Log01:S-68); tameness
    polygenic (Log01:S-69); introduced free-living populations select **against** domestication alleles (Log01:S-70).
  - *The early window:* handling in the first postnatal week, around nursing, made wild-type and domestic rabbits
    approach humans for life, while handled and unhandled rabbits alike still avoided a stuffed fox (Log01:S-71,
    S-72).
- **Creator intent:** no charter → **CD-4**, **CD-5**, **CD-7**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 14.1 | Central-amygdala fear output (bradycardia, freezing) | not in HB | Log01:S-57 | `UNRESOLVED` (CD-4; RQ-4 supplement needed) | The comparison can't be laid side by side |
| 14.2 | Tonic immobility | not in HB | Log01:S-54, S-56 | `UNRESOLVED` (CD-4) | — |
| 14.3 | Size setting of the fear system (amygdala and prefrontal volumes) | — | wild vs domestic (Log01:S-68 to S-70) | `UNRESOLVED` (CD-4, CD-5) | The stock choice sets the starting point |
| 14.4 | Threat-sensitive stress axis | not in HB | Log01:S-53, S-60, S-61, S-83 | `UNRESOLVED` (proposed RQ, human side) | — |
| 14.5 | Facial musculature and dual control | HB-S110 | muzzle-based grimace units (Log01:S-51) | `UNRESOLVED` (CD-7) | — |
| 14.6 | Audience suppression of pain display | learned display rules (HB-S104; L3) | Log01:S-52 (mechanism unknown) | `UNRESOLVED` (CD-4) | Different mechanisms with a similar surface; resolution must stay on mechanism |
| 14.7 | Ear-posture stress display | none | Log01:S-45, S-53 | `UNRESOLVED` (CD-7) | Needs mobile ears (4.5) |
| 14.8 | Locomotor play as a positive-state display | not in HB | Log01:S-45, S-101 | `UNRESOLVED` (CD-4) | Play and vigilance trade off in the base (Log01:S-101) |
| 14.9 | Nonverbal vocal emotion | laughs, screams (HB-S109) | scream (Log01:S-45) | `UNRESOLVED` (CD-7) | — |

- **Coherence links:** 15 (vigilance); 8 (risk timing); 10 (stress delays nesting and raises kit loss,
  Log02:S-27); 16 (rank stress, Log01:S-83); 17 (stress and gut stasis, `[LEAD]`); 11.6 (the early window).
- **Post-engineering drift:** *Domestication-type under creator management (HWC-15):* in the fox benchmark, basal
  cortisol halved by generation 20 under selection in which fewer than 10% bred (PI-S75), with the founder-stock
  caveat (PI-S73). *Reversion `[hazy]`:* if a lineage built with a reduced, domestic-type fear system later lives
  under real risk, the base shows free-living populations selecting against domestication alleles (Log01:S-70).
  Pace: per generation (CD-2).
- **Lineage deltas:** CD-4 and CD-5 by lineage. **The early window creates a rearing-dependent delta:** if 11.6 is
  kept, whoever handles infants inside the window (human staff, robots, earlier-generation members) becomes a
  non-feared category for life, while predator fear is untouched (Log01:S-71, S-72); generalization to other
  handlers was only partial in a training study (Log01:S-76). Creator type acts here only through the rearing plan
  (M-4 §6), never as an essence (`CLAUDE.md` rule 3).
- **Individual variance range** (D-7): in the base, low scanners show large stress-hormone rises to predator odor
  while high scanners stay stable (Log01:S-62); pups already differ by relative body mass and huddle history
  (Log01:S-78, S-104); domestic and wild brains differ (Log01:S-68). On the human side, expression-to-context links
  vary by culture and context (HB-S104 to S-106). **Range for the race:** if rabbit-derived fear circuitry is kept,
  from the full wild form (freezing, heart-slowing, immobility under capture) to the reduced domestic form, which is
  smaller but **not absent** (Log01:S-68); individuals spread along a scanning and stress-response axis
  (Log01:S-62). If it is not kept, this domain carries no animal side, and D-7 must be met elsewhere.
- **Handwaves used:** HW-1.
- **Confidence:** Sourced (animal side); Unresolved (resolution).
- **Canon check:** (1) None. (2) No. (3) No. (4) No.

---

## 15 · Cognition (perception-to-action, attention, memory, notable differences) *(behavior-bearing)*

- **Ordinary condition (provisional):** *Settled:* language-capable, culture-bearing cognition (C-7; D-1). On current
  sources that means a brain on the human pattern at roughly human scale (HB-S45, S-46), which sets the body-size
  floor in 1.1. *Open:* what the rabbit side adds on top: attention built to scan a horizon and swing toward sounds
  (Log01:S-03, S-04, S-12); two vigilance modes, overt toward predators and subtle toward their own kind
  (Log01:S-59); predator recognition that is partly inherited and partly learned (Log01:S-63, S-64); pheromone-gated
  one-trial learning and inherited food preferences (Log01:S-20, S-73). Also open: how long the learning period
  lasts (CD-2).
- **Human baseline:** ~86 billion neurons (HB-S46); the brain uses ~20% of resting energy (HB-S45); working memory
  ~4 chunks (HB-S48); at 2.5 years children outperform apes on social-learning tasks (HB-S47); false-belief
  understanding at ~4–5 years in five cultures (HB-S49); overimitation (HB-S125); teaching contested (HB-S126). Most
  data are WEIRD-biased (HB-S50); psychological sex differences are mostly small (HB-S51).
- **Animal baseline:** one-trial MP-gated odor learning in newborns (Log01:S-20, S-22); prenatal flavor learning
  (Log01:S-23); classical conditioning (Log01:S-57); place preference (Log01:S-75); clicker training that generalized
  only partly to a second familiar person (Log01:S-76, lab, n = 13); diet preferences passed by three redundant routes,
  even for a toxic plant (Log01:S-73, S-74); short-term object memory as measured by marking (Log01:S-40); social
  memory for neighbors versus strangers (Log01:S-43) and for group membership by odor (Log01:S-34). Spatial memory:
  no study found (Log01 gap 9). Overt vigilance rose with buzzards present; subtle vigilance rose with conspecifics
  nearby (Log01:S-59, Bayreuth, wild-encl); habitat use and vigilance compensate for each other (Log01:S-66, feral,
  Kerguelen). Introduced Australian rabbits avoided co-evolved predators' odors (Log01:S-63) and later also novel
  marsupial predators' (Log01:S-64); recorded as variation. Personality and problem solving unlinked (Log01:S-77,
  preprint, n = 15).
- **Creator intent:** no charter → **CD-4**, **CD-7**, **CD-2**. Robot-made lineages carry an extra charter question:
  robot norms allow minds to be "only ever partially specced, by law" (C-46); whether that applies to minds robots
  make biologically is Q-19, a charter matter, not L1.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 15.1 | Language-capable, culture-bearing general cognition (brain scale and architecture) | HB-S46, S-47 | — | `HUMAN-DOM` | Same chain as 13.1 (C-7; D-1; repo scope). Culture-bearing includes some cultural-transmission mechanism; this resolution claims capacity, not any specific human learning style. Body-size floor follows (1.1) |
| 15.2 | Attention architecture: horizon scanning and sound-to-gaze orienting | foveal fixation (HB domain 3) | Log01:S-03, S-04, S-12 | `UNRESOLVED` (CD-7) | Rides with vision geometry (3.1, 3.2) |
| 15.3 | Vigilance modes (overt to predators, subtle to conspecifics) | group vigilance from chronotype spread (HB-S57), a different mechanism | Log01:S-59, S-66 | `UNRESOLVED` (CD-4) | — |
| 15.4 | Predator-category recognition (inherited plus learned generalization) | not in HB | Log01:S-63, S-64, S-71 | `UNRESOLVED` (CD-4) | — |
| 15.5 | Chemosensory one-trial learning and vertical diet-preference transmission | not in HB | Log01:S-20, S-22, S-73, S-74 | `UNRESOLVED` (CD-3, CD-8; proposed RQ, human side) | — |
| 15.6 | Social recognition by odor (group membership, neighbor vs stranger) | faces and voice (HB P-4 extension) | Log01:S-34, S-43 | `UNRESOLVED` (CD-10) | — |
| 15.7 | Length of the learning period (developmental windows) | long (HB-S122) | — | `UNRESOLVED` (CD-2) | Coherence conflict CM-8 |

- **Coherence links:** 3, 4 (attention follows the senses); 7 (brain energy, pHWC-8); 11 (learning period); 13;
  14; 16.
- **Post-engineering drift `[hazy]`:** *if a lineage lives without predators,* the base shows anti-predator responses
  persisting for about 150 years in introduced populations without co-evolved predators, partly through learning
  (Log01:S-63, S-64), and urban relaxation reported at low confidence (Log01, Ziege 2016, [TI]). Direction: slow
  relaxation, not quick loss. Pace: per generation.
- **Lineage deltas:** CD-4 and CD-7 by lineage; CD-2 sets each lineage's learning period.
- **Individual variance range** (D-7): in the base, behavioral styles that are not consistent across tests
  (Log01:S-62); exploration time repeatable (Log01:S-77, preprint). On the human side, wide individual and cultural
  variation, with most measures WEIRD-biased (HB-S50). **Range for the race:** if CD-7 and CD-4 keep the rabbit
  attention and vigilance package, from members whose attention is dominated by horizon scanning and sound-orienting,
  to others in whom it is milder; individuals differ on a scanning axis (Log01:S-62). The language-capable core
  (15.1) is constant.
- **Handwaves used:** HW-1; pHWC-1 (if CD-2 picks a rabbit-line pace).
- **Confidence:** Derived (15.1); Unresolved (the rest).
- **Canon check:** (1) C-46 and Q-19 (robot mind-design norms) bear on robot-made lineages' charters. (2) No. (3) No.
  (4) No.

---

## 16 · Social instinct (group structure, territoriality, dominance, affiliation, kin recognition) *(behavior-bearing)*

- **Ordinary condition (provisional):** *Open.* The base's social system is a set of **condition-dependent rules**,
  not a fixed form: small territorial breeding groups sharing refuge; separate rank orders in each sex, fought out and
  later ritualized; aggression and dispersal that change with density; female competition over nursery sites
  (Log01:S-82, S-83, S-85, S-86, S-95). Most of those rules hang on mechanisms decided elsewhere: androgen-dependent
  marking and aggression (CD-10), the fear and stress system (CD-4), and rabbit-type nest rearing (CD-3). The human
  side brings flexible multilevel groups, reverse dominance and prestige, and kin detection by co-residence
  (HB-S113, S-118, S-119), much of which runs through culture (L3).
- **Human baseline:** multilevel groups with a layer ratio of ~3–4 (HB-S113); co-residing forager bands ~28 adults,
  mostly unrelated (HB-S114); "~150" contested (HB-S111, S-112); kin detected by watching one's mother care for an
  infant and by childhood co-residence (HB-S118); egalitarianism kept by coalitions against would-be dominants, and
  status by dominance or prestige (HB-S119); territoriality ecology-dependent (HB-S121); either sex may disperse among
  foragers (HB-S114, S-115). Affiliation neurobiology is **not sourced** (HB gap 11).
- **Animal baseline:** groups of 1–5 adult males and 1–8 adult females (Log01:S-85, summarizing); separate linear rank
  orders in each sex, set by fighting and later ritualized (Log01:S-83, S-85, Bayreuth); high rank gives priority
  access and higher fitness (Log01:S-83; Log01:S-90 conflicts on timing); age-graded female hierarchies mean less
  aggression and infanticide (Log01:S-85, S-86). Density changes the system: more groups, smaller territories, and
  female–female aggression from ~0.8/h in two-female groups to ~2.6/h in six-female groups (Log01:S-80, S-85); urban
  groups were far smaller (mean 1.5–4 vs 8.8–10 rural) (Log01:S-42); a sparse population had no warrens (Log01:S-97,
  introduced wild, New Zealand); under terrestrial predators rabbits were mostly alone or in pairs (Log01:S-65, native
  translocated). Dispersal is male-biased on average but variable: 93% of males and 64% of females dispersed in one
  enclosure (Log01:S-91, [SN]); philopatry 18–90% for males and 32–95% for females across Australian populations
  (Log01:S-95). Litter sisters together have more positive interactions and breed ~14 days earlier (Log01:S-88);
  time near mother and littermates lowers stress hormones and parasite loads (Log01:S-85, S-103); lab females work for
  social contact nearly as hard as for food (Log01:S-79, [SN]); juveniles are highly interconnected (Log01:S-98).
  Newcomers are attacked (Log01:S-81). Infanticide by non-mother females hits ~5% of litters, in the first 10 days,
  over nursery burrows (Log01:S-86, S-87). Mothers guard the nursery and answer distress calls (Log01:S-49, S-85).
  **Kin recognition is not demonstrated;** identity and group membership by odor are (Log01:S-34, S-43). Revised
  models: hierarchy in both sexes, not males only; dispersal condition-dependent; "communal rearing" unsupported
  (Log01 §16).
- **Creator intent:** no charter → **CD-3**, **CD-4**, **CD-10**, **CD-13**.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| 16.1 | Group size and territoriality as condition-dependent rules | ecology-dependent (HB-S121); multilevel (HB-S113) | density- and predation-dependent (Log01:S-42, S-65, S-80, S-85) | `UNRESOLVED` | Both baselines are condition-dependent, but neither source names a shared mechanism, so `SHARED*` would overclaim |
| 16.2 | How rank is acquired | reverse dominance and prestige (HB-S119) | sex-separate agonistic rank orders (Log01:S-83, S-85) | `UNRESOLVED` (CD-10, CD-4) | — |
| 16.3 | Androgen-dependent aggression and marking | not in HB | Log01:S-28 (secondary citations) | `UNRESOLVED` (CD-10) | — |
| 16.4 | Dispersal and philopatry rule | either sex (HB-S114) | male-biased, density-dependent (Log01:S-95) | `UNRESOLVED` (proposed RQ) | Only mechanism candidates are sourced (P-13) |
| 16.5 | Kin recognition | co-residence and maternal-perinatal cues (HB-S118) | not demonstrated; odor familiarity (Log01:S-34, S-43, S-88) | `UNRESOLVED` (CD-13; proposed RQ) | Whether the maternal-perinatal cue survives artificial gestation is not stated in canon (Human Baseline setting modifier on C-52); for generation zero, with no birth mother, it has nothing to act on `[derived]` |
| 16.6 | Nursery-site competition and infanticide | none | Log01:S-86 | `UNRESOLVED` (CD-3) | Exists only with rabbit-type nest rearing |
| 16.7 | Affiliation drive and social buffering | not sourced (HB gap 11) | Log01:S-79, S-85, S-103 | `UNRESOLVED` (proposed RQ) | — |
| 16.8 | Response to strangers (newcomer aggression; "dear enemy") | high tolerance of unrelated co-residents (HB-S114) | Log01:S-43, S-81 | `UNRESOLVED` (CD-4, CD-10) | — |
| 16.9 | Who rears young | mother plus allocare (HB-S88) | mother only (Log01:S-99; Log02:S-20, S-31) | `UNRESOLVED` (CD-3) | Coupled to 11.9 |

- **Coherence links:** social instinct ↔ cognition ↔ reproduction and rearing (CM-6); 13; 14; 10.
- **Post-engineering drift `[hazy]`:** *if a lineage keeps the androgen and marking system and lives densely housed*
  (a crowded habitat archetype), the base predicts smaller groups, more female–female agonism, and boundary-weighted
  marking (Log01:S-42, S-80, S-85). Domestication-type selection for low reactivity (HWC-15) would act on 16.8 through
  the stress axis (PI-S75). Pace: per generation.
- **Lineage deltas:** CD-3, CD-4, CD-10 by lineage; lineages differing on these would differ in their social rules
  before any culture is added (L3 sits on top).
- **Individual variance range** (D-7): in the base, philopatry ranges from 18% to 90% (males) and 32% to 95% (females)
  between populations (Log01:S-95); rank and stress vary within groups (Log01:S-83); early contact with mother and
  littermates buffers stress (Log01:S-103); litter sisters change a female's social life (Log01:S-88). On the human
  side, very large cross-cultural variation (HB domain 16). **Range for the race:** from members living in human-style
  multilevel groups ruled mostly by culture, with little scent-mediated rank (if CD-10 and CD-3 go human-type), to
  members whose group membership, rank, and nursery access are partly set by odor and agonism. Even in the base, the
  outcome depends on density and predation.
- **Handwaves used:** HW-1.
- **Confidence:** Sourced (baselines); Unresolved (resolution).
- **Canon check:** (1) C-48 to C-50 (robot kinship: maker/made is not kin; robots lack the genetic basis of
  tribalism) belong to robot-made lineages' inherited stock (L3), not L1. Q-13 (legal status) is downstream. (2) No.
  (3) No. (4) No.

---

## 17 · Health and vulnerabilities (diseases, toxicities, inherited conditions from engineering or founder effects)

- **Ordinary condition (provisional):** *Settled:* the engineered genome carries **design-residue risks** named by
  real hybrid biology: if the imprinting map or immune self-tolerance was imperfect, early generations risk placental
  and fetal growth disorders and autoimmune residue (G-2, G-7; PI-S26, PI-S23). A small or narrow founder group carries
  founder effects (G-8; C-54 precedent), and low immune-gene diversity raised parasite load in a base population
  (Log02:S-74, wild-encl). Canon already records engineered people with epigenetic disorders (C-35). *Open:* which
  rabbit-specific vulnerabilities come with the genes chosen: viral susceptibility, dietary toxins, dental disease,
  heat intolerance, stress-linked gut failure. Each is tied to a charter choice.
- **Human baseline:** vitamin C requirement, high uric acid, lactose malabsorption where lactase doesn't persist
  (HB-S38, S-41, S-42); low back pain the leading cause of years lived with disability (HB-S127), its link to upright
  posture interpretive (HB-S128); myopia (HB-S10); wet-bulb heat limits (HB-S64); hypothermia (HB-S67); altitude
  sickness (HB-S70); G-LOC (HB-S71); microgravity bone loss (HB-S72); difficult birth (HB-S84); dental mismatch
  (HB-S44, S-128).
- **Animal baseline:**
  - *Myxomatosis:* lethal in *Oryctolagus*, mild in its native cottontail hosts (Log02:S-67); resistance evolved
    within decades through polygenic immune change, including IFN-α21A variants (Log02:S-67, wild tested in lab;
    Log02:S-68, museum exomes); still endemic in the native range, 59.9% seropositive (Log02:S-70, wild native, Spain).
    The flea vector can mature its ovaries only on a pregnant doe (Log02:S-75, [SN]).
  - *Rabbit hemorrhagic disease:* GI.1 kills within 1–3 days through necrotizing hepatitis and clotting failure; it
    binds ABH histo-blood-group antigens on mucosa; kittens resist; maternal IgG protects to ~13 weeks (Log02:S-66);
    GI.2 kills the young too (Log02:S-69).
  - *Parasites:* coccidia and nematodes were main mortality causes at Bayreuth (Log02:S-02); hepatic coccidiosis in
    24% of 87 shot wild rabbits (Log02:S-73, [SN]); one MHC allele lowered coccidia only in heterozygotes in a low-MHC
    population (Log02:S-74).
  - *Domestic coordinates only:* dental disease 15.4% a year in UK pets, tied to diet (Log02:S-60, S-63); gut stasis
    4.3% of deaths, with a stress → gut-shutdown → liver chain that rests on veterinary sources (Log02:S-58; #65,
    `[LEAD]`); flystrike the commonest recorded cause of death (Log02:S-58); uterine adenocarcinoma in 13.1% of intact
    females (Log02:S-64); enteritis risk at the weaning switch (Log02:S-84); persin and *Allium* toxicity (Log02:S-79,
    S-80); atropinesterase polymorphism (Log02:S-78); heat stress (Log02:S-81).
- **Creator intent:** no charter → CD-8, CD-9, CD-3, CD-4, CD-6, CD-15, CD-17. Q-29 (whether L1 needs an immunology
  and pathogen domain) is directly relevant.

| # | Mechanism | Human | Rabbit | Tag | Reasoning |
|---|---|---|---|---|---|
| — | Imprinting residue; immune self-tolerance; mitochondrial match; founder load | see G-2, G-7, G-6, G-8 | | (Domain 0) | Not re-counted |
| 17.5 | Susceptibility to rabbit viruses (myxoma host range; RHDV's ABH-antigen binding) | human ABH expression not in HB | Log02:S-66, S-67 | `UNRESOLVED` (CD-17; Q-29) | Depends on which receptor and immune genes the genome carries |
| 17.6 | Ectoparasite coupling to host reproductive hormones (flea) | — | Log02:S-75 ([SN]) | `UNRESOLVED` (proposed RQ) | If rabbit-type pregnancy hormones are kept (CD-3), whether the rabbit flea could breed on a rabbit-person host is untested |
| 17.7 | Dietary toxin sensitivities | vitamin C, uricase (HB-S41, S-42) | persin, *Allium*, atropinesterase (Log02:S-78 to S-80) | `UNRESOLVED` (CD-8) | — |
| 17.8 | Dental disease risk | third-molar variation (HB-S44) | continuous growth needs wear (Log02:S-60, S-63) | `UNRESOLVED` (CD-8) | pHWC-9 |
| 17.9 | Heat intolerance | wet-bulb limits (HB-S64) | Log02:S-81, S-114 | `UNRESOLVED` (CD-9) | The Step 4 conflict in 9 lands here |
| 17.10 | Stress-linked gut stasis | — | Log02:S-58; #65 (`[LEAD]`) | `UNRESOLVED` (CD-4, CD-8) | Low confidence: the physiology chain is veterinary-sourced |
| 17.11 | Hormone-dependent reproductive-tract cancer | — | Log02:S-64, S-65 | `UNRESOLVED` (CD-3) | — |
| 17.12 | Musculoskeletal load of the chosen posture | low back pain (HB-S127) | light skeleton (`[LEAD]`) | `UNRESOLVED` (CD-6; proposed RQ) | — |

- **Coherence links:** every domain; strongest with 7, 9, 10, 14.
- **Post-engineering drift:** *Disease as selection:* the base evolved substantial myxoma resistance within decades
  under very high mortality (Log02:S-67, S-68); if a lineage's genes leave it open to a lethal pathogen, fast
  polygenic resistance is a sourced possibility, in rabbit-people generations (CD-2). *Founder effects:* G-8, with
  canon's closed-pool precedent (C-54).
- **Lineage deltas:** founders (CD-15), receptor and immune genes (CD-17), and gut and teeth (CD-8) per lineage.
- **Individual variance range:** not behavior-bearing. Polymorphic detox (Log02:S-78) and MHC-dependent parasite
  load (Log02:S-74) show individual variance mechanisms in the base.
- **Handwaves used:** HW-1; HWC-2, HWC-5, HWC-6, HWC-8; pHWC-5, pHWC-9, pHWC-10.
- **Confidence:** Derived (design residue); Unresolved (rabbit-specific items).
- **Canon check:** (1) C-35 (engineered people suffer epigenetic disorders) is a precedent for design residue. (2) No.
  (3) **Binds beyond this race:** cross-species disease (humans, livestock, other peoples sharing a settlement) is
  Q-29 and M-6 axis B10. (4) Register through Q-29.

---

## Coherence matrix (M-1 Step 4)

Rows CM-1 to CM-7 are M-1's minimum pairings; CM-8 onward were found in this pass. **Status:** `OK` (agrees, or
biology forces agreement) · `CONFLICT` (with how it was handled: (a) revise or exclude, (b) charter item, (c) known
vulnerability, (d) to the developer) · `pending` (cannot be checked until a charter decision is made).

| # | Domain A | Domain B | Must agree on | Status | Note |
|---|---|---|---|---|---|
| CM-1 | 7 Diet, dentition, digestion | 8 Activity | Feeding pattern and timing | pending (CD-8, CD-11) | If the gut is rabbit-derived: many small meals, mostly in the dark, with soft pellets made in quiet periods (Log02:S-01, S-84). **Fixed coupling either way:** continuously growing teeth need abrasive food (Log02:S-63) |
| CM-2 | 8 Activity | 3 Vision | Light sensitivity | pending (CD-11, CD-7) | Rod-rich retina fits dim-light activity (Log02:S-108); a fovea-dominant eye fits day activity (HB domain 3). A fovea-dominant eye on a night clock has no source; flag if chosen |
| CM-3 | 10 Reproduction | 1 Body mass; 11 Newborn state | Litter size and output against body size; gestation against newborn state | **CONFLICT → (a) + (d)** | Rabbit breeding pace at human-range size is **excluded** (O-5; HWC-10). What remains goes to the developer as CD-2 and CD-3. Still unresearched: multiple births through an upright pelvis (PI Gaps 11; pHWC-3) |
| CM-4 | 11 Maturation | 12 Lifespan; 1 Body mass | Life history scales together | OK as a rule; values pending (CD-2) | Development time predicts lifespan (PI-S48); LQ > ~5 excluded (O-6); size by fast growth predicts faster aging (PI-S57) |
| CM-5 | 13 Communication | 4 Hearing; vocal anatomy | Channels, production, reception | OK (hearing); pending (vocal anatomy, CD-7) | The speech band is audible under either ear (4.2). Production is governed by CM-10 |
| CM-6 | 16 Social instinct | 15 Cognition; 10–11 Rearing | Who raises young shapes groups | pending; **potential CONFLICT → (d)** | A long human-type dependency needs provisioning by others (HB-S87, S-88); the base's mother-only, minutes-a-day nursing (Log02:S-20, S-31) provides none. The rearing choice (CD-3) must match the pace (CD-2) |
| CM-7 | 9 Thermoregulation | 9.1 Body covering; 8 Activity | Heat balance | **CONFLICT → (c) + (d)** | Rabbit-type fur, no functional sweating, and human-range size leave heat loss to ears and panting, whose relative capacity falls with size `[derived]`. Logged as vulnerability 17.9; decision CD-9 |
| CM-8 | 15 Cognition; 11.7 Language window | G-3 Tempo; 11.3 Brain growth | Time to grow a language-capable brain and acquire language | **CONFLICT under a rabbit-line pace → (d)** | Human brain growth runs years (HB-S90) and the grammar window to ~17 years (HB-S122); a rabbit-line pace matures in ~1 year `[derived]`. No source shows compressed acquisition (pHWC-1). Sent to the developer inside CD-2 |
| CM-9 | 15.1 Brain | 7.1 Gut | Energy supply for the brain | pending (CD-8; proposed RQ) | Brain ~20% of resting energy (HB-S45); cecal fermentation ~40% of maintenance in the rabbit (Log02:S-84); pHWC-8 |
| CM-10 | 13.1 Language | 13.2 Voice; 2.2 Hands | Language must have a channel | OK as a constraint | **Excluded (a):** dropping both the human-type speech apparatus and sign-capable hands. At least one must be kept |
| CM-11 | 3.1–3.2 Vision geometry | 4.4 Localization | The ear's job follows the eye | pending (CD-7) | Across species, localization acuity falls as the best-vision field widens (Log01:S-12) |
| CM-12 | 4.3 Outer ear (hearing) | 9.3 Outer ear (heat) | One organ, two jobs | pending (CD-7, CD-9) | The radiator share falls with body size `[derived]` |
| CM-13 | 14 Fear and stress | 10, 16, 17 | Stress spills into breeding, rank, gut | pending (CD-4) | Stress delays nesting and raises kit loss (Log02:S-27); subordinates carry more stress hormone (Log01:S-83); gut-stasis chain `[LEAD]` |
| CM-14 | 5.4 Newborn MP response | 10.15 Nursing; Q-32 route | Newborns must be able to nurse | pending (CD-3, CD-13) | If kept, rearing without a lactating mother must supply the pheromone (pHWC-7) |
| CM-15 | G-5 Placental program | 10.10 Neonatal immunity; 11 Rearing | Passive immunity route | **OK** | Prenatal IgG under either program (PI-S34, PI-S35) |
| CM-16 | G-1 Karyotype | O-1, O-2; Q-15 | Who can breed with whom | **OK** (biology-forced) | Isolation from rabbits certain; from humans unless Q-31 rules a bend; between lineages, by shared design (O-3) |
| CM-17 | 10.11 Litters | 11.8 Sibling effects; D-7 variance | Sources of individual variance | pending (CD-3) | With singletons, one sourced variance mechanism (sibling position and competition; Log02:S-36, S-49) disappears |
| CM-18 | 11.6 Early window | Q-32 route; L0 §6 rearing | Who handles infants during the window | pending (CD-4, CD-13) | Sets which category of beings is non-feared for life (Log01:S-71, S-72) |
| CM-19 | 8.1 Clock | 10.15 Nursing time | Night nursing | pending | Wild does nurse at 01:00–02:00 (Log02:S-32); lab nursing near 03:51 (Log02:S-29) |
| CM-20 | 13.4, 16.3 Androgen-dependent marking and aggression | 1.7 Dimorphism; 16.2 Rank | Sex differences in signaling and agonism | pending (CD-10) | Log01:S-28 (secondary citations); dimorphism direction unresolved (Log02:S-123) |
| CM-21 | 10 Reproductive hormones | 17.6 Vector biology | Parasites keyed to host hormones | pending (proposed RQ) | Log02:S-75 ([SN]) |
| CM-22 | 1.1 Size | 7.2 Cecotrophy | Size rationale | **CONFLICT → (a)** | Obligate cecotrophy at human-range size excluded unless HWC-16 is accepted |
| CM-23 | 10.6 Seasonal gating | 8 Clock; `[hazy]` habitat | Light-cued breeding | pending | 16 h of light abolishes seasonality in domestic does (Log02:S-01) |
| CM-24 | 1.2 Posture | 2.1 Forearm | Whether forelimbs carry weight | pending (CD-6) | A pronation lock has a job only in a quadruped (Log02:S-119) |

---

## M-2 Step C · first pass against this draft

M-2 Step C asks, per mechanism, *"Does this race's resolved physiology keep the mechanism that produces this?"* On
this first pass the answer is a **candidacy** check against the draft, using M-1 tags (M-2 Step C, circularity note).
A blocked or unresolved check is not an absence.

| Log highlight | Mechanism | Candidate for retention? | L1 items | Tag now | Decided by |
|---|---|---|---|---|---|
| Log01 #1 | Horizon-weighted panoramic vision coupled to coarse, orienting hearing | Yes; no input constrains it by size | 3.1, 3.2, 4.4, 15.2 | `UNRESOLVED` | CD-7 |
| Log01 #2 | Fear by heart-slowing and freezing; tonic immobility | Yes; the human comparison is missing (RQ-4 gap) | 14.1, 14.2 | `UNRESOLVED` | CD-4 |
| Log01 #3 | Arousal-gated window that re-categorizes humans, not predators | Yes; interacts with the rearing route | 11.6 | `UNRESOLVED` | CD-4, CD-13 |
| Log01 #4 | Chemical identity and status signals outside the sender's control | Yes; additive (no human mechanism competes) | 13.3, 13.4 | `UNRESOLVED` | CD-10 |
| Log01 #5 | Pheromone-gated one-trial learning; vertical diet-preference transmission | Yes; the newborn part is tied to nursing | 5.4, 5.5, 7.8, 15.5 | `UNRESOLVED` | CD-3, CD-8 |
| Log01 #6 | Sex-separate rank orders; density-dependent aggression and dispersal; nursery competition | Partly; most depends on 13.4, 14, and 10 | 16.2–16.6 | `UNRESOLVED` | CD-3, CD-4, CD-10 |
| Log01 #7 | Audience-modulated expression | Yes | 13.7, 14.6 | `UNRESOLVED` | CD-4 |
| Log01 #8 | Domestication acts on fear circuitry | Informs the stock choice and drift | 14.3 | `UNRESOLVED` | CD-5, CD-16 |
| Log02 #1 | Separable reproductive mechanisms | Induced ovulation: yes, size-free. Rate traits (gestation, litter frequency, nursing economy): **constrained at human scale** | 10.4, 10.11, 10.12, 10.15 | `UNRESOLVED` (rate traits partly excluded) | CD-2, CD-3 |
| Log02 #2 | Hindgut fermentation, cecotrophy, continuously growing teeth | Gut: yes, with redesign. Obligate cecotrophy: **excluded at scale** unless HWC-16. Teeth: yes, with diet coupling | 7.1–7.3 | `UNRESOLVED` | CD-8 |
| Log02 #3 | Nocturnal-type clock vs condition-dependent expressed timing | Yes, separably | 8.1, 8.2 | `UNRESOLVED` | CD-11, CD-4 |
| Log02 #4 | Ear radiators | Yes, but with a falling share at scale | 9.3 | `UNRESOLVED` | CD-7, CD-9 |
| Log02 #5 | Disease synchronized with breeding | Only if the receptor, immune, and hormone genes come along | 17.5, 17.6 | `UNRESOLVED` | CD-3, CD-17 |

M-2 Step C must rerun against the finished L1 once charters exist.

---

## Plausibility check (D-7, binding)

### Outcome-tag count

**Mechanism level** (135 mechanisms; Domain 0 counted once; cross-referenced rows not re-counted):

| Tag | Count | Where |
|---|---:|---|
| `UNRESOLVED` | 121 | every domain |
| `SHARED*` | 8 | G-4, G-9, 3.4, 3.5, 4.2, 5.2, 9.5, 10.10 |
| `ENG-NOVEL*` | 3 | G-1, G-2, G-7 |
| `HUMAN-DOM` | 3 | 11.7, 13.1, 15.1 |
| `ANIMAL-DOM` | 0 | — |
| `BLENDED` | 0 | — |
| `SUPPRESSED-LATENT` | 0 | — (needs a charter that designs a trait out) |

**Domain level:** all 17 domains, and Domain 0, are `UNRESOLVED` overall. Domains with resolved sub-mechanisms: 0
(`ENG-NOVEL*`, `SHARED*`), 3, 4, 5, 9, 10 (`SHARED*`), 11, 13, 15 (`HUMAN-DOM`).

**Behavior-bearing domains** (7, 8, 10, 13, 14, 15, 16): 62 mechanisms; 59 `UNRESOLVED`, 2 `HUMAN-DOM` (13.1, 15.1),
1 `SHARED*` (10.10), 0 `ANIMAL-DOM`, 0 `BLENDED`.

**Biology-forced exclusions recorded** (narrowing without picking): G-3 (organ mosaic of tempos), G-5 (averaged
placenta), G-6 (unmatched mitochondria), 7.2 (obligate cecotrophy at human scale), 10.12 and O-5 (rabbit breeding
pace at human scale; very short gestation with developed newborns), O-6 (lifespan beyond LQ ~5, or long life with fast
maturity), CM-10 (language with no channel), 1.1 (rabbit-scale body).

### The test

- **Fails if every behavior-bearing domain is `HUMAN-DOM`.** None is. **Formal result: PASS.**
- **Large-majority `HUMAN-DOM` review:** not triggered (3 of 135, about 2%). A review note is given anyway, because
  the guard asks that silence never default to human:
  - **13.1 Language capacity** and **15.1 language-capable cognition:** chain = C-7 ("full races"), D-1 (each
    lineage inherits its creators' culture, which requires acquiring a symbolic system), the repo's scope (conscious,
    sentient races), and the fact that the only sourced language mechanism is human (HB-S97, S-101, S-103) while the
    rabbit side offers none (Log01 §13). This is a canon-derived functional requirement, not silence. What it does
    **not** decide: modality (13.2), attention style (15.2), learning period (15.7).
  - **11.7 Language sensitive period:** part of the same mechanism (HB-S124: late first-language exposure causes
    lasting deficits); its duration is left open (CD-2).
- **Silent-default check:** no `HUMAN-DOM` or `ANIMAL-DOM` was assigned from silence. Every place where only a charter
  could decide is `UNRESOLVED`.

### Substantive status: CONDITIONAL

**No behavior-bearing mechanism is yet `ANIMAL-DOM` or `BLENDED`.** Biology, on these inputs, does not force any
rabbit behavior to be kept; it only removes some (the rate-based ones at human scale). So today the animal side in
behavior is guaranteed **only by D-7 itself**, as a developer ruling binding on every race. The formal pass is real
but weak; the meaningful D-7 test moves to the charters.

**What each open behavior-bearing domain could carry, by option:**

| Domain | Animal-side options available (with the charter decision) | If the human-type option is chosen | Legibility to the audience |
|---|---|---|---|
| 7 Diet | Fiber-dependent grazing in many small bouts (CD-8); inherited food preferences from the mother's diet (7.8, usable under either gut); continuously growing teeth that require abrasive food (7.3) | No animal side here unless 7.8 is kept | Medium: eating scenes, food choices |
| 8 Activity | Night clock (CD-11); risk-sensitive shifting of activity timing (8.2, usable under either clock if CD-4 keeps vigilance) | No animal side unless 8.2 is kept | Medium–high: schedules, who is awake |
| 10 Reproduction | Induced ovulation without a cycle; hormone-driven nest-building; brief, infrequent nursing; litters (CD-3), all inside CD-2's pace | None | High, but audience-sensitive; and at human scale biology already mutes the breeding rate (O-5) |
| 13 Communication | Identity and rank odors, chin-marking, latrines (CD-10); tail-flag (CD-6); thumping, distress calls (CD-4); ear postures (CD-7) | Language only | High: visible and audible signals beside speech |
| 14 Emotion | Freezing and heart-slowing under threat, immobility when seized, pain displays suppressed under observation, locomotor play (CD-4); ear stress posture (CD-7) | Human expressive machinery only | **Very high:** read directly in body language |
| 15 Cognition | Horizon-scanning attention and sound-orienting (CD-7); overt and subtle vigilance; inherited-plus-learned predator recognition (CD-4); chemosensory one-trial learning | Human attention style | High: where they look, startle, scan |
| 16 Social | Sex-separate rank orders, density-dependent aggression and dispersal, nursery competition, odor-defined group membership (CD-3, CD-4, CD-10) | Human social structure, run by culture (L3) | Medium: needs group scenes |

**If every charter decision took the human-type option,** all seven behavior-bearing domains would resolve
`HUMAN-DOM` apart from shared items, and the race would **FAIL D-7**. D-7 therefore becomes a constraint on the charter
set: **for each lineage, at least some of CD-3, CD-4, CD-7, CD-8, CD-10, and CD-11 must keep an animal-side option in
a behavior-bearing domain.** How many is the developer's call; `Charter_Decision_Points.md` shows which options do it.

**A biological pattern that matters for D-7.** The animal traits most tied to the base's small body (breeding rate,
obligate cecotrophy, the minutes-a-day nursing economy, ear cooling) are the ones biology removes or weakens at human
scale (O-5, 7.2, pHWC-2, 9.3). The ones **no input constrains by size** are neural and sensory: the fear architecture,
horizon-scanning attention and vigilance, chemical signaling, the early handling window, inherited food preferences,
clock type, and induced ovulation. At human scale, the D-7 animal side will mostly have to come from these. (This is
an absence of sourced constraint, not proof of scalability.)

**Variance (D-7 point 2).** Each behavior-bearing domain records an individual variance range above. Two cautions
carry into the charters: sibling-position effects exist only if litters do (CM-17), and founder diversity (CD-15) sets
how much genetic variance any lineage starts with.

### Handwaves used

| Code | Status | Where |
|---|---|---|
| HW-1 · The splice works | Accepted | All domains |
| HWC-1 to HWC-8 · What the splice must have fixed | Candidates (cost) | Domain 0; 10; 11; 17 |
| HWC-9 · Interfertility with humans | Candidate (bend) | Only if Q-31 rules yes (O-2; CD-12) |
| HWC-10 · Rabbit breeding pace at human size | Candidate (bend), recommended reject | Recorded as excluded (O-5) |
| HWC-11 · Lifespan far above prediction | Candidate (bend), recommended reject | Recorded as excluded (O-6) |
| HWC-12 · Cross-lineage interbreeding | Candidate (bend/cost) | O-3; CD-14 |
| HWC-13 · Life history off the line, inside the envelope | Candidate (cost) | CD-2 options |
| HWC-14 · Size by growth acceleration | Candidate (cost) | 1.1, 12 |
| HWC-15 · Domestication-type drift under creator management | Candidate (cost) | Drift in 10, 11, 14, 16; CD-16 |
| HWC-16 · Cecotrophy at human size | Candidate (bend) | 7.2 (only if kept) |
| pHWC-1 to pHWC-10 | **New, proposed, not registered** | Below |

---

## Proposed handwave candidates (not registered)

**Not entered in `HANDWAVES.md`.** Codes are provisional; the developer rules on each (D-7; `CLAUDE.md` rule 6). Tags
follow the register: **bend** = biology would have to give; **cost** = biology holds, but a mechanism, resource, or
vulnerability must be accepted and shown.

| # | Candidate | Tag | What would be waved | What is NOT waved (must be shown) | Raised in |
|---|---|---|---|---|---|
| pHWC-1 | **Full language acquisition inside a rabbit-line developmental pace** (maturity in about a year) | **bend** | Growing a language-capable brain and acquiring a first language within months | Human data: phonology tuned in year 1, grammar ability high to ~17 years, lasting deficits after late exposure (HB-S122, S-124); brain growth over years (HB-S90). No source supports compression | 11.3, CM-8 |
| pHWC-2 | **The rabbit nursing economy at human scale** (minutes-long nursing of concentrated milk about once a day; weaning triggered by the next pregnancy) | undetermined: cost or bend (proposed RQ) | Delivering a day's milk in minutes to large young | The source synthesis ties it to a small, burrow-nesting body (Log02 highlight 1, [derived]); oxytocin release scales with the number of suckling young (Log02:S-01). Scaling unsourced | 10.15 |
| pHWC-3 | **Multiple births through an upright pelvis** | undetermined (proposed RQ) | Delivering a litter through a biped's birth canal | Maternal size bounds newborn size (PI-S31); obstetric constraint unresearched (PI Gaps 11) | 10.11, CM-3 |
| pHWC-4 | **Postpartum conception with concurrent lactation at human scale** | cost | — | Concurrent pregnancy and lactation already put farm does in negative energy balance (Log02 #16, [SN]); the energy must be shown | 10.7 |
| pHWC-5 | **A furred, low-sweating body at human scale** (cost: heat-limited); or **full fur plus full human sweating on the same skin** (undetermined: the shared gland-to-hair regulator is partly decoupled in human evolution, HB-S61) | cost / undetermined | — | The heat ceiling and its consequences for immunity and embryo survival (Log02:S-01, S-81) | 9.2, CM-7, 17.9 |
| pHWC-6 | **Gestation of about 40–60 days at human-range size with helpless newborns** | cost | — | Sits between Plausibility Inputs' "plausible" floor (~60 days) and its "bend" line (~40 days with developed newborns) (PI §6.4), though it is the rabbit-line scaling prediction itself (PI §6.3). Needs a ruling on the gray zone | 10.12 |
| pHWC-7 | **Pheromone-dependent newborns under artificial gestation or rearing** | cost | — | If the newborn nipple-search response is kept, the mammary pheromone must be supplied wherever no lactating mother is present (Log01:S-19, S-21) | 5.4, CM-14, CD-13 |
| pHWC-8 | **A language-capable brain fueled by hindgut fermentation** | cost (proposed RQ) | — | Brain ~20% of resting energy (HB-S45) against cecal fatty acids ~40% of maintenance in the rabbit (Log02:S-84); diet volume and feeding time must be shown | 7, 15, CM-9 |
| pHWC-9 | **Continuously growing teeth on soft or processed food** | cost | — | Dental disease as a standing vulnerability (Log02:S-60, S-63) | 7.3, 17.8 |
| pHWC-10 | **Rabbit-virus susceptibility carried into the race** | cost | — | Myxoma and RHDV biology (Log02:S-66, S-67); cross-species implications go through Q-29 | 17.5 |

---

## Open items raised by this pass (not registered)

**Charter decisions:** `Charter_Decision_Points.md`, CD-1 to CD-17. Those matching an existing question: CD-1
(Q-9, partly), CD-12 (Q-31), CD-13 (Q-32), CD-14 (Q-15). The rest would need new `Q-` codes on registration.

**Proposed research items** (for `RESEARCH_QUEUE.md`; not added):
1. **Human fear and stress physiology** (freezing, heart-rate responses, stress-hormone axis, startle): a Human
   Baseline supplement. Without it, 14.1–14.4 can't be laid side by side.
2. **Minimum brain for language-capable cognition**, and brain-mass scaling; sets the body-size floor (1.1).
3. **Obstetric constraint for multiple births in an upright pelvis** (PI Gaps 11; pHWC-3).
4. **Skeletal mass scaling** (1.5) and the musculoskeletal load of each posture (17.12).
5. **Rabbit vitamin C synthesis and uricase status** (7.6, 7.7).
6. **Human prenatal flavor learning and vomeronasal status** (5.3, 5.6, 7.8).
7. **Whether high hair density and high eccrine density can coexist** (9.2; HB-S61).
8. **Rabbit vocal-tract anatomy** (13.2).
9. **Rabbit-virus receptor biology in a hybrid genome; rabbit-flea host specificity** (17.5, 17.6; Q-29).
10. **Nursing-economy scaling** (milk delivery rate against body size; pHWC-2).
11. **Substrate-vibration sensing and pinna mobility** (6.3, 4.5).
12. **Small baseline values missing from Human Baseline:** sound-localization threshold, forearm rotation range,
    meal frequency, emesis (4.4, 2.1, 7.4, 7.10).
13. **Sleep architecture on both sides** (8.3).
14. **Rabbit kin recognition versus familiarity** (16.5; Log01 gap 8).

---

## Parameter readiness (for pilot step 4; the sheet is not filled here)

| Parameter | Readable from this L1 now? |
|---|---|
| P-1 Activity cycle | No: CD-11 |
| P-2 Reproduction and rearing | Partly: **founding-generation production mode = an engineered gestation route** (O-8; route is Q-32); everything else waits on CD-2 and CD-3 |
| P-3 Social scale bands | No: CD-3, CD-4, CD-10; RQ-7 also queued |
| P-4 Senses, reach, manipulation | Partly: shared rod and blue-cone vision, speech-band audibility; the rest waits on CD-6 and CD-7 |
| P-5 Maturation, generation, lifespan | No value, but a **sourced envelope** (G-3, O-4 to O-6, 10.12, 12.2) |
| P-6 Life-stage map | No: CD-2 |
| P-7 Diet class | No: CD-8; the cecotrophy exclusion and tooth coupling are readable |
| P-8 Communication | Partly: language is a channel (13.1); its modality and the other channels wait on CD-7 and CD-10 |
| P-9 Environmental tolerances | No: CD-9 |
| P-10 Body plan | No: CD-1, CD-6 (size floor readable) |
| P-11 Mating system | No: CD-3 |
| P-12 Enculturation | Partly: a language sensitive period exists (11.7); an engineered-founder versus born split exists (O-8) |
| P-13 Dispersal | No |
| P-14 Sex differences | Partly: two sexes, XY (G-9); everything else open |
| P-15 Cognitive profile | Partly: language-capable cognition (15.1); every temperament value stays `Unresolved` (rule 3) |

---

## Canon check summary (M-1 Step 7)

- **Canon used:** C-2, C-4, C-7, C-23, C-25, C-30, C-31, C-35, C-46, C-47, C-48 to C-54, C-56, C-57 (idea only).
- **Contradictions found:** none. O-1 and O-2 are consistent with C-7, which never claims interfertility with humans.
- **Binds beyond this race:** Q-31 (human canon, family and romance storylines); Q-15 (every rabbit lineage); Q-9
  (doll mapping, character intake, C-2 and C-4); Q-29 (cross-species disease); generations elapsed before *New
  Centauri* (CD-2 × Q-2 era; C-25).
- **Needs registering back (on the developer's rulings):** Q-9, Q-15, Q-29, Q-31, Q-32 in `DECISIONS.md`; the new
  charter decisions as `Q-` codes; the handwave candidates in `HANDWAVES.md`. Nothing flows to other repos without a
  decision (`CLAUDE.md` rule 8).

---

## Revision history

- **v0.1, 2026-10-21:** first M-1 pass (pilot). Species baseline only; no lineages; no charters. Written alongside
  `Charter_Decision_Points.md` and `methodology-observations/2026-10-21_M-1_Pilot_Rabbit.md`.
