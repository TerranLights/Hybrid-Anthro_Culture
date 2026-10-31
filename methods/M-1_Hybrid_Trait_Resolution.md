# M-1 · Hybrid Trait Resolution Method (HTRM)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Layer produced:** L1 (Physiology & Life History), plus the values the parameter sheet reads from it.
**Applies to:** any race engineered from two or more biological sources. **Layering:** this file names no race.
Race content lives in `races/`.

## Purpose
An engineered hybrid has several possible sources for every trait, and nothing in the word for the race
says which source wins (`CLAUDE.md` rule 2). HTRM resolves each trait from its sources through a recorded
chain. It then checks that the resolved traits form a body that could actually work, and traces what
generations of natural reproduction did to the engineered starting point.

## Inputs (read in this order, in full, before Step 1)
1. **`CANON.md`:** all entries touching this race, its creators, and the relevant technology.
2. **Every L0 Origin Frame** for this species, one per creator lineage (D-1).
3. **M-2 output:** the base-animal research log. Read the *general* biology before any narrow topic, per
   Mechanic 9 rule 1 (a partial file read as complete is the measured failure mode).
4. **Human baseline (RQ-4):** sourced human values for each domain.
5. **Each lineage's M-4 Design Charter**, where it exists. Where it doesn't, creator intent is `[Q-n]`.
6. **Plausibility inputs:** RQ-5 (hybrid and chimera limits), RQ-6 (body-size scaling), RQ-8 (domestication
   syndrome).

## Procedure

### Step 1 · Lay the sources side by side
For each trait domain (the 17 in `templates/L1_Physiology_TEMPLATE.md`), write the human baseline, the
animal baseline, and each lineage's creator intent **in one place before resolving anything.**
- *Why:* in Inner Tepenia, single-input passes produced generic content and cross-reference synthesis
  produced the best findings. A domain resolved from one source at a time will default to whichever source
  was read last.

### Step 2 · Name the mechanisms
For each baseline trait, name the mechanism that produces it: anatomical, neural, hormonal, developmental,
or learned.
- Resolution operates on mechanisms, not behaviors.
- *Example of the distinction, in the abstract:* a behavior seen in the base animal is inherited only if the
  mechanism behind it is. If it was learned in the animal's ecology, it is not inherited by default at all.
  It becomes a question for L3 (culture), not L1.

### Step 3 · Resolve
Assign each mechanism one outcome and record the reasoning.

| Tag | Meaning | Required justification |
|---|---|---|
| `HUMAN-DOM` | Human mechanism retained | Which source or charter item makes it win |
| `ANIMAL-DOM` | Animal mechanism retained | Same |
| `BLENDED` | Intermediate or combined | **The mechanism of the blend.** "Somewhere in between" is not a mechanism |
| `ENG-NOVEL` | In neither source | **Must cite a Design Charter item.** If no charter exists, this outcome is unavailable: the trait is `UNRESOLVED`, and the question goes to the developer |
| `SUPPRESSED-LATENT` | Designed out, but the genetic basis persists | What suppresses it, and what could release it (feeds Step 5) |
| `UNRESOLVED` | The sources don't settle it | Log a `Q-` (developer decision) or an `RQ-` (missing research). **This is a valid result** (`CLAUDE.md` rule 4) |

**Default rule when creator intent is silent:** none. Do not assume the human or the animal mechanism wins.
Silence is `UNRESOLVED`, unless real biology itself constrains the outcome. For example, RQ-5 might show
a combination can't develop, or RQ-6 might show body size forces a value. In that case the outcome cites that
biology.

### Step 4 · Coherence check
Biology comes in linked sets. Resolved traits must agree with each other. Fill in the L1 coherence matrix.
Minimum required pairings:
- **Diet ↔ dentition and digestion ↔ activity cycle** (feeding pattern)
- **Activity cycle ↔ vision** (light sensitivity)
- **Reproduction ↔ maternal anatomy ↔ body mass ↔ neonatal state** (litter size against body size; RQ-6)
- **Maturation ↔ lifespan ↔ body mass** (life history scales together; RQ-6, M-7)
- **Communication channels ↔ vocal anatomy ↔ hearing range**
- **Social instinct ↔ cognition ↔ reproduction and rearing** (who raises young shapes group structure)
- **Thermoregulation ↔ body covering ↔ activity cycle**

**Each conflict must be resolved by one of:**
- (a) revising a resolution, with the reason recorded;
- (b) citing a Design Charter item that engineered around it (this then binds the charter);
- (c) logging it as a known vulnerability in domain 17;
- (d) sending it to the developer as a `Q-`.

Never leave a conflict silently standing.

### Step 5 · Post-engineering drift
After creation the race reproduced naturally (canon). For each domain, trace:
- **Founder effect:** from the founding population size and diversity in the L0 Origin Frame.
- **Relaxed selection:** engineered features that natural reproduction no longer maintains.
- **Reversion:** `SUPPRESSED-LATENT` traits that may resurface.
- **New selection:** pressures from the race's conditions. **Under D-2 these are `[hazy]` archetypes only,
  written conditionally:** "if the habitat is X, selection favors…".
- **Domestication-syndrome effects** (RQ-8), if a lineage was reared under creator management.

**Pace:** generations from P-5 / M-7, never raw years. Record direction and mechanism. Give magnitude only
when it is sourced.

### Step 6 · Lineage deltas
Where creator lineages made different choices, record the difference against the species baseline.
- If lineages interbreed (Q-15), trace how the deltas blend or sort over generations. This is Step 5 again,
  applied to admixture.
- If they don't interbreed, the "species" may in practice be two or more peoples sharing an animal base.
  Flag this for the developer; don't decide it.

### Step 7 · Canon check
Run the four-question check (`CLAUDE.md` rule 7) on each domain's resolution. Anything that binds beyond this
race is flagged.

### Step 8 · Write out
- Write the L1 document from `templates/L1_Physiology_TEMPLATE.md`. Write the ordinary-condition summary last.
- Fill in the parameter sheet from L1, never directly from research.

## Guards
- **Never infer from the word** (`CLAUDE.md` rule 2). A fantasy or folk image of the animal is not an animal
  baseline. Only M-2 research is.
- **Pop ethology is not a source.** Popular models that researchers have since revised are logged in M-2 as
  dead ends, not used.
- **The plausibility standard (D-7, binding).** "A humanized lizard, never a California college student."
  - **The animal side always remains in behavior.** If every behavior-bearing domain resolves `HUMAN-DOM`,
    the resolution **fails D-7** and must be reopened, however well each trait was argued. The
    behavior-bearing domains are 7 (diet), 8 (activity), 10 (reproduction), 13 (communication), 14 (emotion
    expression), 15 (cognition), and 16 (social instinct).
  - **Count the tags anyway.** If the large majority are `HUMAN-DOM`, write a review note showing each one's
    justification. Silence must never have defaulted to human.
  - **Record variance.** Each behavior-bearing domain states an **individual variance range**: how much, and
    which, animal expression varies between individuals and lineages. A single point is not enough.
  - **Handwaves:** any resolution that needs one cites a `HANDWAVES.md` entry. A trait that would need a
    fantastical handwave is `UNRESOLVED` and goes to the developer.
- **No creator essentialism** (`CLAUDE.md` rule 3). A lineage's creator type changes L1 only through a cited
  Design Charter item.
- **Never compare races during a pass** (`CLAUDE.md` rule 10).

## Open method questions
- Is the 17-domain list complete? Revise after the pilot.
- How should Step 6 handle a collaboration lineage whose creators disagreed on a trait? Tentatively, the
  charter records the conflict and the outcome (M-4), and HTRM resolves against the outcome.
