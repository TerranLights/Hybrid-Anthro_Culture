# Human-Assumptions Register (M-0)

**Status:** First full sweep complete, 2026-10-21. The four files below are line-cited against the Inner
Tepenia originals. Nothing in them edits those originals (`CLAUDE.md` rule 8).

| File | Method | Entries | Blocking | Adjust | Cosmetic |
|---|---|---|---|---|---|
| `HAR_ULM.md` | Universal Location Methodology | 57 | 18 | 32 | 7 |
| `HAR_CST.md` | Cultural Synthesis Techniques | 39 | 7 | 27 | 5 |
| `HAR_RWBEM.md` | Real-World Basis Extrapolation Method | 18 | 5 | 9 | 4 |
| `HAR_HUF.md` | Human Universals Culture Framework | 42 | 19 | 21 | 2 |
| **Total** | | **156** | **49** | **89** | **18** |

**Severity key:**
- **Blocking:** the method gives a wrong or empty answer for a non-human race unless a replacement exists first.
- **Adjust:** runs, but needs a parameter-driven change.
- **Cosmetic:** wording only.

**Overlap note:** `HAR-ULM-40` to `-48` cover the CST and RWBEM copies inside the ULM's `Disciplines/` folder.
They duplicate entries in `HAR_CST.md` and `HAR_RWBEM.md`; DR-14 keeps those copies out of a ULM pass anyway.

---

## What the sweep changed in this repo (2026-10-21)
- **`MASTER_PLAN.md` §3:** the L3 mechanism was corrected to two stages, "mediated" first generation and
  "personal" later generations (HAR-ULM-49). §C.9b is a robot-only ruling.
- **M-2** was written from `HAR_RWBEM.md`'s carry-over analysis.
- **M-6** was written from `HAR_CST.md`'s biological-axes proposal.
- **M-3** gained a "do not inherit" list of robot verdicts (`HAR_HUF.md` Part B).

---

## Consolidated parameter proposal

**Accepted 2026-10-21 (D-8); now in the template.** The four registers proposed overlapping fields with
clashing numbers. This is the single consolidated numbering.

### New parameters
| Code · Parameter | Holds | Merges / sources |
|---|---|---|
| P-10 · Body plan, scale, locomotion, and integument | Stature and mass range; posture and locomotion modes; limb and hand form; fur or skin; baseline need for clothing or adornment; what built environment the body needs | HAR_ULM P-10 + HAR_CST "Body Scale and Locomotion". Feeds M-6 axis B7, which has no parameter yet |
| P-11 · Mating system and pair-bond form | Mating system; seasonal or continuous; induced or spontaneous ovulation; whether durable pair bonds exist | HAR_ULM P-11 |
| P-12 · Enculturation and transmission mode | Developmental learning windows; how culture is acquired (teaching, imitation, innate, engineered); vertical, oblique, or horizontal transmission; language-acquisition window; **plus the engineered-founder vs. born cohort split** | HAR_ULM P-12 + HAR_HUF-37. Needed for the two-stage L3 mechanism. Without it, every race silently gets human immersion learning |
| P-13 · Dispersal and philopatry | Which sex and age leave the natal group, how far, attachment to the birth site | HAR_ULM P-13 |
| P-14 · Sex differences and dimorphism | Physical and life-history differences between sexes, with mechanisms | HAR_HUF-22 |
| P-15 · Cognitive profile and temperament | Species-level cognitive and temperamental tendencies, **each routed through a cited mechanism** | HAR_HUF-21. ⚠ **This is the parameter most exposed to stereotyping** (`CLAUDE.md` rule 3). Every value needs a mechanism chain, or it stays `Unresolved` |

### Field extensions to existing parameters
- **P-2:** an adult-equivalent population figure (derived), so scale bands reflect the social body rather than
  headcount (HAR-ULM-04).
- **P-4:** a recognition channel: sight, scent, or voice (HAR-ULM-02).
- **P-6:** whether a senescent or post-reproductive stage exists (HAR-ULM-37).
- **P-8:** signal control. For each signal, voluntary, involuntary, or trainable; a culture can shape only the
  first and third (HAR_CST).

### Derived values (M-7), not inputs
- **Culture-Bearing Weight:** adult fraction at steady state, years of adult participation, and generational
  overlap with co-resident species. It converts a headcount share into a share of cultural transmission
  (HAR_CST).

### Not parameters: handled elsewhere
| Proposal | Where it goes instead |
|---|---|
| Lineage / engineering program of origin (HAR_HUF-23) | Already structural: L0 per lineage, `CL-` codes, and the "Lineage deltas" columns |
| Population-level biological divergence rate (HAR_HUF-24) | **Needs a ruling first (Q-24).** It touches the no-stereotype law |
| Channel-Rendering Map (HAR_CST) | **Per game**, not per race. It belongs in a game GDD and is read through the CST adapter |
| Embodiment Fit (HAR_CST, HAR_RWBEM) | An operator term, not a field. Used provisionally in M-6 Mode A. Promoting it into the Inner Tepenia divergence operator is a developer call (Q-27) |
| EBEM Pick List (HAR_RWBEM) | An M-2 research artifact: `races/<Race>/research_log/Ethological_Picks.md` |

---

## Adapter notes (M-0b): next step
`ULM_Adapter.md`, `CST_Adapter.md`, and `RWBEM_Adapter.md` will map each Blocking and Adjust entry to its
replacement. Unblocked by D-8.

---

## Known inconsistencies between registers (2026-10-21, from the adapter pass)
- **Twin entries with different severities.** The adapter rows use the **higher** severity:

  | ULM entry | Its twin | Severities |
  |---|---|---|
  | HAR-ULM-46 | HAR-CST-34 | Adjust vs. Blocking |
  | HAR-ULM-48 | HAR-RWBEM-11 | Adjust vs. Blocking |
  | HAR-ULM-41 | HAR-CST-13 | Cosmetic vs. Adjust |
- **Recognition channel:** HAR-ULM-02 placed it in P-8. D-8 placed it in P-4, which is authoritative.
- **Gap (needs a game GDD):** no game has a Channel-Rendering Map yet.
- **Gaps closed the same day:**
  - Embodiment Fit now applies to every lineage (M-6).
  - M-7 Step 8 computes Culture-Bearing Weight, per-race R5 bands, and the `00b` benchmark.
