# Dual whole transcriptome and proteome analysis <!-- omit in toc -->

This document describes an end-to-end protocol for quantitative whole-proteome analysis by mass spectrometry that also harvests matched material that can be used for whole transcriptome analysis by RNA sequencing. This protocol is also appropriate for harvesting material for other assays, such as qPCR or Western blotting, and does not require any specialized equipment (e.g. sonicator). This protocol can be used as a general guideline as there are many different ways of doing many of these individual steps and still achieving success. The topics covered include how to perform harvest and lysis of cell line material, clean-up of proteins, tryptic digestion, and final peptide clean-up. The protocol is designed to work with cell line material, but may be appropriate for tissues or other sources.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. RNA and Protein Sample Preparation](#1-rna-and-protein-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3 Protocol](#13-protocol)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-rna-and-protein-sample-preparation"></span>

## 1. RNA and Protein Sample Preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to measure RNA and proteins, make an effort to minimize potential keratin and RNase contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands). I like to use the Zymo RNA kit to purify total RNA, but you can substitute virtually any RNA isolation kit you would like. 

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- DPBS (Thermo Scientific, CAT#14190144)
- 1M TrisCl pH 8.5 (Thermo Scientific, CAT#fAAJ61038AP)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- Urea (Sigma, CAT#33247-250G)
- MgCl2 (Sigma, CAT#M8266)
- Triton X100 (Sigma, CAT#X100-100ML)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- cOmplete protease inhibitor tablets, EDTA free (Sigma, CAT#11836170001)
- BCA protein assay kit (Thermo Scientific, CAT#PI23227)
- TCEP (Sigma, CAT#580560)
- Chloroacetamide (Sigma, CAT#C0267)
- Benzonase nuclease, 250U/uL (GeneBioSystems, CAT#OTD-02)
- Calcium chloride (Sigma, CAT#C4901)
- Acetic acid (Sigma, CAT#A6283)
- Clean water (Thermo Scientific, CAT#10977023)
- ProteoSure Trypsin (Marvelgent Biosciences, CAT#14-SRT-1MG)
- Thermomixer with 2mL tube block (Eppendorf)
- Cell scrapers (multiple vendors)
- Magnetic rack for 1.5mL or 2.0mL tubes (I like this rack: Promega, CAT#Z5342)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Trifluoroacetic acid (Sigma, CAT#T6508-100ML)
- Direct-Zol RNA microprep kit (Zymo Research, CAT#R2061)
- Sonication tubes (optional, Brandtech, CAT#1388259)
- Sonicator (optional, we typically use a QSonica Q800, but others are suitable)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 100mM TrisCl pH 8.5 - 10uL of 1M stock for every 90uL of water (stock, stable at room temperature indefinitely)
- 100mM TrisCl pH 7.5 - 10uL of 1M stock for every 90uL of water (stock, stable at room temperature indefinitely)
- 0.5M MgCl2 - 508mg in 5mL of water (stock, stable at room temperature indefinitely)
- 10% (v/v) Triton X100 - 10uL for every 90uL of water (stock, stable at room temperature indefinitely)
- 1% (v/v) SDS - 10uL of 20% stock for every 190uL of water (stock, stable at room temperature indefinitely)
- 10X cOmplete protease inhibitor stock - 1 tablet in 1mL of water (store at -80C)
- Lysis buffer (needs depend on the size of your cell pellet, recipe for 1mL)
  - 4M Urea (240mg of powder)
  - 100mM TrisCl pH 8.5 (100uL of 1M stock)
  - 5mM MgCl2 (10uL of 0.5M stock)
  - 0.1% (v/v) Triton X100 (10uL of 10% stock)
  - 0.01% (v/v) SDS (10uL of 1% stock)
  - 0.5X cOmplete protease inhibitor (50uL of 10X stock)
  - water to 1mL (550uL of clean water)
- Nuclease mix (need 10uL per sample, recipe for 100uL)
  - 250U benzonase (1uL of stock)
  - water to 100uL
- TC solution (need 10uL per sample, recipe for 1000uL)
  - 24.8mg TCEP
  - 37.2mg of CAA
  - water to 1000uL
- 50mM acetic acid - 28.7uL of 17.4M acetic acid in 9.97mL of water
- 1M calcium chloride - 1.1g in 10mL of water
- Digestion solution (need 80uL per sample, recipe for 1mL)
  - 10uL of 1M calcium chloride solution
  - 100uL of 1M TrisCl pH 7.5
  - 890uL of water
- 80% (v/v) ethanol (prepare fresh)
- 8M urea - 480mg of powder, 100uL of 1M TrisCl pH 8.5, 500uL of water
- 10% (v/v) TFA - 10uL of 100% stock for every 90uL of water

<span id="13-protocol"></span>

### 1.3 Protocol

This protocol assumes you have your cells growing in conventional 6-well dishes. If you are using a 10cm or bigger dish, I suggest harvesting your cells using trypsin and freezing the pellets and proceeding with the processing as below (skipping the cell scraping steps). No matter what vessel you are using, I suggest plating your cells 24h before your planned harvest time to achieve a confluence of 70-80% at harvest time. This will ensure a maximum number of cells are actively growing and producing protein. If your cells are slow to attach or are typically slow to start growing, you can do this 48h before. The end goal is to have an actively growing cell population that is not over-confluent.

If your cells are pelleted in a tube, you can scale the amount of lysis buffer based on the size of your pellet. We recommend not performing lysis in less than 75uL. In this case, you can skip the steps below associated with cell harvest from a dish.

Prior to starting, prepare sufficient Lysis buffer for all of the samples to be processed. Prepare three tubes for each sample to be processed (one for RNA - 1.5mL tube, one for protein - 2mL tube, one for protein - 1.5mL tube). To the RNA tubes, add 350uL of RNA lysis buffer to each (the RNA lysis buffer should be included with whatever kit you are using, or use a Trizol solution instead). 

1. Using a pipette, remove the culture medium from the growing cells on the 6-well plate.
2. Add 2mL of DPBS to each well and swirl the plate to rinse. Pipette up and discard the DPBS (or aspirate).
3. Add 200uL of Lysis buffer to each well and rock the plate back and forth to ensure the cells are covered.
4. Working one well at a time, use a cell scraper to dislodge the cells and a micropipette to transfer 200uL of lysate to the protein tube on ice. Repeat for each sample.
5. After you have harvested all of the samples in this manner, transfer 50uL of each lysate to the corresponding RNA tube containing RNA lysis buffer and vortex mix. These cells can be frozen at -80C for RNA extraction at a later time. This harvested RNA can be used for virtually any RNA assay (e.g. qPCR, RNA-seq).
6. To the remaining 150uL of lysate in the protein tube, add 10uL of nuclease mix and pipette mix. Incubate for 10-minutes at +24C without shaking.
7. Optional - transfer the lysate to a sonication tube and sonicate (Power = 80%, Pulse = 15 seconds on, 15 seconds off, Time = 10 minutes). 
8. Transfer the lysate to a 1.5mL tube and spin at 18,000g for 5-minutes. 
9. Measure the protein concentration using 1uL of lysate and the BCA Assay kit. 
10. To the remaining lysate, add 10uL of TC solution. Vortex mix and leave at room temperature for 30-minutes.
11. This is a good stop point. At this point, the protein lysate is compatible with Western blotting and can also be frozen for later processing. 
12. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 13):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
13. To a fresh 2mL tube for each sample, add 5uL of SP3 bead stock, 50ug of your lysate, and water to 50uL of total volume. Mix by gentle shaking. 
14. Add 250uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +24C for 5-minutes.
15. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 100ug trypsin vial using 100uL of the provided reconstitution solution (or the same volume of 50mM acetic acid).
    2. Aliquot the reconstituted trypsin and store at -80C for later use. Retain an aliquot for immediate use.
    3. Transfer 1uL of trypsin per sample to a fresh tube, and add 80uL of Digestion solution per sample. Vortex mix and keep on ice.
16. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
17. Place the tubes on a magnetic rack and discard the supernatant from each tube and add 800uL of 80% ethanol. Off the magnetic rack, pipette mix to reconstitute the beads.
18. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant as before. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
19. Add 80uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
20. Transfer the tubes to a shaking Thermomixer set at +37C and 1,000rpm, and digest for 14-18 hours.
21. The next day, spin the tubes at 1,000g for 2-minutes and add 10uL of 8M urea.
22. Sonicate the tubes in a water bath for 10-minutes.
23. During the above incubation, prepare a fresh 1.5mL tube for each sample and add 10uL of 10% TFA to it.
24. Centrifuge the digest tubes at 12,000g for 2-minutes, place the samples on a magnetic rack and transfer the supernatant to the tubes with the TFA.
25. At this point, you can clean-up your sample prior to MS analysis or it can be stored in the -80C freezer for later use. 