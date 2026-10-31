# Species Parameter Sheet — TEMPLATE (M-0a)

**Copy to:** `races/<Species>/02_Parameter_Sheet.md`
**Status:** Template v0.2, 2026-10-21. P-1 to P-9 are the original set; P-10 to P-15 and the field extensions
were added by D-8.

**What this is:** the plug-in that lets the Inner Tepenia ULM, CST, RWBEM, and HUF run *unchanged* against a
non-human race (`CLAUDE.md` rule 11). Each adapter note in `methods/adapters/` says where each parameter
plugs in.

**Rules:**
- **Every value cites its L1 source item.** A parameter is never filled directly from research. It is read
  off the L1 Physiology & Life History document, which carries the research chain. If L1 doesn't settle a
  value, the value is `Unresolved`, never estimated here.
- **Lineage variance:** if lineages differ (D-1), give the species value and list each lineage's delta.
- **Confidence:** `Sourced` (direct biological data) · `Derived` (reasoned from sourced data, chain shown) ·
  `Charter` (rests on a creator design choice) · `Unresolved`.

---

| Code · Parameter | Value | L1 source | Confidence | Lineage deltas | Feeds |
|---|---|---|---|---|---|
| P-1 · Activity cycle | Diurnal / crepuscular / nocturnal / flexible, plus sleep architecture | | | | ULM Phase 4; CST timing techniques |
| P-2 · Reproduction and rearing | Litter size, cycle type (spontaneous / induced / seasonal), gestation, interbirth interval, who rears young, how kin are recognized. **Adult-equivalent population** (derived with P-6): the social body, not the headcount. **Founding-generation production mode** (by lineage): how the founding cohort was produced (artificial gestation, surrogacy, cloning, other), if different from later generations (HAR-HUF-38) | | | | ULM Phases 2 and 6; HUF kinship items; M-3 |
| P-3 · Social-cognition scale bands | Stable group size, the "everyone is witnessed" threshold, stranger tolerance, territoriality, colonial / solitary / fission-fusion | | | | ULM `01` scale bands; M-6 |
| P-4 · Senses, reach, and manipulation | Each sense's range and acuity; dominant channel; body reach; fine manipulation ability. **Recognition channel:** how individuals recognize each other (sight, scent, voice) | | | | CST §0b player-facing test and Technique 1; ULM Phase 3 |
| P-5 · Maturation, generation, lifespan | Age at maturity, generation time (mean parental age at birth), typical and maximum lifespan | | | | Divergence operator; Acts; CST R5 timing; M-7 |
| P-6 · Life-stage map | The stages that exist, their boundaries, and their markers. **Senescent or post-reproductive stage present?** | | | | ULM Review Panel archetype replacement |
| P-7 · Diet class and constraints | Herbivore / carnivore / omnivore; obligate needs; toxicities; feeding pattern | | | | CST R4; ULM Phase 8 cuisine; M-6 |
| P-8 · Communication channels | Vocal range and anatomy; body signals (ears, tail, posture, face); chemical or scent signals; which channels can carry language. **Signal control:** for each signal, voluntary, involuntary, or trainable | | | | ULM Phase 8 language; future language-repo handoff (Q-12) |
| P-9 · Environmental tolerances | Temperature range, light needs and tolerance, gravity and pressure tolerance, other physiological limits | | | | ULM G2 / spine capability profile (conditional under D-2) |

## Added parameters (D-8, 2026-10-21)
| Code · Parameter | Value | L1 source | Confidence | Lineage deltas | Feeds |
|---|---|---|---|---|---|
| P-10 · Body plan, scale, locomotion, integument | Stature and mass range; posture and locomotion modes; limb and hand form; fur or skin; baseline clothing or adornment need; built-environment needs | | | | ULM Phase 3 architecture, Phase 8 dress and tools, Gate 11 density; CST T1; M-6 axis B7 |
| P-11 · Mating system and pair-bond form | Mating system; seasonal or continuous; ovulation type; whether durable pair bonds exist | | | | ULM Phase 4 private life, Phase 6 kin; Review Panel "Lover" replacement |
| P-12 · Enculturation and transmission mode | Developmental learning windows (re-derived per M-7 Step 5b); acquisition mode (teaching, imitation, innate, engineered); vertical, oblique, or horizontal transmission; language-acquisition window; engineered-founder vs. born cohort split | | | | L3 two-stage mechanism; ULM Phase 7c; DR-11 precedent |
| P-13 · Dispersal and philopatry | Which sex and age leave the natal group, how far; natal-site attachment | | | | ULM Phase 2 arrival modes; migration |
| P-14 · Sex differences and dimorphism | Number of sexes (open for aliens); physical and life-history differences between sexes, each with its mechanism | | | | Division of labor items (M-3); ULM Phase 7 |
| P-15 · Cognitive profile and temperament | Species-level tendencies, **each routed through a cited mechanism, or `Unresolved`** (`CLAUDE.md` rule 3; stereotype risk) | | | | M-3; ULM Phase 4 and 7 |

## Derived values (from M-7)
| Value | Formula / chain | Result | Confidence |
|---|---|---|---|
| Witness span (generations one individual sees) | lifespan ÷ generation time | | |
| Divergence pace (generations per Act) | per M-7 | | |
| Oral-history depth | per M-7 | | |
| Culture-Bearing Weight (D-8) | Adult fraction at steady state × years of adult participation, plus generational overlap with co-resident species | | |
