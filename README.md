# Hybrid Anthro Culture

This is a centralized repo for developing cultures for different types of genetically-engineered races.

Across various settings within the Tepenian Multiverse, there will be a variety of conscious, sentient biological life in the form of different "races", which will appear in various works of media.

### Examples:
- Elf
    - Setting: a cross-dimensional parallel Earth
    - Media: "Elven Steel"; "Outer Tepenia: New Centauri" (i.e., Outer Tepenia 3)
- Orc
    - Setting: a cross-dimensional parallel Earth
    - Media: "Elven Steel"
- Alien
    - Setting: the Alpha/Proxima Centauri star system
    - Media: "Outer Tepenia: New Centauri" (i.e., Outer Tepenia 3)
- Dog (anthro)
    - Setting: the Alpha/Proxima Centauri star system
    - Media: "Outer Tepenia: New Centauri" (i.e., Outer Tepenia 3)
- Cat (anthro)
    - Setting: the Alpha/Proxima Centauri star system
    - Media: "Outer Tepenia: New Centauri" (i.e., Outer Tepenia 3)
- Rabbit (anthro)
    - Setting: the Alpha/Proxima Centauri star system
    - Media: "Outer Tepenia: New Centauri" (i.e., Outer Tepenia 3)

(more expected to come)

---

## What this repo is
The workshop **and** the home for the cultures of conscious, sentient, **biological, non-human, non-robot** races: the anthros (genetically engineered splicings of human and animal DNA), elves, orcs and aliens. Despite the name, the scope is all of these, not only the anthros.

- **Why it has its own repo:** these cultures apply almost entirely to *Outer Tepenia: New Centauri* (where the player can be a Human, a Robot, an Elf or an Anthro) and, for elves and orcs, to *Elven Steel*. So the methods, the research and the finished cultures all stay here, rather than in the [Culture Library](https://github.com/TerranLights/CultureLibrary) (which holds the cultures of humans and robots on Earth, in Tepenia and beyond).
- **Out of scope:** robots, whose biological-and-cultural floor is kept in the [Tepenian Universe Timeline](https://github.com/TerranLights/TepenianUniverseTimeline) (`Reference/Robot_Universals/`), and human cultures.
- **Canon authority:** the Timeline is the cross-project canon. This repo is the working shop; nothing flows out of it without the author's decision.

## How the work is done
A race is built in five layers, from where it came from to the populations that live it:

| Layer | What it settles |
|---|---|
| **L0 · Origin frame** | Who made the race and why. Anthro creators may be aliens, humans and/or robots (D-1), so origin is set **per lineage**, and a race may have several lineages (D-5) |
| **L1 · Physiology and life history** | The body: senses, reproduction, lifespan, social instinct, derived from human biology and the base animal's |
| **L2 · Species universals** | What every member of the race shares, set against the human universals |
| **L3 · Inherited stock** | The culture each lineage inherits from its creators' design and drift |
| **L4 · Populations** | Local cultures in real places; **deferred** until the worlds exist (D-2: locations are known only in the haziest terms) |

**Methods M-1 to M-7** (`methods/`): hybrid trait resolution, ethological basis extrapolation, species universals, creator intent and drift, xenobiology from first principles, interspecies composition, and life-history calibration. The shared location and culture methods (ULM, CST, RWBEM, and the Human Universals Culture Framework) from [Derivation Mechanisms](https://github.com/TerranLights/DerivationMechanisms) are run in place through adapters (`methods/adapters/`) and each race's parameter sheet, never copied.

**Standing rules** (full text in `CLAUDE.md`):
- **Derive, don't invent.** Every trait traces back to its sources; a gap is logged as an open question, never filled with a guess.
- **Never infer physiology from the word.** "Elf" does not mean long-lived, "cat" does not mean aloof, "orc" does not mean aggressive.
- **Condition, never essentialism.** "X-people do this because they're X" is never an answer.
- **The plausibility standard (D-7): "a humanized lizard, never a California college student."** Every hybrid race keeps some of its animal side in how it behaves; human culture reaches it only through its body; handwaves are allowed only within plausibility, each one logged.
- **Research fully** (depth over speed; a recalled fact is a guess) and **one race on its own terms** (comparisons only as a check on the finished work).

## Layout

| Path | What it holds |
|---|---|
| `CLAUDE.md` | The repo's standing rules; read first |
| `MASTER_PLAN.md` | The architecture (layers L0 to L4), the methods and the phase sequence |
| `DECISIONS.md` | The author's rulings (D-1 onward) |
| `OPEN_QUESTIONS.md` | What is blocked, and on what |
| `CANON.md` | Existing canon from other repos, with sources |
| `HANDWAVES.md` | Every plausibility handwave: what is waved and what is not |
| `RESEARCH_QUEUE.md` | Research items waiting to run |
| `methods/` | M-1 to M-7, the adapters to the shared methods, and templates (origin frame, physiology, species parameter sheet) |
| `races/` | One folder per race (Alien, Cat, Dog, Elf, Orc, Rabbit, and `_Shared_Anthro` for what all anthros share) |
| `source_reference/` | Research baselines: human biology, plausibility inputs, the universals checklist, the real Alpha Centauri system, xenobiology method sources |
| `methodology-observations/` | Lessons from each pilot, held for review |
| `to-be-integrated/` | Material waiting to be sorted |

## Status
- **Rabbit-people (pilot, base animal: the European rabbit):** base-animal research done (240 sources across two logs), plus the human baseline and plausibility inputs; the first physiology pass is done and has produced 17 Charter Decision Points waiting for the author (`races/Rabbit/Charter_Decision_Points.md`), along with the lineage questions.
- **Cat- and dog-people, elves, orcs, aliens:** not started (the cat and dog folders have empty research logs ready).
