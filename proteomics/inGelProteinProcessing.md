# In gel protein processing <!-- omit in toc -->

This document describes a protocol for SDS-PAGE separation of a protein sample, extraction, digestion, and mass spectrometry analysis for identification. Although the protocol mainly describes extraction of a single protein band, it could also be used for extraction and preparation of multiple bands from a single, or multiple, lanes. This protocol starts after the gel has been run and in theory should be compatible with virtually any SDS-PAGE gel.

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [Reagents and materials](#reagents-and-materials)
- [Solution recipes](#solution-recipes)
- [Protocol](#protocol)
- [Notes](#notes)

<hr style="height:6pt; visibility:hidden;" />

<span id="reagents-and-materials"></span>

## Reagents and materials

- Acetonitrile, HPLC grade (Thermo Scientific, CAT#51101)
- Water, HPLC grade (Thermo Scientific, CAT#51140)
- Methanol, HPLC grade (Sigma, CAT#34860-4L)
- Acetic acid (Sigma, CAT#A6283)
- Brilliant blue (Sigma, CAT#B7920)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- Dithiothreitol (Bio-Rad, CAT#1610611)
- Chloroacetamide (Sigma, CAT#C0267)
- Urea (Sigma, CAT#U5128)
- Trypsin/rLysC mix (Promega, CAT#V5073)
- C18 TopTips (CAT#TT3C18, Glygen Corp.)
- Trifluoroacetic acid, HPLC grade (CAT#85183, Thermo Scientific)
- Formic acid, HPLC grade (CAT#85178, Thermo Scientific)
- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Thermomixer capable of holding 1.5mL or 2.0mL tubes (Eppendorf)
- Dimethylsulfoxide (Sigma, CAT#D8418)
- Benchtop centrifuge (capable of holding 1.5mL or 2mL microfuge tubes)
- Sonicating water bath (optional)
- Razor blade (or some sort of clean cutting tool)
- Small, clean glass plate (this is useful for cutting the gel on)
- Methanol, HPLC grade (CAT#610090040, Thermo Scientific)
- Water, HPLC grade (CAT#51140, Thermo Scientific)
- Trifluoroacetic acid, HPLC grade (CAT#85183, Thermo Scientific)
- Formic acid, HPLC grade (CAT#85178, Thermo Scientific)
- Strata-X microelution SPE plates (CAT# 8M-S100-4GA, Phenomenex)
- AxyMats Sealing mat for 96-well microplates (VWR, CAT#14-222-024)
- 96-well PCR microplates (VWR, CAT#14-222-326)

<span id="solution-recipes"></span>

## Solution recipes

- Gel fixing solution (recipe for 50mL)
  - Methanol - 25mL
  - Water - 20mL
  - Acetic acid - 5mL
- Gel destaining solution (recipe for 50mL)
  - Methanol - 22.5mL
  - Water - 22.5mL
  - Acetic acid - 5mL
- Coomassie concentrated solution (only need this if you are staining your gel)
  - Methanol - 30mL
  - Acetic acid - 6mL
  - Brilliant blue - 1.2g
- Gel staining solution (recipe for 50mL) (only need this if you are staining your gel)
  - Methanol - 250mL
  - Water - 200mL
  - Acetic acid - 50mL
- Gel piece destaining solution (make 5mL)
  - 100mM TrisCl pH 7.5 - 500uL of 1M stock solution
  - 20% (v/v) acetonitrile - 1mL of 100% acetonitrile solution
  - Water - 3.5mL (to a final volume of 5mL)
- 100mM TrisCl pH 7.5 - 10uL of 1M stock for every 90uL of water
- 0.2M of dithiothreitol (DTT) - 15mg in 500uL of 100mM TrisCl pH 7.5, prepare fresh and keep on ice
- 0.4M of chloroacetamide (CAA) - 18mg in 500uL of 100mM TrisCl pH 7.5, prepare fresh and keep on ice
- 0.02M of dithiothreitol (DTT) - 100uL of 0.2M stock in 900uL of 100mM TrisCl pH 7.5, prepare fresh and keep on ice
- 0.04M of chloroacetamide (CAA) - 100uL of 0.4M stock in 900uL of 100mM TrisCl pH 7.5, prepare fresh and keep on ice
- 4M urea (24mg for every 100uL of 100mM TrisCl pH 7.5, prepare just before use) (need 100uL per sample)
- 5% formic acid - 500uL of formic acid in 10mL of water
- Buffer A - methanol
- Buffer B - 0.1% trifluoroacetic acid (TFA) in water
- Rinse buffer - 0.1% formic acid, 4% methanol, in water
- Elution buffer - 0.1% formic acid in 60% methanol
- Sample Reconstitution Solution - 1% formic acid in water


<span id="protocol"></span>

## Protocol

This protocol generally takes 2-3 days. I tried to break it up into major sections based on this. If you have already stained your gel, you can skip the staining steps. If you don't have a sonicating bath you can just vortex the solution in the steps below that call for it.

1. For staining of the gel:
   1. Remove gel from the running cassette and place carefully in a container with gel fixing solution (enough to cover the gel).
   2. Incubate the gel in fixing solution on a rotary mixer for 30-minutes and discard the fixing solution afterwards.
   3. Add gel staining solution (enough to cover the gel) and stain the gel for 30-minutes and discard the staining solution afterwards.
   4. Add gel destaining solution and shake until no visible background remains (2-3 hours). The destaining can be accelerated by changing the destain liquid frequently, or adding a folded up KimWipe to the container.
   5. Keep the gel in fixing solution for long term storage at this stage if desired.
2. To prepare gel bands for extraction and perform digestion:
   1. Prepare a sufficient number of 2mL tubes for the number of gel bands you would like to cut out and add 200uL of the gel piece destain solution to each.
   2. Place the gel on cutting surface (such as a glass plate) and cut out your band of interest using a clean razor blade.
   3. Cut the extracted gel piece into small cubes (~1mm) and insert into the tube with gel piece destain solution in it.
   4. Destain the gel pieces until no blue remains! This process can be accelerated by changing the gel piece destain solution frequently.
   5. Remove and discard the destain and add 500uL of acetonitrile. Mix well by vortexing.
   6. Once the gel pieces have turned completely white, discard the acetonitrile.
   7. Add 50uL of DTT from the 0.02M stock to the gel pieces (or enough to cover the gel pieces) and incubate for 30-minutes at room temperature (+21C).
   8. Remove and discard any excess liquid and add 50uL of CAA from the 0.04M stock to the gel pieces (or the same volume that was added for DTT) and incubate for 30-minutes at room temperature in the dark.
   9. Discard any excess liquid in the tubes and add 500uL of acetonitrile and mix until the gel pieces are completely white.
   10. Discard the acetonitrile and add 200uL of 100mM TrisCl pH 7.5 and mix until the gel pieces are clear again.
   11. Discard the excess TrisCl pH 7.5 solution from the tubes and add 500uL of acetonitrile and mix until the gel pieces are completely white.
   12. During the above incubation, prepare your digestion mixture:
    1. Reconstitute urea powder with an appropriate amount of 100mM TrisCl pH 7.5. Vortex mix. NOTE - urea will increase the volume of the solution generally by the amount of powder you have weighed out. For example, to 240mg of urea, I would add 760uL of 100mM TrisCl pH 7.5 to make 1mL of solution.
    2. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution.
    3. Transfer 2uL of trypsin per sample to a fresh tube, and add 100uL of prepared urea per sample. Vortex mix and keep on ice.
   13. Discard the excess acetonitrile.
   14. Add 100uL of the digestion solution to the tubes (or enough to cover the gel pieces) and incubate for 2-hours at +30C in a Thermomixer with shaking at 800rpm.
   15. Add 300uL of 100mM TrisCl pH 7.5 to the gel pieces and incubate overnight at +30C in a Thermomixer with mixing at 800rpm.
3. To extract the generated peptides from the gel pieces:
   1. Spin digest tubes for 1-minute at 10,000g and transfer the supernatant liquid to a fresh labeled 1.5mL tube for each sample.
   2. Add 100uL of 5% formic acid to the tubes and sonicate in a water bath for 10-minutes.
   3. Spin the tubes for 1-minute at 10,000g and transfer the liquid to the 1.5mL tubes from Step 3.1.
   4. Repeat the previous two steps one addition time for a total of 2 extractions with 5% formic acid.
   5. Add 200uL of acetonitrile to the tubes and sonicate in a water bath for 10-minutes.
   6. Spin the tubes for 1-minute at 10,000g and transfer the liquid to the tubes containing the other material for the sample.
   7. Concentrate the peptide sample by evaporation. You can use a SpeedVac or a Lyophilizer for this purpose. The evaporated samples can be stored at -80C indefinitely.
4. To desalt samples prior to mass spectrometry analysis:
    1. Reconstitute your dried sample by adding 200uL of Buffer B, vortexing, and then centrifuging for 2-minutes at 12,000g.
    2. Add 200uL of Buffer A to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    3. Add 200uL of Buffer B to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    4. Add 200uL of the peptide samples to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    5. Repeat Step 3 to load the remainder of the sample.
    6. Add 200uL of Rinse buffer to the SPE plate wells and centrifuge at 250g for 3-minutes. Empty the collection plate to the waste.
    7. Add 200uL of Elution buffer to the SPE plate wells and centrifuge at 250g for 3-minutes.
    8. Transfer the elution from the collection plate to fresh 1.5mL tubes for each sample.
    9. Concentrate the peptide sample by evaporation. You can use a SpeedVac or a Lyophilizer for this purpose.
    10. After the sample is evaporated, add 20uL of Sample Reconstitution Solution to the tube, vortex, and then spin at 12,000g for 2-minutes.
    11. Transfer 10uL of the reconstituted peptides to a 96-well plate with a silicone mat lid. Freeze the remainder of the peptide material at -80C.
    12. Samples for MS analysis in the 96-well plate can be stored at this stage at -20C until analysis.