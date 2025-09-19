# FFPE Tissue Whole Proteome Analysis <!-- omit in toc -->

This document describes an end-to-end protocol for quantitative whole-proteome analysis by mass spectrometry of FFPE tissues. This protocol is also appropriate for harvesting material for other assays, such as Western blotting. This protocol can be used as a general guideline as there are many different ways of doing many of these individual steps and still achieving success. 

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
- PCR tubes (available from a variety of vendors)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- Covaris 130uL microTUBE (Covaris, CAT#520045)
- PCR Thermocycler (multiple vendors)
- Thermomixer with 2mL tube block (multiple vendors)
- SpeedVac concentrator (multiple vendors)
- Bath sonicator (multiple vendors)
- Xylenes (Sigma, CAT#247642-500ML)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#15567027)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- Deoxycholate (Sigma, CAT#30970)
- Pierce BCA Protein Assay Kit (Thermo Scientific, CAT#23225)
- Dithiothreitol (Bio-Rad, CAT#1610611)
- Iodoacetamide (Bio-Rad, CAT#1632109)
- Ammonium bicarbonate (Sigma, CAT#A6141)
- Calcium chloride (Sigma, CAT#C4901)
- ProteoSure Trypsin (Marvelgent Biosciences, CAT#14-SRT-500UG)
- Acetic acid (Sigma, CAT#A6283)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250 and CAT#45152105050250)
- Acetonitrile (Sigma, CAT#34998-4X4L)
- Methanol (Sigma, CAT#34885-4X4L-R)
- Isopropanol (Sigma, CAT#34863-4x4L)
- Chloroacetamide (Sigma, CAT#C0267)
- Urea (Sigma, CAT#U5128)
- Trifluoroacetic acid (Sigma, CAT#T6508)
- Formic acid (Thermo Scientific, CAT#A11750)
- Water (Sigma, CAT#270733-4X4L)
- Desalting column (Ascentis Express C18 pH+ 2.7um, 2.1x50mm, Sigma, CAT#70015-U) - or similar
- Enolase from Baker's yeast (Sigma, CAT#E6126-500UN)
- RePLiCal labeled peptide standard (PolyQuant, CAT#PQ-CS-2561)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 20% (w/v) sodium deoxycholate - 2g in 10mL of water (stable at room temperature indefinitely)
- Lysis solution (recipe for 1mL)
  - 100mM TrisCl pH 7.5 (100uL of 1M stock solution)
  - 5% (v/v) SDS (250uL of 20% stock)
  - 5% (v/v) sodium deoxycholate (250uL of 20% stock)
  - 400uL of water
- Dithiothreitol solution (need 10uL per sample, recipe for 1000uL)
  - 15mg dithiothreitol
  - water to 1000uL
- Alkylation solution (need 10uL per sample, recipe for 1000uL)
  - 36mg iodoacetamide
  - 36mg chloroacetamide
  - water to 1000uL
- Enolase standard
  - reconstitute 9.3mg of powder in 900uL of Lysis solution
  - add 10uL of Dithiothreitol solution and incubate at +65C for 15-minutes
  - add 10uL of Alkylation solution and incubate at room temperature for 15-minutes
  - add 10uL of Dithiothreitol solution to quench the reaction
  - aliquot and store as a 10mg/mL stock solution (-20C storage)
  - dilute to 20ng/uL in water as a working solution
- SP3 binding solution (need 200uL per 100uL of sample, recipe for 10mL)
  - 6mL acetonitrile
  - 2mL methanol
  - 2mL isopropanol
- 50mM acetic acid - 28.7uL of 17.4M acetic acid in 9.97mL of water
- 100mM calcium chloride - 12mg in 1mL of water (stable at 4C for a year)
- 1M ammonium bicarbonate - 79mg in 1mL of water (make fresh)
- Digestion solution (need 80uL per sample, make fresh)
  - 10uL of 100mM calcium chloride solution
  - 190uL of 1M ammonium bicarbonate
  - 800uL of water
- 80% (v/v) ethanol (prepare fresh)
- 8M urea - 480mg in 1mL of water
- 10% (v/v) trifluoroacetic acid (1mL in 10mL of water)
- 100fmol/uL RePLiCal peptide mix (reconstitute stock in 255uL and store as 10uL aliquots)
- 0.1% (v/v) formic acid in water (1mL of 100% stock in 1L of water)
- 1% (v/v) formic acid (100uL in 10mL of water)

<span id="13-protocol"></span>

### 1.3 Protocol

This protocol assumes your samples are tissue scrolls in 1.5mL tubes. Prior to starting, prepare sufficient Lysis buffer for all of the samples to be processed. Prepare 1 Covaris tube for each sample to be processed. Set a Thermomixer block to +65C. 

1. Add 800uL of xylenes to the 1.5mL tube with tissue and incubate in a Thermoblock at +65C for 10-minutes. 
2. Centrifuge the tube with xylenes at 12,000g for 5-minutes at room temperature (+24C). 
3. Discard the supernatant to an appropriate was container, taking care to remove as much xylene as possible (use a smaller pipette if necessary).
4. SpeedVac the tissue tube for 10-minutes (or to dryness).
5. Add 100uL of Lysis solution to the dried tissue piece and incubate in a Thermoblock at +65C for 10-minutes. 
6. One at a time, pipette mix and transfer the lysate to a PCR tube.
7. Incubate in a PCR Thermocycler for 1h at +95C followed by 30-minutes at +80C with the heated lid set to +105C.
8. Transfer the lysate to a Covaris tube and sonciate in the Covaris M220 unit using the built-in deparaffinization protocol for FFPE tissues ('FFPE_Paraffin_Removal_Step').
   1. Peak Power = 75
   2. Duty Factor =  20
   3. Cycles/Burst = 200
   4. Temperature Set Point = +20C
9.  Transfer the lysate to a 1.5mL tube and measure the protein concentration of 5uL of the lysate using the BCA assay. 
10. Add 10uL of the Dithiothreitol solution and incubate at +65C for 15-minutes.
11. Add 10uL of the Alkylation solution and incubate at room temperature for 15-minutes.
12. Add 10uL of the Dithiothreitol solution to quench the reaction.
13. At this point, the lysate can be stored frozen until downstream processing.
14. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 15):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock (100ug/uL) and it can be stored at +4C indefinitely.
 15. To a fresh 2mL tube for each sample, add 5uL of SP3 bead stock, 5uL of 20ng/uL Enolase standard, 50ug of your lysate, and water to 100uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
 16. Add 200uL of SP3 binding solution to each tube of protein lysate and incubate at +37C for 5-minutes with shaking at 800rpm.
 17. During the above incubation, prepare your digestion mixture.
     1.  Reconstitute a 100ug trypsin using 100uL of 50mM acetic acid.
     2.  Transfer 1000ng of trypsin per sample to a fresh tube, and add 100uL of Digestion solution per sample. Vortex mix and keep on ice.
 18. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
 19. Place the tubes on a magnetic rack and discard the supernatant from each tube.
 20. Add 800uL of 80% ethanol to each tube and pipette mix to reconstitute the beads.
 21. Centrifuge the tubes at 5,000g for 5-minutes, place on a magnetic rac, and discard the supernatant. 
 22. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
 23. Add 80uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
 24. Transfer the tubes to a shaking Thermomixer set at +37C and 800rpm, and digest for 14-hours.
 25. The next day, add 10uL of 10% trifluoracetic acid to a fresh 1.5mL tube for each sample. 
 26. Spin the digest tubes at 12,000g for 2-minutes, place on a magnetic rack, and transfer the digest to the new tubes with trifluoroacetic acid.
 27. To the tubes with the beads on the magnetic rack, add 40uL of 8M urea and sonicate in a bath sonicator for 5-minutes. 
 28. Spin the digest tubes at 12,000g for 2-minutes, place on a magnetic rack, and transfer the urea elution to the new tubes with trifluoroacetic acid.
 29. This sample can now be desalted using a variety of approaches, but I recommend using an HPLC setup.
     1.  Equilibrate HPLC column at a flow rate of 0.3mL/min of 2% mobile phase B (acetonitrile). Mobile phase A is 0.1% formic acid in water.
     2.  Zero out your DAD detector (we use the 254nm wavelength for detection).
     3.  Inject your sample and rinse for 3-minutes at 2% mobile phase B.
     4.  Switch the condition to 60% mobile phase B in 0.01-minutes and collect your eluted peptides (your wait time here depends on the dead volume of your HPLC system, you will need to calibrate this using a standard digest).
     5.  Re-equilibrate the column at 2% mobile phase B for the next injection.
 30. SpeedVac the desalted sample to dryness.
 31. Reconstitute at a concentration of 1ug/uL in a solution of 1% formic acid. Prior to injection, add 1uL of 100 fmol/uL RePLiCal peptide standard per 12uL of solution. The concentration is dependent on the mAU signal from the HPLC during clean-up. On our system, 4mAU @254nm corresponds to ~1ug of peptide.
 32. Inject 2uL to the HPLC-MS system for analysis.