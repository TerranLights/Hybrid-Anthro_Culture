# Methodology Observations — M-1 Pilot Run (Rabbit-People), 2026-10-21

**Status:** observations and **proposals only.** Nothing in `methods/`, `HANDWAVES.md`, `OPEN_QUESTIONS.md`, or
`RESEARCH_QUEUE.md` was edited. Each proposal needs a developer decision (`CLAUDE.md` rule 6).
**Run:** the first real pass of M-1 (Hybrid Trait Resolution) v0.1 with `templates/L1_Physiology_TEMPLATE.md`, for the
rabbit-people species baseline, with **no lineages and no Design Charters** (Q-14 open).
**Outputs:** `races/Rabbit/01_Physiology_and_Life_History.md` (L1 v0.1) and `races/Rabbit/Charter_Decision_Points.md`.
**Codes used here:** `MO-n` = an observation in this file.

---

## Summary

1. **Before any charter exists, M-1 mostly produces `UNRESOLVED`, and that is correct:** 121 of 135 mechanisms. The
   run's real products were things M-1 doesn't name as outputs: a list of **biology-forced outcomes and exclusions**,
   a set of **couplings** (traits that must move together), and a **list of charter decisions** for the developer.
   M-1 should name and template these (MO-1, MO-3).
2. **The tag set is missing two things:** a tag for mechanisms both sources share (MO-2), and a way to record that
   biology *narrowed* the options without picking one (MO-3).
3. **The D-7 check is toothless before charters.** An all-`UNRESOLVED` draft passes it formally. D-7 needs a third
   verdict (`CONDITIONAL`) and a route into M-4 (MO-10).
4. **The template needs a Domain 0** for genome-wide single settings (karyotype, imprinting, tempo, placenta,
   mitochondria, immune self-tolerance, sex determination), which cut across many domains (MO-7).
5. **Body size and developmental tempo are upstream variables that M-1 never sequences.** The pilot found **tempo
   matters far more than size** for life history (MO-11).
6. **Human Baseline gaps blocked Step 1 exactly where D-7 matters most:** there is no human fear or stress physiology
   to set beside the rabbit's (MO-19).

---

## What worked

- **"Silence is `UNRESOLVED`" (Step 3's no-default rule)** did its job. It stopped silent human-defaulting and made
  visible a real finding: at this stage, the animal side in behavior is **entirely** charter-dependent; biology forces
  none of it (L1 D-7 section).
- **Resolving on mechanisms, not behaviors (Step 2)** kept the work honest. Where two baselines had a similar surface
  with different mechanisms (pain display under observation: learned display rules in humans, unknown mechanism in
  rabbits; group vigilance: chronotype spread in humans, dedicated vigilance modes in rabbits), the mechanism rule
  stopped a false match.
- **Laying all sources side by side first (Step 1)** surfaced the cross-domain findings: the cognition-versus-tempo
  conflict (CM-8), the brain-energy-versus-diet question (CM-9), and the language-channel constraint (CM-10). None was
  visible from one source at a time, as the Inner Tepenia precedent predicted.
- **The coherence check (Step 4)** was the most productive step. Twenty-four pairings were filled; four conflicts were
  resolved by excluding combinations and one was logged as a vulnerability.
- **The inputs were strong.** The M-2 logs' "mechanism highlights" sections were nearly ready-made Step 2 inputs. Their
  "variation is data" discipline (recording wild versus domestic and population differences without averaging)
  directly fed the variance ranges. Plausibility Inputs' worked allometry table and the HWC register gave Step 3 its
  only real biology constraints. RWBEM's hypothesis that lower tiers are often the most valuable held again: almost
  all mechanisms came from lab, farm, and introduced populations.
- **The canon four-question check (Step 7)** surfaced every binding-beyond-race item without strain: Q-9, Q-15, Q-29,
  Q-31, and generations before *New Centauri*.

---

## Observations: what broke, was missing, or was ambiguous

### Outputs and run modes

**MO-1 · M-1 has no pre-charter run mode, and no name for its most useful pre-charter output.**
- *Evidence:* 121 of 135 mechanisms are `UNRESOLVED`. Every useful result was either a biology-forced outcome
  (O-1 to O-9 in L1 Domain 0), an exclusion, a coupling, or a decision for the developer (CD-1 to CD-17). M-1 Step 3
  routes all developer questions to "log a `Q-`", which would have produced 17 bare questions with no option analysis.
- *Proposal:* define two run modes. A **pre-charter pass** produces (a) biology-forced outcomes, (b) exclusions and
  couplings, and (c) a **Charter Decision Points** document (questions, options, downstream effects, D-7 effect,
  lineage variability) that feeds the L0 questionnaire and M-4. A **post-charter pass** then resolves against the
  charters. Add a template for (c), modeled on the pilot file.

**MO-28 · The run order puts M-4 before M-1, but M-4 needs M-1's option analysis to ask good questions.**
- *Evidence:* M-4's Design Charter table asks "Which traits were deliberately chosen?" (§3) without saying which
  traits are open, which are excluded, and what each choice costs. The pilot's CD list is that missing input.
- *Proposal:* run order **M-1 pre-pass → L0/M-4 per lineage → M-1 full pass**. Update the diagram in
  `00_Method_Index.md`.

**MO-17 · Step 8 says to fill the parameter sheet; pre-charter, almost nothing can be filled.**
- *Proposal:* allow a **parameter readiness table** as the pre-charter Step 8 output (the L1 has one).

### The outcome tags

**MO-2 · No tag for a mechanism both sources share.**
- *Evidence:* eight cases: rod pigment (~498 nm in both), the short-wave cone class, speech-band audibility, the main
  olfactory system, brown-fat thermogenesis, the hemochorial placental family, prenatal IgG transfer, and two-sex
  XY determination. Tagging these `HUMAN-DOM` or `ANIMAL-DOM` would misstate the chain, since neither source "won".
- *Proposal:* add **`SHARED`**: both baselines have the mechanism; no resolution needed; still subject to a charter
  designing it out. The pilot used `SHARED*` provisionally.

**MO-3 · `UNRESOLVED` loses the information that biology narrowed the options.**
- *Evidence:* gestation (10.12) is `UNRESOLVED`, but biology excludes the rabbit's 30 days at human size and anything
  under ~40 days with developed newborns. The tag alone hides that. The same goes for cecotrophy (7.2), tempo (G-3),
  placenta (G-5), mitochondria (G-6), and the language channel (CM-10).
- *Proposal:* a mandatory **"Excluded by biology"** column in each mechanism table (the pilot added one in the
  reasoning text), plus a **"Biology-forced outcomes"** list for results that aren't mechanisms (reproductive
  isolation, the life-history package). Optionally, a tag modifier, `UNRESOLVED (constrained)`.

**MO-4 · `ENG-NOVEL` requires a lineage Design Charter item, but some engineered necessities come from canon.**
- *Evidence:* the unified karyotype (G-1), the coherent imprinting map (G-2), and immune self-tolerance (G-7) are
  required by C-7 (natural reproduction) plus HW-1 (accepted), with no lineage charter. Strictly read, M-1 makes them
  `UNRESOLVED`, which is wrong: they are certain, only their design is open.
- *Proposal:* allow **species-level authority** for `ENG-NOVEL`: canon (`C-`), a developer ruling (`D-`), or an
  accepted handwave (`HW-`), marked as such. The pilot used `ENG-NOVEL*`.

**MO-5 · No rule for functional requirements derived from canon.**
- *Evidence:* language capacity (13.1) and language-capable cognition (15.1) are `HUMAN-DOM`. That's not because a
  charter chose human, but because canon requires the function (C-7 "full races"; D-1 culture inheritance) and the
  human mechanism is the only sourced one. M-1's `HUMAN-DOM` justification ("which source or charter item makes it
  win") doesn't name this route, and the guard against silent human-defaulting makes it look suspicious.
- *Proposal:* add a justification type: **"canon or ruling requires the function; only one sourced mechanism
  provides it."** It must cite both halves, and it should trigger a research item for alternatives (here: whether a
  smaller or non-human brain could be language-capable).

**MO-6 · "Which source wins" doesn't fit additive mechanisms.**
- *Evidence:* vibrissae, scent glands, the nest-building drive, ear radiators, and tail signals have **no human
  counterpart**, so the question is presence or absence, not which mechanism wins. "`ANIMAL-DOM`" would mean
  "present", but the tag reads as if a human mechanism was displaced.
- *Proposal:* Step 3 should first classify each mechanism as **competing** (both sources have a version) or
  **additive** (one source only), and use `PRESENT` / `ABSENT` (or `ANIMAL-DOM` / `SUPPRESSED-LATENT`) language for
  additive ones.

**MO-9 · Tags are per mechanism (Step 3), but the template and the D-7 guard count per domain.**
- *Evidence:* domain 13 has one `HUMAN-DOM` mechanism and nine `UNRESOLVED`. The template gives no aggregation rule.
- *Proposal:* count at **both** levels, as the pilot did, and define the domain tag (for example, `UNRESOLVED` if any
  behavior-defining mechanism is unresolved; otherwise the majority tag, with the distribution shown).

### The D-7 check

**MO-10 · The D-7 check passes formally on an all-`UNRESOLVED` draft, so it tests nothing before charters exist.**
- *Evidence:* the pilot's verdict is a formal PASS, with no behavior-bearing mechanism `ANIMAL-DOM` or `BLENDED`. The
  animal side is guaranteed only by D-7 itself.
- *Proposal:*
  1. A three-state verdict: **PASS / FAIL / CONDITIONAL.** CONDITIONAL means it passes formally while the animal side
     rests on open charter decisions.
  2. The pre-charter pass exports a **D-7 option table** (which charter options keep animal behavior, and how legible
     each is) into the Charter Decision Points file.
  3. M-4 adds a field: **"Behavior-bearing animal mechanisms this charter keeps,"** checked against a D-7 floor.
  4. The developer sets the floor (for example, at least N behavior-bearing domains, with at least one readable on
     screen). D-7 says "some" without a number.

**MO-23 · Domain 11 holds behavioral development but isn't on the behavior-bearing list.**
- *Evidence:* the early handling window that sets lifelong fear categories (11.6) and the language sensitive period
  (11.7) are behavioral mechanisms filed in domain 11.
- *Proposal:* add 11 to the behavior-bearing list, or move the developmental windows into 14 and 15 with a
  cross-reference.

**MO-15 · The variance requirement asks for a range, but the *sources* of variance depend on charter choices.**
- *Evidence:* sibling-position effects exist only if litters do (CM-17); genetic variance depends on founders (CD-15);
  condition-dependent plasticity depends on which mechanisms are kept.
- *Proposal:* the template asks for **variance sources, and which charter choices remove them**, not only a range.

### Template structure

**MO-7 · The template has no place for genome-wide single settings.**
- *Evidence:* karyotype, imprinting, tempo, placenta, mitochondria, immune self-tolerance, founders, and sex
  determination each bind several domains (PI §5.7). Filing each under one domain would hide its reach; repeating it
  everywhere would inflate the counts.
- *Proposal:* add **Domain 0 · Genome architecture and developmental program**, resolved once and cross-referenced.

**MO-8 · The 17-domain list is incomplete.** This answers M-1's own open question.
- *Missing or homeless in this run:*
  - **integument** (P-10 has it; the domain list doesn't; the pilot used 9);
  - **fear, defense, and anti-predator behavior** (both M-2 logs had cross-domain sections; the pilot split them
    across 8, 14, and 15);
  - **play** (a cross-domain section in Log 01);
  - **immunology and pathogens** (Q-29 already asks this);
  - **sex determination and number of sexes** (a P-14 sub-field with no domain);
  - **elimination and latrine behavior** (both a signal and a hygiene matter);
  - **enculturation and developmental windows** (P-12, implicit in 11 and 15);
  - **body scale** (buried in domain 1, but upstream of everything; MO-11).
- *Proposal:* revise the list after the cat and dog pilots, but at least add Domain 0, an immunology domain (Q-29),
  and a defense and anti-predator domain.

**MO-16 · A single "ordinary condition" statement doesn't fit a pre-charter domain.**
- *Proposal:* split it into **Settled** (by biology, canon, or ruling) and **Open** (with the deciding CD). The pilot did
  this and it read cleanly.

**MO-13 · Per-domain drift fields are mostly repetitive before charters.**
- *Evidence:* founder size (L0), generation time (P-5), and environment (D-2, `[hazy]`) are all unavailable, so drift
  is direction-only almost everywhere. That is correct under Step 5's rule, but repetitive.
- *Proposal:* one **drift section** (founders, relaxed selection, reversion, domestication-type effects, `[hazy]`
  selection archetypes), plus per-domain notes only where a domain-specific mechanism is sourced (for example, the
  myxomatosis resistance precedent in 17, or reversion of domestic fear alleles in 14).

**MO-14 · Step 6 (lineage deltas) can't run, but charter choices that *would* create deltas can be named.**
- *Proposal:* rename the field **"Delta-generating charter choices"** for pre-charter passes. The pilot found such
  choices useful: the stock choice creates timing and fear deltas; the infancy handling window creates
  rearing-dependent deltas; a human-scaffold lineage creates a fertility and isolation delta.

### Sequencing

**MO-11 · Body size and developmental tempo are upstream variables M-1 never sequences.**
- *Evidence:* Step 3's example ("RQ-6 might show body size forces a value") presumes size is known, but here size is
  itself a charter decision (CD-1). Worked through, the allometry gives a further finding: across 30–80 kg, the
  rabbit-line predictions barely move (gestation ~40–64 days, maximum lifespan ~20–27 years, conception to maturity
  ~0.8–1.1 years). **Developmental tempo, a genome-wide single setting (PI-S32), decides life history far more than
  size does.**
- *Proposal:* add **Step 0 · Upstream variables:** fix, or explicitly branch on, (a) adult scale and (b) developmental
  tempo before domain resolution. Permit a declared **"worked branch"** (the pilot used CD-1 option A) so consequences
  can be stated without pretending the branch is resolved.

**MO-12 · Step 4's conflict-resolution options don't fit a pre-charter pass.**
- *Evidence:* option (b), citing a charter item, is impossible; most conflicts were resolved by *excluding a
  combination* (rabbit breeding pace at human size; obligate cecotrophy at human size; language with no channel).
- *Proposal:* add **(e) record the combination as excluded, with the biology, and send the remaining option space to
  the developer.**

**MO-27 · Minimum coherence pairings: five more earned a place.**
- *Evidence:* the most consequential pairings found were not on M-1's minimum list:
  - cognition ↔ developmental tempo (CM-8: the language window against a fast pace);
  - brain energy ↔ diet (CM-9);
  - language ↔ voice ↔ hands (CM-10);
  - early-window development ↔ the generation-zero rearing route (CM-18);
  - karyotype ↔ lineage structure (CM-16).
- *Proposal:* add these five to the minimum list.

### Rules and guards

**MO-21 · The line between "a mechanism measured in domestic animals" and "a domestic trait" needs a rule in M-1.**
- *Evidence:* M-2's sequencing rule treats domestic and lab data as mechanism-only until a charter names the stock.
  But some mechanisms differ between wild and domestic rabbits: nursing timing (Log02:S-32), fear-circuit volumes
  (Log01:S-68), taste-bud counts (Log01:S-30). The mechanism itself is stock-dependent.
- *Proposal:* when wild and domestic data differ for a mechanism, M-1 records **both** and routes the choice to the
  stock decision (here, CD-5), instead of using either as "the" mechanism.

**MO-22 · Some sourced behaviors have no identified mechanism.**
- *Evidence:* risk-sensitive shifting of activity timing (Log02:S-103), density-dependent dispersal switching
  (Log01:S-95), and audience suppression of the pain face (Log01:S-52) are well documented, but their neural or
  hormonal mechanism isn't.
- *Proposal:* Step 2 states explicitly that a behavior with an unidentified mechanism is resolved as **"mechanism
  unidentified"** → `UNRESOLVED` plus an `RQ-`, and may still be offered to the charter as a package (as the pilot did
  with the vigilance package, CD-4).

**MO-25 · Rule 2 ("never infer from the word") correctly makes even ears and tail charter items, but M-4 doesn't ask
for them.**
- *Evidence:* M-4 §3 ("Designed in") is generic. Every visible feature of the race (ears, eyes, tail, fur, posture)
  ended up as a CD item.
- *Proposal:* M-4 §3 gets sub-prompts mirroring the CD list (body scale, tempo, body plan, head and senses, integument,
  gut, reproduction, fear system, signaling, clock), each with a link to the Charter Decision Points file.

**MO-26 · Not exercised:** M-1's open question about collaboration lineages whose creators disagreed. No lineages
existed.

### Citation mechanics

**MO-18 · Both M-2 logs number their sources from S-01, so codes collide.**
- *Evidence:* "S-02" is a Bayreuth fear-and-vision source in Log 01 and the Bayreuth life-history paper in Log 02. The
  pilot had to prefix every citation (`Log01:S-46`, `Log02:S-02`).
- *Proposal:* M-2 Step F gives each log a unique prefix (for example `R1-S01`, `R2-S01`) or continues one numbering
  across a race's logs.

**MO-30 · Readability.** The L1 is long (about 130 KB) because it carries 135 mechanism rows with full chains. That is
right for an authority document, but the developer needs the Charter Decision Points file as the readable entry point.
- *Proposal:* the L1 template's summary keeps a **"Settled / decided by you"** split (as the pilot's does), and the
  CD file becomes a standard companion.

---

## Input-file observations (they blocked or limited steps)

**MO-19 · Human Baseline (RQ-4) gaps, in order of D-7 importance:**
1. **Fear and stress physiology** (freezing, heart-rate responses to threat, the stress-hormone axis, startle): the
   core of domain 14 has no human column.
2. **Affiliation and pair-bond neurobiology** (HB gap 11): domains 10 and 16.
3. **Prenatal flavor learning; vomeronasal status:** domains 5 and 7.
4. **Sleep architecture** (HB gap 2): domain 8.
5. **Vestibular and proprioceptive systems** (HB gap 1): domain 6.
6. **Small values:** sound-localization threshold, forearm rotation range, meal frequency, emesis, brain mass (the
   pilot had to derive ~1.2 kg from 2% of 62 kg).
- *Proposal:* an RQ-4 supplement, fear physiology first.

**MO-20 · A gray zone in Plausibility Inputs.** The rabbit-line gestation prediction for a 65 kg body (43–61 days,
PI §6.3) falls partly **below** PI §6.4's "plausible" floor (~60 days) while staying **above** its "bend" line
(~40 days with developed newborns). Is a scaling prediction for the base lineage plausible by definition, or not?
- *Proposal:* reconcile §6.3 and §6.4. The pilot logged this as pHWC-6.

**MO-29 · Plausibility Inputs Gap 11 (obstetric constraint) turned out to be load-bearing.** Any lineage that keeps
litters at human size runs into it (pHWC-3). It is worth promoting to a queued `RQ-`.

---

## Consolidated proposals (for the developer; none applied)

| # | Proposal | Touches |
|---|---|---|
| P1 | Pre-charter and post-charter run modes; Charter Decision Points as a named M-1 output with a template | M-1, templates, Method Index |
| P2 | Run order: M-1 pre-pass → L0/M-4 → M-1 full pass | Method Index |
| P3 | New tag `SHARED`; an "Excluded by biology" column; a "Biology-forced outcomes" list | M-1 Step 3, L1 template |
| P4 | `ENG-NOVEL` may cite species-level authority (C-, D-, accepted HW-) | M-1 Step 3 |
| P5 | Justification type: canon-required function with one sourced mechanism | M-1 Step 3 |
| P6 | Competing vs additive mechanisms; presence language for additive ones | M-1 Step 3 |
| P7 | Count tags at mechanism and domain level; a domain-tag rule | M-1 guards, L1 template |
| P8 | D-7 verdict PASS / FAIL / CONDITIONAL; D-7 option table; an M-4 "kept animal mechanisms" field; a developer-set floor | M-1 guards, M-4, L1 template |
| P9 | Domain 11 behavior-bearing (or move its windows) | M-1 guards |
| P10 | Variance *sources* and what removes them | L1 template |
| P11 | Domain 0; immunology domain; defense and anti-predator domain; integument placement | L1 template |
| P12 | Settled / Open split for ordinary conditions | L1 template |
| P13 | One drift section plus domain-specific notes | L1 template |
| P14 | "Delta-generating charter choices" field | L1 template, M-1 Step 6 |
| P15 | Step 0: upstream variables (scale, tempo) and a declared worked branch | M-1 |
| P16 | Step 4 option (e): exclude the combination | M-1 Step 4 |
| P17 | Five new minimum coherence pairings | M-1 Step 4 |
| P18 | Wild-vs-domestic mechanism differences route to the stock decision | M-1 Step 2 |
| P19 | "Mechanism unidentified" rule | M-1 Step 2 |
| P20 | M-4 §3 sub-prompts mirroring the CD list | M-4 |
| P21 | Log-unique S-code prefixes | M-2 Step F |
| P22 | RQ-4 supplement (fear physiology first) | RESEARCH_QUEUE |
| P23 | Reconcile PI §6.3 and §6.4; promote PI Gap 11 to an RQ | Plausibility Inputs, RESEARCH_QUEUE |
