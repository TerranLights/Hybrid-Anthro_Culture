# M-3 · Species Universals Differentiation (SUD)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Layer produced:** L2 (Species Universals), written as a "*[Race]* Universals" volume.
**Applies to:** every race. **Layering:** this file names no race.

**Builds on:**
- the Human Universals Culture Framework (HUF) Part 2, `InnerTepeniaGDD/Neo-Races-and-Cultures/_Method/Human_Universals_Culture_Framework.md`;
- its polished robot application, `TepenianUniverseTimeline/Reference/Robot_Universals/` (Parts II and IV).

SUD reuses HUF's procedure and adds the two outcome types a biological, engineered race needs.

## ⛔ Do not inherit: robot verdicts
The HUF and Robot Universals state their robot verdicts confidently and in general terms, so it is easy to
pick one up out of habit. Several were reached *because robots have no biology*:
- parental investment "has zero referent";
- kinship;
- sexual jealousy;
- maker/made;
- innate drives.

**None of them is a default here.** The full list, with sources, is `HAR_HUF.md` Part B (the entries marked
"do not copy" in `source_reference/Universals_Checklist.md`). Read it before Step 1.

## Purpose
SUD sets the **floor**: what is true of every population of this race, whichever lineage, era, or (later)
place. It also hands everything that is free to vary to the Differentiation Engine, for L3 and L4 to work with.

## Inputs
1. **`source_reference/Universals_Checklist.md`:** the itemized universals (`U-` codes), with each item's
   biology-dependence flag.
2. **The race's L1 document,** read in full first (Mechanic 9). Every root-cause check is against L1, never
   against the name of the race.
3. **The race's parameter sheet.**
4. **HUF Part 2 and Brown's explanatory modes,** as summarized in the HUF and the Extraction.
4a. **The book itself, not only the notes** (developer direction, 2026-10-21). Brown, *Human Universals*
    (1991), is at `InnerTepeniaGDD/Reference/Materials/books/Human Universals - Donald E Brown [1991].pdf`.
    It is an image-only scan, so read it page by page. PDF page = printed page + 9 from Ch. 1 onward (+10 only for
    the front matter and Introduction).
    - Two sets of notes: the existing Extraction covers Ch. 2, 4, 6, and 7, and
      `source_reference/Brown_Supplementary_Extraction.md` covers Ch. 1, 3, and 5 plus the book's
      biology-and-animals passages.
    - When Step 3 or Step 4 turns on an item's root cause, **go back to Brown's own pages for that item**, not
      only the paraphrase. A summary can blur the cause.
    - The Universals volume cites Brown by printed page.
    - Paraphrase and short quotes only.
5. **The Human-Assumptions Register entry for HUF** (`methods/adapters/Human_Assumptions_Register/HAR_HUF.md`).

## Procedure

### Step 1 · Triage each checklist item
For each `U-` item, decide which of four outcomes applies. These come from Inner Tepenia's Local Robot
Culture Methodology, and they keep "checked and found nothing" separate from "never applied."
- `YES`: applies; continue to Step 2.
- `NULL`: checked, and nothing species-specific results. **This is a result.**
- `N/A`: the item's precondition doesn't exist for this race.
- `UNCERTAIN`: L1 doesn't settle it. Log the gap (`Q-` or `RQ-`).

### Step 2 · Essence vs. accident
Is the universal rooted in something essential, which any population with this cause will show? Or is it an
accident of human circumstance?

### Step 3 · Find the root cause
Using Brown's explanatory modes, name *why* humans show this universal.

### Step 4 · Root-cause check against L1
Does this race have the **cause**, not just a surface resemblance? Cite the L1 domain. This step is where most
of the outcomes are decided.

### Step 5 · Classify
| Outcome | Meaning | Origin |
|---|---|---|
| `DIRECT` | Transfers unchanged | HUF |
| `ANALOG` | A structural analog: the same function, built on different biology | HUF |
| `NON-TRANSFER` | The cause is absent, so the universal doesn't hold | HUF |
| `NEW` | A universal this race has that humans don't, arising from its own conditions | HUF |
| `ANIMAL-INHERITED` | **New.** A species-wide pattern whose root cause is an `ANIMAL-DOM` or `BLENDED` mechanism in L1 | SUD |
| `ENGINEERED` | **New.** A species-wide pattern installed by creator design (cites a Design Charter item via L1) | SUD |

**Do not copy robot verdicts.** For robots, genetics, kinship, and parental investment were `NON-TRANSFER`,
because robots have no genetic relatedness. A biological race that reproduces naturally has those causes
back, on different biology. Every item is re-derived from this race's L1.

### Step 6 · Discovery pass (what Brown's list can't contain)
Brown catalogs *human* universals, so a checklist built from Brown can't surface an animal-side pattern humans
lack. Walk every L1 domain tagged `ANIMAL-DOM`, `BLENDED`, `ENG-NOVEL`, or `SUPPRESSED-LATENT`, and ask: *does
this mechanism produce a species-wide social or cultural pattern?* Each yes becomes a `NEW`,
`ANIMAL-INHERITED`, or `ENGINEERED` universal with its own code (`U-<race>-nn`).

### Step 7 · Lineage test
A universal belongs on the **species** floor only if it holds for **every** creator lineage (D-1). If it holds
for some lineages and not others, it is **lineage-level**. It moves to that lineage's L3 material, not L2.

### Step 8 · Formal vs. substantive sort
- **Formal / process** survivors (the *that*) go on the floor, L2.
- **Substantive** survivors (the *how*) are free to vary. They go to the Differentiation Engine: condition,
  then variation, then the universal pool (Robot Universals ch. 18).
- Under D-2, the engine's conditions are lineage, era, and `[hazy]` habitat archetype only. Specific places
  wait for L4.

### Step 9 · Honesty check (Robot Universals ch. 18, both directions)
- No variation gets explained by "because they're X" (`CLAUDE.md` rule 3).
- Where a universal genuinely produces no variation, say so. Don't manufacture difference.

## Output: the "*[Race]* Universals" volume
`races/<Species>/04_Universals/`, following the Robot Universals shape:
- **Part I · Fundamentals:** a summary of L1 and L0 (by lineage), pointing to those files, not copying them.
- **Part II · Differentiation:** chapters on where this race departs from human experience. Every
  `NON-TRANSFER`, `ANALOG`, `ANIMAL-INHERITED`, and `ENGINEERED` item, grouped by theme.
- **Part III · Cultural Universals:** the positive floor content, organized by topic.
- **Part IV · Applying:** the Differentiation Engine conditions for this race, plus worked examples. Worked
  examples are deferred until there is real material to work on (D-2).
- **Appendix:** the full checklist table with each item's triage, root cause, L1 citation, and outcome.

## Guards
- **Over-convergence:** if most substantive items come out `DIRECT`, review whether Step 4 really checked
  causes against L1, or matched on surface resemblance. This is the "humans with ears" alarm again.
- **Never compare races during a pass** (`CLAUDE.md` rule 10). The shared Anthro floor is consolidated
  *afterward*, from finished volumes.
