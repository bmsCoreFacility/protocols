# SPE peptide cleanup <!-- omit in toc -->

This document describes a protocol for performing SPE cleanup of peptide samples prior to MS analysis. The approach described is based on the use of 96-well spin plates, but suggestions are given for adaptation to other types of media, such as SPE cartridges, StageTips, and TopTips.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [1. Peptide Sample Preparation](#1-peptide-sample-preparation)
  - [1.1 Reagents and materials](#11-reagents-and-materials)
  - [1.2 Solution recipes](#12-solution-recipes)
  - [1.3 Protocol](#13-protocol)

<hr style="height:6pt; visibility:hidden;" />

<span id="1-peptide-sample-preparation"></span>

## 1. Peptide Sample Preparation

For all the solutions described below and throughout this protocol in general, you should do your best to use sterile glassware and reagents. As the goal here is to measure proteins, make an effort to minimize potential keratin contamination (e.g. wear a lab coat and don't touch your tubes with un-gloved hands).

<span id="11-reagents-and-materials"></span>

### 1.1 Reagents and materials

- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- Clean water (Thermo Scientific, CAT#10977023)
- SPE medium (one of below)
    - Strata-X microelution SPE plates (CAT# 8M-S100-4GA, Phenomenex)
    - Empore C18 disk (CAT#66884-U, Sigma)
    - Strata-X C18 10mg, 1mL tube (CAT#8B-S100-AAK, Phenomenex)
- Methanol, HPLC grade (CAT#610090040, Thermo Scientific)
- Water, HPLC grade (CAT#51140, Thermo Scientific)
- Trifluoroacetic acid, HPLC grade (CAT#85183, Thermo Scientific)
- Formic acid, HPLC grade (CAT#85178, Thermo Scientific)
- 1.5mL snap-lock tubes (CAT#05-402-25, Thermo Scientific)
- Benchtop centrifuge with plate-holder rotor (multiple vendors)
- AxyMats Sealing mat for 96-well microplates (VWR, CAT#14-222-024)
- 96-well PCR microplates (VWR, CAT#14-222-326)

<span id="12-solution-recipes"></span>

### 1.2 Solution recipes

- Buffer A - methanol
- Buffer B - 0.1% trifluoroacetic acid (TFA) in water
- Rinse buffer - 0.1% formic acid, 4% methanol, in water
- Elution buffer - 0.1% formic acid in 60% methanol
- Sample Reconstitution Solution - 1% formic acid in water

<span id="13-protocol"></span>

### 1.3 Protocol

#### 96-well SPE plate

This protocol assumes you are using a 96-well spin plate. The plates listed in the materials have 2mg of material and as a general rule, we will assume a 10% binding capacity (e.g. 2mg of material can bind 200ug of peptide). In reality, it is likely higher than this, but it is better to err on the side of having more capacity than not enough. 

1. Clean up your sample using a Strata-X SPE plate:
    1. Add 200uL of Buffer A to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    2. Add 200uL of Buffer B to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    3. Add 200uL of the peptide samples to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    4. Repeat Step 3 to load the remainder of the sample.
    5. Add 200uL of Rinse buffer to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    6. Add 200uL of Elution buffer to the SPE plate wells and centrifuge at 250g for 3-minutes.
    7. Transfer the elution from the collection plate to fresh 1.5mL tubes for each sample.
2. Concentrate the peptide sample by evaporation. You can use a SpeedVac or a Lyophilizer for this purpose.
3. After the sample is evaporated, add 20uL of Sample Reconstitution Solution to the tube, vortex, and then spin at 12,000g for 2-minutes.
4. Transfer 10uL of the reconstituted peptides to a 96-well plate with a silicone mat lid. Freeze the remainder of the peptide material at -80C.
5. Samples for MS analysis in the 96-well plate can be stored at this stage at -20C until analysis.


#### SPE tube

If you are using an SPE tube (e.g. 1mL tube with 50mg of material), 800uL of volume per step is generally a good starting point. As above, we assume a 10% binding capacity (e.g. 50mg of material can bind 5mg of peptide).

1. Clean up your sample using a Strata-X SPE tube (1mL volume):
    1. Add 800uL of Buffer A to the SPE tube and elute using a vacuum manifold or positive pressure with a pipette. The desired flow rate is ~1mL/min.
    2. Add 800uL of Buffer B to the SPE tube and elute as above.
    3. Add up to 800uL of the peptide samples to the SPE tube and elute as above. 
    4. Repeat Step 3 to load the remainder of the sample, if necessary.
    5. Add 800uL of Rinse buffer to the SPE tube and elute as above.
    6. Add 800uL of Elution buffer to the SPE tube and elute into a fresh 1.5mL collection tube.
2. Concentrate the peptide sample by evaporation. You can use a SpeedVac or a Lyophilizer for this purpose.
3. After the sample is evaporated, add 20uL of Sample Reconstitution Solution to the tube, vortex, and then spin at 12,000g for 2-minutes.
4. Transfer 10uL of the reconstituted peptides to a 96-well plate with a silicone mat lid. Freeze the remainder of the peptide material at -80C.
5. Samples for MS analysis in the 96-well plate can be stored at this stage at -20C until analysis.


#### StageTip

If you are using a centrifuge for your StageTips, you may need to adjust your speeds to get a reasonable flow rate. The most important thing is that you don't want your bead bed to dry out prior to sample loading, especially with StageTips. Try to keep some volume above the top of the bead bed. If you are using a StageTip, each plug will generally bind 2-4ug of peptide, so scale accordingly. The more plugs you have, the slower your flow rate will be, so you may need to alter your spin times. 

1. Clean up your sample using a StageTip (2 layers in a 200uL pipette tip):
    1. Add 100uL of Buffer A to the StageTip and elute using a centrifuge at 600g for 3.5-minutes.
    2. Add 100uL of Buffer B to the StageTip and elute as above.
    3. Add up to 200uL of the peptide samples to the StageTip and elute using a centrifuge at 600g for 7-minutes. 
    4. Repeat Step 3 to load the remainder of the sample, if necessary.
    5. Add 200uL of Rinse buffer to the StageTip and elute using a centrifuge at 600g for 7-minutes.
    6. Add 150uL of Elution buffer to the StageTip and elute into a fresh 1.5mL collection tube (600g for 15-minutes).
2. Concentrate the peptide sample by evaporation. You can use a SpeedVac or a Lyophilizer for this purpose.
3. After the sample is evaporated, add 20uL of Sample Reconstitution Solution to the tube, vortex, and then spin at 12,000g for 2-minutes.
4. Transfer 10uL of the reconstituted peptides to a 96-well plate with a silicone mat lid. Freeze the remainder of the peptide material at -80C.
5. Samples for MS analysis in the 96-well plate can be stored at this stage at -20C until analysis.