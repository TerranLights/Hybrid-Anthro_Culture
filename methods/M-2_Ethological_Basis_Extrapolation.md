# M-2 · Ethological Basis Extrapolation Method (EBEM)

**Status:** Proposed draft v0.1, 2026-10-21. Not yet piloted.
**Built from:** RWBEM (`InnerTepeniaGDD/Worldspace/Locations-and-Levels/Real-World_Basis_Extrapolation_Method.md`),
following the step-by-step carry-over analysis in `adapters/Human_Assumptions_Register/HAR_RWBEM.md`
("Carry-over into M-2"). RWBEM's step shape is kept. Its subject changes from *real human places* to *real,
named animal populations*.
**Produces:** a per-race research log and pick list, which feed M-1 (and so L1).
**Applies to:** any race with a real-animal base. **Layering:** this file names no race.

---

## Step 0 · Governing laws (stated in full here, never only cited, because a procedure that cites its governing law instead of stating it gets run without it; RWBEM:7)

### LAW 0-R · Research fully. A pick isn't finished just because it has been searched.
The developer's instruction, verbatim (RWBEM):
> "When doing web research on a particular place/location/topic/idea/etc etc etc, research FULLY. I don't
> expect you to deliver 'fast results'. What I want is for you to do it *RIGHT*."

> "Doing web research is for ensuring REALISM and ACCURACY, and that's only possible with real, accurate
> input data."

This research is the **input data layer** for the race's biology. Everything downstream inherits its quality.
- **A recalled fact is not input data.** It is a guess in a confident tone. That includes every "(verify)"
  animal fact already written in this repo's registers and checklist (RQ-12).
- **A wrong fact is worse than a missing one.** It produces biology that is confident, coherent, and wrong, and
  nothing downstream flags it.
- **A thin fact set produces a thin race,** and no later check can detect thinness.
- **The standard is not "did I find something."** It is: *"is what I found real, and is there enough of it to
  build on?"*

**What "fully" means:**
1. Don't stop at the first useful result.
2. Query every pick from more than one angle (see Step B).
3. A pick with sub-populations counts as at least two picks: a species is not one population, and a wild
   population is not its domestic form.
4. **Go back to picks already logged as covered.**
5. A near-duplicate search is still worth running and logging.
6. Log dead ends, and where each died: at the **query** (recoverable by rephrasing) or at the **sources** (a
   real absence).
7. Never decide a source is redundant from its title.

**There is no time limit and no search budget.** After each source, ask: *did this change a finding, or just
decorate one?* Record either answer honestly.

### No forced fit
"This race doesn't keep the mechanism" is a complete and legitimate answer. "Not resolved yet" must never
read as "not possible."

### One subject on its own terms
Never use another race's L1 as a control or an implied normal (`CLAUDE.md` rule 10).

### The prohibition: a coordinate, never a cause
*A study population's human context (who bred or kept it, where, under which program, how it was
introduced) is a coordinate, never a cause of a race trait.*
- **Swap test:** if a sentence's meaning would change when you swap the study population for another population
  of the same taxon that has the same mechanism, the sentence describes the population's circumstances, not the
  mechanism. Rewrite it or drop it.
- **The sequencing exception.** "The base ruling names the stock."

  | Stage | Admissible |
  |---|---|
  | **Before** Q-4 or the L0 Origin Frame names the base population | Mechanisms only. Husbandry and domestication history are coordinates |
  | **After** the base is ruled, *and* the M-4 Design Charter says the creators used that population | That population's domestication history and selected traits become legitimately in scope, because they are causal through L0 |

### Mechanisms cross; learned traditions don't
Mechanisms can cross the engineering boundary, as M-1 resolves them. An animal population's **learned**
traditions cannot, because no animal raised the race. This holds unless the L0 Origin Frame says otherwise.
This is the line between an **Animal-Inherited Universal** (M-3) and transplanted animal culture, which
doesn't exist.

### Folk meaning is not a source
The animal's folk image, its symbolism, and fantasy conventions are never evidence (`CLAUDE.md` rule 2). If a
source's claim matches a folk image, it still needs its own primary support. Don't put disclaimers on folk
material: leave it out entirely ("silence, not disclaimer"; "omit, don't reframe").

---

## Step A · Pull the full pick list
**File:** `races/<Race>/research_log/Ethological_Picks.md`, filled only **after Q-4** rules on the base.
Nothing exists before that ruling.

| Tier | Contents |
|---|---|
| **Primary** | The ruled base population(s) |
| **Secondary** | The wild ancestor; feral or introduced populations; other major domestic or wild populations |
| **Supporting** | Closely related taxa; captive and lab colonies, always flagged as such |

- **Use every tier,** not just Primary. Don't stop at the first result.
- **Research the specific population, never the species in general.** A named population in a named study
  beats "rabbits" or "wolves."
- **Never pick a population for its image or setting.**
- **Hypothesis to measure, not assume:** RWBEM found lower tiers were often the most valuable. Record whether
  that holds here.
- Each pick records its human-management status (wild, feral, captive, domestic, lab) and why it was picked.

## Step B · Research each pick as a real, specific thing
**Take inventory first, interpret later.** Cover every category for every pick:
- behaviors
- signals and their channels
- social structure
- life history (maturation, reproduction, lifespan)
- senses and their ranges
- activity cycle
- diet and digestion
- habitat use and locomotion

**Angles,** each pick queried from several:
- mechanism (anatomical, neural, hormonal);
- development (how the trait appears in the young);
- variation between populations;
- what the trait costs the animal;
- what it is a contrast *for*.

**Source standard:**
- Use primary ethology and biology literature and scholarly reviews. Web summaries are leads only.
- Use the literature's operational definitions. Never import human role nouns ("queen," "alpha," "wife").

**Revised-model watch:** record each claim's date, and whether the field has since revised it. *The
captive-wolf "alpha" dominance model, which later field work on wild packs revised, is the standing
example.* A revised model is logged as a dead end, not used.

**Variation is data.** When two populations disagree, record both and never average them. The disagreement
feeds M-1's choice of which population counts, and may reopen Q-4.

## Step C · The question, per detail
Ask about each detail individually, never each pick as a whole:

> **Does this race's resolved physiology keep the mechanism that produces this?**

Never ask "would they have their own version?" The answer is checked against L1, using this map:

| Step B turned up a… | Check it against |
|---|---|
| behavior pattern | L1 social instinct and cognition domains; P-3 |
| signal (any channel) | L1 communication; P-8 (with signal control); P-4 for whether the receiver can perceive it |
| social-structure trait | L1 social instinct; P-3; P-2 (who raises young) |
| life-history fact | L1 maturation, reproduction, lifespan; P-2, P-5, P-6 |
| sensory capacity | L1 senses; P-4 |
| activity or diet fact | L1; P-1, P-7 |
| habitat use or locomotion | L1 locomotion; P-10 (body plan); P-9 |

- **Circularity note.** M-2 feeds M-1, and M-1 produces L1. On the first pass, Step C runs against the
  **M-1 draft**. The question it asks is "is this mechanism a candidate for retention?" Its answers become
  M-1 Step 1 inputs. After M-1 resolves, Step C reruns against the finished L1 as a check.
- **Outcomes use M-1's tags,** never a bare yes or no.
- **A blocked or unresolved check is not an absence.**

## Step D · Cross-check before writing (in tier order)
1. `CANON.md` and D-rulings (hard canon).
2. The developer's own stated vision for the race (authorial, upstream; never treated as derived).
3. The race's L1 document (the current best derivation).
4. Derived notes: parameter-sheet drafts and earlier syntheses.

*A synthesis written before the chain can't validate the chain.* Run the four-question canon check
(`CLAUDE.md` rule 7) here.

## Step E · Write to the target
- **Targets:** L1 traits, via M-1. L2 is reached only through M-3, never written directly from here.
- Every trait written carries its M-1 outcome tag and source chain.

## Step F · The research log
**File:** `races/<Race>/research_log/`, one log per race. Keep the RWBEM log structure in full: every
search, its query, the result, and whether it changed or decorated a finding, plus dead ends and where each
died. **For each source, also record:**
- taxon and named population
- wild / feral / captive / domestic / lab
- field or lab study
- sex and life stage sampled
- sample size
- study year, and whether the model has since been revised
- study site (as a coordinate only)
- which M-1 trait domain the source fed
