# Yeast protein standard <!-- omit in toc -->

This document describes protocol for preparing a yeast peptide standard that can be used to monitor mass spectrometer performance.

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
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- TCEP (Sigma, CAT#580560)
- Chloroacetamide (Sigma, CAT#C0267)
- Benzonase nuclease, 25U/uL (Sigma, CAT#70664-3)
- Calcium chloride (Sigma, CAT#C4901)
- Acetic acid (Sigma, CAT#A6283)
- Clean water (Thermo Scientific, CAT#10977023)
- Trypsin/rLysC mix (Promega, CAT#V5071)
- Thermomixer with 2mL tube block (Eppendorf)
- Thermoblock set to +60C (multiple vendors)
- Magnetic rack for 1.5mL or 2.0mL tubes (I like this rack: Promega, CAT#Z5342)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Yeast protein extract, 1mg (Promega, CAT#V7341)
- Pierce Peptide Retention Time Calibration Mixture (Thermo Scientific, CAT#88321)
- Formic acid, HPLC grade (CAT#85178, Thermo Scientific)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- 100mM TrisCl pH 7.5 - 10uL of 1M stock for every 90uL of water (stock, stable at room temperature indefinitely)
- TC solution (need 40uL per sample, recipe for 1000uL)
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
- Sample Reconstitution Solution - 1% formic acid in water

<span id="13-protocol"></span>

### 1.3 Protocol

1. Thaw the yeast protein extract and transfer 5uL (50ug) to each of 2x2mL tubes. Aliquot the remaining yeast extract into 10uL portions and freeze at -80C until use. 
2. Add 35uL of water to each of the 2x2mL tubes containing the yeast extract. 
3. Add 5uL of 1M TrisCl pH 7.5 to each of the extract tubes.
4. Add 0.5uL of benzonase to each of the extract tubes and incubate at +37C for 10-minutes.
5. Add 5uL of 20% SDS to each of the extract tubes and incubate at +60C for 10-minutes.
6. Add 10uL of TC solution to each of the extract tubes and incubate at +24C for 30-minutes.
7. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 7):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
8. Add 10uL of the SP3 bead stock to each sample followed by 240uL of acetone and gently shake the tube to mix. Incubate at +24C for 5-minutes.
9. During the above incubation, prepare your digestion mixture:
    1. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution (or the same volume of 50mM acetic acid).
    2. Transfer 5uL of trypsin per sample to a fresh tube, and add 200uL of Digestion solution per sample. Vortex mix and keep on ice.
10. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
11. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
12. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
13. Add 200uL of the prepared trypsin/urea mix to each tube. Do not attempt to mix, vortex, or pipette.
14. Transfer the tubes to a shaking Thermomixer set at +37C and 1,000rpm, and digest for 14-18 hours.
15. The next day, spin the tubes at 12,000g for 2-minutes and then place on a magnetic rack. Recover the supernatant to a fresh 1.5mL tube.
16. SpeedVac the tubes to near dryness and reconstitute or bring each up to a final volume of 50uL using water and combine the two tubes to a final 100uL (this should be approximatey 1ug/uL based on the starting amount of 100ug). 
17. If this is your first time using the retention time standard, make 10uL aliquots and store at -20C until needed.
18. Transfer 10uL of the digested yeast peptides to an autosampler vial or injection well. Add 2uL of the retention time standard. Add 188uL of Reconstitution solution and pipette mix.
19. Depending on the instrument and setup, inject 2uL to monitor MS performance (~100ng of peptides). 