# Deep Source

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinagvilas/deep-source/master)


This is the Github repository for the Deep Source project, created during [Neurohackademy 2019](https://neurohackademy.org/neurohack_year/2019/).

## Goal
- Simulate MEG source data with deep sources (e.g. hippocampal activity) and estimate which source reconstruction method performs better.
- For a detailed overview of our project, see our [project-outline](/project_outline.ipynb)

## Contributors
**\*(in alphabetic order**)
- Azeez Adebimpe
- Ryan Timms
- Martina G. Vilas


## Next steps:
1. - [ ] Incorporate and compare other source reconstruction methods (other than MNE and Beamformer)
2. - [ ] Quantitatively compare the source reconstruction methods using the following algorithms:
        - Crosstalk-to-Signal Ratio (CSR)
        - Neural Activity Index (NAI)
        - Point-Spread Functions
3. - [ ] Simulate the ground truth data to vary in the following aspects:
        - Depth of the sources
        - Correlation of the sources
        - Closeness of the sources
        - The SNR
        <br>
        ... and compare the performance of different source reconstruction methods.
