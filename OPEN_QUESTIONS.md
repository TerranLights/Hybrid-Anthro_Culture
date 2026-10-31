# Open Questions

Questions only the developer can answer. Each has a short code (`Q-`) and a plain name. When one is
answered, record the ruling in `DECISIONS.md` and mark it here as answered, with the `D-` code. Don't delete
answered questions.

**Status key:**
- **Blocking:** work in that area can't proceed.
- **Partly answered:** some of it is settled; the rest is still open.
- **Deferred (D-2):** waits on worlds that don't exist yet.
- **Non-blocking:** can be answered whenever.

---

## Blocking

| Code · Name | Question | Status | Blocks |
|---|---|---|---|
| Q-1 · Orc category | Orcs aren't in `Doll_Representation_Categories.md`. Are they a 5th category, alien-engineered like elves, an anthro-type splice, or something else? | Blocking | Orcs entirely |
| Q-2 · Anthro origin events | D-1 settled *who* (A, H, and/or R). Still open: for each lineage, *when* (era relative to Outer Tepenia 1–2), *where* (hazy is fine), and **why**. | Partly answered (D-1) | L0 and M-4 for each lineage |
| Q-4 · Base-animal selection (**rabbit: answered, D-4**) | Dog: wolf, generic domestic dog, or specific breed groups? Cat: domestic *Felis catus*, or its wild ancestor *F. lybica*? Rabbit: *Oryctolagus cuniculus*, the only domesticated rabbit (proposed default)? Could different creator lineages have used different bases? | Rabbit answered (D-4); dog and cat still blocking | M-2 Step A for each species |
| Q-5 · Elf base stock | What did the aliens engineer elves *from*: parallel-Earth humans, another species, or something original? Are those aliens the same aliens as the Centauri ones, or the same as any anthro-making aliens? | Blocking | Elves; whether elves use M-1 or M-5 |
| Q-6 · Alien origin, internal answer | "Origin unknown" in-world. Do you want a private internal answer for consistency? Are the aliens native to the Centauri system? | Blocking | Aliens (M-5) |
| Q-14 · Lineage map (**partly answered, D-5**) | For each anthro species, which creator lineages exist? For example, is there one rabbit-people lineage made by H+R, or several independent rabbit-people lineages (one alien-made, one robot-made…)? D-5: multiple lineages are very likely. Still open: which ones, for each species. | Partly answered; the pilot uses placeholder lineages | L0 structure for every anthro species |
| Q-15 · Cross-lineage compatibility | Where a species has several lineages, can they interbreed? Are they one species with lineage-level variation, or distinct peoples that share an animal base? | Blocking (D-5 says multiple lineages are likely) | L1 baseline-plus-deltas structure, M-1 step 5. **Biology input (HWC-12):** lineages can plausibly interbreed only if they share one genome design, such as co-designed or built from a shared template. Otherwise expect partial or total isolation |
| Q-17 · Alien access to Earth DNA | Dogs, cats, and rabbits are Earth animals. Alien-made anthros imply aliens had Earth animal and human genetic material, which implies contact with Earth or its colonies. Is that intended, and when did that contact happen? | Blocking for alien-made lineages; it also binds the timeline | L0 for A-lineages, timeline canon |

## Partly answered or deferred

| Code · Name | Question | Status |
|---|---|---|
| Q-3 · Anthro arrival at Centauri | How and when do anthros reach the Alpha/Proxima Centauri system? Were they created there or brought there? (Hazy answers are fine.) **Canon constraint (C-24):** no interstellar travel, or any hint of it, before Outer Tepenia 2. | Open; detail deferred (D-2) |
| Q-10 · Centauri composition | Which populations share the Centauri settings (humans, robots, which races), and in what proportions? | Deferred (D-2) |
| Q-11 · *Elven Steel* and the multiverse | Canon intake found that *Elven Steel* is a sci-fi, Gaelic-language web TV series set on the parallel Earth (C-11), with an earlier, nearly empty short-story folder, *Shardfall* (C-13). Still open: its era, and whether the parallel Earth falls under `TepenianUniverseTimeline`'s authority. The timeline says "Universe," this repo says "Multiverse," and *Elven Steel* isn't on the timeline's project list (C-12, X-6). How do elves reach Centauri (X-7)? Because *Elven Steel* is a TV series, CST's player-facing test (§0b), which assumes an interactive CRPG, needs a non-interactive variant for it (`HAR_CST.md` note 4). | Open |

## Non-blocking

| Code · Name | Question |
|---|---|
| Q-7 · Repo scope | Should L4 population catalogs live here, or in each game's repo (the Robot Universals precedent)? Should finished Universals volumes move to `TepenianUniverseTimeline/Reference/`? |
| Q-8 · Fork vs. parameterize | Confirm "parameterize, don't fork" (`MASTER_PLAN.md` §4). It is being used provisionally (D-3). |
| Q-9 · Doll constraint | Every Dolliverse character is based on a real doll. Does a real doll's form constrain anthro or elf body plans (for example, a humanoid range), and how much? |
| Q-12 · Language handoff | Should anthro and elf languages go through `slang-synthesis` / `TepenianHawaiian`-style derivation repos, or be handled here? |
| Q-13 · Legal status | Do anthros have a legal framework analogous to the Fundamental Laws of Robotics (property, citizenship, protected class)? May differ by creator lineage. |
| Q-16 · Other origins | D-1 says anthros were "mostly" made by A, H, or R. What are the other cases: anthros engineering new anthros, accidents, escaped or unsanctioned programs, something else? |
| Q-18 · Update the categories canon | `Doll_Representation_Categories.md` still says anthros were "genetically engineered by humans." Update it to reflect D-1? (Needs your go-ahead, `CLAUDE.md` rule 8.) |
| Q-19 · Robots as makers of biological life | Canon supports robots doing genetic science (C-27 Ariun Nuur, C-28 Charlene XT-17), but nothing states robots create biological *sentients* (C-44). Should a canon note be added? Separately, do the robot norms on making minds apply to anthros robots make? Those norms are: the Fundamental Laws as a creation safeguard (C-45); minds "only ever partially specced, by law" (C-46); maker/made is not kinship (C-48). |
| Q-20 · Selandriel Lumorndaer | The 2023 *Shardfall* folder ties an elf-styled character name to a real doll (C-15). Is she a confirmed Category 3 (elf) character? If so, `Doll_Representation_Categories.md`'s "no characters assigned" is out of date (X-2). |
| Q-21 · The ElsaBabe premise | An unadopted idea-list premise has a pharmaceutical company secretly making human/animal hybrids, based on the ElsaBabe "anthro" doll line (C-8). Adopt it as an H-lineage seed, keep it as an idea, or drop it? It also bears on Q-9 (a real doll line as the anthro basis). |
| Q-22 · Uploaded minds as creators | Earthtech's leaders are uploaded human minds in android bodies (C-40). If such beings ever create anthros, do they count as H, R, or something else under D-1? |

## Raised by the Human-Assumptions Register (2026-10-21)

| Code · Name | Question | Status |
|---|---|---|
| Q-23 · Accept the consolidated parameters (**answered, D-8**) | Add P-10 to P-15 and the field extensions in `methods/adapters/Human_Assumptions_Register/README.md` to the parameter-sheet template? The adapter notes (M-0b) wait on this. | Answered (D-8) |
| Q-24 · Heritable divergence within a species | May peoples of one species diverge **biologically** (heritably) between settlements, and how fast? Short-generation races could, in real biology. Brown allows biology to explain differences between populations, but this repo's no-stereotype rule makes a silent default either way a design decision. (HAR-HUF-24) | Non-blocking until L4 |
| Q-25 · The elapsed-time ban vs. M-7 | Proposed reading: Inner Tepenia's "never reason from elapsed time" bans deriving outcomes from a year count ("after 250 years, X"). M-7 converting years into generations and witness depth is compatible with that, and M-7 must never produce "after N years, X." Confirm or overrule. (HAR-CST-08) | Non-blocking |
| Q-26 · D-2 and the real Centauri system (**answered, D-6**) | D-2 rules out inventing worlds. May M-5 research the **real** Alpha Centauri / Proxima system (published astronomy), as long as it builds no specific planet? Or should the whole system stay unexamined for now? | Answered (D-6): research it |
| Q-27 · Findings about the Inner Tepenia methods | The sweep found things that would need Inner Tepenia rulings or fixes, not adapters here. Do you want these filed in the InnerTepeniaGDD repo, held here, or ignored for now? (Nothing has been edited there.) The findings: 11 notes in `HAR_ULM.md`; that the ULM copy of CST drops Zodiac Lens step 7 (the per-hit contradiction check) and carries a stale pin; that CST R5's thresholds cite no source; and whether Embodiment Fit should join the divergence operator. Also: `source_reference/Brown_Supplementary_Extraction.md` ends with merge-back notes for the Inner Tepenia `Human_Universals_Extraction.md`. They cover a page-offset error, a swapped kin mechanism, an inverted smell example, and other misstatements found against the actual book. | Non-blocking |
| Q-28 · Robot symbol systems on biological races | CST's Zodiac cross-check prompts from robot symbol systems. For a biological race, is that allowed as a pure designer prompt, or should it be replaced? (`HAR_CST.md` note 5) | Deferred to Phase 7 |
| Q-31 · Can anthros breed with humans? | Real biology says no: humans and the base animals diverged tens of millions of years ago, and mammal hybrids stop working after a few million (HWC-9). The only plausible route is a lineage deliberately built on a human chromosome scaffold, and even then expect reduced fertility. Do you want human–anthro offspring to be possible for any lineage? It decides a Design Charter item, and bears on romance and family storylines. | Blocking for the M-4 charters |
| Q-32 · How was generation zero gestated? | The first generation can't be carried by an unmodified human or animal mother (immune rejection; size mismatch). Was it an artificial womb, an engineered surrogate, or something else, per lineage (HWC-7)? Artificial wombs are already established Tepenian tech (C-52). | Blocking for the M-4 charters |
| Q-30 · Real human cultures as inherited stock | For an H-lineage, the creators' culture is that lineage's starting stock (L3). Should RWBEM (researching real human places) ever supply that stock? The default in `methods/adapters/RWBEM_Adapter.md` is **no**: the stock comes from the in-universe human culture of the creators (the Inner Tepenia lineage and its successors). The one exception is when an L0 Origin Frame names a real-world-derived creator culture. Confirm or overrule. | Non-blocking |
| Q-29 · An immunology domain | M-6's candidate axis B10 (cross-species disease transmission) needs an immunology and pathogen domain in M-1's L1 template, which it doesn't have. Add one? | Non-blocking |
