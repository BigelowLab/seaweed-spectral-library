# Experimental Design

## TNC Basin Lab Day (22nd June 2021)

For both Asco and Fucus, we had 5 samples, each with varying biomass. Each sample was measured three times over the day, so we could investigate the variability desiccation (i.e. drying) has on the reflectance spectra.

## Pemaquid Lab Day (22nd July 2021)

We had three different sets of experiments:

1. Varying biomass - for both Asco and Fucus, we had 8 samples, each with different biomasses. 
2. Desiccation - for both Asco and Fucus, we had 1 sample which we measured over the course of the day.
3. Salad toss - for both Asco and Fucus, we had 1 sample which we mixed by hand between each scan.

**See the `sample_list.csv` file which contains all the sample information for all of the above experiments.**

# Measurement approach for (almost) all samples

For each sample, the following approach was taken:

1. The sample was placed on an adjustable table, on a piece of blackout card, under the PSR fibre optic
2. The height of the table was changed so the distance between the top of the seaweed sample and the fibre optic was 17cm
3. The sample reflectance was measured 10 times (repeated measurements at a 5 second interval)
4. The blackout card + sample were rotated by 90 degrees
5. Steps 3 & 4 were repeated until there were a total of 40 scans (i.e. the sample had been measured from 4 viewing directions/orientations)

Each measurement has the naming convention:

`filestem_xxxx.sed`

where `filestem` is a unique identifying descriptor, and `xxxx` is the scan number (e.g. `0001`).

**Notes:**
1. The rotation/different viewing orientations was to remove any bidirectional reflectance effects
2. Occassionally didn't stop the scanning in time and ended up with more than 10 scans from one orientation

## Exceptions to the above measurement approach

1. `Asco9` and `Fucus9` from the Pemaquid lab day have only 8 scans. These samples were given the 'salad toss' treatment. This was to replicate the different arrangements of seaweed over different tidal cycles.
