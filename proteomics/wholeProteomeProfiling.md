# Whole proteome analysis <!-- omit in toc -->

This document describes an end-to-end protocol for quantitative whole-proteome analysis by mass spectrometry. This protocol is also appropriate for harvesting material for other assays, such as Western blotting. This protocol can be used as a general guideline as there are many different ways of doing many of these individual steps and still achieving success. The topics covered include how to perform harvest and lysis of cell line material, clean-up of proteins, tryptic digestion, and final peptide clean-up. The protocol is designed to work with cell line material, but may be appropriate for tissues or other sources.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. Protein Sample Preparation](#1-protein-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3.1 Protocol](#131-protocol)
  - [1.3.2 Protocol](#132-protocol)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-protein-sample-preparation"></span>

## 1. Protein Sample Preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to measure proteins, make an effort to minimize potential keratin contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands).

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- Lysing Matrix D (MP Biomedicals, CAT#116540434) - optional
- Bead beading instrument (we use a Qiagen TissueLyser II, but there are many other options)
- DPBS (Thermo Scientific, CAT#14190144)
- Water (Thermo Scientific, CAT#10977023)
- Ammonium bicarbonate (Sigma, CAT#A6141)
- Triton X100 (Sigma, CAT#93443)
- Urea (Sigma, CAT#51456)
- MgCl2 (Sigma, CAT#M8266)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- cOmplete protease inhibitor tablets, EDTA free (Sigma, CAT#11836170001)
- Pierce BCA Protein Assay Kit (Thermo Scientific, CAT#23225)
- Calcium chloride (Sigma, CAT#C4901)
- ProteoSure Trypsin (Marvelgent Biosciences, CAT#14-SRT-500UG)
- Acetic acid (Sigma, CAT#A6283)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Thermomixer with 2mL tube block (Eppendorf)
- Dithiothreitol (Sigma, CAT#43815)
- Iodoacetamide (Sigma, CAT#I1149)
- Chloroacetamide (Sigma, CAT#C0267)
- Trifluoroacetic acid (Sigma, CAT#T6508)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 10% (v/v) Triton X100 - 1mL in 10mL of water (stock, stable at room temperature indefinitely)
- 1% (v/v) SDS - 500uL of 20% stock in 10mL of water (stock, stable at room temperature indefinitely)
- 0.5M MgCl2 - 508mg in 5mL of water (stock, stable at room temperature indefinitely)
- 10X cOmplete protease inhibitor stock - 1 tablet in 1mL of water (store at -80C)
- Lysis buffer A (recipe for 1mL)
  - 1M ammonium bicarbonate (80mg of powder)
  - 4M urea (240mg of powder)
  - 1mM MgCl2 (2uL of 0.5M stock)
  - 0.1% (v/v) Triton X100 (10uL of 10% stock)
  - 0.01% (v/v) SDS (10uL of 1% stock)
  - 0.5X cOmplete protease inhibitor (50uL of 10X stock)
  - water to 1mL (~640uL of clean water)
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
- Digestion solution (need 200uL per sample)
  - 10uL of 100mM calcium chloride solution
  - 100uL of 1M ammonium bicarbonate
  - 890uL of water
- 80% (v/v) ethanol (prepare fresh)
- 10% (v/v) trifluoroacetic acid (1mL in 10mL of water)

<span id="13-protocol"></span>

### 1.3.1 Protocol

This version of the protocol assumes you have your cells present as a frozen pellet. This version of the protocol is also suitable for tissues. Depending on the size of your cell pellet/tissue, you may want to perform physical disruption and an option is provided for that. As a general rule of thumb, I will perform lysis in a volume at least 2X the size of the pellet/tissue. If you are performing lysis in more than 300uL, I would suggest performing physical disruption. For tissues, I always suggest performing disruption. 

Prior to starting, prepare sufficient Lysis buffer for all of the samples to be processed. Prepare 1 tube for each sample to be processed (2mL tube).

1. If you are performing disruption, transfer 500uL of Lysing Matrix D to a 2mL tube for each sample. If you are not performing disruption, skip to Step 2. 
   1. Add the thawed lysate or tissue material to the tube with the lysing matrix and add an appropriate amount of Lysis buffer (>=300uL).
   2. Disrupt on the Qiagen TissueLyser for 5-minutes at a speed setting of 30.
   3. Centrifuge the tubes at 12,000g for 5-minutes and recover the supernatant to a fresh tube.
   4. Go to Step 3 to continue.
2. If you are starting your lysis here, add sufficient lysis buffer for your material (see above, at least 2X the estimated volume of material) and pipette mix.
3. Add 0.5uL of Benzonase per 100uL of Lysis solution and incubate at 24C for 10-minutes. 
4. Measure the protein concentration of the lysate using the BCA assay.
5. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 6):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock (100ug/uL) and it can be stored at +4C indefinitely.
 6. To a fresh 2mL tube for each sample, add 1uL of SP3 bead stock, 50ug of your lysate, and water to 40uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
 7. Add 160uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +37C for 5-minutes with shaking at 800rpm.
 8. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 100ug trypsinusing 100uL of 50mM acetic acid.
    2. Transfer 1uL of trypsin per sample to a fresh tube, and add 100uL of Digestion solution per sample. Vortex mix and keep on ice.
 9. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
 10. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
 11. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
 12. Add 100uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
 13. Transfer the tubes to a shaking Thermomixer set at +37C and 800rpm, and digest for 14-18 hours.
 14. The next day, spin the tubes at 1000g for 2-minutes. Add 10uL of 100mM dithiothreitol and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 15. Add 10uL of iodoacetamide/chloroacetamide solution to each sample and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 16. Spin tubes at 12,000g for 2-minutes, place on a magnetic rack, and recover the supernatant to a fresh tube containing 5uL of 10% trifluoroacetic acid.
 17. This sample can now be desalted using a variety of approaches, but I recommend using an HPLC setup as described elsewhere on this web page.


### 1.3.2 Protocol

This version of the protocol assumes you have your cells growing in a 6-well dish.  

Prior to starting, prepare sufficient Lysis buffer for all of the samples to be processed. Prepare 1 tube for each sample to be processed (2mL tube).

1. Remove the medium from your cells and rinse 2X with 2mL of PBS.  
2. Prepare the lysis solution by mixing 0.5uL of Benzonase with 200uL of Lysis solution per well.
3. Add 200uL of the prepared Lysis solution with Benzonase to each well and incubate at +37C for 10-minutes. 
4. Harvest the lysate using a cell scraper to assist if necessary and measure the protein concentration of the lysate using the BCA assay.
5. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 6):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock (100ug/uL) and it can be stored at +4C indefinitely.
 6. To a fresh 2mL tube for each sample, add 1uL of SP3 bead stock, 50ug of your lysate, and water to 40uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
 7. Add 160uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +37C for 5-minutes with shaking at 800rpm.
 8. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 100ug trypsinusing 100uL of 50mM acetic acid.
    2. Transfer 1uL of trypsin per sample to a fresh tube, and add 100uL of Digestion solution per sample. Vortex mix and keep on ice.
 9. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
 10. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
 11. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
 12. Add 100uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
 13. Transfer the tubes to a shaking Thermomixer set at +37C and 800rpm, and digest for 14-18 hours.
 14. The next day, spin the tubes at 1000g for 2-minutes. Add 10uL of 100mM dithiothreitol and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 15. Add 10uL of iodoacetamide/chloroacetamide solution to each sample and place in a Thermomixer at +37C for 15-minutes at 800rpm.
 16. Spin tubes at 12,000g for 2-minutes, place on a magnetic rack, and recover the supernatant to a fresh tube containing 5uL of 10% trifluoroacetic acid.
 17. This sample can now be desalted using a variety of approaches, but I recommend using an HPLC setup as described elsewhere on this web page.