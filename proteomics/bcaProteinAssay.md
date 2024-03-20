# BCA Protein Assay <!-- omit in toc -->

This document describes a protocol for performing BCA assays on protein samples.

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
- 1M TrisCl pH 7.5 (Thermo Scientific, CAT#J60636.K2)
- MgCl2 (Sigma, CAT#M8266)
- KCl (Sigma, CAT#P9333)
- NP-40 (Sigma, CAT#NP40)
- Deoxycholate (DOC) (Sigma, CAT#D6750)
- 20% SDS (Thermo Scientific, CAT#BP1311)
- cOmplete protease inhibitor tablets, EDTA free (Sigma, CAT#11836170001)
- TCEP (Sigma, CAT#580560)
- Chloroacetamide (Sigma, CAT#C0267)
- Clean water (Thermo Scientific, CAT#10977023)
- BCA Assay Kit (Thermo Scientific, CAT#23227)

<span id="solution-recipes"></span>

## Solution recipes

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
- Lysis buffer B (need 50uL per sample, recipe for 1mL)
  - 600mM TrisCl pH 7.5 (600uL of 100mM stock)
  - 8% (v/v) SDS (400uL of 20% stock)
- TC solution (need 40uL per sample, recipe for 1000uL)
  - 24.8mg TCEP
  - 37.2mg of CAA
  - water to 1000uL


<span id="protocol"></span>

## Protocol

This protocol is designed to be used with the standard whole-proteome processing protocol detailed elsewhere in this repository.

1. Begin by preparing an appropriate diluent to use with your BSA standard curve. To do this, you will need to mix Lysis buffer A, Lysis buffer B, and TC solution in the same ratio that you did for the original lysis. For example, in the standard whole proteome protocol in this repository, you would use 150uL of Lysis buffer A, 50uL of Lysis buffer B, and 20uL of TC solution. 
2. It is a good idea to prepare a total of 5mL of diluent. For our protein samples, we are going to dilute them 1/6 (5uL of sample in 25uL of water), so our diluent needs to match this. In this scenario, you would mix 750uL of Lysis buffer A, 250uL of Lysis buffer B, 100uL of TC solution, and 5.5mL of water. This will be your diluent for the BSA standards.
3. Prepare your BSA standards as detailed in the BCA kit manual making sure to use your prepared diluent when noted. 
4. Pipette 25uL of each standard into a well of a 96-well plate. Do this in triplicate for each standard. 
5. For your samples, pipette 25uL of water into each well you plan on using (I typically do just one well per sample, but it is OK to do more). 
6. Pipette 5uL of sample into the 25uL of water in the wells. 
7. Prepare the BCA reagent as detailed in the product manual and add 200uL per well. Pipette mix trying to avoid bubbles. 
8. Incubate at +37C for 30-minutes and read on a plate reader at 562nm. 
9. Calculate the concentration of your samples using the BSA standard curve. Remember to back calculate your dilution!