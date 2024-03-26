# Whole proteome analysis from FFPE tissues <!-- omit in toc -->

This document describes an end-to-end protocol for quantitative whole-proteome analysis by mass spectrometry of FFPE tissues. This protocol is also appropriate for harvesting material for other assays, such as Western blotting. This protocol can be used as a general guideline as there are many different ways of doing many of these individual steps and still achieving success. The topics covered include how to perform lysis of tissue material, clean-up of proteins, tryptic digestion, and final peptide clean-up. The protocol is designed to work with FFPE tissues, but may be appropriate for other tissue types.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. Protein Sample Preparation](#1-protein-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3 Protocol](#13-protocol)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-protein-sample-preparation"></span>

## 1. Protein Sample Preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to proteins, make an effort to minimize potential keratin contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands). 

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- Xylenes (Sigma, CAT#214736)
- Lysing matrix D tubes (MP Biomedicals, CAT#116913050-CF) - optional but recommended, if using FastPrep
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

This protocol assumes you have your tissue as scrolls in a tube. This protocol is compatible with processing 1 or a greater number of scrolls. I have provided a protocol that uses the FastPrep machine for tissue disruption and I highly recommend this. It helps break down the tissue and supports greater access to the tissue for de-paraffinization and clean-up. We have observed that the losses of tissue are negligible with this approach.

Prior to starting, prepare sufficient Lysis buffer A and B for all of the samples to be processed. Make sure you have a Thermomixer heated to +95C or greater.  

1. If you are using the FastPrep, start here. If not, jump to Step 2.
    1. Transfer your tissue scrolls to a Lysing matrix D tube.
    2. Add 800uL of xylene to the tube and disrupt on the FastPrep machine using a duration of 45s at speed 6.
    3. Using a pipette, transfer the xylene + tissue mixture to a 2mL tube and spin at 12,000g for 2-minutes. Discard the supernatant. 
    4. Add 800uL of 80% ethanol to the Lysing matrix D tube and briefly vortex mix. Transfer the ethanol to the 2mL tube with the tissue and spin at 12,000g for 2-minutes. Discard the supernatant.
    5. Repeat Step 4 two additional times for a total of 3 rinses.
    6. Using a 200uL pipette, remove as much of the 80% ethanol as possible, taking care to not remove any tissue.
    7. Proceed to lysis at Step 3.
2. If you are not using the FastPrep, start here.
    1. Transfer your tissue sections to a 2mL tube if they are not already in one.
    2. Add 800uL of xylene to the tube and vortex briefly. Spin at 12,000g for 2-minutes and using a pipette, carefully remove the xylene to waste. 
    3. Repeat Step 2 one additional time.
    4. Add 800uL of 80% ethanol to the 2mL tube with the tissue, vortex briefly, and spin for 2-minutes at 12,000g. Carefully remove the supernatant to waste. This part can be very challenging if you have not disrupted the tissue. Do your best to not lose tissue, but it is likely some will be lost.
    5. Repeat Step 4 two additional times for a total of 3 rinses. 
    6. Using a 200uL pipette, remove as much of the 80% ethanol as possible, taking care to not remove any tissue.
    7. Proceed to lysis at Step 3.
3. Add 150uL of Lysis buffer A to each tube with tissue. You may need to scale this up if you have used a lot of tissue.
4. Add 10uL of Nuclease mix and gently shake the tube to make sure the tissue pellet is reconstituted in the lysis buffer. Incubate for 10-minutes at +24C without shaking.
5. After incubation, add 50uL of Lysis buffer B to the tissue lysate and pipette mix. 
6. Place the tissue mixture in the pre-heated Thermomixer at +95C (with the heated lid, if possible) and incubate for 60-minutes with shaking at 1,000rpm.
7. Remove the protein lysate from the Thermoblock and quick-spin the tubes at low speed to remove any condensation from the lid (e.g. 250g for 30 seconds).
8. Add 10uL of TC solution. Vortex mix and leave at room temperature for 30-minutes.
9. At this point, the protein lysate is compatible with Western blotting. I will usually add 6uL of 6X SDS Loading Buffer to 24uL of my sample, and run 20-30uL on a gel. 
10. This is a good stop point. You should measure the protein concentration in your sample using a BCA assay at this point. The samples here can be stored at -80C indefinitely, or directly used for other protocols such as Western blotting, as mentioned above.
11. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 14):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
12. To a fresh 2mL tube for each sample, add 10uL of SP3 bead stock, 20ug of your lysate, and water to 100uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
13. Add 400uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +24C for 5-minutes.
14. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution (or the same volume of 50mM acetic acid).
    2. Transfer 5uL of trypsin per sample to a fresh tube, and add 200uL of Digestion solution per sample. Vortex mix and keep on ice.
15. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
16. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
17. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
18. Add 200uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
19. Transfer the tubes to a shaking Thermomixer set at +37C and 1,000rpm, and digest for 14-18 hours.
20. The next day, spin the tubes at 12,000g for 2-minutes and then place on a magnetic rack. Recover the supernatant to a fresh 1.5mL tube.
21. At this point, you can clean-up your sample prior to MS analysis. See other protocols on this page for direction on that process.