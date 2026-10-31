# M-5 · Xenobiology First-Principles Method (XFP)

**Status:** Proposed draft v0.1, 2026-10-21. Expected to need several revisions. Not yet piloted.
**Layer produced:** L1 for races with no Earth-animal base, in the same document format as M-1, so M-3 runs
unchanged afterward.
**Applies to:** aliens (origin unknown, per canon). Possibly orcs (Q-1) or elves (Q-5), depending on rulings.
**Layering:** this file names no race.

## Purpose
With no real animal to research, biology has to be derived from the conditions a race evolved under. XFP is a
chain: each link is built only from the links before it, and each claim carries a grounding tier. That way
nothing speculative passes as researched.

## Sources
- Real system data: `source_reference/Alpha_Centauri_System.md` (RQ-9; D-6)
- Method arguments, with their strength: `source_reference/Xenobiology_Method_Sources.md` (RQ-10)

## Grounding tiers (every claim carries one)
| Tier | Meaning |
|---|---|
| `GROUNDED` | Real, sourced data (astronomy, physics, chemistry) |
| `INFERRED` | Reasoned from comparative biology or physics, with the chain shown and sources cited |
| `SPECULATIVE` | No firm basis; a labeled choice. **Speculative claims go to the developer as options, not conclusions** |
| `RULED` | A developer decision (`D-`) |

## Step 0 · Origin questions (to the developer, Q-6)
- Is there a private internal origin answer, even if it stays "unknown" in-world?
- Is the race native to the environment where it appears, or did it come from elsewhere?
- If it came from elsewhere, steps 1–2 describe an **unknown** home environment. The chain then runs on
  `[hazy]` archetype branches (Step 2), and the output is conditional throughout.

## The chain

### Step 1 · Stellar environment
For a real star system, use real data (RQ-9): spectral type, luminosity, flare activity, the spectrum
available to life, and habitable-zone distance.
- **Tier:** `GROUNDED`.
- **Constraint:** current observational status is cited with its date, because exoplanet knowledge changes.

### Step 2 · Planetary environment `[hazy]`
D-2 forbids inventing worlds. So unless the developer rules otherwise, Step 2 sets up **archetype branches**
(for example, a tidally locked rocky planet, or a planet that is not tidally locked), each bounded by Step 1
data. Every later step runs **per branch**, or the developer picks a branch.
- **Tier:** `INFERRED` or `SPECULATIVE`. Never `GROUNDED` unless the planet's properties are actually measured.

### Step 3 · Biochemistry baseline
- **Default:** carbon chemistry in liquid water, as the best-supported assumption (cite the astrobiology
  basis, RQ-10).
- Any departure is `RULED` or `SPECULATIVE`.
- Record the knock-on constraints: temperature range, and atmosphere needs.

### Step 4 · Body plan
From gravity, atmospheric density, and the environment's physical demands, work out:
- size limits;
- support and locomotion options;
- manipulation (sentience plus technology implies manipulators of some kind; state why).

Use convergent-evolution arguments with cited examples, and say plainly how strong each argument is.

### Step 5 · Senses
From what signals the environment offers (the light spectrum from Step 1, the acoustic medium from Step 2, the
chemical medium), work out the likely sensory channels and their ranges. **The human sensory set is not the
default.**

### Step 6 · Life history
From environmental stability and hazards, work out:
- the mortality schedule (adult vs. juvenile mortality, how variable it is, and how strongly the population
  is density-regulated). The older "r/K" framing is
  outdated and is not used; see `source_reference/Xenobiology_Method_Sources.md` (XB-S34);
- lifespan and maturation;
- reproductive mode.

This feeds M-7 directly.

### Step 7 · Cognition and sociality
From Steps 4–6:
- what drove intelligence (cite the comparative-cognition hypotheses used);
- social structure options;
- communication channels.

**This step carries the most uncertainty.** Expect `SPECULATIVE` options here, to go to the developer.

### Step 8 · Hand-off
- Write L1 from `templates/L1_Physiology_TEMPLATE.md`, using the `FIRST-PRINCIPLES` tag plus a grounding tier
  per domain.
- Fill in the parameter sheet.
- M-3 then runs unchanged.
- **Note for M-3:** checklist items marked biology-independent ("formal/process") are the *candidates* most
  likely to transfer to any sentient social species. Even so, each still gets the Step 4 root-cause check.
  Nothing transfers by default.

## Interfaces
- **If aliens made anthros or elves (D-1, canon):** the alien creators' culture is the inherited stock for
  those lineages (M-4, L3). XFP's output is therefore an input to other races' L3. Until XFP runs, that stock is
  an explicit unknown.
- **Q-17 (Earth genetic material in alien hands)** binds the timeline. XFP doesn't resolve it; it is a canon
  question.

## Guards
- **No pop-culture aliens.** Familiar fictional alien designs are not sources. If one is used as a reference,
  it is named as a stylistic reference, never as reasoning.
- **No world invention** (D-2). Branches, not a planet.
- **Every claim is tiered.** A claim with no tier doesn't go in.
