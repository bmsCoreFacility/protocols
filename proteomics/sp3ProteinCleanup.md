# Cleanup of protein mixtures using SP3 <!-- omit in toc -->

This document describes how to perform SP3 on a prepared protein mixture that contains contaminants you would like to remove (e.g. detergents). The described protocol includes information of directly eluting proteins, or digestion with trypsin as the final elution step from the beads. This protocol is described based on the use of 100ug of input lysate, but the protocol can be scaled for any amount of input material. Refer to the Nature Protocols paper on SP3 for considerations related to scaling volumes or bead amounts when you use different amounts of input material (PMID: 30464214).

<hr style="height:6pt; visibility:hidden;" />

## Quick links <!-- omit in toc -->

- [Reagents and materials](#reagents-and-materials)
- [Solution recipes](#solution-recipes)
- [Protocol](#protocol)
- [Notes](#notes)

<hr style="height:6pt; visibility:hidden;" />

<span id="reagents-and-materials"></span>

## Reagents and materials

- 1.5mL or 2.0mL Safe-Lock tubes (Thermo Scientific, CAT#05-402-25 or CAT#05-402-7)
- Benchtop centrifuge with holder for microcentrifuge tubes (multiple vendors)
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- Ethanol, absolute (whatever vendor sells this to your lab)
- SP3 beads (Sigma, CAT#65152105050250, CAT#45152105050250)
- Acetone (Sigma, CAT#179124)
- Trypsin/rLysC mix (Promega, CAT#V5073)
- Urea (Sigma, CAT#U5128)
- Thermomixer capable of holding 1.5mL or 2.0mL tubes
- Magnetic rack for 1.5mL or 2.0mL tubes (I like this rack: Promega, CAT#Z5342)

<span id="solution-recipes"></span>

## Solution recipes

- 100mM TrisCl pH 7.5 - 10uL of 1M stock for every 90uL of water (need 400uL per sample)
- 80% (v/v) ethanol (prepare fresh) (need 2mL per sample)
- 4M urea (24mg for every 100uL of 100mM TrisCl pH 7.5, prepare just before use) (need 100uL per sample)

<span id="protocol"></span>

## Protocol

The protocol steps below assume that you have 20ug of prepared protein lysate that has been DNase treated and is in a volume of ~100uL. You may need to scale the reactions below based on your actual starting conditions. 

1. To perform clean-up prior to digestion, prepare the SP3 beads stock (if you don't have an existing stock, otherwise skip to Step 2):
    1. Vortex the two 15mL containers of bead stocks from the manufacturer to re-suspend the material.
    2. Take 500uL of each of the bead stocks and combine in a fresh 2mL tube.
    3. Place on a magnetic rack and wait for beads to settle. Discard the supernatant.
    4. Reconstitute the beads in 1mL of water with pipetting and place back on the magnetic rack. After the beads settle, discard the supernatant.
    5. Repeat the above rinse one additional time for a total of 2 rinses.
    6. Reconstitute the beads in 500uL of water. This is your bead stock and it can be stored at +4C indefinitely.
2. To a fresh 2mL tube for each sample, add 10uL of SP3 bead stock and 90uL of your prepared lysate and mix by gentle shaking. The remaining lysate can be stored at -80C for validation assays (e.g. Western blotting), or as a backup sample if your protein digestion fails.
3. Add 400uL of acetone to each tube of protein lysate and gently shake the tube to mix. Incubate at +24C for 5-minutes.
4. During the above incubation, prepare your digestion mixture:
    1. Reconstitute urea powder with an appropriate amount of 100mM TrisCl pH 7.5. Vortex mix. NOTE - urea will increase the volume of the solution generally by the amount of powder you have weighed out. For example, to 240mg of urea, I would add 760uL of 100mM TrisCl pH 7.5 to make 1mL of solution.
    2. Reconstitute a 20ug trypsin/rLysC vial using 100uL of the provided reconstitution solution.
    3. Transfer 2.5uL of trypsin per sample to a fresh tube, and add 100uL of prepared urea per sample. Vortex mix the digestion solution and keep on ice.
    4. The remaining trypsin/rLysC stock can be aliquoted and stored at -80C for use at a later date.
5. Centrifuge the protein lysate tubes at 5,000g for 5-minutes at room temperature.
6. Discard the supernatant from each tube and add 800uL of 80% ethanol. Pipette mix to reconstitute the beads.
7. Centrifuge the tubes at 5,000g for 5-minutes and discard the supernatant. Using a P200 or P20 micropipette, make sure you have removed as much leftover liquid from the rinse as possible from the tubes.
8. Add 100uL of the prepared trypsin/urea mix to each tube. Do not attempt to pipette mix or vortex the tubes.
9. Transfer the tubes to a shaking Thermomixer set at +30C and 1,000rpm, and digest for 2-4 hours.
10. Add 300uL of 100mM TrisCl pH 7.5 to each tube and place back in the Thermomixer and incubate overnight at +30C and 1,000rpm mixing.
11. The next day, spin the tubes at 12,000g for 2-minutes and then place on a magnetic rack and recover the supernatant to a fresh tube. This recovered peptide solution can be purified by SPE for MS analysis, or stored at -80C indefinitely.

<hr style="height:6pt; visibility:hidden;" />

<span id="notes"></span>

## Notes

1. Other beads can be substituted, such as BangsLabs Magnefy beads (CAT#MFY0001), or other carboxylate modified particles. Other companies, such as MagReSyn also offer HILIC beads which are also compatible.
2. The bead stock from the vendor is 50mg/mL. We recommend using the beads at a 10:1 (ug of beads : ug of protein) ratio. This is far in excess of what is necessary, but will improve rinsing and elution efficiency by reducing the amount of 'clumping' that happens during binding.