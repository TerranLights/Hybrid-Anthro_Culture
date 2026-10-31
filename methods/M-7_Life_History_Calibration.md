# M-7 · Life-History Calibration (LHC)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Produces:** parameter sheet values P-3, P-5, and P-6, plus the derived values (witness span, divergence pace,
oral-history depth).
**Applies to:** every race. **Layering:** this file names no race.

## Purpose
Several Inner Tepenia method elements quietly assume a human life cycle:
- the divergence operator and its "Acts";
- "after enough generations";
- the Review Panel's human life stages;
- human-sized social groups.

M-7 converts a race's L1 life history into the values those elements need. It also shows what changes when a
generation lasts 3 years instead of 25 or 200.

**Precedent:** the ULM already adjusted for robots, noting that "a given individual spans more of the
divergence" (`00_RUNBOOK.md` §C.9d, "For robots specifically"). M-7 generalizes that adjustment.

## Inputs
- L1 domains 10–12 (reproduction, development, lifespan) and 16 (social instinct).
- RQ-6 (body-size scaling). **Feedback to M-1:** if the resolved body size makes a resolved life history
  implausible, that is an M-1 coherence conflict (step 4). Send it back; don't patch it here.
- RQ-7 (social-group size and cognition).

## Procedure

### Step 1 · Generation time (→ P-5)
Generation time is **mean parental age at birth of offspring**, not age at maturity. Work it out from:
- age at first reproduction;
- reproductive span;
- birth or litter schedule;
- survivorship, where sourced.

Show the chain. If inputs are `Charter` or `UNRESOLVED`, the result carries that status.

### Step 2 · Convert time to generations
Inner Tepenia's binding rule is never to reason from elapsed time. Any span of years, when relevant, is
converted to **generations** for this race, and divergence is reasoned in generations.
- The same century is a very different amount of cultural change for different races.
- **State that difference.** Don't flatten it.

### Step 3 · Witness span (derived)
Witness span is **lifespan ÷ generation time**: how many generations one individual lives alongside.
- It drives how much of the divergence any one person sees.
- It also sets how much elder knowledge overlaps between generations.

### Step 4 · Oral-history and memory depth (derived)
From witness span plus the communication channels (L1 domain 13), estimate how many generations back
first-hand and second-hand memory reach. This feeds the L3 inherited-stock analysis: how faithfully the
creators' culture passes down.

### Step 5 · Life-stage map (→ P-6)
From L1 domain 11, list the stages that actually exist, their boundaries, and how each is socially marked or
recognized.
- This **replaces** the Review Panel's human archetypes (Maiden, Crone, Child, Parent, Elder; King, Warrior,
  Magician, Lover) for this race. It doesn't relabel them.
- If a race has stages humans lack, or lacks stages humans have, the panel changes shape accordingly.

### Step 5b · Developmental windows (→ P-12)
Re-derive each human developmental window that a method or Brown relies on, using this race's maturation
timeline. Never carry over the human figure. The standing example is the co-rearing window for incest
avoidance, roughly the first six years in humans (Brown pp. 120–123). Others are language acquisition and
the critical periods in L1 domain 11.

### Step 6 · Social scale bands (→ P-3)
From L1 domain 16 and RQ-7, work out:
- stable group size;
- the "everyone is witnessed" threshold;
- stranger tolerance and territoriality.

These **replace** the ULM's ~30 / ~500 / ~50k bands for this race. Each band records its basis and confidence.
If a basis is thin, say so; don't calibrate to false precision.

### Step 7 · Divergence pace and Acts (derived)
Express the Inner Tepenia Act structure in this race's generations. If lineages differ in P-5, compute this per
lineage.

### Step 8 · Culture-Bearing Weight and composition bands (derived; D-8)
- **Culture-Bearing Weight.** From P-2 and P-5, compute three things:
  - the adult fraction of a steady-state population;
  - the years of adult participation per individual;
  - the generational overlap with any co-resident race.

  This converts a headcount share into a share of cultural transmission, which CST's R1–R7 need.
- **Per-race R5 bands.** Restate CST R5's thresholds as **absolute adult counts relative to this race's P-3
  band**, with a growth note driven by P-2 fecundity (M-6 Mode B rule 7). Until these exist, R5 is
  "human-calibrated, unverified" for this race.
- **Sector-share benchmark.** If the ULM's `00b` general-population benchmark is needed for this race (L4,
  deferred), re-derive it from the adult-equivalent population (P-2), not from human working-age shares.

## Output
Values written into `races/<Species>/02_Parameter_Sheet.md` (P-3, P-5, P-6, and the derived table), each
citing L1.

## Guards
- **No sharper numbers than the sources support.** A range with its basis beats a falsely exact number.
- **Body size is not destiny.** Allometry (RQ-6) informs plausibility. Engineered or charter values can
  override it, but the override must be recorded as `Charter`, and M-1's coherence check must accept it.
