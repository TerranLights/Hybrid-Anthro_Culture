# Method Index

All methods follow the Layering Law: no race content in method files. Race content lives in `races/`.

| Code · Name | File | Layer produced | Status |
|---|---|---|---|
| M-0 · Human-Assumptions Register | `adapters/Human_Assumptions_Register/` (`HAR_ULM`, `HAR_CST`, `HAR_RWBEM`, `HAR_HUF`) | Adapter layer | First sweep done: 156 entries (49 Blocking). See its README |
| M-0a · Species Parameter Sheet | `templates/Species_Parameter_Sheet_TEMPLATE.md` | Parameter sheet (P-1 to P-15) | Template v0.2 (D-8) |
| M-0b · Adapter notes | `adapters/ULM_Adapter.md`, `CST_Adapter.md`, `RWBEM_Adapter.md` | Plug-in map | Draft v0.1: all 98 Blocking and Adjust entries mapped |
| M-1 · Hybrid Trait Resolution | `M-1_Hybrid_Trait_Resolution.md` | L1 | Draft v0.1 |
| M-2 · Ethological Basis Extrapolation | `M-2_Ethological_Basis_Extrapolation.md` | M-2 research logs, feeding L1 | Draft v0.1 |
| M-3 · Species Universals Differentiation | `M-3_Species_Universals_Differentiation.md` | L2 (Universals volume) | Draft v0.1 |
| M-4 · Creator Intent & Drift | `M-4_Creator_Intent_and_Drift.md` | Design Charter and Drift Ledger for each lineage, feeding L1 and L3 | Draft v0.1 |
| M-5 · Xenobiology First-Principles | `M-5_Xenobiology_First_Principles.md` | L1 for races with no animal base | Draft v0.1 |
| M-6 · Interspecies Composition | `M-6_Interspecies_Composition.md` | Composite inherited stock (L3); later, mixed settlements (L4) | Draft v0.1 (Mode A usable now; Mode B deferred) |
| M-7 · Life-History Calibration | `M-7_Life_History_Calibration.md` | P-3, P-5, P-6, derived values | Draft v0.1 |

## Source references
- `source_reference/Universals_Checklist.md`: the M-3 item list (`U-` codes), checked against Brown's own Chapter 6
- `source_reference/Brown_Supplementary_Extraction.md`: Brown's Ch. 1, 3, and 5, plus the book's biology passages
- Brown, *Human Universals* (1991), the book itself: `InnerTepeniaGDD/Reference/Materials/books/` (image-only scan)

## Templates
- `templates/L0_Origin_Frame_TEMPLATE.md`: the lineage questionnaire (one per creator lineage, D-1)
- `templates/L1_Physiology_TEMPLATE.md`: the general physiology document (Mechanic 9)
- `templates/Species_Parameter_Sheet_TEMPLATE.md`: M-0a

## Run order for one engineered species (Phase 3 pilot shape)

```
L0 Origin Frames (one per lineage; developer questionnaire)
   │
   ├──► M-2  base-animal research ──────────────┐   (creator-independent; can start once Q-4 is settled)
   ├──► M-4  Design Charter per lineage ────────┤
   │                                            ▼
   │                                  M-1  trait resolution ◄──► M-7 (coherence feedback)
   │                                            │
   │                                            ▼
   │                                  L1 document  +  Parameter Sheet
   │                                            │
   │                                            ▼
   │                                  M-3  Species Universals (L2)
   │                                            │
   └──► M-6  composite creator stock ──►  L3 inherited stock per lineage (+ M-4 Drift Ledger)
                                                │
                                                ▼
                                  L4 populations: DEFERRED (D-2)
```

For races with no animal base (aliens), M-5 replaces M-2 and M-1.
