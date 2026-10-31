# M-6 · Interspecies Composition (ISC)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Built from:** CST Composition Merge R1–R7 (`Cultural_Synthesis_Techniques.md`, CST:981 onward), using the
biological-axes analysis in `adapters/Human_Assumptions_Register/HAR_CST.md` ("Composition Merge — biological
axes"). **Nothing here edits CST.**
**Produces:** a composite inherited stock (L3) for collaboration lineages. Later, mixed-settlement composition
(L4).
**Layering:** this file names no race.

## Two modes

| Mode | When | Merges | Status |
|---|---|---|---|
| **A · Creator-stock merge** | Now (D-1) | The *creators'* cultures (two or three of human, robot, alien) into one founding stock for a collaboration lineage | Usable now |
| **B · Settlement merge** | Deferred (D-2) | Co-resident *races* in one place | Waits for worlds; drafted here so its rules are ready |

---

## Embodiment Fit applies to every lineage
Embodiment Fit (Step A4 below) is how D-7's "human culture arrives only through this body" is carried out.
It applies to **every** lineage, including single-creator ones. **A single-creator lineage runs Mode A with
one stock:** it skips Steps A1–A3 and runs A4 and A5 on that one stock.

## Mode A · Creator-stock merge (A+H, A+R, H+R, A+H+R lineages)

**The problem:** a lineage made by a collaboration starts with a culture drawn from more than one creator
stock. CST Composition Merge was built for exactly this shape, settlers of several origins in one place, so
its rules are reused, aimed at *creators*.

### Inputs
- The lineage's L0 Origin Frame and M-4 Design Charter, especially:
  - the **role split** (who did what);
  - the **rearing plan**, which decides whose culture the founders were actually immersed in;
  - any recorded **creator disagreements**.
- **Each creator's culture stock:**
  - **H:** human. The source era and society come from L0.
  - **R:** the robot meta-culture. `Robot_Universals`, plus the canon line that a robot's culture comes from
    "the humans and other robots they're in the community of" (`00_RUNBOOK.md` §C.9d).
  - **A:** unknown until M-5 runs for the creating aliens. It enters as an **explicit unknown component.** It is
    never filled in, and never treated as zero.
- The race's L1 document (for Step A4).

### Steps
1. **Weight by exposure, not by credit.** A creator's share of the founding stock is its share of what the
   founders were *immersed in* (rearing, language, daily contact). It is never its share of the engineering
   work. A creator that designed the genome but never raised the founders may contribute almost nothing to the
   stock. This applies CST's R1 (majority default) to exposure. Record the chain from the Design Charter.
2. **Read the cultural distance between creator stocks** on CST's R4 cultural axes (staple, household and kinship
   form, script and numbering, calendar, funerary requirement, dietary prohibition, climate assumptions). Note
   where creator stocks rest on **different bodies**. A human stock's kinship form rests on genetic relatedness;
   a robot stock's rests on shared experience (Robot Universals ch. 8 and 11). Distance there is deep.
3. **Apply R2–R7 as written** to produce the composite. Follow CST's rule order, and record each rule's
   firing.
4. **Embodiment Fit** (proposed operator term, `HAR_CST.md`). For each practice in the composite, ask whether this
   race's body (L1) can **keep** it, **bend** it, or must **drop** it, and state the mechanism.
   - This is where a creator practice built for a different body gets tested against the founders' actual body.
   - **Don't presume the answer** (`CLAUDE.md` rules 3 and 4). For example, a stock built for genetic kinship
     won't automatically fit a litter-born race, and a stock built for experience-based kinship won't
     automatically fail it.
5. **Write the composite** into the lineage's `05_Inherited_Stock.md`. Every practice carries:
   - its source creator(s);
   - the R-rule that placed it;
   - its Embodiment Fit verdict.
   An unknown alien component stays marked as unknown.

---

## Mode B · Settlement merge (deferred, D-2)

### Axes
Keep CST's R4 **cultural** axes as distance measures. Split off each axis's hidden biological "can't":
staple → diet class; household → reproduction and rearing; calendar → activity cycle and breeding
seasonality; climate → physical tolerance. Then add the **biological** axes, measured as **overlap** (how much
of daily life two races can do together), not as distance:

| Axis | Parameter | Measure |
|---|---|---|
| B1 Diet class | P-7 | Compatible / partly overlapping / incompatible (no shared plate) |
| B2 Activity cycle | P-1 | Hours when both are active and alert |
| B3 Reproduction and kin model | P-2 | Whether kin categories and rearing units can be mapped onto each other |
| B4 Lifespan and generation ratio | P-5, P-6, Culture-Bearing Weight | Generation ratio, plus the share of cultural transmission each side carries |
| B5 Sensory mismatch | P-4 | Channels one side perceives and the other doesn't |
| B6 Communication-channel mismatch | P-8 | Signals one side *produces* that the other can't perceive or answer |
| B7 Body scale and locomotion | P-10 | Whether the built environment can be shared without parallel fixtures |
| B8 Social-cognition band mismatch | P-3 | Stable group size, stranger tolerance, territoriality |
| B9 Environmental tolerance | P-9 | Whether one interior climate and light regime can be shared |
| B10 Pathogen compatibility *(candidate)* | none yet. Needs an M-1 immunology domain if adopted | Cross-species disease transmission |
| Conditional: inherited predator/prey history | L1 of **both** races | Counts only if both L1 documents keep the mechanism. Never from a folk image |

### Rules
1. **Biological axes don't negotiate.** They neither blend (R4 "deep") nor erode (R3 "dispersed"). They are
   **accommodated**, **segregated**, or they **cause harm**.
2. **Read cultural distance and bodily overlap as a 2×2. Never average them:**

   | | **Near body** | **Far body** |
   |---|---|---|
   | **Near culture** | R4 DEEP, as in CST | **"One form, several executions":** a shared institution (often from the same creator stock), performed differently by each species. The seams are in the performance, not the form |
   | **Far culture** | R4 SHALLOW BUT BROAD, as in CST | **Parallel infrastructure with a minimal commons** limited to the overlap zone. That small commons is likely the most originally local culture in the place |
3. **R5b pooling applies per axis.** Two races can pool on B2 and not on B1. Report pooled figures for each
   axis, never as one merged entry.
4. **R6 across species:** what becomes universal is the *accommodation*, never the physical practice.
5. **R7 across species:** applies only on the origin axis. The species axis never reaches "shows up nowhere."
   Its fully integrated state is accommodation nobody remarks on.
6. **R1 across species:** the majority species' default includes the physical plant (doors, hours, food), so a
   species minority feels its status there before it feels it in custom.
7. **R5 thresholds:** CST gives no source for them, even for humans (`HAR_CST.md`). For non-humans:
   - On the **species axis**, replace them with a **biological floor**: physical needs need accommodation from
     the **first** resident, at any population share.
   - On the **origin axis** (within one species), restate bands as **absolute adult counts relative to the
     race's P-3 band**, with a growth note driven by fecundity (P-2).
   - Until M-7 produces per-race bands, treat R5 as "human-calibrated, unverified" and don't apply it.

## Guards
- **Composition names the stock; time and place produce the culture** (Inner Tepenia §C.9d). M-6 produces
  *stock*, never an outcome.
- **No creator or species essentialism** (`CLAUDE.md` rule 3). A merge result cites rules and mechanisms,
  never "because aliens / robots / cat-people."
- **Predator/prey framing** between races is admissible only through both L1 documents, and with care. It is the
  easiest place for folk images to leak in.
