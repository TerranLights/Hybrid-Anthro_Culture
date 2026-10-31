# Standing rules for this repo

## What this repo is
The shared workshop for developing cultures of conscious, sentient, **biological, non-human, non-robot**
races across the Tepenian Multiverse: anthros (dog-, cat-, rabbit-people, more to come), elves, orcs, and
aliens. They appear in *Outer Tepenia: New Centauri* (Outer Tepenia 3) and *Elven Steel*. Robots are out of
scope because they have their own floor in `TepenianUniverseTimeline/Reference/Robot_Universals/`.

`TepenianUniverseTimeline` is the cross-project canon authority. This repo is the working shop.

## Read first, every session
1. `MASTER_PLAN.md`: the architecture (five layers, L0–L4), the methods (M-0 to M-7), and the phase sequence.
2. `DECISIONS.md`: developer rulings. **D-1** (anthro creators are A, H, and/or R, so origin is per
   lineage) and **D-2** (locations hazy only) reshape almost everything.
3. `OPEN_QUESTIONS.md`: what is blocked, and on what.
4. `CANON.md`: existing canon from other repos, with sources.

## Rules
1. **Derive, don't invent.** Every trait has a recorded chain back to its sources: human biology, base-animal
   biology, creator intent, environment, or a developer ruling. A trait with no chain doesn't go in. A gap is
   logged as a `Q-`, never filled with a guess.
2. **Never infer physiology from the word.** "Elf" does not imply long life, "cat" does not imply aloofness,
   and "orc" does not imply aggression. The race's own physiology document is the only authority. Folk
   images, fantasy conventions, and pop ethology are not sources.
3. **Condition, never essentialism.** This extends the universe-wide law "a population's origin names its
   ancestry, never its identity" (`Tepenian_Universe_Overview.md`, C-60). "X-people do this because they're
   X" is never an answer. A documented
   biological mechanism *plus* a concrete condition can be. Creator type (D-1) is a condition too: it acts
   through a design charter or an inherited stock, never as an essence. Species-level tendencies route
   through mechanisms, never through character stereotypes.
4. **No forced fit.** A null is a result. If a universal produces no species-level difference, say so plainly.
5. **LAW 0 and LAW 0-R** (from Inner Tepenia, binding on all worldbuilding):
   - Depth over speed.
   - Research fully, with no search budget.
   - Verify biology against primary or scholarly sources, and query from more than one angle.
   - Log dead ends.
   - A recalled biological fact is a guess.
   - Selective quotes and paraphrase only, never bulk reproduction of a source.
6. **Status discipline.** Everything is `Proposed:` until the developer accepts it, and acceptance is logged
   in `DECISIONS.md`. Revise through history, never by silent overwrite.
7. **Canon is federated.** Before writing any trait, run the four-question check:
   1. Does canon already answer this?
   2. Does this contradict canon?
   3. Does this bind anything beyond this race?
   4. Does this need registering back?

   Canon lives in `TepenianUniverseTimeline`, the game GDDs, and sibling repos, none of which are visible to a
   local search of this repo.
8. **Nothing flows out without a decision.** Do not edit `TepenianUniverseTimeline`, any game GDD, *Elven
   Steel*, or the Inner Tepenia methods from here without an explicit developer go-ahead. Findings that
   affect those go to the developer as proposals.
9. **Hazy locations only (D-2).**
   - Environments are generic archetypes, tagged `[hazy]` and written conditionally.
   - Never invent a planet, settlement, climate, or geography.
   - No L4 population passes until worlds exist.
10. **One race on its own terms.** Don't develop one race by contrast with another during a pass. Comparing
    them is a check on the finished corpus, never a way to generate content.
11. **Parameterize, don't fork** (provisional, Q-8). The Inner Tepenia ULM, CST, RWBEM, and HUF are used in
    place, through `methods/adapters/` and each race's parameter sheet. Don't copy them into this repo.
12. **Name items two ways.** Each item gets a short code plus a plain descriptive name, and both are cited
    together:
    - `C-` canon, `D-` decision, `Q-` question, `RQ-` research item
    - `M-` method, `P-` parameter, `L-` layer, `U-` universal
    - `HAR-` human-assumption entry, `CL-` creator lineage
13. **American English** for all prose.
14. **The plausibility standard (D-7): "a humanized lizard, never a California college student."**
    - Every hybrid race keeps *some* of its animal side in how it **behaves**, with believable variance.
    - Human culture reaches a race only *through its body* (Embodiment Fit), never worn whole.
    - Handwaves are allowed only within plausibility. Each one is logged in `HANDWAVES.md` with what is and
      isn't waved; a fantastical handwave is rejected.
    - Among plausible options, prefer the one the audience can *read*.

## Key external paths
- Inner Tepenia methods: `/home/kuroskalacs/Documents/Doll-Fi/media/games/Inner Tepenia/InnerTepeniaGDD/`
  - ULM: `Worldspace/Locations-and-Levels/Universal_Location_Methodology/`
  - CST: `Worldspace/Locations-and-Levels/Cultural_Synthesis_Techniques.md`
  - RWBEM: `Worldspace/Locations-and-Levels/Real-World_Basis_Extrapolation_Method.md`
  - HUF: `Neo-Races-and-Cultures/_Method/Human_Universals_Culture_Framework.md` (and `Human_Universals_Extraction.md`)
- Canon: `/home/kuroskalacs/Documents/Doll-Fi/media/Reference/TepenianUniverseTimeline/`
  (`Reference/Doll_Representation_Categories.md`, `Reference/Robot_Universals/`)
- Archive for retired material: `/home/kuroskalacs/Documents/Doll-Fi/media/w-other/ArchiveVault/`
  (archive rather than delete; confirm first).
