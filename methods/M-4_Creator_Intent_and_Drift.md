# M-4 · Creator Intent & Drift Analysis (CIDA)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Layer produced:** for each creator lineage, a Design Charter and a Drift Ledger. These feed L1 (via M-1)
and L3.
**Applies to:** every race that was *made*. That means anthros (D-1: Aliens, Humans, and/or Robots), elves
(aliens, per canon), and any future engineered race. Runs **once per creator lineage.**
**Layering:** this file names no race.

## Purpose
A made race's starting point was chosen by someone. That choice works the way the Fundamental Laws work for
robots, or the founding generator (G4) works for a ULM location. CIDA structures what the creators intended
and how that intent held up. **Almost all of it is developer decision.** CIDA's job is to ask the right
questions in the right order, and to show the downstream consequences of each possible answer. It doesn't
answer them.

## Inputs
- The lineage's L0 Origin Frame (`templates/L0_Origin_Frame_TEMPLATE.md`).
- `CANON.md`.
- **The creators' own culture sources, by creator type:**
  - **H:** human culture. The Inner Tepenia city corpus and its successors, where the lineage descends from it
    (`MASTER_PLAN.md` §10).
  - **R:** the robot meta-culture, `TepenianUniverseTimeline/Reference/Robot_Universals/`, including
    the Fundamental Laws (ch. 1) and reproduction and kinship (ch. 8).
  - **A:** undeveloped (Q-6). Recorded as an explicit unknown, never filled.

## Part 1 · The Design Charter (what the creators intended)

| § | Field | Question to the developer | Consequence note (what each answer changes) |
|---|---|---|---|
| 1 | Purpose | Why was this lineage made? | Sets which traits were designed in (§3), the status (§5), and the rearing plan (§6) |
| 2 | Intended niche `[hazy]` | For what environment or role were they made? | Sets environmental tolerances (P-9) and selection after release (M-1 step 5) |
| 3 | Designed in | Which traits were deliberately chosen, and from which source? | These become `HUMAN-DOM`, `ANIMAL-DOM`, or `ENG-NOVEL` outcomes in M-1, with a citation |
| 4 | Designed out | Which human or animal traits were deliberately removed? | These become `SUPPRESSED-LATENT` or removed in M-1. Latent ones can resurface (M-1 step 5) |
| 5 | Status assigned | Property, ward, citizen, something else? (Q-13) | Shapes L3's relation-to-creator material, and any legal canon |
| 6 | Rearing plan | Immersion in creator society, a managed facility, or other? | **The main L3 hinge.** It decides whether the inherited stock is the creators' full culture or a thin institutional one |
| 7 | Reproduction plan | Designed to reproduce naturally? Controlled? Sterile, then later changed? | Sets how natural reproduction began (canon says it happened), and whether that was intended or against design |
| 8 | Controls and safeguards | Any built-in limits, dependencies, or behavioral constraints? | A biological analog to the robot Fundamental Laws, if one exists. **Never assume one exists** |
| 9 | Creator self-image | How did the creators see what they made: tool, child, kin, art, experiment? | Feeds L3 (inherited attitudes) and the drift ledger |

**Collaboration lineages (A+H, A+R, H+R, A+H+R):** for every field, record *which creator* set it, and
**where creators disagreed**. Disagreements are valuable: a charter with an internal contradiction designed
into it is a real source of later drift. Don't smooth it over.

**Creator-specific questions** (asked, never assumed):
- **R-made:** How do the Fundamental Laws bear on robots creating sentient biological life (Q-19)? What does
  a population with no genetic relatedness (Robot Universals ch. 8; C-49, C-50) bring to making genetic
  offspring? Three existing robot creation norms are relevant, and their application to anthros is **not**
  canon. Ask about each:
  - the Laws as a safeguard built into how robots make robots (C-45);
  - minds "only ever partially specced, by law" (C-46);
  - "maker/made is not kinship" (C-48).
  Robots also outlive many anthro generations (C-51), which matters for the Drift Ledger.
  *These are open seams to examine, not conclusions.*
- **A-made:** Where did the Earth genetic material come from (Q-17)? Is anything about alien intent knowable
  in-world, or only to the developer (Q-6)?
- **H-made:** Which human society, and which era's ethics and law, governed the program?

## Part 2 · The Drift Ledger (how the intent held up)

Give every charter item one verdict:

| Verdict | Meaning |
|---|---|
| `HELD` | Still true of the race |
| `ERODED` | Weakened over generations |
| `INVERTED` | Now the opposite of the design |
| `ABANDONED` | The creators dropped it |
| `OUTGROWN` | The race itself rejected or replaced it |
| `UNKNOWN` | Not yet decided or derivable |

Each verdict cites a **mechanism**:
- **Biological drift:** M-1 step 5 (relaxed selection, reversion, founder effects).
- **Cultural drift:** L3 divergence, with pace from M-7.
- **Event:** **developer-decided only.** CIDA never invents a revolt, an exodus, or a falling-out.

## Outputs
`races/<Species>/lineages/CL-<nn>_<Name>/03_Design_Charter_and_Drift.md`, containing Part 1 and Part 2, with
a status tag on every field (`[D-]`, `[C-]`, `[Q-]`, `[Proposed]`, `[hazy]`).

## Guards
- **Ask, don't decide** (`CLAUDE.md` rules 1 and 8). Consequence notes describe effects. They don't recommend
  canon unless the developer asks.
- **No creator essentialism** (rule 3). "Aliens would naturally…" or "robots would obviously…" is never
  reasoning. Charter answers come from the developer or canon, and their consequences come from mechanisms.
- **Thematic parallels are optional.** Several possible parallels exist, such as robots made by humans and later
  exiled, now making something themselves. CIDA may note them for the developer, but they never steer an
  answer.
