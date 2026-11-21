# SFOA

This repository accompanies the manuscript *Shaft-speed scaling of bearing vibration and order-domain diagnosis of compound faults*. We will release the SFOA implementation here upon acceptance.

## Overview

In a 6205 bearing, an inner-race harmonic and an outer-race harmonic both lie near 10.8 cycles per shaft revolution. A peak can follow shaft speed closely while remaining compatible with either fault. We use vibration envelope spectra to track peaks during steady operation and run-up, then examine how spectral shape varies with bearing type and load after alignment.

For diagnosis, Source-Factor Order Augmentation (SFOA) projects the short-window vibration power spectrum onto a shared shaft-order grid. Shared shaft-order projection (SSOP) supplies the order spectrum for the three-part order representation (TPOR), which also includes the local residual and its gradient. During training, factorized counterfactual order augmentation (FCOA) varies the power profile using bearing and load templates. The local views still come from the measured window.

On HUST we evaluate compound-fault diagnosis across 12 joint bearing-type and load holdouts. On JNU we compare fixed-sample windows with windows spanning 1.92 shaft revolutions at the same centers, using the healthy condition and three single faults.

## Data

- [HUST bearing vibration and shaft-speed data, version 3 (Mendeley Data)](https://doi.org/10.17632/cbv7jyx4p9.3)
- [JNU bearing dataset (GitHub)](https://github.com/ClarkGableWang/JNU-Bearing-Dataset)
