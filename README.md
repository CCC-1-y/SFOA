# SFOA

Repository for **Source-Factor Order Augmentation for Compound Bearing Fault Diagnosis under Joint Bearing and Load Shifts**.

## Code availability

**The code will be made publicly available upon acceptance of the manuscript.**

This repository currently provides the project description and release notice. The implementation has not yet been released.

## Overview

SFOA addresses compound bearing fault diagnosis when both bearing type and operating load change. It combines order-domain normalization, a three-view spectral representation, and source-factor augmentation. Training uses labeled source data; inference uses a frozen classifier without target-domain adaptation.

The study evaluates seven-class joint bearing-and-load holdouts on the HUST bearing dataset, cumulative ablations, noise robustness, and frozen-model transfer to the JNU dataset.

## Release plan

The planned release includes preprocessing, model and training code, evaluation scripts, and instructions for reproducing the reported experiments. Public dataset sources and the required directory structure will be documented with the release.
