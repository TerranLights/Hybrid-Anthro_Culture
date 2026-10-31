# Human-Assumptions Register — CST
**Status:** Proposed, 2026-10-21 sweep. Part of M-0 (see `MASTER_PLAN.md` §4).
**Files swept:**
- `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Cultural_Synthesis_Techniques.md` (the original; 1,194 lines;
  read in full). **All `CST:` line numbers cite this file.**
- `InnerTepeniaGDD/Worldspace/Locations-and-Levels/Universal_Location_Methodology/Disciplines/Cultural_Synthesis_Techniques.md`
  (the ULM copy; 1,196 lines; diff-checked against the original; see Notes item 1). Line offset from the
  original: about +95 through Technique 1 (e.g., `CST:57` = copy l.152; `CST:207` = copy l.302), and +21 in the
  Composition Merge (`CST:1038` = copy l.1059).

## Summary
- **39 entries: 7 Blocking, 27 Adjust, 5 Cosmetic.** The human assumptions are identical in both copies. The
  copies differ in other ways, and one of those differences matters (Notes item 1).
- **The two deepest problems are in §0b and the divergence operator.** §0b's channel list *is* the human
  sensorium, and it treats "how residents express it" and "how a player perceives it" as the same question.
  The divergence operator has no term for the body, which is the core L3 question for anthros.
- **Technique 1's human reach is only the most visible case.** Many divergence tables are scaled to the human
  body, the human day, or the human life course. The question shape of each technique survives. The rows and
  limits don't.
- **The Composition Merge works on one axis: human national origin.** Mixed-species settlements need a second,
  biological axis. That axis behaves differently: it's non-negotiable, it doesn't erode, and it never becomes
  invisible. R4, R5, R6 and R7 each need a species-axis rule.
- **R5's thresholds have no source, even for humans.** "Re-justify for non-humans" therefore means "justify at
  all" first.
- **The register is mostly latent for now.** CST runs only on a finished location pass (ULM). Under D-2 there
  are no locations for these races, so most entries don't apply until Phase 7. The exceptions are HAR-CST-07 and
  the Composition Merge material, which feed L3 and the M-6 draft now.
- **Biological examples in the "Breaks for" column are research prompts, not facts.** Examples like "retained
  olfaction" or "group territoriality" must be checked through M-2 under LAW 0-R and rule 5 before anyone
  relies on them.

## Register
| Code · Name | Source | Assumption | Why it's human-bound | Breaks for | Replacement | Severity |
|---|---|---|---|---|---|---|
| HAR-CST-01 · Human common-sense plausibility baseline | CST:37–39, 43–45 | "bars and pubs with live-music nights are entirely reasonable… A giraffe is not"; a player should think "of course this is here." | The test for "characteristically inevitable" is a human reader's sense of what a human place contains. It never routes through the population's physiology. | All races. A social-drinking evening venue assumes a body that eats and drinks socially, is active in the evening, and tolerates alcohol, and none of that is established. The giraffe line also inverts in a setting that contains engineered animal-people. | L1 as the plausibility baseline (Mechanic 9 standing input); P-1, P-3, P-7. Adapter rule: "characteristic" means consistent with L1 + L2 + this place, never with a human default. | Adjust |
| HAR-CST-02 · Sensory channel set fixed to the human sensorium | CST:56–60 | "seen (environment, crowd behavior, dress) · heard (ambient audio, overheard talk) · entered · handled · spoken · done · hooked" | There is no smelled, tasted, or vibration-felt channel, and nothing outside human ranges. A custom expressed mainly by scent or substrate is scored "can only be read about" (CST:62) by a test that can't detect it. | Dog-, cat-, and rabbit-people, if L1 keeps animal-weighted olfaction or substrate signaling (verify through M-2). Aliens: any sensorium. Elves only if their L1 differs. | P-4 (the race's channel list replaces the fixed seven); P-8 for signaling channels. | **Blocking** |
| HAR-CST-03 · Resident perception treated as player perception | CST:8–9, 56, 62 | "The end consumer is a player moving through the space"; "A finding that can only be read about is weak." | The test assumes player and resident share one sensorium, so "how it's expressed" and "how the player meets it" are one question. For a non-human population they split: a scent-borne custom is fully physical to residents and invisible through a screen and speakers. | Any race whose P-4/P-8 channels exceed what the game can render (audio-visual plus UI). | **NEW PARAMETER NEEDED: Channel-Rendering Map** (per game, not per race; see below). §0b then counts a rendered proxy as a legitimate physical expression. | **Blocking** |
| HAR-CST-04 · "Handled" presumes human hands | CST:58 | "handled (an item)" | Presumes human-type manipulators and an item economy of picking up, carrying, and giving. | Races whose L1 body plan changes manipulation. Q-9 (doll constraint) may make humanoid hands likely for anthros and elves, which would reduce this to Cosmetic, but that's not assumed. Aliens: open. | P-4 (manipulation). | Adjust |
| HAR-CST-05 · "Spoken" presumes vocal-verbal language | CST:59 | "spoken (an NPC can mention or complain about it)" | Treats speech as the default channel for complaint and gossip. | Races whose P-8 weights non-vocal channels (posture, scent), or whose vocal range falls partly outside human hearing (verify). | P-8; Q-12 (language handoff). | Adjust |
| HAR-CST-06 · Starting stock is a human nation or ethnicity | CST:150–176, 984 | "composition names the STOCK"; GPS law framed as "Russian heritage" vs. "a fundamentally Japanese city"; "which national/ethnic cultures are represented" | Stock is defined only as human national-ethnic origin. For anthros the starting stock is the creators' human culture *lived in a non-human body* (L3). Mixed places add a biological axis (species). | Anthros; elves (culture mediated by their creators, Q-5); mixed settlements (Q-10). Aliens have native stock with no national frame. | L3 (Inherited Stock); M-4 Design Charter (the creators' culture); M-6 (species axis); rule 3 (species-stereotype ban) as the analog of the national-stereotype ban. | Adjust |
| HAR-CST-07 · Divergence operator has no embodiment term | CST:178–179 (restated 1146–1148) | "time · separation · local environmental setting · local struggles and hardships · local goals · local sensibilities and habits" | All six terms are outside pressures acting on a human body held constant. The central L3 question has no slot: which inherited practices "this body keep[s], bend[s], or drop[s]" (`MASTER_PLAN.md` §3). | Anthros above all (human stock, non-human body); elves, if their base stock's body differs from their creators'. | **NEW PARAMETER NEEDED: Embodiment Fit** (an operator term, not a sheet field): per inherited practice, record keep / bend / drop, routed through L1 (P-1, P-2, P-4, P-7, P-8). It is adapter-only. Putting it into the original operator would be a proposed Inner Tepenia ruling (M-0b). | **Blocking** |
| HAR-CST-08 · Elapsed-time ban conflicts with generation-length calibration | CST:181–182, 1150 | "DO NOT REASON FROM THE ELAPSED TIME… process the data purely on its own terms." | The rule was made in a single-species setting, where generation length is constant and carries no information. Across species, equal elapsed time means unequal numbers of generations, and M-7 exists to reason from exactly that. | Every race whose P-5 is far from human. | M-7 and P-5, pending a developer ruling on scope (Notes item 3). | Adjust |
| HAR-CST-09 · The Acts are timed to human generations | CST:185–187 | Act 1 "(2564 → early 2600s)": "X who live in Antarctica"; Act 2: "origin is ancestry, not identity" | The shift from Act 1 to Act 2 is a process measured in human generations, written as calendar dates. "Origin is ancestry" happens once enough native-born generations exist. | Any race whose P-5 differs from human. A short-generation race reaches Act 2 in far fewer years; a long-lived one may not reach it in the same span. (The dates and Antarctica are Inner Tepenia project data.) | P-5; M-7 (which lists Acts timing explicitly). | Adjust |
| HAR-CST-10 · Franchise limit measured by human reach | CST:200–203, 207, 212, 220–221 | "How far an arm reaches from your window"; "What you can physically reach and return from"; the Window Reach instance | The limits that the table says come from a body are human arm length, human travel range, and human carrying capacity. | Races whose body scale, reach, or locomotion differ in L1 (for example climbing or burrowing). Also races with long-range senses, where "what I control" may be perceptual: what you can smell or hear as yours. | P-4 (reach, perception range, manipulation); the proposed body-plan parameter (Body Scale and Locomotion; matches `HAR_ULM.md`'s proposed P-10). | Adjust |
| HAR-CST-11 · Franchise holder is an individual adult | CST:198–203 | "an ordinary individual holds absolute, unarguable authority" | Assumes the natural unit of control is one adult person. | Races whose P-3 territoriality or P-2 rearing model puts control in a group, a breeding pair, one sex, or one life stage. Establish this through M-2 and M-1; don't presume it from the animal. | P-3 (territoriality); P-2; P-6. | Adjust |
| HAR-CST-12 · Time limits assume a diurnal work schedule | CST:208, 211, 213 | "your shift"; "the hours you hold it"; "a recurring hour" | Time-based franchise limits presume a human day divided into work shifts. | Crepuscular, nocturnal, or polyphasic races (P-1). In mixed places, one "hour" can be prime time for one species and dead time for another. | P-1. | Cosmetic |
| HAR-CST-13 · Failure states keyed to human aging and working life | CST:239, 241, 244 | "The people who would continue it run out"; "you age out"; "You can no longer work" | The failure conditions are stages of a human life course: a performing prime, a working life, dependency after work, successors once per generation. | Races with a different P-6 stage map (for example no post-reproductive stage, or a long dependent childhood) and a different P-5 lifespan. | P-6; P-5; M-7. | Adjust |
| HAR-CST-14 · Micro-practices use human gestures and timing | CST:264–279 | "a nod… a glance… a breath, a marked step… confirming aloud"; "seconds not minutes; no equipment"; "a visitor would notice within an hour" | The examples are human facial, vocal, and hand gestures, and the durations are human perceptual scales. The technique also never separates a *learned* micro-practice from an *involuntary* signal (ear, tail, or posture). | Races with different P-8 body or scent signals, where a greeting might be a scent check or a posture. Races with involuntary signals that a human-modeled pass might mistake for customs. | P-8 (with the proposed signal-control subfield); P-4; M-3 (is the signal reflex or culture?). | Adjust |
| HAR-CST-15 · Rank signaling presumes a human status hierarchy | CST:274 | "Status legibility — A deference gesture calibrated to rank" | Assumes a human-style status hierarchy shown through learned deference. | Races whose resolved social structure differs. This row also invites the discredited "alpha" model if it's filled in from pop ethology. | P-3; M-2 caution on pop ethology. | Cosmetic |
| HAR-CST-16 · Carried object presumes clothing and private meaning | CST:292–297, 312–313 | "form is standard but whose meaning is individual and never asked about"; "worn at the collar" | Presumes wearing or carrying, and that an object's personal meaning stays hidden unless someone asks. In a scent-reading species an object may carry its owner's scent and history, so it's readable without asking, and the "never asked about" premise fails. | Races with retained olfactory acuity (verify): the etiquette moves from "not asking" to "not remarking on what you smelled." Races without inherited clothing norms (L3, Q-9). | P-4; P-8; L3; Q-9. | Adjust |
| HAR-CST-17 · Unexplained effects listed in order of human salience | CST:329–331 | "persistent light quality · a smell · a temperature or humidity anomaly · a sound with no named source…" | The hunting list follows human perception. Smell is one item of seven, and nothing outside human range is considered (ultrasound, infrasound, UV, substrate vibration). A race may also miss effects a human would record. | Races whose P-4 ranges reach beyond or fall short of human ranges. | P-4; P-9 (thermal tolerance changes what counts as an "anomaly"). | Adjust |
| HAR-CST-18 · Forcing constraints leave out the body | CST:355–356, 361–362 | "what was affordable · fastest · what survived the climate · what one founding trade knew · a shortage · a disaster"; "cheapest fast warm shelter" | The constraint families are economic and environmental, judged against human needs such as warmth. The body's own non-negotiables are not a family, yet for a non-human population they're the likeliest source of "necessity before meaning": diet, light regime, nesting and rearing needs, activity cycle. | All non-human races. | Add a constraint family, "what the body required," routed through L1: P-1, P-2, P-7, P-9. | Adjust |
| HAR-CST-19 · Testifying media assume human records and human generation length | CST:376–378 | "a naming convention that stops or changes · a skill nobody can account for learning · … a population gap" | The media are ones a human perceives. A "population gap" is read at human generation length. Lasting scent marks and wear left by a non-human body are missing. | Races with retained scent-marking (verify). Short-generation races, where one bad year can be a whole cohort. | P-4; P-8; P-5. | Cosmetic |
| HAR-CST-20 · Record-keeping presumes writing and human lineage | CST:395–405 | "inscribe or archive permanently"; "Lineage and service"; "Names / Numbers" | Assumes a writing culture, and lineage that runs through single births and known parents. | Anthros probably inherit writing (L3), but they record what their kinship makes legible. With litters, possible multiple paternity, or different kin recognition (P-2), "lineage" may not be linear. Aliens: the record medium is unknown. | P-2 (kin recognition); P-8; L3. | Adjust |
| HAR-CST-21 · Membership timescales assume a human lifespan and default stranger tolerance | CST:441–452 | "A work term"; "Having survived one cycle in place"; "First time someone vouches for you" | Conversion mechanisms are scaled to a human life, where a season or a year is a small fraction of it. They also assume newcomers are tolerated by default, so membership is economic or reputational. | Short-lived races, where one cycle can be a large share of adult life (P-5). Races where group identity is recognized biologically, for example by scent if L1 keeps that, so membership may be physiological rather than economic. Races with low stranger tolerance (P-3). | P-3 (stranger tolerance); P-5; P-8; M-3 (is group recognition an Animal-Inherited Universal?). | Adjust |
| HAR-CST-22 · Counterculture from misfit ignores biological misfit | CST:469–482 | "who cannot, or will not, give it?"; "people the demand doesn't fit" | Assumes those who "cannot" comply are cut out by temperament or circumstance, inside one body type. In a mixed place a whole species may be physically unable to give what's compelled (being visible at a diurnal hour, sharing a meal). That's a condition, not essentialism, but it collapses the counterculture onto species lines, which risks both over-convergence and stereotype. | Mixed settlements (Q-10). | M-6; rule 3. Adapter rule: a species-shaped counterculture must name its mechanism *and* record the members of that species who do comply. | Adjust |
| HAR-CST-23 · "Native vs. transplanted" has only two layers | CST:495–500 | "what arrived for what grew… Develop the layers separately" | Two layers, immigrant and local. A made race has at least four sources: creator-installed, animal-inherited, inherited creator culture, and locally grown. | Anthros, elves, and any made race. | L3; M-3 (Animal-Inherited and Engineered Universal outcomes); M-4 Design Charter; L4. | Adjust |
| HAR-CST-24 · The research stream is real human places only | CST:509–514, 536–537, 560 | "tiered real-world reference picks (Primary / Secondary / Supporting)"; "Research first (`Real-World_Basis_Extrapolation_Method.md`)" | Only one research stream feeds CST: real human places. There's no biological stream, and under D-2 there are no per-location picks for these races. | All races (D-2). Animal-based races need the M-2 stream. | M-2 (EBEM) as a second stream. Technique 13's "spend record" becomes the race's EBEM research log as well as RWBEM's. | Adjust |
| HAR-CST-25 · Population Share Check misses sex and life-stage narrowing | CST:543–552 | "Does this describe the general population, or one profession's, ritual's, or context's version?" | The "narrow source" categories are human social roles. In biological sources the commonest narrowing is to one sex, one life stage, the breeding season, or a captive or lab context, because many ethology studies sample exactly that. | All animal-based races (M-2 output feeding L1 and L2); races with strong P-6 stage differences or sex differences. | P-6; P-2; M-2 Step B (log the identity of each study population). | Adjust |
| HAR-CST-26 · "Forms every society needs" is the human list | CST:589–590 | "mourning, celebration, arbitration, hospitality, apprenticeship" | Borrowed Form fires on an empty category, and it takes these needs as universal. That's Brown's human floor, not a species floor. | Any race whose M-3 run returns Non-Transfer or Structural Analog for a listed need. | M-3 (the race's L2 floor supplies its own "every society needs" list). | Adjust |
| HAR-CST-27 · The shared meal is assumed to be available | CST:603–606 | "a meal with a beginning and an end, eaten in one place, with the same people present" | Treats a bounded shared meal as an available human form. Whether a species' feeding pattern supports one is a P-7 and P-1 question; the alternatives include continuous grazing, solitary feeding, and feeding shaped by digestion. | Races whose P-7 feeding pattern differs; mixed places with incompatible diet classes (no shared plate). | P-7; P-1; M-6 diet axis. | Cosmetic (worked instance; the ULM copy states it generally at copy l.686–689 but keeps the example) |
| HAR-CST-28 · The Zodiac Lens reads human personality archetypes | CST:718–745 (esp. 731–740) | "Run all twelve signs… as independent interrogation prompts against a location's own already-established character" | The sign files in `Zodiac_Personality_Substrate/` describe human personality registers (core need, shadow, light expression). Reading them against a non-human population is a direct path to "humans with ears." The zodiac is also an Earth-sky calendar. | All non-human races; strongest for aliens. | Adapter guard: check each lens result against L1 and L2 before the §0 filter; P-6 for registers tied to life stages. | Adjust |
| HAR-CST-29 · Composition counts every head as an equal culture-bearer | CST:1001–1003 (consumed by 1058–1065) | "An origin roster with SHARES (percentages, headcounts, or any ratio)" | Across species, the share of heads isn't the share of cultural transmission. A high-fecundity, short-lived species has a large juvenile fraction. A long-lived one keeps individuals who carry a practice across many of another species' generations. | Mixed settlements; also a single species with a skewed age structure. | **NEW PARAMETER NEEDED: Culture-Bearing Weight** (from P-5 and P-6; see below). | **Blocking** (for M-6) |
| HAR-CST-30 · R1–R3 read a single composition axis | CST:984, 1010–1036 | "a mechanism for determining… which national/ethnic cultures are represented, and to what degree" | The distribution has one dimension, origin. Mixed places have at least two: species × origin. Two anthro species can share one creator culture. | Mixed settlements (Q-10). | M-6: run R1–R3 on each axis, then cross them (see Composition Merge section). | **Blocking** (for M-6) |
| HAR-CST-31 · R1's default is treated as purely cultural | CST:1016–1017 | "Leader > 50%: Its forms simply ARE the local forms. Everything else is marked, optional" | For humans the "forms" are customs. Across species the leader's default also sets the built environment to its body scale, the schedule to its activity cycle, and the food to its diet class. A minority's mismatch with those is physical. It can't be "optional" or survive "at the leader's sufferance." | Mixed settlements. | M-6 axes for body scale, activity cycle, and diet; P-1, P-7, P-9; proposed body-plan parameter. | Adjust |
| HAR-CST-32 · R4's stock-distance axes are cultural only | CST:1040–1042 | "staple and its cooking method · household and kinship form · script, calendar and numbering · funerary requirement · dietary prohibition · what the source practices assume about CLIMATE" | All six measure human cultural practice. Several quietly merge a biological "can't" with a cultural "won't": staple vs. diet class, household vs. reproduction, calendar vs. activity cycle, climate vs. physical tolerance. | Mixed settlements. Also L3 for anthros (inherited human practice vs. a new body). | M-6 (see the Composition Merge section). | **Blocking** (for M-6) |
| HAR-CST-33 · R4's "built commons" assumes everything can be negotiated | CST:1049–1054 | "When nothing inherited was common to everyone, the commons had to be INVENTED ON SITE." | In a human far-stock place, any practice can in principle be shared. A biological distance can't be invented away: a common practice can only sit where the bodies overlap. | Mixed settlements. | M-6: the built commons forms only on axes where the races' L1s overlap. Incompatibility on a biological axis produces parallel infrastructure, not a commons. | Adjust |
| HAR-CST-34 · R5's thresholds are uncited and human-calibrated | CST:1056–1069 | "under ~2% Traces… ~5–10% One institution… ~10–20% A parallel institutional set… over ~20% A CO-DEFAULT" | No source or derivation is given; the numbers reflect human minority sociology. Percentages don't depend on scale, but whether an institution is viable depends on absolute numbers and on stable group size, which is a human band. | All races; mixed settlements especially. | Re-derive for each race from P-3 and Culture-Bearing Weight (M-7, M-6). Until then label R5 "human-calibrated, unverified" in the CST adapter. | **Blocking** |
| HAR-CST-35 · R5's "non-negotiable" set is cultural | CST:1062 | "One institution — and it will be the non-negotiable one: funerary, dietary, or devotional" | For a biological minority the first non-negotiables are physical: diet class, light and activity regime, rearing needs, environmental tolerance. They need accommodation at any share, starting with the first individual. | All non-human populations in mixed places. | P-7, P-1, P-2, P-9; an M-6 biological floor (R5-B, below). | Adjust |
| HAR-CST-36 · R6's "goes universal" crosses a biological boundary | CST:1093–1103 | "Small share · load-bearing · no local alternative → SURVIVES AND GOES UNIVERSAL" | In a human place a small group's load-bearing practice spreads because every body can perform it. A practice that is load-bearing because of one species' L1 can't be performed by the others. What can go universal is the accommodation around it: the schedule, the venue, the etiquette. | Mixed settlements. | M-6; route through L1 overlap. | Adjust |
| HAR-CST-37 · R7's end state assumes the body disappears | CST:1111–1127 | "their descendants are simply from here… that outcome is what full local integration actually LOOKS like" | "Origin is ancestry, not identity" works because human descendants are physically unmarked. Species is a body, not an ancestry, so a species never becomes invisible in a mixed place. R7 holds on the origin axis within one species. It doesn't hold on the species axis. | Mixed settlements. | M-6: restrict R7 to the origin axis. The species axis gets its own end state: integration means accommodation nobody remarks on, not invisibility. | Adjust |
| HAR-CST-38 · The sequencing gate names nationality, not species | CST:1144–1145 | "you may never infer WHO LIVES SOMEWHERE from cultural reputation" | Written for national reputation. The species form of the same error isn't named: inferring which species lives somewhere from the environment ("burrow-friendly ground, so rabbit-people") or from a folk image. | All races; mixed settlements; D-2. | Rule 2 and rule 3; Q-10 (composition is a developer decision). | Adjust |
| HAR-CST-39 · Player value is phrased as "human decisions" | CST:218 | "a readable field of individual human decisions" | The word "human" is literal. | All races. | Wording only (adapter note). | Cosmetic |

## Generalizes cleanly
These parts carry over unchanged, as long as the parameter sheet feeds them.
- **The self-check against copying (CST:15–23).** "Similar shape means at least one is wrong" is the CST form of
  `MASTER_PLAN.md` §8's "one race on its own terms." It applies to races as written.
- **§0's two failure modes (CST:35–50).** The "uncharacteristic" and "over-constrained" structure holds. Only
  the plausibility baseline changes (HAR-CST-01).
- **"The violation is usually the gameplay" (CST:64–65).** This holds wherever a race has social norms and
  sanctions, which P-3 will state.
- **The source-map discipline (CST:69–135).** "A technique that cannot name its input is run from whatever the
  session happens to remember." The same rule should bind M-1 through M-7: every method step names the L1 file
  it reads.
- **The architecture of Techniques 2, 5, 6, 7, 8, 9, 11, and 14.** The questions transfer. Only the example rows
  carry human scale (entries above). For Technique 9 (Non-Thematic Export), food exports in a mixed place also
  have to clear diet-class compatibility (P-7), which is a filter, not a rewrite.
- **The Unrecognized Instrument (CST:643–695), complete.** "A capability deficit is a deficit of the general
  faculty, not of every instance" doesn't depend on any biology.
- **Zodiac Lens process discipline.** The stopping-criterion rule (CST:768–780) and the per-hit contradiction
  check (CST:832–863) are rules about search behavior, not content. They are also the material the ULM copy
  dropped (Notes item 1).
- **Composition Merge, species-neutral parts:**
  - R2 (contested lead) and R3 (concentrated vs. dispersed), as arithmetic on any one axis.
  - The input-contract ban on estimating shares (CST:1003). This is the most important guard for Q-10: don't
    invent species percentages to unblock M-6.
  - R5b's "pooling is a hypothesis, not an entitlement" (CST:1086–1090).
  - R6's core claim, survival as share × necessity.
  - Guard 1 (structure, never character), which is rule 3's direct ancestor.
  - Guard 5 (one shared proportion across two populations carries no signal). This is already proven on a
    two-population roster of robots and humans (CST:1152–1153), so it applies as-is to species sub-splits.
  - Guards 6 and 7.
  - "Listed is not represented" (CST:1111), on the origin axis.

## Proposed new parameters
**Numbering is left open on purpose.** The sibling sweeps already claim P-10 to P-14 for other fields (`HAR_ULM.md` P-10 to P-13; `HAR_HUF.md` five names "if accepted, P-10 to P-14"). Codes get assigned once, when M-0 consolidates the four registers. *Body Scale and Locomotion* is the same field as `HAR_ULM.md`'s proposed P-10 ("Body plan, scale & integument") and should merge into it. Its row below only adds this sweep's evidence.

| Proposed code | Name | Scope | What it holds | Raised by |
|---|---|---|---|---|
| *(unnumbered)* | **Channel-Rendering Map** | **Per game**, not per race (lives with the game GDD, read through the adapter) | For each P-4 sensory channel and P-8 signal channel: rendered directly (visual or audio), rendered by proxy (NPC reaction, visible marking or residue, item text, UI cue, companion comment), or not rendered. Also: whose senses the player character has, which is open for *New Centauri* and depends on the medium for *Elven Steel* (Q-11). | HAR-CST-02, -03, -05, -16, -17 |
| *(unnumbered)* | **Culture-Bearing Weight** | Per race (derived, M-7) | Adult fraction of a population at steady state; years of adult participation; overlap of generations with co-resident species. Converts a headcount share into a share of cultural transmission for R1–R7. | HAR-CST-29, -34 |
| *(= `HAR_ULM.md` P-10)* | **Body Scale and Locomotion** | Per race | Stature and mass range; locomotion modes (bipedal, climbing, digging, and so on); what built environment the body needs (door, step, and seat scale; vertical vs. horizontal space). P-4 currently covers only reach and manipulation, yet M-6 lists "body scale" as an axis with no parameter to feed it. Split it out of P-4, or add it here. | HAR-CST-10, -31; M-6 |
| — (operator term) | **Embodiment Fit** | Adapter rule on the divergence operator | A seventh operator term: for each inherited practice, keep / bend / drop given L1, with the mechanism stated. It is not a sheet field. Promoting it into the Inner Tepenia operator is the developer's call (M-0b). | HAR-CST-07 (and HAR-RWBEM-07) |
| P-8 subfield | **Signal control** | Per race | For each signal, whether it is voluntary, involuntary, or trainable. A culture can *shape* only the first and third. | HAR-CST-14 |

## Composition Merge — biological axes
**A proposal for M-6. Nothing here edits CST.**

### 1. The current R4 axes: keep each, and split off its biological "can't"
| R4 axis (CST:1040–1042) | Verdict | Biological counterpart it currently hides |
|---|---|---|
| Staple and its cooking method | **Stays** (cultural) | **Diet class (P-7)**: what a body *can* eat, as distinct from what a culture cooks |
| Household and kinship form | **Stays** (cultural) | **Reproduction and rearing model (P-2)**: litter size, cycle type, who raises young, kin recognition |
| Script, calendar, and numbering | **Script and numbering stay.** Calendar **splits** | **Activity cycle (P-1)** and breeding seasonality (P-2). Script also depends on manipulation and vision (P-4), but only at the margins |
| Funerary requirement | **Stays** | Lifespan and mortality model (P-5), and the M-3 verdict on whether mourning transfers at all |
| Dietary prohibition | **Stays.** This is the explicit "won't" axis | None. Keep it strictly cultural so it can't absorb diet class |
| Climate assumptions | **Stays** | **Physical tolerances (P-9)**: temperature, light regime, gravity, atmosphere. Climate is what the source practice assumes; tolerance is what the body survives |

### 2. Biological axes for M-6
| Axis | Parameter | In `MASTER_PLAN.md` M-6? | Measure |
|---|---|---|---|
| B1 Diet class | P-7 | Yes | Compatible / partly overlapping / incompatible (no shared plate) |
| B2 Activity cycle | P-1 | Yes | Hours of the day both are active and alert |
| B3 Reproduction and kin model | P-2 | Yes | Whether kin categories and rearing units can be mapped onto each other |
| B4 Lifespan and generation ratio | P-5, P-6, proposed Culture-Bearing Weight | Yes ("lifespan ratio") | Generation ratio, plus Culture-Bearing Weight |
| B5 Sensory mismatch | P-4 | Yes | Channels one side perceives and the other doesn't |
| B6 Communication-channel mismatch | P-8 | **Added** | Signals one side *produces* that the other can't perceive or can't produce. Kept apart from B5, because "can perceive but can't answer" is its own social situation |
| B7 Body scale and locomotion | proposed body-plan parameter (`HAR_ULM.md` P-10) | Yes ("body scale") | Whether the built environment can be shared without parallel fixtures |
| B8 Social-cognition band mismatch | P-3 | **Added** | Stable group size, stranger tolerance, and territoriality. Decides whether R3's "negotiation between named parties" is even possible across the line |
| B9 Environmental tolerance | P-9 | **Added** | Whether the two can share one interior climate and light regime |
| B10 Pathogen and hygiene compatibility *(candidate)* | none yet | **Added, flagged** | Cross-species disease transmission. **M-1's domain list (`MASTER_PLAN.md` §5) has no immunology domain.** If the developer wants this axis, M-1 needs one |
| Conditional: inherited predator/prey history | L1 of *both* races | Yes (conditional) | Counts only if both L1s keep the mechanism (plan rule). Never from folk image |

### 3. How the biological axes behave differently (the M-6 rules)
1. **They're non-negotiable.** A biological incompatibility doesn't **blend** (R4 "deep") and doesn't **erode**
   (R3 "dispersed"). It gets accommodated, segregated, or causes harm.
2. **Measure overlap, not distance.** The useful reading is how much of daily life two races can *co-perform*
   (the same hours, the same food, the same rooms, the same signals). The cultural axes stay as R4 distance.
3. **Read the two distances as a 2×2, never averaged:**

   | | **Near body** | **Far body** |
   |---|---|---|
   | **Near culture** | R4 DEEP, as in CST: the human case | **NEW: "one form, several executions."** The institution is shared, inherited from the same creator culture, but each species performs it its own way. The seams sit in the *performance*, not the form. This is likely the commonest anthro case (three species, one human creator stock) |
   | **Far culture** | R4 SHALLOW BUT BROAD, as in CST: a built commons | **Parallel infrastructure with a minimal commons** limited to the overlap zone. Following R4's own third-order logic, that small commons is the most originally local culture in the place |
4. **R5b pooling works per axis.** Two species can pool on B2 (both crepuscular, so they share the night market)
   and not on B1. Report pooled figures for each axis, never as one merged entry.
5. **R6 across species:** what goes universal is the accommodation, never the physical practice itself
   (HAR-CST-36).
6. **R7 across species:** it applies only on the origin axis. The species axis never reaches "shows up nowhere."
   Its integrated state is accommodation nobody remarks on (HAR-CST-37).
7. **R1 across species:** the majority species' default includes the physical plant, so minority status on the
   species axis is felt in doors, hours, and food before it's felt in custom (HAR-CST-31).

### 4. Can R5's thresholds be re-justified for non-humans?
**Short answer: on the origin axis within one species, probably yes, once they're derived properly. On the
species axis, no. Replace them there.**
- **Step zero: they aren't justified even for humans.** CST:1056–1069 gives no source and no derivation. The
  first job is to find a source in minority-community sociology or relabel R5 a "working heuristic." This
  belongs with the developer as a finding about the Inner Tepenia original, not as a fix made here.
- **Percentages are the wrong unit.** Whether an institution survives depends on absolute numbers of adults
  able to staff it. That number scales with the race's stable group size (P-3) and its Culture-Bearing Weight
  (proposed above). Proposed form: state each R5 band as an **absolute adult count relative to the race's P-3
  band**, and convert it to a percentage only for a specific settlement.
- **Fecundity moves the target.** A high-fecundity minority (P-2) can cross bands within a few of its own
  generations. Every R5 reading needs a growth note.
- **Species axis: R5-B, a biological floor.** Physical needs (diet, light and activity regime, rearing,
  tolerances) need accommodation **from the first resident**, at any share. R5's bands then apply only to the
  *cultural* institutions a species minority can sustain, using the absolute-count form above.
- **Recommendation:** mark R5 "human-calibrated, unverified" in `CST_Adapter.md` now. Don't apply it to any
  non-human population until M-7 produces per-race bands. Send the missing-source finding to the developer as a
  proposed Inner Tepenia observation.

## Notes for the developer
1. **The ULM copy differs from the original in substance, not only in worked examples.**
   - **Expected differences:** the copy prepends LAW 0 in full; it replaces every Cancer/Concordia worked instance
     with a pointer (the Window Reach instance included, though the "How far an arm reaches" table row survives
     at copy l.302); and it replaces the Composition Merge project-data block (CST:1165–1183) with a pointer.
   - **The material difference: the copy drops Zodiac Lens step 7, the per-hit contradiction check
     (CST:832–863).** It also drops the paragraph "The count is not evidence of rigor. The stated stopping
     reason is" (CST:819–825) and the standing caution (CST:827–830). Copy l.879–884 replaces all of CST:800–863
     with a short summary of the divergence table. The copy contains no "contradiction" text anywhere, so a ULM
     cold run never sees a binding developer instruction. This is outside this repo's scope and is reported,
     not fixed.
   - **Count inconsistencies:**
     - The original says "eighteen more" cross-checks and "216 prompts" (CST:879, 896, 913), yet "eleven Robot
       Planetary Symbols… nineteen… 228" (CST:881–884). The copy is consistent at nineteen and 228.
     - "Using this file" says "fourteen" in the original (CST:567) and "eighteen" in the copy (copy l.651).
   - **The pin looks stale.** The copy's header pins "1193 lines, re-pinned 2026-09-06." The original is now
     1,194 lines and was last committed 2026-10-01 (`14b01319`).
   - **For this register:** every human assumption appears identically in both files.
2. **CST is an L4 tool, and D-2 leaves it nothing to run on yet.** Every technique reads a finished ULM location
   pass (source map, CST:83–101). Until Phase 7, the register's job is to stop the adapters from being written
   wrong. The parts usable now are Embodiment Fit (for L3) and the Composition Merge analysis (for drafting M-6).
3. **The elapsed-time ban vs. M-7 needs a ruling (HAR-CST-08).** One reading makes them compatible: the ban
   forbids deriving outcomes from a year count ("after 250 years, X"), while M-7 turns years into generations
   and witness-depth, which is processing the race's own data on its own terms. M-7 would then be barred from
   ever producing "after N years, X happens." Please confirm or overrule.
4. **§0b assumes a CRPG (CST:8–9).** *Elven Steel*'s medium is unknown (Q-11). If it isn't interactive, "done"
   and "hooked" have no meaning there, and §0b needs a variant for that medium. The Channel-Rendering Map is per game for the
   same reason.
5. **The Zodiac cross-check uses robot symbol systems** (Robot Elementals and Planetary Symbols, CST:878–884).
   On a biological race that's a designer prompt drawn from robot culture. It isn't a human assumption, but it's
   a leak between populations, so it should be ruled on before Phase 7: allowed as a pure prompt, or replaced.
6. **Inner Tepenia project data inside the mechanism** (Acts dates, Antarctica, per-nation audit) doesn't apply
   to these races and needs no adapter. It's listed only where it sits inside a human-bound rule (HAR-CST-09).
7. **Severity convention used here:**
   - **Blocking:** the method gives a wrong or empty answer for a non-human race unless the replacement exists
     first.
   - **Adjust:** the method runs but needs a parameter-driven change to its rows or rules.
   - **Cosmetic:** wording or a worked instance only.
   - "(for M-6)" means the item blocks only mixed-species use.
