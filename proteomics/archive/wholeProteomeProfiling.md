# Whole proteome analysis <!-- omit in toc -->

This document describes an end-to-end protocol for quantitative whole-proteome analysis by mass spectrometry. This protocol is also appropriate for harvesting material for other assays, such as Western blotting, and does not require any specialized equipment (e.g. sonicator). This protocol can be used as a general guideline as there are many different ways of doing many of these individual steps and still achieving success. The topics covered include how to perform harvest and lysis of cell line material, clean-up of proteins, tryptic digestion, and final peptide clean-up. The protocol is designed to work with cell line material, but may be appropriate for tissues or other sources.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. Protein Sample Preparation](#1-protein-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3 Protocol](#13-protocol)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-protein-sample-preparation"></span>

## 1. Protein Sample Preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to measure proteins, make an effort to minimize potential keratin contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands).

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- DPBS (Thermo Scientific, CAT#14190144)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- MgCl2 (Sigma, CAT#M8266)
- KCl (Sigma, CAT#P9333)
- NP-40 (Sigma, CAT#NP40)
- Deoxycholate (DOC) (Sigma, CAT#D6750)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- cOmplete protease inhibitor tablets, EDTA free (Sigma, CAT#11836170001)
- TCEP (Sigma, CAT#580560)
- Chloroacetamide (Sigma, CAT#C0267)
- Benzonase nuclease, 25U/uL (Sigma, CAT#70664-3)
- Calcium chloride (Sigma, CAT#C4901)
- Acetic acid (Sigma, CAT#A6283)
- Clean water (Thermo Scientific, CAT#10977023)
- Trypsin/rLysC mix (Promega, CAT#V5071)
- Thermomixer with 2mL tube block (Eppendorf)
- Thermoblock set to +60C (multiple vendors)
- Cell scrapers (multiple vendors)
- Magnetic rack for 1.5mL or 2.0mL tubes (I like this rack: Promega, CAT#Z5342)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 100mM TrisCl pH 7.5 - 10uL of 1M stock for every 90uL of water (stock, stable at room temperature indefinitely)
- 2M KCl - 745mg in 5mL of water (stock, stable at room temperature indefinitely)
- 0.5M MgCl2 - 508mg in 5mL of water (stock, stable at room temperature indefinitely)
- 10% (v/v) NP-40 - 10uL for every 90uL of water (stock, stable at room temperature indefinitely)
- 10% (w/v) DOC - 500mg in 5mL of water (stock, stable at room temperature indefinitely)
- 10X cOmplete protease inhibitor stock - 1 tablet in 1mL of water (store at -80C)
- Lysis buffer A (need 200uL per sample, recipe for 1mL)
  - 20mM TrisCl pH 7.5 (200uL of 100mM stock)
  - 150mM KCl (76uL of 2M stock)
  - 5mM MgCl2 (10uL of 0.5M stock)
  - 0.5% (v/v) NP-40 (50uL of 10% stock)
  - 0.5% (v/v) DOC (50uL of 10% stock)
  - 0.5X cOmplete protease inhibitor (50uL of 10X stock)
  - water to 1mL (565uL of clean water)
- Nuclease mix (need 10uL per sample, recipe for 100uL)
  - 100U benzonase (4uL of stock)
  - water to 100uL
- Lysis buffer B (need 50uL per sample, recipe for 1mL)
  - 600mM TrisCl pH 7.5 (600uL of 100mM stock)
  - 8% (v/v) SDS (400uL of 20% stock)
- TC solution (need 10uL per sample, recipe for 1000uL)
  - 24.8mg TCEP
  - 37.2mg of CAA
  - water to 1000uL
- 50mM acetic acid - 28.7uL of 17.4M acetic acid in 9.97mL of water
- 1M calcium chloride - 1.1g in 10mL of water
- Digestion solution (need 200uL per sample)
  - 2uL of 1M calcium chloride solution
  - 20uL of 1M TrisCl pH 7.5
  - 178uL of water
- 80% (v/v) ethanol (prepare fresh)

<span id="13-protocol"></span>

### 1.3 Protocol

This protocol assumes you have your cells growing in conventional 6-well dishes. If you are using a 10cm or bigger dish, I suggest harvesting your cells using trypsin and freezing the pellets and proceeding with the processing as below (skipping the cell scraping steps). No matter what vessel you are using, I suggest plating your cells 24h before your planned harvest time to achieve a confluence of 70-80% at harvest time. This will ensure a maximum number of cells are actively growing and producing protein. If your cells are slow to attach or are typically slow to start growing, you can do this 48h before. The end goal is to have an actively growing cell population that is not over-confluent.

If you want a more concentrated cell lysate, use 75uL of Lysis Buffer A in the first step and 25uL of Lysis buffer B later on. Scale as is appropriate based on your cell culture dish size or harvested pellet size.

Prior to starting, prepare sufficient Lysis buffer A and B for all of the samples to be processed. Make sure you have a Thermoblock heated to +60C or greater. Prepare 1 tube for each sample to be processed (protein - 2mL tube).

1. Using a pipette, remove the culture medium from the growing cells on the 6-well plate.
2. Add 2mL of DPBS to each well and swirl the plate to rinse. Pipette up and discard the DPBS (or aspirate).
3. Add 150uL of Lysis buffer A to each well and rock the plate back and forth to ensure the cells are covered.
4. Working one well at a time, use a cell scraper to dislodge the cells and a micropipette to transfer 150uL of lysate to the protein tube on ice. Repeat for each sample. 
6. To the 150uL of lysate in the protein tube, add 10uL of nuclease mix and pipette mix. Incubate for 10-minutes at +24C without shaking. OPTIONAL - you can add the nuclease mix directly to the lysis buffer prior to adding it to the cells on the dish and do this incubation while you are scaping the cells off of the plate, in which case, you would skip this step.
7. After incubation, add 50uL of Lysis buffer B to the protein lysate and pipette mix. 
8. Place the protein lysate in the pre-heated Thermoblock at +60C and incubate for 5-minutes.
9. Remove the protein lysate from the Thermoblock and quick-spin the tubes at low speed to remove any condensation from the lid (e.g. 250g for 30 seconds).
10. Add 10uL of TC solution. Vortex mix and leave at room temperature for 30-minutes.
11. At this point, the protein lysate is compatible with Western blotting. I will usually add 6uL of 6X SDS Loading Buffer to 24uL of my sample, and run 20-30uL on a gel. 
12. This is a good stop point. You should measure the protein concentration in your sample using a BCA assay at this point. The samples here can be stored at -80C indefinitely, or directly used for other protocols such as Western blotting, as mentioned above.
13. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 14):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
14. To a fresh 2mL tube for each sample, add 10uL of SP3 bead stock, 20ug of your lysate, and water to 100uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
15. Add 400uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +24C for 5-minutes.
16. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution (or the same volume of 50mM acetic acid).
    2. Transfer 5uL of trypsin per sample to a fresh tube, and add 200uL of Digestion solution per sample. Vortex mix and keep on ice.
17. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
18. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
19. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
20. Add 200uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
21. Transfer the tubes to a shaking Thermomixer set at +37C and 1,000rpm, and digest for 14-18 hours.
22. The next day, spin the tubes at 12,000g for 2-minutes and then place on a magnetic rack. Recover the supernatant to a fresh 1.5mL tube.
23. At this point, you can clean-up your sample prior to MS analysis. See other protocols on this page for direction on that process.