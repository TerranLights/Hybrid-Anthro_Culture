# L0 Origin Frame — TEMPLATE (one per creator lineage)

**Copy to:** `races/<Species>/lineages/CL-<nn>_<Plain_Name>/00_Origin_Frame.md`
**Layer:** L0 · **Feeds:** M-1 (lineage deltas), M-4 (Design Charter), L3 (inherited stock), M-7
**Status:** Template, 2026-10-21.

The Origin Frame is **mostly a questionnaire for the developer.** This repo asks; it doesn't decide
(`CLAUDE.md` rules 1 and 8). Every field carries a status tag:

| Tag | Meaning |
|---|---|
| `[D-n]` | Developer ruling, logged in `DECISIONS.md` |
| `[C-n]` | Existing canon, recorded in `CANON.md` |
| `[Q-n]` | Open, tracked in `OPEN_QUESTIONS.md` |
| `[Proposed]` | A suggestion awaiting acceptance. Must carry its reasoning |
| `[hazy]` | Deliberately generalized under D-2. Never sharpen without a ruling |

Where a field is open, the **consequence note** says what each plausible answer would change downstream.
That lets the developer choose with the effects in view. Consequence notes describe effects; they never
recommend a canon answer unless asked.

---

## 1. Identity
| Field | Value | Status |
|---|---|---|
| Lineage code · name | `CL-nn · <plain name>` | |
| Species | | |
| Creator set | A / H / R / A+H / A+R / H+R / A+H+R / other (Q-16) | |
| Role split (collaborations only) | Who supplied what: genome design, gestation tech, rearing, funding or authority, the base genetic material | |

## 2. When
| Field | Value | Status |
|---|---|---|
| Era | Relative to `TepenianUniverseTimeline` eras, and to Outer Tepenia 1 / 2 / New Centauri | |
| Sequence relative to other lineages | First / parallel / later. Did this lineage know of the others? | |

## 3. Where `[hazy]`
| Field | Value | Status |
|---|---|---|
| Creation site archetype | e.g. "orbital facility," "planetary surface, unspecified," "the parallel Earth" | |
| Later home archetype(s) | | |

## 4. Why
| Field | Value | Status |
|---|---|---|
| Stated purpose | Labor? companionship? colonists for a specific environment? research? art or prestige? something else? | |
| Actual purpose, if different | Hidden or contested purposes | |
| Consequence note | How each candidate purpose would shape the Design Charter (M-4) and the inherited stock (L3) | |

## 5. From what
| Field | Value | Status |
|---|---|---|
| Animal base | Exact source population (Q-4). Wild ancestor, domestic form, or specific breed group? | |
| Human genetic source | Whose human genome? For A- or R-led lineages, where did it come from? (Q-17 for A) | |
| Other genetic sources | Creator-original sequences, a third species, a prior anthro lineage | |
| Founding population size and diversity | Number of founders, and how genetically varied. Drives founder effects and drift (M-1 step 5) | |

## 6. How they were raised (the main L3 hinge)
| Field | Value | Status |
|---|---|---|
| Gestation | Natural / artificial womb / creator-specific technology | |
| First-generation rearing | Inside creator society (immersion, the DR-11 precedent) / apart from it (managed facility) / by earlier-generation members / mixed | |
| Language of first rearing | | |
| Consequence note | Immersion means the creators' culture is the inherited stock. Apart-rearing means the facility's own culture is, which is a much thinner stock. These produce very different L3s | |
| Cohort structure | Were founders reared together in cohorts, and how large and from what age? | |
| Consequence note (co-rearing) | Brown (pp. 120–124, `Brown_Supplementary_Extraction.md`): incest avoidance arises from **early co-rearing, not from knowing who is kin**. Children raised together lose sexual interest in each other even when unrelated; kin raised apart don't. In humans the window is roughly the first six years, a human developmental figure that must be re-derived from this race's own maturation (M-7). Cohort-reared founders may therefore avoid mating with cohort-mates, which shapes mate choice, founder-effect dynamics (M-1 step 5), and early kinship forms. It holds only if L1 keeps the mechanism | |

## 7. Status and relationship
| Field | Value | Status |
|---|---|---|
| Status assigned at creation | Property / ward / citizen / something else (Q-13) | |
| Onset of natural reproduction | Designed from the start / permitted later / emerged against design | |
| Relationship to creators over time | Continuing / estranged / broken by an event / creators gone. The developer decides any event | |

## 8. Canon check (`CLAUDE.md` rule 7)
For each answered field, answer the four questions:
1. Does canon already answer this?
2. Does this contradict canon?
3. Does it bind anything beyond this lineage? Flag especially: alien–Earth contact (Q-17), robots as makers of
   biological life (Q-19), and timeline placement.
4. Does it need registering back?

## 9. Open items raised by this frame
List each `Q-` raised, with its plain name.
