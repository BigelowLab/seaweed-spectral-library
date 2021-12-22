# Seaweed Spectral Library

This repository contains information about creating a spectral library of different seaweeds.

Measurements were all made in the lab, with samples collected from different locations along Maine's coast.

## File Descriptions

**`01-Creating-sample_list_v2`** is the workflow to include the time stamps and number of measurements for each sample in the `sample_list_v1` csv 

**`02-SpectralLibraryCreation`** is the workflow to create `spectral_library.csv` from the raw .sed and .sig files

**`03`, `04` and `05`** notebooks visualize the spectral library data, the leaf clip data, and the mixing (salad toss) data respectively

**`06` and `07`** notebooks perform partial least squares regression to model the relationship between biomass (wet weights) and reflectance for asco and fucus respectively

**`06a` and `07a`** notebooks perform partial least squares regression to model the relationship between biomass (canopy depth) and reflectance for asco and fucus respectively

**`Measurement Setup.md`** contains information on the measurements for each sample (both experimental design and measurement approach)

**`sample_list_v1.csv`** is the sample information copied from the lab notebook (from the experiment days)

**`sample_list_v2.csv`** is as v1, plus the time stamp for each sample and the number of measurements taken for each sample

**`spectral_library.csv`** the mean reflectance and standard deviation for all lab samples

