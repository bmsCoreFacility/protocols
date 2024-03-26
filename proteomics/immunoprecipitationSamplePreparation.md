# Preparation of immunoprecipitation samples for MS analysis <!-- omit in toc -->

This document describes how to perform preparation of immunoprecipitated protein samples for analysis by mass spectrometry. The assumed starting point for this protocol are beads just after you have performed your affinity purification. As we will be using SP3 as the first processing step, elution can be performed in virtually any condition. Below, I give a formulation of a typical elution buffer that we use in immunoprecipitation (IP) experiments.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. Immunoprecipitation sample preparation](#1-immunoprecipitation-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3 Optional IP protocol](#13-optional-ip-protocol)
  - [1.4 Post IP sample processing](#14-post-ip-sample-processing)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-immunoprecipitation-sample-preparation"></span>

## 1. Immunoprecipitation sample preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to measure proteins, make an effort to minimize potential keratin contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands).

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- MgCl2 (Sigma, CAT#M8266)
- KCl (Sigma, CAT#P9333)
- NP-40 (Sigma, CAT#NP40)
- Deoxycholate (DOC) (Sigma, CAT#D6750)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- 5M NaCl (Thermo Scientific, CAT#AM9760G)
- cOmplete protease inhibitor tablets, EDTA free (Sigma, CAT#11836170001)
- TCEP (Sigma, CAT#580560)
- Chloroacetamide (Sigma, CAT#C0267)
- Tween20, 50% solution (Thermo Fisher, CAT#003005)
- Dynabeads, protein G (Thermo Scientific, CAT#10003D)
- Benzonase nuclease, 25U/uL (Sigma, CAT#70664-3)
- RNase A, 10mg/mL (Thermo Scientific, CAT#EN0531)
- Clean water (Thermo Scientific, CAT#10977023)
- Trypsin/rLysC mix (Promega, CAT#V5071)
- Thermomixer with 2mL tube block (Eppendorf)
- Thermoblock set to >60C (multiple vendors)
- Magnetic rack for 1.5mL or 2.0mL tubes (I like this rack: Promega, CAT#Z5342)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Thermo Scientific, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Trifluoroacetic acid, HPLC grade (CAT#85183, Thermo Scientific)

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
- 1X TBST (prepare fresh, recipe for 40mL)
  - Tris-Cl pH 7.5 (800uL of 1M stock)
  - NaCl (1.2mL of 5M stock)
  - Tween20 (400uL of 10% stock)
  - Water (38mL)
- 80% (v/v) ethanol (prepare fresh)

<span id="13-optional-ip-protocol"></span>

### 1.3 Optional IP protocol

Example protocol for IP (optional if you have followed your own protocol and are at the elution step). This protocol is suitable for an antigen that is primarily cytoplasmic. This assumes you are starting with a frozen cell pellet. I typically like to scale the amount of lysis buffer I use based on the estimated volume of the cell pellet. For example, for a 100uL cell pellet, I will typically lyse in 200uL. Prior to starting, prepare sufficient Lysis buffer A for all of the samples to be processed. If you want to substitute an alternative solution for elution, such as SDS Loading Buffer (including DTT or another reducing agent), you can do so without changing this protocol. Just use 100uL of your desired elution buffer and proceed from Step 4 in the protocol in Section 1.4. If you used an elution buffer without DTT or another reducing agent, simply add one to a final concentration of 10mM.

1. Thaw the cell pellets to be processed on ice.
2. Add 190uL of Lysis buffer A to each cell pellet and reconstitute by pipetting. Transfer to a fresh 1.5mL tube.
3. Add 10uL of nuclease mix to each tube and incubate at +24C for 10-minutes.
4. Centrifuge the lysate at 5,000g for 5-minutes and collect the supernatant to a fresh 2mL tube. The leftover pellet can be stored at -80C for later analysis if desired.
5. Add 2ug of your target antibody to the sample and pipette mix. Incubate with end-over-end mixing for 2-hours at room temperature (or overnight at +4C depending on your antibody).
6. During this incubation, prepare your Protein G beads by rinsing 25uL per sample in 800uL of TBST for a total of 3x rinses. Reconstitute the rinsed beads in 25uL of TBST per sample.
7. To your incubated IP sample, add 25uL of rinsed protein G beads and incubate for an additional 1-hour at +24C with end-over-end rotation.
8. Place IP samples on a magnetic rack and discard the supernatant.
9. Rinse the IP beads 5x with 800uL of TBST and reconstitute the beads in 75uL of Lysis buffer A.
10. Add 25uL of Lysis buffer B and incubate at +65C for 10-minutes.
11. Place samples on a magnetic rack and recover the supernatant to a fresh 2mL tube. Store at -80C until purification or proceed to the protocol below (start at Step 4).

<span id="14-post-ip-sample-processing"></span>

### 1.4 Post IP sample processing

This protocol assumes you have performed an immunoprecipitation and have rinsed your beads and are at the elution step. Prior to starting, prepare sufficient Lysis buffer A and B for all of the samples to be processed. Make sure you have a Thermoblock heated to +60C. Prepare 1x 2mL tube for each sample to be processed. As above, you can use a different elution solution if you desire, such as SDS Loading Buffer (including DTT @ 10mM or another reducing agent). Just use 100uL of your desired elution buffer and proceed from Step 4 in the protocol below. If you used an elution buffer without DTT or another reducing agent, simply add one to a final concentration of 10mM.

1. Reconstitute the beads in 75uL of Lysis buffer A (OPTIONAL - if you haven't done a nuclease digestion as in the protocol above, this is a good step to add 10uL of nuclease mix and incubate at +24C for 10-minutes prior to eluting).
2. Add 25uL of Lysis buffer B and incubate at +60C for 10-minutes.
3. Place samples on a magnetic rack and recover the supernatant to a fresh 2mL tube.
4. Place the eluted IP in the pre-heated Thermoblock at +60C and incubate for 5-minutes.
5. Remove the protein lysate from the Thermoblock and quick-spin the tubes at low speed to remove any condensation from the lid (e.g. 250g for 30 seconds).
6. Add 10uL of TC solution. Vortex mix and leave at room temperature for 30-minutes. 
7. This is a good stop point. You should measure the protein concentration in your sample using a BCA assay at this point. The samples here can be stored at -80C indefinitely, or directly used for other protocols such as Western blotting, as mentioned above.
8. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 14):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
9. To a fresh 2mL tube for each sample, add 10uL of SP3 bead stock, 20ug of your lysate, and water to 100uL of total volume. Mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
10. Add 400uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +24C for 5-minutes.
11. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution (or the same volume of 50mM acetic acid).
    2. Transfer 2uL of trypsin per sample to a fresh tube, and add 200uL of Digestion solution per sample. Vortex mix and keep on ice.
12. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
13. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
14. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
15. Add 200uL of the prepared trypsin mix to each tube. Do not attempt to mix, vortex, or pipette.
16. Transfer the tubes to a shaking Thermomixer set at +37C and 1,000rpm, and digest for 14-18 hours.
17. The next day, spin the tubes at 12,000g for 2-minutes and then place on a magnetic rack. Recover the supernatant to a fresh 1.5mL tube.
18. At this point, you can clean-up your sample prior to MS analysis. See other protocols on this page for direction on that process.