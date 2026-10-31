# Plausibility Inputs (RQ-5, RQ-6, RQ-8)
**Status:** Working source reference, 2026-10-21. Defines what real biology constrains, for D-7 and HW-1.

**Scope and rules.** This file answers RQ-5 (hybrid and chimera biology limits), RQ-6 (body-size scaling of
life history), and RQ-8 (domestication syndrome). It is a **plausibility input, not a veto** (RQ-5 wording,
`RESEARCH_QUEUE.md`). It names no race's resolved traits: the worked allometry predictions are *what
mammalian scaling would predict for a body of that size and ancestry*, for M-1 Step 4 and M-7 to test against.
They are not L1 values. Everything here is `Proposed:` until the developer accepts it (`CLAUDE.md` rule 6).

**Conventions.**
- Sources are coded `PI-S##`. Claims cite them in brackets.
- Paraphrase and short quotes only (LAW 0-R).
- **Read level** is recorded for each source: *full text*, *abstract*, or *secondary* (I saw only an index
  entry, a press report, or another paper's summary). A secondary-level claim should be re-checked before it
  binds anything.
- **[contested]** marks a point the literature disputes. Both sides are recorded.
- **[repo analysis]** marks this file's own reasoning or arithmetic, as distinct from what a source says.

---

## Sources (PI-S…)

### RQ-5: hybrids, chimeras, genome engineering, development

| Code | Citation | Read level | Used for |
|---|---|---|---|
| PI-S01 | Tjio, J. H. & Levan, A. (1956). The chromosome number of man. *Hereditas* 42: 1– | secondary | Human 2n = 46 |
| PI-S02 | Animal Genome Size Database entry for *Oryctolagus cuniculus* (2n = 44); also the 1982 Jackson Laboratory rabbit linkage-map entry ("2N = 44") and a New Zealand White rabbit meiosis study (Korea Science, 2001) reporting 2n = 44 with arm-morphology counts. The classic primary karyotype, Gustavsson (1964, *Acta Vet. Scand.*), could not be opened (publisher login wall) | secondary | Rabbit 2n = 44 |
| PI-S03 | Dog karyotype 2n = 78 (38 acrocentric autosome pairs plus XY), corroborated by a cytogenetics chapter and the genome literature. Lindblad-Toh et al. (2005), *Nature*, the standard genome reference, was **not** retrieved | secondary | Dog 2n = 78 |
| PI-S04 | University of Missouri Feline Genetics and Comparative Medicine Laboratory, "Cat Genomic Resources: Karyotypes" (2n = 38, 18 autosome pairs plus XY) | secondary (institutional) | Cat 2n = 38 |
| PI-S05 | Huang, J. et al. (2014). Analysis of horse genomes provides insight into the diversification and adaptive evolution of karyotype. *Scientific Reports* 4: 4958. doi:10.1038/srep04958 | full text (via PMC) | Przewalski × domestic horse fertility |
| PI-S06 | Chandley, A. C. et al. (1975). Testicular meiosis in a mule, a hinny, and a Przewalski × domestic horse hybrid | secondary (abstract via index) | Meiotic pairing in equid hybrids |
| PI-S07 | Cowell, F. (2023). 100 years of Haldane's rule. *Journal of Evolutionary Biology* 36(2): 337–346. doi:10.1111/jeb.14112 | full text | Haldane's rule |
| PI-S08 | Bhattacharyya, T. et al. (2013). Mechanistic basis of infertility of mouse intersubspecific hybrids. *PNAS* 110(6): E468–E477. doi:10.1073/pnas.1219126110 | full text | Asynapsis from sequence divergence |
| PI-S09 | Nunes, A. C. et al. (2011; online 2010). Fertility of house mouse hybrids carrying a chain-of-four Robertsonian configuration (Madeira races). *Heredity* 106: 348–356 | abstract | Partial sterility from rearrangements |
| PI-S10 | "Chromosome Synapsis and Recombination in Male Hybrids between Two Chromosome Races of the Common Shrew (*Sorex araneus*)" (2017; journal not confirmed), PMC5664132; and Hatfield, Barton & Searle (1992), hybrid-zone model for *S. araneus* | abstract | Simple vs complex chromosomal heterozygotes |
| PI-S11 | Rong, R. et al. (1988). A fertile mule and hinny in China. *Cytogenetics and Cell Genetics* (PMID 3378453) | abstract | Rare fertile female mule |
| PI-S12 | Fitzpatrick, B. M. (2004). Rates of evolution of hybrid inviability in birds and mammals. *Evolution* 58(8). doi:10.1554/04-190 | secondary (citing papers) | Mammalian hybrid-viability window |
| PI-S13 | Divergence times: Quental, R. et al. (2010), *BMC Evol. Biol.* 10: 212 (TimeTree-derived averages: human–Glires ≈ 91 Myr, human–Laurasiatheria ≈ 97.4 Myr); a 2017 Dryad placental-phylogeny dataset (superorders diverged 90–110 Mya); a crown-age table giving Euarchontoglires 77–104 Myr and Laurasiatheria 77–95 Myr by model | secondary | How far apart human, rabbit, dog, and cat are |
| PI-S14 | Wu, J. et al. (2017). Interspecies chimerism with mammalian pluripotent stem cells. *Cell* 168(3): 473–486 | full text (via PMC, first 100k chars) | Human–pig chimeras |
| PI-S15 | Tan, T. et al. (2021). Chimeric contribution of human extended pluripotent stem cells to monkey embryos ex vivo. *Cell*. doi:10.1016/j.cell.2021.03.020 | secondary (press, multiple outlets) | Human–monkey chimeric embryos |
| PI-S16 | Wang, J. et al. (2023). Generation of a humanized mesonephros in pigs from induced pluripotent stem cells via embryo complementation. *Cell Stem Cell* 30(9): 1235–1245.e6. doi:10.1016/j.stem.2023.08.003 | secondary (press, abstract) | Best-case human organ contribution |
| PI-S17 | Kobayashi, T. et al. (2010). Generation of rat pancreas in mouse by interspecific blastocyst injection of pluripotent stem cells. *Cell* 142(5): 787–799 | abstract | Interspecies blastocyst complementation |
| PI-S18 | Yamaguchi, T. et al. (2017). Interspecies organogenesis generates autologous functional islets. *Nature* 542. doi:10.1038/nature21070 | abstract | Organ size follows host |
| PI-S19 | Ross, P. & Nakauchi, H., human–sheep chimeric embryos, AAAS annual meeting presentation, February 2018 (press coverage only; no peer-reviewed paper found) | secondary (press) | Human–sheep chimeras |
| PI-S20 | "New concepts for generating interspecies chimeras using human pluripotent stem cells." *Protein & Cell* 13(4) (2022) | abstract | Barriers to human–animal chimerism |
| PI-S21 | Fredens, J. et al. (2019). Total synthesis of *Escherichia coli* with a recoded genome. *Nature* 569: 514–518. doi:10.1038/s41586-019-1192-5 | secondary (repository, press) | Synthetic genomics state of the art |
| PI-S22 | Zhao, Y. et al. (2023). Sc2.0 chromosome consolidation (syn6.5 strain; >50% of the synthetic yeast genome in one strain). *Cell* | abstract | Synthetic eukaryotic genome status |
| PI-S23 | Anand, R. P. et al. (2023). Design and testing of a humanized porcine donor for xenotransplantation. *Nature* 622. doi:10.1038/s41586-023-06594-4 | abstract and press | Multiplex editing scale; immune barrier |
| PI-S24 | Wellcome (2025). Synthetic Human Genome (SynHG) project launch (press release) | secondary (press release) | Human genome synthesis timeline |
| PI-S25 | McGrath, J. & Solter, D. (1984). Completion of mouse embryogenesis requires both the maternal and paternal genomes. *Cell*; with the companion Surani, Barton & Norris (1984), *Nature* (PMID 6482961) | abstract | Imprinting: both parental genomes required |
| PI-S26 | Vrana, P. B. et al. (1998). Genomic imprinting is disrupted in interspecific *Peromyscus* hybrids. *Nature Genetics* 20: 362–365; and Vrana et al. (2000), *Nature Genetics* (hybrid overgrowth) | abstract | Imprinting breakdown in hybrids |
| PI-S27 | Species difference in *IGF2R* imprinting: a 1996 methylation study (PMID 8824797) and a 1997 review, "Imprinted genes in liver carcinogenesis," *FASEB J.* 11(1): 60–67 | abstract | Imprinting maps differ between species |
| PI-S28 | Carter, A. M. & Enders, A. C. (2004). Comparative aspects of trophoblast development and placentation. *Reproductive Biology and Endocrinology* 2: 46 | full text (first 100k chars) | Placenta types |
| PI-S29 | Furukawa, S., Kuroda, Y. & Sugiyama, A. (2014). A comparison of the histological structure of the placenta in experimental animals. *J. Toxicol. Pathol.* 27(1) | abstract | Placenta types |
| PI-S30 | Allen, W. R. & Short, R. V. (1997). Interspecific and extraspecific pregnancies in equids: anything goes. *J. Heredity* 88(5): 384–; Enders, A. C. et al. (1996), *J. Anatomy* (donkey-in-horse trophoblast) | abstract | Xenogeneic pregnancy failure |
| PI-S31 | Joubert, D. M. & Hammond, J. (1954). *Nature* 174: 647, summarizing Walton, A. & Hammond, J. (1938), Shire × Shetland reciprocal crosses | secondary | Maternal constraint on fetal size |
| PI-S32 | Matsuda, M. et al. (2020). Species-specific segmentation clock periods are due to differential biochemical reaction speeds. *Science* 369(6510): 1450–1455; Rayon, T. et al. (2020). Species-specific pace of development is associated with differences in protein stability. *Science* 369(6510): eaba7667 | secondary (summaries, preprint follow-up) | Developmental tempo is genome-wide |
| PI-S33 | Kenyon, L. & Moraes, C. T. (1997). Expanding the functional human mitochondrial DNA database by the establishment of primate xenomitochondrial cybrids. *PNAS* | abstract and secondary | Mitonuclear compatibility limits |
| PI-S34 | Maternal antibody transfer to colostrum and cord blood in dogs (2025), *Frontiers in Immunology*, doi:10.3389/fimmu.2025.1753521 (also bioRxiv) | abstract | Endotheliochorial placenta limits IgG transfer |
| PI-S35 | Catunda Lemos, A. P. et al. (2012). Characterization of the rabbit neonatal Fc receptor (FcRn)… *PLoS ONE* | abstract | Rabbit prenatal IgG via yolk sac |
| PI-S36 | Larkin, D. M. et al. (2009). Breakpoint regions and homologous synteny blocks in chromosomes have different evolutionary histories. *Genome Research*. doi:10.1101/gr.086546.108 | abstract | Scale of chromosome rearrangement across amniotes |

### RQ-6: allometry and life history

| Code | Citation | Read level | Used for |
|---|---|---|---|
| PI-S40 | Kleiber, M. (1932). Body size and metabolism. *Hilgardia* 6(11): 315–353; Kleiber, M. (1961). *The Fire of Life* (the 70·M^0.75 kcal/day form, per a Smil essay) | secondary | Kleiber's law |
| PI-S41 | West, G. B., Brown, J. H. & Enquist, B. J. (1997). A general model for the origin of allometric scaling laws in biology. *Science* | secondary | Network model of 3/4 scaling |
| PI-S42 | Kozłowski, J. & Konarzewski, M. (2004), critique of the WBE model; Brown, West & Enquist (2005), reply; Etienne, Apol & Olff (2006); Savage, Deeds & Fontana (2008) | secondary | The 3/4 debate |
| PI-S43 | Glazier, D. S. (2005). Beyond the "3/4-power law." *Biological Reviews* 80: 611–662. doi:10.1017/S1464793105006834 | abstract | Exponent not universal |
| PI-S44 | Kolokotrones, T., Savage, V., Deeds, E. J. & Fontana, W. (2010). Curvature in metabolic scaling. *Nature* 464: 753–756 | secondary | Log-log curvature |
| PI-S45 | Stahl, W. R. (1967). Scaling of respiratory variables in mammals. *J. Appl. Physiol.* 22(3): 453–460 | full text (scanned, partly illegible) | Heart-rate exponent −0.25; deviation caveat |
| PI-S46 | A 1989 *J. Exp. Biol.* study of small wild mammals citing Stahl's heart-rate equation as ≈ 241·M^−0.25 bpm (M in kg) | secondary | Heart-rate coefficient |
| PI-S47 | Levine, H. J. (1997). Rest heart rate and life expectancy. *J. Am. Coll. Cardiol.* (PMID 9316546) | abstract | Lifetime heartbeats |
| PI-S48 | de Magalhães, J. P., Costa, J. & Church, G. M. (2007). An analysis of the relationship between metabolism, developmental schedules, and longevity using phylogenetic independent contrasts. *J. Gerontol. A* 62(2): 149–160 | full text | Lifespan and maturity equations |
| PI-S49 | Clauss, M. et al. (2014). Low scaling of a life history variable: analysing eutherian gestation periods with and without phylogeny-informed statistics. *Mammalian Biology*. doi:10.1016/j.mambio.2013.01.002 | abstract | Gestation exponent, OLS vs PGLS |
| PI-S50 | Jackson, G., Mooers, A. Ø., Dubman, E., Hutchen, J. & Collard, M. (2014). Basal metabolic rate and maternal energetic investment durations in mammals. *BMC Evol. Biol.* 14: 194 | full text | Gestation PGLS slopes by order |
| PI-S51 | Sibly, R. M. & Brown, J. H. (2007). Effects of body size and lifestyle on evolution of mammal life histories. *PNAS* 104(45): 17707–17712 | full text | Production-rate scaling; lagomorphs |
| PI-S52 | Werner, J. & Griebeler, E. M. (2011). Reproductive biology and its impact on body size. *PLoS ONE* 6(12): e28442 | full text (first 100k chars) | Litter size vs mass within orders |
| PI-S53 | Hamilton, M. J., Davidson, A. D., Sibly, R. M. & Brown, J. H. (2011). Universal scaling of production rates across mammalian lineages. *Proc. R. Soc. B* 278: 560–566 | abstract | Production scaling is shared across lineages |
| PI-S54 | Austad, S. N. & Fischer, K. E. (1991). Mammalian aging, metabolism, and ecology: evidence from the bats and marsupials. *J. Gerontol.* 46(2): B47–B53 | abstract | Bats; longevity quotient |
| PI-S55 | Healy, K. et al. (2014). Ecology and mode-of-life explain lifespan variation in birds and mammals. *Proc. R. Soc. B* 281: 20140298 | abstract | Flight, arboreality, fossoriality |
| PI-S56 | Ruby, J. G., Smith, M. & Buffenstein, R. (2018). Naked mole-rat mortality rates defy Gompertzian laws by not increasing with age. *eLife* 7: e31157 | abstract | Naked mole-rat |
| PI-S57 | Kraus, C., Pavard, S. & Promislow, D. E. L. (2013). The size–life span trade-off decomposed: why large dogs die young. *American Naturalist* 181(4): 492–505 | abstract and secondary | Within-species reversal |
| PI-S58 | AnAge: The Animal Ageing and Longevity Database (Human Ageing Genomic Resources), species entries for *Oryctolagus cuniculus*, *Lepus europaeus*, *Canis lupus*, *Canis familiaris*, *Felis catus*, *Puma concolor*, *Panthera pardus*, *Hydrochoerus hydrochaeris*, *Sus scrofa*, *Homo sapiens*; accessed 2026-10-21 | database | Species life-history values |
| PI-S59 | Quintana, J., Köhler, M. & Moyà-Solà, S. (2011). *Nuralagus rex*. *J. Vertebrate Paleontology* 31: 231–240 (≈ 12 kg); Moncunill-Solé, B. et al. (2015), *J. Zoology* (≈ 8 kg) | secondary | Largest lagomorph ever |
| PI-S60 | Rabbit age at first breeding: PestSmart (Centre for Invasive Species Solutions), "Rabbit biology, ecology and distribution" (breeding from ~4 months); a New Zealand life-history account (females ~5 months, males ~9 months) | secondary | Rabbit maturity |

### RQ-8: domestication syndrome

| Code | Citation | Read level | Used for |
|---|---|---|---|
| PI-S70 | Darwin, C. (1868). *The Variation of Animals and Plants under Domestication* (cited through PI-S71; the primary text was not read) | secondary | Origin of the trait-suite observation |
| PI-S71 | Wilkins, A. S., Wrangham, R. W. & Fitch, W. T. (2014). The "domestication syndrome" in mammals: a unified explanation based on neural crest cell behavior and genetics. *Genetics* 197(3): 795–808; and their 2021 reply in *Genetics* (PMC8633094) | abstract | Neural crest hypothesis |
| PI-S72 | Sánchez-Villagra, M. R., Geiger, M. & Schneider, R. A. (2016). The taming of the neural crest. *Royal Society Open Science* 3: 160107 | abstract | Uneven trait distribution |
| PI-S73 | Lord, K. A., Larson, G., Coppinger, R. P. & Karlsson, E. K. (2020). The history of farm foxes undermines the animal domestication syndrome. *Trends in Ecology & Evolution* 35(2) | secondary (press, abstract fragments) | Fox founders; syndrome critique |
| PI-S74 | Johnsson, M., Henriksen, R. & Wright, D. (2021). The neural crest cell hypothesis: no unified explanation for domestication. *Genetics* iyab097 | full text | Critique of neural crest hypothesis |
| PI-S75 | Trut, L., Oskina, I. & Kharlamova, A. (2009). Animal evolution during domestication: the domesticated fox as a model. *BioEssays* 31(3): 349–360. doi:10.1002/bies.200800070 | full text (PMC author manuscript, via NCBI BioC) | Fox experiment numbers |
| PI-S76 | Geiger, M., Sánchez-Villagra, M. R. & Lindholm, A. K. (2018). A longitudinal study of phenotypic changes in early domestication of house mice. *Royal Society Open Science* 5: 172099; correction, *R. Soc. Open Sci.* 10: 231829 (2023), whose content could not be read (HTTP 403) | abstract | Unselected "domestication" in mice |
| PI-S77 | Carneiro, M. et al. (2014). Rabbit genome analysis reveals a polygenic basis for phenotypic change during domestication. *Science* 345: 1074–1079 | abstract | Rabbit domestication genetics |
| PI-S78 | Brusini, I. et al. (2018). Changes in brain architecture are consistent with altered fear processing in domestic rabbits. *PNAS* 115(28): 7380–7385 | abstract | Rabbit brain changes |
| PI-S79 | Hare, B., Wobber, V. & Wrangham, R. (2012). The self-domestication hypothesis: evolution of bonobo psychology is due to selection against aggression. *Animal Behaviour* 83: 573–585 | abstract | Bonobo self-domestication |
| PI-S80 | Sánchez-Villagra, M. R. & van Schaik, C. P. (2019). Evaluating the self-domestication hypothesis of human evolution. *Evolutionary Anthropology* 28: 133–143. doi:10.1002/evan.21777 | secondary (citing papers) | Human self-domestication critique |
| PI-S81 | Shilton, D., Breski, M., Dor, D. & Jablonka, E. (2020). Human social evolution: self-domestication or self-control? *Frontiers in Psychology* 11: 134 | abstract | Human self-domestication critique |
| PI-S82 | Mouginot, M., Wilson, M. L., Desai, N. & Surbeck, M. (2024). Differences in expression of male aggression between wild bonobos and chimpanzees. *Current Biology* 34(8): 1780–1785 | secondary (press, multiple outlets) | Bonobo aggression data |
| PI-S83 | Benítez-Burraco, A., Clay, Z. & Kempe, V. (2020). Editorial: Self-domestication and human evolution. *Frontiers in Psychology* | abstract | Field overview |

---

## RQ-5 Hybrid and chimera limits

### 5.1 Chromosome numbers and what a "natural" F1 would look like

| Species | Diploid number (2n) | Haploid set | Source |
|---|---|---|---|
| Human | 46 | 23 | PI-S01 |
| European rabbit | 44 | 22 | PI-S02 |
| Dog | 78 | 39 | PI-S03 |
| Domestic cat | 38 | 19 | PI-S04 |

An F1 gets one haploid set from each parent, so a natural human × rabbit F1 would carry 23 + 22 = 45
chromosomes, human × dog 23 + 39 = 62, and human × cat 23 + 19 = 42 **[repo analysis]**. The number is not the
real obstacle, though. What matters is whether each chromosome has a partner it can **pair with** in meiosis.

**Divergence scale.** Human and rabbit belong to the same superorder (Euarchontoglires). TimeTree-derived
averages put the human–Glires split at about 91 Myr, and the human–Laurasiatheria split (the group that
includes dog and cat) at about 97 Myr (PI-S13). Estimates vary by method: one crown-age table gives
Euarchontoglires 77–104 Myr and Laurasiatheria 77–95 Myr. A ten-amniote comparison mapped 2,233 homologous
synteny blocks separated by 1,064 evolutionary breakpoint regions (PI-S36). Ninety million years of separate
chromosome evolution means the parental chromosome sets are not merely different in number; they are cut and
rearranged differently along their whole length.

**The mammalian hybrid-viability window.** Wilson's group, and later Fitzpatrick (2004) using cytochrome *b*
and phylogenetically appropriate statistics, found that **mammals lose the ability to form viable hybrids
after roughly 2–4 Myr of divergence**, against about 21 Myr in birds. Wilson's group attributed this to
faster regulatory evolution in mammals (PI-S12; numbers from citing papers, not the paywalled original). Human
versus rabbit, dog, or cat is therefore roughly **20–45 times beyond the window** in which mammals still make
viable hybrids, before fertility is even considered **[repo analysis on PI-S12, PI-S13]**.

### 5.2 Why chromosome mismatch causes sterility

- **Pairing failure (asynapsis).** In sterile F1 males from two mouse *subspecies*, most early pachytene
  spermatocytes had several unsynapsed autosomes. The unpaired chromosomes left DNA breaks unrepaired, which
  triggers the meiotic checkpoint and cell death (PI-S08). The striking control: when a chromosome pair was
  the same subspecies on both copies, it paired normally, even in a hybrid. Asynapsis tracked the
  **heterospecific status of the homolog pair**, not chromosome number. The authors suggest fast-evolving
  noncoding sequence divergence disrupts pairing, which they flag as still untested. **Implication [repo
  analysis]:** chromosome-number matching is not enough. Homologs must also be similar enough in sequence to
  pair.
- **Sex asymmetry.** Hybrid females of the same cross were fertile (Haldane's rule), but 40–50% of their
  oocytes showed asynapsis (about half the male rate), most such oocytes were eliminated before birth, and
  surviving eggs had raised aneuploidy (9–11% against 2% in controls) (PI-S08).
- **Haldane's rule.** When one hybrid sex is absent, rare, or sterile, it is the heterogametic sex (XY males in
  mammals). Presgraves (2008) found it in all 26 mammal species considered. The main explanations are
  recessive X-linked incompatibilities (dominance theory) and the faster evolution and greater fragility of
  male reproduction (faster-male theory); faster-X effects and meiotic drive are supporting candidates
  (PI-S07). **For engineered lineages:** if any heterospecific chromosome pairing survives in a lineage's
  genome, males are expected to suffer first.
- **Rearrangement heterozygotes.** A mule and a hinny (2n = 63) showed pairing abnormalities in most germ cells
  at pachytene (PI-S05, PI-S06). In house mice, hybrids carrying a chain of four chromosomes (a small
  monobrachial-fusion difference) were not sterile but lost **about 50% of fertility**, with 16.7% meiotic
  aneuploidy and 50.9% germ-cell death in males (PI-S09). In common shrews, simple Robertsonian heterozygotes
  had under 10% synaptic aberrations, while carriers of complex multi-chromosome configurations had multiple
  pairing failures (PI-S10).

### 5.3 Fertile hybrids despite different chromosome numbers

- **Przewalski's horse (2n = 66) × domestic horse (2n = 64).** The F1 has 65 chromosomes and is fertile. The
  difference is a single Robertsonian rearrangement: one domestic horse metacentric (ECA5) corresponds to two
  Przewalski acrocentrics (EPR23 and EPR24). The genome analysis supports this, and the event did not add
  local rearrangements (PI-S05). Meiosis in this hybrid was normal (PI-S06). The direction (fusion in
  domestics versus fission in Przewalski's) is **[contested]**.
- **Mechanism:** a Robertsonian difference leaves gene content and order intact. The single metacentric pairs
  with both acrocentrics as a trivalent and segregates mostly correctly. Simple heterozygotes are the mildest
  case; complex chains are where fertility collapses (PI-S09, PI-S10).
- **Fertile female mules.** Rare, cytogenetically verified exceptions exist. A fertile female mule and a
  fertile female hinny in China each produced a foal by a donkey, and the foals had unique hybrid karyotypes
  (PI-S11). A 2002 Moroccan case appears only in uncited secondary pages (**dead end**, see search log).
  Fertility in these cases is exceptional, female only, and the offspring karyotypes are irregular.

**Bound for the fiction [repo analysis]:** the known fertile mismatches are separated by one or a few
whole-arm rearrangements within a genus, a few million years apart at most. Nothing in real biology
approaches meiotic compatibility across ~90 Myr.

### 5.4 Human–animal chimera research: what was achieved, and the limits

A chimera mixes *cells* of two species in one body; it is not a hybrid genome. It is still the closest real
work to "human plus animal in one developing body."

| Study | What was done | Best result | Limit |
|---|---|---|---|
| Rat ↔ mouse (Kobayashi 2010; Yamaguchi 2017) | Rat cells into *Pdx1*-null mouse blastocysts, and the reverse | A functional rat-cell pancreas in mice (PI-S17); mouse-cell pancreases in rats whose islets cured diabetic mice for >370 days without immunosuppression (PI-S18) | **Organ size followed the host:** the rat-cell pancreas grown in a mouse was mouse-sized (PI-S18) |
| Rat ↔ mouse, in Wu 2017 | Rat PSCs into mouse embryos | About 20% chimerism efficiency; up to ~10% contribution in heart; one chimera lived 2 years (PI-S14) | Rat–mouse divergence is small |
| Human → pig (Wu 2017) | 1,466 human-iPSC-injected pig embryos transferred to sows; recovered at day 21–28 | Human cells confirmed in some embryos; contribution "much lower" than rat–mouse; many fluorescence-positive embryos were growth-retarded (PI-S14). Press accounts give about 1 human cell per 100,000 (PI-S19) | Authors cite evolutionary distance and developmental-timing mismatch. Rat and mouse PSCs showed **no** detectable contribution to pig embryos (PI-S14) |
| Human → sheep (Ross and Nakauchi, 2018) | Human cells into sheep embryos, gestated 28 days | About 1 human cell per 10,000 (PI-S19) | Conference presentation only; no peer-reviewed paper found |
| Human → monkey (Tan 2021) | Human extended PSCs into 132 cynomolgus embryos, cultured *ex vivo* | 3–4% human cells on average, up to 7% in one embryo; 3 embryos survived to day 19 (PI-S15) | Not implanted; steep embryo loss |
| Human → pig kidney niche (Wang 2023) | *SIX1/SALL1*-null pig embryos (kidney niche emptied); human iPSCs given inducible *MYCN* and *BCL2* to survive competition; 1,820 embryos into 13 sows | Five chimeric embryos analyzed at day 25–28; mesonephros about 50–60% human cells (PI-S16) | Needed both an emptied niche and pro-survival engineering of the human cells; experts flagged the oncogene and degeneration risks (PI-S16) |

**Barriers named in the literature (PI-S14, PI-S20):** evolutionary distance; developmental incompatibility;
cell competition, where host cells eliminate the "loser" human cells by apoptosis; mismatched developmental
timing; and species differences in epiblast and trophectoderm development. None of the studies reviewed here
carried a human–nonhuman chimeric embryo past 28 days of gestation. **The highest human contribution achieved
in a living animal embryo is roughly half of one organ, for under a month, in a niche emptied for it.**

### 5.5 Genome-scale engineering: what is feasible now

| Milestone | Scale | Source |
|---|---|---|
| Syn61 *E. coli* | A fully synthetic 4 Mb genome, with 18,214 codons recoded to free three codons; the strain is viable but grows more slowly with longer cells | PI-S21 |
| Sc2.0 synthetic yeast | 6.5 synthetic chromosomes consolidated in one strain, then the largest (synIV) substituted, for >50% of the genome in one strain by 2023. Full completion was not confirmed by the sources found | PI-S22 |
| eGenesis donor pig | 69 genomic edits in one mammal: glycan antigens removed, 7 human transgenes added, endogenous retroviruses inactivated. Kidneys with the full edit set kept monkeys alive for a median of about 176 days, with one over 2 years; glycan knockouts alone did poorly | PI-S23 |
| SynHG (2025) | Five-year, £10 million program to build *tools* for human genome synthesis. Target: one synthetic human chromosome (about 2% of the genome) in roughly 5–10 years; a whole synthetic human genome is expected to take decades | PI-S24 |

**Gap to the fiction [repo analysis]:** current practice is tens of edits in a mammal, or a whole genome in a
bacterium or half of one in yeast. An anthro genome would mean designing and building a mammalian genome of
roughly 3 Gb with no natural template, plus its epigenetic programming. That is the ground HW-1 waves. The
direction of the real field (recoding, consolidation, multiplex editing) makes the *kind* of capability
plausible for an advanced creator. The *scale* is the handwave.

### 5.6 Developmental compatibility

**Imprinting.**
- Mouse embryos with two maternal or two paternal genomes fail; both parental genomes are required for
  development to term. Paternal genes are especially needed for the extraembryonic tissues, including the
  placenta (PI-S25).
- In *Peromyscus* hybrids, imprinting is widely disrupted. The reciprocal crosses show placental dysplasia and
  fetal overgrowth or undergrowth, tied to loss of imprinting at *Peg3*, *Mest*, *Snrpn*, *H19*, and *Grb10*.
  The authors suggest that the signals controlling imprinting **evolve quickly** and may contribute to
  mammalian speciation (PI-S26).
- Imprinting maps differ even between well-studied species. *Igf2r* is imprinted in all mouse tissues, but
  human *IGF2R* is biallelic in adults and only polymorphically imprinted in some fetal tissues (PI-S27).
- **Implication [repo analysis]:** a spliced genome inherits two incompatible imprinting maps. The creators
  must specify one coherent set of imprinted loci and their control regions. Failure would show as placental
  and fetal growth disorders, which is the documented hybrid phenotype.

**Placenta type.**

| Species | Interhemal type | Shape and exchange | Source |
|---|---|---|---|
| Human | Hemochorial, *hemomonochorial*; deep interstitial invasion | Discoid, villous | PI-S28 |
| Rabbit (Lagomorpha) | Hemochorial, *hemodichorial* (outer syncytial and inner cellular trophoblast) | Discoid to spherical, labyrinthine | PI-S28, PI-S29 |
| Dog, cat (Carnivora) | **Endotheliochorial** | Zonary (circumferential), labyrinthine | PI-S28, PI-S29 |

- Human and rabbit share the hemochorial family. Dog and cat do not.
- Placental structure is considered phylogenetically conservative, but it varies within some orders (bats; a
  few rodents) (PI-S28). A splice therefore *chooses* a placental program; it cannot average two.
- **Consequence for neonatal immunity.** The number of tissue layers sets how much maternal IgG crosses before
  birth. In dogs only about 4.5–6% of the maternal titer crosses the placenta, so puppies depend on colostrum,
  which is strongly enriched in IgG (PI-S34). Humans receive most of their maternal IgG across the placenta via
  FcRn (PI-S34). Rabbits transfer IgG before birth across the yolk sac, not the trophoblast (PI-S35). **[repo
  analysis]:** a carnivore-type placenta binds a newborn's survival to early nursing. That makes the placenta
  choice a behavior-relevant charter item (M-1 coherence: reproduction ↔ neonatal state ↔ rearing).

**Xenogeneic pregnancy (relevant to generation zero).** Donkey embryos transferred into horse mares form a
small chorionic girdle that fails to invade, no endometrial cups form, and a strong maternal cell-mediated
reaction targets the donkey trophoblast. About 70–80% abort around days 80–100. Immunizing the mare against
donkey lymphocytes reduced losses, and hormone support did not (PI-S30). Horse and donkey diverged far more
recently than human and rabbit. **[repo analysis]:** the first anthros could not plausibly be carried by an
unmodified human, rabbit, dog, or cat mother. Generation zero needs an engineered gestation route.

**Maternal size constraint.** In Shire × Shetland reciprocal crosses, foal birth size and placental weight
tracked the *dam's* size rather than the midpoint of the parents (PI-S31, summary of the 1938 work). A rabbit
uterus could not carry a human-scale fetus, and maternal size bounds neonate size in the established species
too.

**Developmental tempo.** Mouse and human segmentation clocks run at species-specific periods (2–3 h against
5–6 h) because of slower biochemical reactions, including protein degradation, in human cells (PI-S32). In
human motor-neuron differentiation, a roughly twofold slower pace correlated with roughly twofold greater
protein stability and longer cell cycles. Signal sensitivity and gene-regulatory order did not explain it
(PI-S32). A 2024 preprint extended slower degradation to ~5,000 proteins (secondary). **[repo analysis]:** tempo
looks like a *genome-wide* property, not a single switch. A mosaic genome cannot run a rabbit-tempo gut and a
human-tempo brain by default. The charter must set one developmental tempo, and that tempo then drives
gestation and maturation (RQ-6).

**Mitochondrial–nuclear compatibility.** Human cells with no mtDNA can be rescued by chimpanzee or gorilla
mtDNA, but not by mtDNA from more distant primates such as the orangutan. The authors attribute this to
species-specific co-evolution of the two genomes (PI-S33). Rabbit, dog, and cat mitochondria are about 90 Myr
from human nuclear genes. **[repo analysis]:** the charter must pick one mitochondrial lineage and match the
nuclear-encoded respiratory-chain genes to it.

**Immune coherence.** In a pig donor, removing three glycan antigens alone gave poor graft survival in
monkeys. Adding seven human transgenes was needed for long survival (PI-S23). **[repo analysis]:** a body
built from two proteomes must be self-tolerant to both, with one coherent MHC and complement system. Once the
species exists, mother and fetus are the same species, and normal maternal–fetal tolerance applies. The
xenogeneic problem belongs to generation zero (see above) and to any cross-species mating.

### 5.7 RQ-5 summary: what a viable, fertile, self-reproducing splice needs fixed

"Natural" hybridization is ruled out by every line of evidence above. HW-1 is therefore read as an
**engineered single genome** that founds a new species, **not** as a hybrid of the two parents. Each fix below
is a candidate Design Charter item; the tags are in the proposals section.

1. **One karyotype, homozygous across the founders.** Every chromosome has a fully sequence-compatible
   homolog. This is required for meiosis, and males fail first otherwise (PI-S07, PI-S08).
2. **One coherent imprinting map** (PI-S25, PI-S26, PI-S27).
3. **One placental program and its passive-immunity route** (PI-S28, PI-S34, PI-S35).
4. **One developmental tempo** (PI-S32), which then has to agree with RQ-6.
5. **Matched mitochondrial and nuclear respiratory genes** (PI-S33).
6. **A self-tolerant immune system** with one MHC and complement system (PI-S23).
7. **A generation-zero gestation route**, such as an artificial womb or an engineered surrogate (PI-S30,
   PI-S31, PI-S14).
8. **A founding population with genetic diversity.** This matters for M-1 Step 5 founder effects. It is a
   biological requirement for long-term natural reproduction, though this pass did not source it; see Gaps.

**Consequences that follow without further handwaves [repo analysis]:**
- The new species is reproductively isolated from humans and from its base animal (§5.1–5.3).
- Two lineages built to **different** karyotype designs would be partly or wholly isolated from each other.
  Simple differences give reduced fertility (PI-S09, PI-S10); deep differences give sterility. This bears
  directly on **Q-15**: cross-lineage fertility is a charter fact that depends on shared genome architecture,
  not on the shared base animal.

---

## RQ-6 Body-size scaling — with a worked "human-sized rabbit / dog / cat" prediction table

### 6.1 The general law and its debate

General form: **Y = a·M^b**, linear on log–log axes.

| Quantity | Equation | Units | Source |
|---|---|---|---|
| Basal metabolic rate (Kleiber) | B ≈ 70·M^0.75 kcal/day ≈ 3.4·M^0.75 W | M in kg | PI-S40 (1961 form; the 1932 fit was ≈ 0.74 per Smil's account) |
| Resting heart rate | f ≈ 241·M^−0.25 beats/min | M in kg | PI-S45 (exponent −0.25, r ≈ −0.88, visible in the scanned table; coefficient illegible), PI-S46 (241 coefficient, secondary) |
| Maximum longevity, mammals without cetaceans | t_max = 4.88·M^0.153 years (n = 856) | M in g | PI-S48 |
| Same, without bats | t_max = 3.34·M^0.193 years (n = 783, r² = 0.57) | M in g | PI-S48 |
| Primates only | t_max = 6.47·M^0.189 years (n = 137) | M in g | PI-S48 |
| Time to maturity (**conception to sexual maturity**, sexes averaged) | t_sex = 0.263·M^0.214 years (n = 606, r² = 0.50) | M in g | PI-S48 |
| Adult lifespan vs maturity | adult span = 11.8·t_sex^0.622 | years | PI-S48 |
| Gestation, PGLS by order | slope b: Carnivora 0.10–0.20; Rodentia 0.06–0.13; Primates 0.06–0.13; Artiodactyla 0.05–0.11; all orders 0.10–0.14 (95% CI), all **below** the metabolic-theory 0.25 | days, M in g | PI-S50 |
| Gestation, all eutherians | OLS b ≈ 0.18–0.20; PGLS b ≈ 0.07–0.10 (1,214 species) | | PI-S49 |
| Mass-specific production (offspring mass per year ÷ adult mass) | 0.98·M^−0.28 per year across 637 species; lagomorph slope −0.208 ± 0.076; fissiped carnivores −0.461 ± 0.059 | M in g, y⁻¹ | PI-S51 |
| Lifetime heartbeats | mean ≈ 7.3 ± 5.6 × 10⁸ across mammals | | PI-S47 |

**The 3/4 debate [contested].**
- Kleiber's ¾ exponent is classic (PI-S40). West, Brown and Enquist explained it with fractal supply networks
  (PI-S41).
- That model was called mathematically inconsistent (Kozłowski & Konarzewski 2004), defended (Brown et al.
  2005), rederived on weaker assumptions (Etienne et al. 2006), and found at odds with finite-size data
  (Savage et al. 2008) (PI-S42).
- Glazier showed the exponent is **not universal**, within or among species, and proposed metabolic-level
  boundaries between ⅔ and 1 (PI-S43).
- Kolokotrones et al. found the mammalian relationship **curved** on log–log axes, convex. Datasets dominated
  by small species give ≈ ⅔, and those dominated by large species give ≈ ¾ (PI-S44). The curvature runs
  opposite to the West–Brown–Enquist prediction.
- **Practical effect [repo analysis]:** scaling a 1.8 kg rabbit's measured BMR (7.40 W, PI-S58) to 65 kg gives
  about **81 W with b = ⅔** and **109 W with b = ¾**. The choice of exponent moves the answer by about 35%.

**Metabolism does not set lifespan [contested, but the better-supported view].** With body mass and phylogeny
controlled, BMR does not correlate with longevity in eutherians (PI-S48). Bats outlive non-flying eutherians of
their size by at least 3× without lower BMR (PI-S54). Levine treats the near-constant heartbeats per lifetime
as an epiphenomenon of energetics (PI-S47). **The "fixed heartbeat budget" is not a usable mechanism.**
Development time is the better predictor: species that mature late for their size live long for their size
(PI-S48).

**Within-clade scaling is weaker than across-clade scaling.** For gestation, phylogeny-corrected slopes are
about half the conventional ones (PI-S49, PI-S50). Litter size shows **no** within-order correlation with body
mass in Lagomorpha, Rodentia, or Primates, although it falls with mass across mammals as a whole (PI-S52).
Lineage shifts the intercept far more than the slope: lagomorphs are among the most productive mammals for
their size (PI-S51). The precocial orders (primates, artiodactyls) have higher gestation intercepts than the
altricial ones (rodents, carnivores) (PI-S50). **Phylogeny is the main reason a species departs from the
mammal-wide line.**

### 6.2 The outliers: how far real mammals deviate

**Longevity quotient** (LQ) is observed t_max divided by the t_max predicted for that mass. The regression
values here are this file's arithmetic using PI-S48 and PI-S58.

| Case | LQ | Why (per source) |
|---|---|---|
| Bats | ≥ 3 on average (PI-S54) | Reduced extrinsic mortality from flight; not low BMR, torpor, or brain size (PI-S54, PI-S55) |
| Naked mole-rat | ~5× predicted for a 40 g rodent; maximum lifespan over 30 years; mortality hazard **does not rise with age** (PI-S56) | Fossorial, eusocial; low extrinsic risk (PI-S55) |
| Human | ≈ 4.6 (122.5 yr, against ≈ 26 yr predicted at 62 kg) | Primates have long development for their size (PI-S48) |
| Puma, leopard | ≈ 1.0 | Typical mammal |
| Domestic dog | ≈ 1.1 | |
| Capybara | ≈ 0.6 | |
| European rabbit | ≈ 0.85 | |
| Brown hare | ≈ 0.6 | |
| Domestic cat | ≈ 1.7 | The 30-year record comes from an enormous captive population **[repo analysis: likely sample-size inflation]** |

- **Arboreality and fossoriality** also lengthen lifespan in non-flying mammals; flight is the strongest
  factor (PI-S55).
- **Within one species, size reverses the trend.** Large dog breeds age faster: they show similar baseline
  mortality and onset of senescence, but mortality rises faster once aging begins. The suggested cause is
  costs of rapid growth (PI-S57). **[repo analysis]:** an engineered size increase achieved by speeding up
  growth would more plausibly give the dog-breed pattern (shorter life) than the across-species pattern
  (longer life). Long life at large size is a property of an evolved *slow* life history, not of size itself.

**The real-mammal envelope at roughly human mass** (AnAge, PI-S58):

| Species | Mass (kg) | Gestation (d) | Litter | Female maturity (d, from birth) | t_max (yr) |
|---|---|---|---|---|---|
| Gray wolf | 26.6 | 62 | 6 | 669 | 20.6 |
| Domestic dog (species entry) | 40 | 63 | 6 | 510 | 27 |
| Leopard | 53.8 | 97 | 2 | 937 | 27.3 |
| Capybara | 55 | 150 | 4.8 | 456 | 15.1 |
| Human | 62 | 280 | 1 | 4,745 | 122.5 |
| Puma | 63 | 92 | 2.5 | 912 | 27 |
| Wild boar | 130 | 115 | 7 | 334 | 27 |

At about 50–130 kg, real placental mammals span gestation of ~60–280 days, litters of 1–7, female maturity of
~0.9–13 years, and maximum lifespan of ~15–122 years. Larger mammals tend toward one or two young per year
(PI-S52), but wolves, capybaras, and wild boar show that large litters persist at this size where the lineage
carries them.

### 6.3 Worked predictions: a human-sized rabbit, dog, and cat

**Method [repo analysis].** Two estimators are shown, plus a real analog.
1. **Lineage-scaled:** the base species' own value × (M_target ÷ M_base)^b. This keeps the lineage's offset
   from the mammal line, which is the phylogenetic effect of §6.1.
2. **Pan-mammal:** the absolute regression value at the target mass.
3. **Real analog:** a real mammal of about human size from the same order, where one exists.

The target is 65 kg, with the 50–80 kg range in brackets. Exponents are from §6.1.
- Gestation: b = 0.10–0.20 (the PGLS range, PI-S50), with 0.07 and 0.25 as outer bounds.
- Maturity: b = 0.214 (PI-S48).
- Lifespan: b = 0.153–0.193 (PI-S48).
- BMR: b = ⅔–¾.
- Heart rate: b = −0.25.

These are **what scaling predicts**, not what the race is. M-1 decides, and a charter may override within the
envelope (M-7 guard "body size is not destiny").

**Base values (PI-S58 unless noted):**
- **Rabbit:** 1.8 kg; gestation 30 d; litter 5; 4.3 litters/yr; t_max 13 yr; BMR 7.40 W. Female maturity is
  about 4–5 months in field sources (PI-S60), but **AnAge lists 730 d**. That conflict is unresolved (see
  Gaps); this table uses the field value.
- **Dog:** the gray wolf (26.6 kg; 62 d; litter 6; maturity 669 d; t_max 20.6 yr) as the undomesticated
  baseline. The domestic dog species entry (40 kg; 63 d; litter 6; 510 d; 27 yr) is noted alongside.
- **Cat:** 3.9 kg; 65 d; litter 4; maturity 289 d (female) and 304 d (male); t_max 30 yr.

| Prediction at 65 kg [50–80] | Human-sized **rabbit** | Human-sized **dog** | Human-sized **cat** | Human (reference) |
|---|---|---|---|---|
| Mass ratio to base | ×36 [28–44] | ×2.4 [1.9–3.0] from wolf | ×17 [13–21] | — |
| BMR, Kleiber at the mass | 78 W ≈ 1,600 kcal/d [64–91 W] | same | same | 83 W measured (AnAge) |
| BMR, keeping the rabbit's measured rate | 81 W (b = ⅔) to 109 W (b = ¾) [68–127 W]; the rabbit runs about 1.4× Kleiber | (no AnAge BMR) | (no AnAge BMR) | about 1.1× Kleiber |
| Resting heart rate (241·M^−0.25) | ≈ 85 bpm [81–91] | same | same | — |
| **Gestation**, lineage-scaled | **43–61 d** (b 0.10–0.20); outer bounds 39–74 d | **68–74 d**; outer 66–78 d | **86–114 d**; outer 79–131 d | 280 d |
| Gestation, real analog | none in Lagomorpha. Largest living leporid: hare, 4.2 kg, 42 d, precocial. Capybara (rodent, 55 kg): 150 d | Wolf 62 d at 27 kg | Puma 92 d; leopard 97 d | — |
| **Litter size**, lineage-held (PGLS: no within-order trend in Lagomorpha, PI-S52) | 5 | 6 | 4 | 1 |
| Litter size, pan-mammal −0.136 (**unsourced compilation; cross-check only**) | ≈ 3 | ≈ 5 | ≈ 2.7 | — |
| Annual offspring output relative to body mass, as a fraction of the base species' (PI-S51 slopes) | **0.37–0.47×** (all-mammal −0.28 to lagomorph −0.208) | 0.66–0.78× (carnivore −0.461 to all-mammal −0.28) | 0.27–0.45× (carnivore −0.461 to all-mammal −0.28) | — |
| Litter, real analog | capybara 4.8; boar 7 | wolf 6 | puma 2.5; leopard 2 | — |
| **Maturity**, conception to maturity, lineage-scaled | 0.90–1.07 yr | 2.4 yr | 1.8 yr | 14.3 yr |
| Maturity, approximate birth to maturity | **≈ 0.7–1.0 yr** | **≈ 2.2 yr** | **≈ 1.5 yr** | ≈ 13.5 yr |
| Maturity, pan-mammal (t_sex) | 2.8 yr | 2.8 yr | 2.8 yr | — |
| Maturity, real analog | capybara 1.25 yr; boar 0.9 yr | wolf 1.8 yr | puma 2.5 yr; leopard 2.6 yr | — |
| **Maximum lifespan**, lineage-scaled | **≈ 22–26 yr** | **≈ 24–25 yr** | 46–52 yr if the domestic-cat record is taken at face value; ≈ 27 yr on the pan-mammal line | 122.5 yr |
| Maximum lifespan, pan-mammal | 26.6 yr [25.5–27.5] | same | same | — |
| Maximum lifespan, real analog | capybara 15 yr; boar 27 yr | wolf 20.6 yr; dog record 27 yr | puma 27 yr; leopard 27.3 yr | — |

**Reading the table [repo analysis].**

- **Rabbit.** A human-sized rabbit body is about 36× its base mass. No lagomorph has ever reached it: the
  largest known, the island giant *Nuralagus rex*, was about 8–12 kg (PI-S59).
  - Scaling predicts gestation stretching to roughly 1.5–2 months.
  - Maturity stretches to under a year.
  - Maximum life is about two decades, typical mammal territory and **far** below a human's.
  - The binding constraint is **reproductive output**. The lineage can keep a litter of about 5, since the
    lagomorph PGLS shows no forced litter shrinkage, but mass-specific production should fall to about 40–50%
    of a rabbit's. So it can have the litter, *or* rabbit-like breeding frequency, *or* relatively large
    neonates, not all three.
  - A human-sized rabbit-person with a 30-day gestation, litters of 5 or more, 4 or more litters a year, and
    maturity at 4 months is **outside** the scaling. Read the other way, those traits only fit a 2 kg body.
- **Dog.** The wolf is already within a factor of 2–3 of human mass, so scaling changes little: gestation
  about 2.2–2.5 months, litters of about 5–6, maturity about 2 years, maximum life about 24 years. **The
  domestic-dog caveat (PI-S57) matters most here.** If the size comes from growth acceleration, expect
  large-breed aging (earlier death), not the wolf line.
- **Cat.** Scaling a domestic cat predicts gestation of about 3–4 months, litters of about 3–4, and maturity
  around 1.5 years. Real human-sized felids (puma, leopard) mature later (about 2.5 years) and have smaller
  litters (2–2.5) than the scaled cat. **[repo analysis]:** the scaled maturity is a lower bound, and the
  felid analogs are the better forecast. The 46–52-year lifespan is an artifact of the domestic cat's record
  and should not be used. Real large felids give about 27 years.

### 6.4 How far can engineering or phylogeny plausibly deviate?

This proposes the bounds for D-7 "plausible", for developer review.

| Trait | Plausible (cost: show the mechanism and the trade-off) | Bend (no real mammal precedent at this size) | Basis |
|---|---|---|---|
| Lifespan | LQ up to about 5 (human 4.6; naked mole-rat about 5). Must come **with** a slow life history, meaning late maturity and low reproduction (PI-S48), and reduced extrinsic mortality as the evolutionary reason (PI-S54, PI-S55, PI-S56) | LQ well above ~5 in a non-flying human-sized mammal; or long life combined with fast maturity and high fecundity | PI-S48, PI-S54, PI-S56 |
| Gestation | Any value within about 60–280 days at 50–80 kg, **if** the neonatal state matches (short gestation means altricial young; long means precocial young) | Under about 40 days at human size (below even the lowest lineage-scaled rabbit value) with large, developed neonates | PI-S50, PI-S58 |
| Litter size | 1–7 (the real range at 50–130 kg), consistent with mass-specific production (PI-S51) and with maternal pelvis and neonate size (PI-S31) | Litters above about 7, or rabbit-scale annual output, at human size | PI-S51, PI-S52, PI-S58 |
| Maturation | About 0.9–13 years from birth, consistent with lifespan (PI-S48) | Maturity in a few months at human size; or human-length childhood with rabbit-scale lifespan *and* fecundity | PI-S48, PI-S58 |
| Metabolic rate | About ±40% around Kleiber at the mass (rabbit +40%; exponent uncertainty about 35%). Stahl notes species deviate by 50% or more on derived invariants (PI-S45) | Rates needing multiples of Kleiber without the food intake and heat dissipation to match | PI-S40, PI-S43, PI-S45 |

---

## RQ-8 Domestication syndrome

### 8.1 The trait suite

Darwin observed that domesticated mammals share heritable traits absent in their wild ancestors (PI-S70, via
PI-S71). Wilkins et al. list (PI-S71):
- depigmentation (white or brown patches);
- floppy ears;
- shorter muzzles and smaller teeth and jaws;
- relatively smaller brains;
- curly tails;
- reduced adrenal stress hormones;
- more frequent estrous cycles;
- juvenile behavior, including docility.

### 8.2 The neural crest hypothesis [contested]

**Claim (PI-S71).** Selection for tameness reduces neural crest cell input during embryonic development. That
shrinks the adrenal "fight-or-flight" output, and the other neural-crest-derived tissues (pigment cells,
facial skeleton, teeth, ear cartilage) change as unselected side effects. The authors noted it had not yet
been tested. In 2021 they renamed it the "neural crest/domestication syndrome" (NCDS) hypothesis (PI-S71).

**Critiques.**
- **The suite is not universal.** Among mammals, only canids show a large set of the predicted traits.
  Domestic traits behave as modules that breeding can reorder, add, or remove (PI-S72).
- **No species passes the test.** Lord et al. could not find a single species meeting all three of their
  criteria for the syndrome, and judged it overstated (PI-S73). Wright et al. challenged this in a letter; the
  authors replied that the burden of proof had not been met (PI-S73, secondary).
- **"An explanation looking for a problem."** Johnsson et al. argue (PI-S74):
  - the core traits (tameness, size, brain, color) do not change consistently across species;
  - domestication traits are polygenic across many pathways;
  - a correlated response does not prove pleiotropy, since linked selection can mimic it;
  - in chickens, apparently shared loci split into separate linked loci with more recombination, and in rats
    tameness and aggression loci were only weakly linked;
  - selective-sweep scans mostly capture recent breed formation, not early domestication;
  - so it is premature to propose any unifying mechanism.
- **Status for this repo:** the **co-occurrence** of some traits under domestication is documented. **Whether
  they form one syndrome with one developmental cause is contested.** M-1 Step 5 should model domestication
  effects **trait by trait, with a mechanism for each**, and should not import "the syndrome" as a package.

### 8.3 The Belyaev–Trut farm-fox experiment, and the revised founder history

**The experiment as reported by its own team (PI-S75, full text).**
- **Founders:** 100 females and 30 males, chosen as about the 10% of foxes that showed the weakest
  aggressive or avoidance response.
- **Founder stock:** drawn from several farm populations that had already been farm-bred for about 50 years.
  Thousands of farm foxes were tested to find them.
- **Selection intensity:** fewer than 10% of each generation became parents.
- **Behavior over generations:**

| Generation | Change |
|---|---|
| 2–3 | Aggressive and fearful offspring eliminated |
| 4 | Dog-like tail wagging appears |
| 6 | Contact-seeking "elite" pups appear: 1.8% (4 of 213) |
| 10 | Elite 17.9% (66 of 379) |
| 20 | Elite 35% (503 of 1,438) |
| 30 | Elite 49% (804 of 1,641) |
| By 2005–2006 | Almost all foxes classed elite |

- **Morphology:** coat-color changes, mainly "Star" piebald spotting and brown mottling, appeared first, in
  generations 8–10. Floppy ears, curly tails, and shorter snouts, legs, and tails came later and at low
  frequency. **Some of these changes also appeared in unselected farm populations.**
- **Physiology:**
  - basal cortisol about half the farm level by generation 20;
  - basal and stress cortisol 3× and 5× lower by generation 45;
  - higher brain serotonin;
  - sexual maturity about one month earlier;
  - some tame lines mating outside the single annual season.

**Revised model [contested].**
- **The founder history (PI-S73).** Genetic testing traced the experiment's foxes to eastern Canada, probably
  fur farms on Prince Edward Island. Those farms had bred for unusual pelt colors, including white spotting,
  and photographs of tame-looking, spotted foxes there predate the Russian project. Karlsson's argument is that
  these traits were partly *pre-existing* in the founder stock, not created within ten generations. Trut
  disputes this and calls the contention "misguided."
- **What the experiment does and does not show.** Trut et al.'s own paper states that the founders came from
  long-farmed stock (PI-S75). Johnsson et al. add that the experiment cannot separate pleiotropy from linked
  selection (PI-S74).

**What survives either way.** Strong selection on behavior (fewer than 10% of each generation bred)
**measurably shifted behavior and the stress axis within about 6–20 generations**. Several morphological
markers rose in frequency in the selected line. The revised model leaves open how much was **released standing
variation** in a long-farmed stock rather than new change, and whether one mechanism links the traits.

### 8.4 Without deliberate selection: commensal drift

A free-living house-mouse population near Zurich got food and water but **no selective breeding**. Over about
a decade it showed significantly more white fur patches and shorter heads (PI-S76). A 2023 correction exists,
but its content could not be read (Gaps). The generation count was not extracted.

### 8.5 Base-animal domestication is already in the DNA

- **Rabbit.** The genetics of domestication were **polygenic**: many allele-frequency shifts, more than 100
  domestic-specific sweeps but few fixed changes, and enrichment in conserved noncoding (regulatory) sites near
  brain and neuronal development genes (PI-S77). Domestic rabbits have a smaller amygdala and a larger medial
  prefrontal cortex than wild rabbits raised under the same conditions; the study had only 8 per group
  (PI-S78).
- **[repo analysis]:** whether a creator sourced **wild or domestic** animal DNA decides whether
  domestication-associated alleles are present *at creation* (an L0/M-2 sequencing choice, D-4), separately
  from any drift afterward. The same applies to dog and cat; the cat question is not sourced here (Gaps).

### 8.6 Self-domestication: humans and bonobos [contested]

- **The hypothesis.** Selection against aggression can act like domestication in wild species. Hare et al.
  propose bonobos as a case: less severe aggression than chimpanzees, juvenilized development, and many
  differences arising as by-products (PI-S79). Benítez-Burraco et al. extend it to human cooperation and
  language (PI-S83).
- **Against it in bonobos.** A field study (12 bonobo and 14 chimpanzee males) found bonobo males had about
  2.8× more aggressive interactions and 3× more physical aggression, mostly male-to-male, and that more
  aggressive males of both species had higher mating success (PI-S82, secondary). The lead author said this
  does not really support the bonobo self-domestication hypothesis.
- **Against it in humans.**
  - Sánchez-Villagra and van Schaik accept parts of the evidence but question the theory. They argue that
    evidence from deliberate breeding (dogs, farm animals, the fox experiment) is misleading for an
    *unintentional* process (PI-S80, secondary).
  - Shilton et al. argue human social evolution resembles other social mammals more than domesticates, and
    propose selection for socially mediated emotional control instead (PI-S81).
- **Status for this repo:** self-domestication is a **contested hypothesis**. It must not be used as an
  established mechanism for any anthro lineage. If used at all, label it as contested and give the selective
  condition, per `CLAUDE.md` rule 3.

### 8.7 Relevance: would creator-managed lineages show domestication traits, and how fast?

All of the following is **[repo analysis on PI-S73 to PI-S78]**.

- **If creators selected for tractability or low reactivity** (a charter item, M-4): expect behavioral and
  stress-axis (HPA) shifts within about **6–20 generations** under strong selection (the fox benchmark, about
  10% of each generation bred). Some pigmentation and skull-shape markers may rise in frequency over a similar
  span, with modest effect sizes. Weaker selection means slower change. Fox data are in fox generations: convert
  through each lineage's P-5 (M-7 Step 2).
- **If creators only housed and fed a lineage without selection:** the commensal-mouse result suggests some
  depigmentation and skull change is possible on a decade scale in a short-generation species. For a
  long-generation anthro, the magnitude is unsourced. Record direction only (M-1 Step 5 rule).
- **What not to assume:** a full "syndrome" package (contested), or any single developmental switch
  (contested). Each trait needs its own mechanism, and the fox founder-stock caveat must be stated.
- **What may already be fixed at creation:** domestic-stock alleles in the base-animal DNA (§8.5). M-1 should
  tag these as inherited at creation, not as drift.

---

## Candidate Design-Charter fixes and handwave candidates (proposed HWC- entries with bend/cost tags — proposals only, do NOT edit HANDWAVES.md)

**Proposals only.** Nothing here is registered in `HANDWAVES.md`. Codes are provisional and are assigned on
registration.
- **Tag meanings** (from `HANDWAVES.md`): **cost** means biology holds, but a mechanism, resource, or
  vulnerability must be accepted and shown; **bend** means biology would have to give.
- **Recommendation column** is this file's view; the developer rules (D-7, `CLAUDE.md` rule 6).

### A. Fixes inside HW-1 (needed for the splice to found a self-reproducing species)

HW-1 waves "the splice works." These candidates make explicit **what the splice must have fixed**, so that
"works" isn't read as a free pass. Each would become a Design Charter item (M-4) per lineage.

| # | Candidate | Tag | What is waved | What is NOT waved (must be shown) | Basis |
|--:|---|---|---|---|---|
| HWC-1 | **Unified karyotype.** The genome is one engineered karyotype with fully sequence-compatible homologs, and the founders are homozygous for it | cost | Building it (HW-1 scale) | The lineage is reproductively isolated from humans and from its base animal. Its males are the sensitive sex if any heterospecific pairing remains | PI-S05 to PI-S12 |
| HWC-2 | **Coherent imprinting map** | cost | Specifying it | Early-generation risk of placental and fetal growth disorders as a known vulnerability (L1 domain 17), if the charter was imperfect | PI-S25, PI-S26, PI-S27 |
| HWC-3 | **Placental program chosen** (hemochorial or endotheliochorial) | cost | — | Its consequences: neonatal passive immunity (prenatal transfer, or colostrum and early-nursing dependence) and the rearing behavior that follows | PI-S28, PI-S29, PI-S34, PI-S35 |
| HWC-4 | **One developmental tempo** | cost | Setting it | That tempo drives gestation and maturation and must pass RQ-6. Organs cannot run at different species' tempos by default | PI-S32 |
| HWC-5 | **Mitonuclear match** | cost | Re-engineering the nuclear respiratory-chain genes or the mtDNA | One maternal mitochondrial lineage per lineage design | PI-S33 |
| HWC-6 | **Self-tolerant immune system** (one MHC and complement system across a mixed proteome) | cost | Its design | Any autoimmune or vulnerability residue goes in domain 17 | PI-S23 |
| HWC-7 | **Generation-zero gestation route** (artificial womb or engineered surrogate) | cost | The technology | Unmodified human, rabbit, dog, or cat mothers cannot carry generation zero (xenogeneic rejection; maternal size constraint). **Q for developer:** which route, per lineage? It also feeds Q-17 and Q-19 | PI-S30, PI-S31, PI-S14 to PI-S16 |
| HWC-8 | **Founder diversity** | cost | — | Founding population size and diversity set inbreeding and founder effects (M-1 Step 5). Unsourced in this pass (Gaps) | (Gaps) |

### B. Candidates that would bend biology

| # | Candidate | Tag | What the fiction would have to settle | Recommendation |
|--:|---|---|---|---|
| HWC-9 | **Anthro × human (or × base animal) interfertility** | **bend** | Meiotic pairing across ~90 Myr of sequence and rearrangement divergence; the mammalian hybrid-viability window is ~2–4 Myr; asynapsis tracks sequence divergence, not just number (PI-S08, PI-S12, PI-S13) | Reject as fantastical, **unless** a lineage's charter built its genome on a human chromosome scaffold *and* sequence-compatible homologs. Even then, expect reduced fertility and male sterility first (Haldane's rule). Treat as a ruling for the developer |
| HWC-10 | **Base-animal life history kept at human size** (for example 30-day gestation, frequent large litters, maturity in months, in a 50–80 kg rabbit-derived body) | **bend** | Exceeds the production-rate scaling (PI-S51) and the real-mammal envelope (§6.2) | Reject as stated. A charter may push toward the edges of the envelope in §6.4 (cost) |
| HWC-11 | **Lifespan well above LQ ~5**, or long life with fast maturity and high fecundity | **bend** | No real mammal precedent; maturity and lifespan co-vary (PI-S48) | Reject. Long life within LQ ≤ ~5 is a cost item and needs a slow life history |
| HWC-12 | **Cross-lineage interbreeding** among lineages with *different* genome architectures | bend if the karyotypes differ; cost if shared | Q-15 | Interbreeding is plausible only where lineages share a karyotype design, for example co-designed or derived from one template. Otherwise expect partial or total isolation (PI-S09, PI-S10) |

### C. Cost items for M-1 and M-7 (not handwaves; charter overrides of allometry)

| # | Candidate | Tag | Note |
|--:|---|---|---|
| HWC-13 | **Charter life history off the lineage's allometric line but inside the real-mammal envelope** (§6.4) | cost | Must be recorded as `Charter` (M-7 guard) with its trade-off: for example longer gestation means fewer and more precocial young, and longer life means later maturity |
| HWC-14 | **Size reached by growth acceleration** | cost | Expect the large-dog-breed aging pattern (PI-S57) unless the charter also slowed the whole life history |
| HWC-15 | **Domestication-type drift under creator management** | cost (not a handwave; an M-1 Step 5 expectation) | Trait by trait, with mechanism and generation pace (§8.7); the syndrome package is contested |

---

## Search log

**Productive queries.**

RQ-5:
- Przewalski × domestic horse karyotype and fertility; Haldane's rule reviews; mouse hybrid asynapsis.
- Madeira and Robertsonian mouse fertility; *Sorex araneus* hybrid synapsis; fertile mule cases.
- Fitzpatrick 2004 hybrid inviability; TimeTree divergence times.
- Wu 2017 human–pig chimeras (full text read via PMC); Tan 2021 human–monkey; Wang 2023 humanized
  mesonephros; Kobayashi 2010 and Yamaguchi 2017; human–sheep 2018; chimera-barrier reviews.
- Syn61; Sc2.0; eGenesis 69-edit pig; SynHG.
- Placenta classification (Carter & Enders full text; Furukawa abstract); *Peromyscus* imprinting; *IGF2R*
  imprinting species difference; McGrath & Solter.
- Donkey-in-horse pregnancy; Walton & Hammond via Joubert & Hammond; Matsuda and Rayon 2020 developmental
  tempo; xenomitochondrial cybrids; canine and rabbit maternal IgG transfer.

RQ-6:
- Glazier 2005; Kolokotrones 2010; WBE and its critiques; Kleiber 1932 and 1961.
- Stahl 1967: the PDF was fetched and text-extracted. The table OCR was partly illegible; the heart-rate
  exponent −0.25 was visible but not the coefficient.
- de Magalhães 2007 (full text; confirmed t_sex = conception to maturity and M in grams).
- Clauss 2014; Jackson 2014 (full text); Sibly & Brown 2007 (full text; units confirmed as grams and y⁻¹);
  Werner & Griebeler 2011.
- Austad & Fischer 1991; Healy 2014; Ruby 2018; Kraus 2013.
- AnAge entries for 10 species; *Nuralagus rex*; wild rabbit age at first breeding.

RQ-8:
- Wilkins 2014; Sánchez-Villagra 2016; Lord 2020; Johnsson 2021 (full text).
- Trut 2009: the PMC page was blocked by a CAPTCHA, so the full text was retrieved through the NCBI BioC API.
- Geiger 2018; Carneiro 2014; Brusini 2018; Hare 2012; Sánchez-Villagra & van Schaik 2019; Shilton 2020;
  Mouginot 2024.

**Dead ends (logged per LAW 0-R).**
- Nature (srep04958) and Springer (Acta Vet Scand rabbit karyotype; *Evolution: Education and Outreach* fox
  paper; BMC 2010) redirected to login walls. Worked around through PMC or other routes where possible.
- Royal Society correction notice (rsos.231829): HTTP 403. Its content is unknown.
- Europe PMC full-text XML for PMC2763232 returned a server error. The BioC route worked.
- PubMed abstract for the offspring-size/clutch-size trade-off paper (PMID 16670999) was blocked by a cookie
  wall, and the litter-size exponent stayed unverified.
- A university teaching page (mason.gmu.edu, "Size and Animal Biology") gives allometric coefficients for
  litter size (2.45·M^−0.136), gestation (65.3·M^0.258 d), and others, but **cites no source and its
  heart-rate units are inconsistent**. It is used only as an unsourced cross-check and is not a citation.
- Litter-size PGLS exponent across eutherians: not found in three searches. Elliot (2008, *J. Evol. Biol.*)
  reports litter allometries by placental type, but only a partial table was visible.
- Blueweiss et al. (1978, *Oecologia*): paywalled, equations not obtained.
- Lindblad-Toh 2005 (dog genome) and Pontius 2007 (cat genome): not retrieved; the karyotypes rest on
  secondary sources.
- The Moroccan fertile mule (2002): only uncited wiki-derived pages. Treated as unverified.
- The "Trut 1999 American Scientist" percentages: superseded by the 2009 full text, which gives the same
  kind of data with counts.
- Human–rabbit and human–cat breakpoint counts: not found. A human–dog figure of 240 breakpoints appeared
  in a snippet without a verifiable citation, so it is not used.
- A homework site claimed a rabbit × cat hybrid would have 41 chromosomes "or 82." That is not a source and
  was ignored. The arithmetic in §5.1 is this file's own.

---

## Gaps

1. **Litter-size allometric exponent** with a verified source (PGLS, by order). Currently only the
   no-within-order-correlation result (PI-S52) and an unsourced −0.136 cross-check.
2. **Rabbit age at maturity conflict:** AnAge gives 730 d for females; field sources give about 4–5 months
   (PI-S60). Resolve under RQ-1 (M-2) before using the rabbit row of §6.3 as an input.
3. **Primary texts not read:**
   - Darwin 1868; Lindblad-Toh 2005; Pontius 2007; Gustavsson 1964; Fitzpatrick 2004 (numbers come from
     citing papers);
   - Lord et al. 2020 (abstract fragments and press only); Mouginot 2024 (press only); Tan 2021 and Wang 2023
     (press and abstract only).
   - Re-check these before any claim from them binds canon.
4. **Stahl 1967 heart-rate coefficient (241)** is secondary only (PI-S46). The scan's coefficient column is
   illegible.
5. **Geiger 2018 correction (2023):** content unknown. The mouse domestication result may be qualified by it.
6. **Founder-population genetics** (minimum viable founder size, inbreeding depression in small engineered
   founder populations) was not researched. HWC-8 needs a source pass, perhaps as a new RQ.
7. **Cat-specific data:** transplacental IgG fraction; whether domestic cats show domestication-associated
   brain or behavior genetics comparable to rabbits (PI-S77, PI-S78). Queue under RQ-3 or RQ-8 follow-up.
8. **Sc2.0 completion status** after 2023 is unconfirmed.
9. **Mitonuclear compatibility distance limit** for nonprimate mitochondria with human nuclear genes:
   evidence found only for primates (PI-S33).
10. **Exact TimeTree pairwise divergence values** for human–rabbit, human–dog, and human–cat (currently
    averages and ranges, PI-S13).
11. **Obstetric constraint:** pelvis versus neonate and litter mass in a bipedal or human-proportioned body
    was not researched beyond the maternal-size effect (PI-S31). It bears on HWC-10 and HWC-13 for any lineage
    keeping multiple births.
12. **Generations elapsed in the Zurich mouse study,** for converting the commensal-drift pace to generations.
