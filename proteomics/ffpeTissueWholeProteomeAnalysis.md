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
- Water (Thermo Scientific, CAT#10977023)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#15567027)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- Deoxycholate (Sigma, CAT#30970)
- Glycine (Sigma, CAT#50046-50G)
- Pierce BCA Protein Assay Kit (Thermo Scientific, CAT#23225)
- Ammonium bicarbonate (Sigma, CAT#A6141)
- Calcium chloride (Sigma, CAT#C4901)
- ProteoSure Trypsin (Marvelgent Biosciences, CAT#14-SRT-500UG)
- Acetic acid (Sigma, CAT#A6283)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Dithiothreitol (Sigma, CAT#43815)
- Iodoacetamide (Sigma, CAT#I1149)
- Chloroacetamide (Sigma, CAT#C0267)
- Trifluoroacetic acid (Sigma, CAT#T6508)
- Formic acid (Sigma, CAT#27001)
- Acetonitrile (Sigma, CAT#34998)
- Water (Sigma, CAT#270733)
- Desalting column (Kinetix F5, 2.1x50mm, Phenomenex, CAT#00B-4722-AN) - or similar
- RePLiCal unlabeled protein standard (PolyQuant, CAT#PQ-CS-1560)
- RePLiCal labeled peptide standard (PolyQuant, CAT#PQ-CS-2561)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 20% (w/v) sodium deoxycholate - 2g in 10mL of water (stable at room temperature indefinitely)
- Lysis buffer (recipe for 1mL)
  - 200mM TrisCl pH 7.5 (200uL of 1M stock solution)
  - 5% (v/v) SDS (250uL of 20% stock)
  - 5% (v/v) sodium deoxycholate (250uL of 20% stock)
  - 200uL of water
- 100fmol/uL RePLiCal protein mix (reconstitute stock in 255uL and store as 10uL aliquots)
- Dithiothreitol solution (need 10uL per sample, recipe for 1000uL)
  - 15mg dithiothreitol
  - water to 1000uL
- Iodoacetamide/chloroacetamide solution (need 10uL per sample, recipe for 1000uL)
  - 18mg iodoacetamide
  - 18mg chloroacetamide
  - water to 1000uL
- 50mM acetic acid - 28.7uL of 17.4M acetic acid in 9.97mL of water
- 100mM calcium chloride - 12mg in 1mL of water (stable at 4C for a year)
- 1M ammonium bicarbonate - 79mg in 1mL of water (make fresh)
- Digestion solution (need 100uL per sample, make fresh)
  - 10uL of 100mM calcium chloride solution
  - 190uL of 1M ammonium bicarbonate
  - 800uL of water
- 80% (v/v) ethanol (prepare fresh)
- 10% (v/v) trifluoroacetic acid (1mL in 10mL of water)
- 100fmol/uL RePLiCal peptide mix (reconstitute stock in 255uL and store as 10uL aliquots)
- 0.1% (v/v) formic acid in water (1mL of 100% stock in 1L of water)
- 0.1% (v/v) formic acid in acetonitrile (1mL of 100% stock in 1L of acetonitrile)
- 1% (v/v) formic acid (100uL in 10mL of water)

<span id="13-protocol"></span>

### 1.3 Protocol

This protocol assumes your samples are tissue scrolls in the Covaris tubes. Prior to starting, prepare sufficient Lysis buffer for all of the samples to be processed. Prepare 1 tube for each sample to be processed (1.5mL tube). Set a Thermomixer block to +95C. 

1. Add 120uL of Lysis solution to the tissue piece in the Covaris tube. Make sure all of the tissue is in the liquid before putting the lid back on.
2. Sonciate in the Covaris M220 unit using the built-in deparaffinization protocol for FFPE tissues. 
3. Transfer the lysate to a PCR tube and incubate in a PCR Thermocycler for 1.5h at +95C with the heated lid set to +105C.
4.  Measure the protein concentration of 5uL of the lysate using the BCA assay. 
5.  To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 6):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock (100ug/uL) and it can be stored at +4C indefinitely.
 6.  To a fresh 2mL tube for each sample, add 2uL of SP3 bead stock, 1uL of 100 fmol/uL RePLiCal protein stock, 50ug of your lysate, and water to 40uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
 7.  Add 160uL of acetone to each tube of protein lysate and incubate at +37C for 5-minutes with shaking at 800rpm.
 8.  During the above incubation, prepare your digestion mixture.
     1.  Reconstitute a 100ug trypsin using 100uL of 50mM acetic acid.
     2.  Transfer 1uL of trypsin per sample to a fresh tube, and add 100uL of Digestion solution per sample. Vortex mix and keep on ice.
 9.  Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
 10. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
 11. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
 12. Add 100uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
 13. Transfer the tubes to a shaking Thermomixer set at +37C and 800rpm, and digest for 14-18 hours.
 14. The next day, spin the tubes at 1000g for 2-minutes. Add 10uL of 100mM dithiothreitol and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 15. Add 10uL of iodoacetamide/chloroacetamide solution to each sample and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 16. Spin tubes at 12,000g for 2-minutes, place on a magnetic rack, and recover the supernatant to a fresh tube containing 10uL of 10% trifluoroacetic acid.
 17. This sample can now be desalted using a variety of approaches, but I recommend using an HPLC setup.
     1.  Equilibrate HPLC column at a flow rate of 1mL/min of 4% mobile phase B (0.1% formic acid in acetonitrile). Mobile phase A is 0.1% formic acid in water.
     2.  Zero out your DAD detector (we use the 210nm wavelength for detection).
     3.  Inject your sample and rinse for 1.5-minutes at 4% mobile phase B.
     4.  Switch the condition to 80% mobile phase B and collect your eluted peptides (your wait time here depends on the dead volume of your HPLC system, on ours it is a 40-second delay and we collect for 50-seconds).
     5.  Re-equilibrate the column at 4% mobile phase B for the next injection.
 18. SpeedVac the desalted sample to dryness.
 19. Reconstitute at a concentration of 1.5ug/uL in a solution of 1% formic acid. Prior to injection, add 1uL of 100 fmol/uL RePLiCal peptide standard per 4uL of solution. The concentration is dependent on the mAU signal from the HPLC during clean-up. On our system, 4mAU @254nm corresponds to ~1ug of peptide.
 20. Inject 1uL to the HPLC-MS system for analysis.