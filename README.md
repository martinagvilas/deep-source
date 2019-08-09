# Deep Source

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinagvilas/deep-source/master)


This is the Github repository for the Deep Source project, created during [Neurohackademy 2019](https://neurohackademy.org/neurohack_year/2019/).

## Goal
- Simulate MEG source data with deep sources (e.g. hippocampal activity) and estimate which source reconstruction method performs better when reconstructing them.
- For a detailed overview of what we are going to achieve, see our [project-outline](/project_outline.ipynb)

## Contributors
**\*(in alphabetic order**)
- Azeez Adebimpe
- Ryan Timms
- Martina G. Vilas


## Next steps:
1. - [ ] Tidy-up jupyter notebooks
2. - [ ] Incorporate and compare other source reconstruction methods (other than MNE and Beamformer)
3. - [ ] Translate HMM source reconstruction methods into Python
4. - [ ] Quantitatively compare the source reconstruction methods using the following algorithms:
        - Crosstalk-to-Signal Ratio (CSR)
        - Neural Activity Index (NAI) --> translate them to Python
        - Point-Spread Functions --> translate them to Python
5. - [ ] Simulate the ground truth data to vary in the following aspects:
        - Depth of the sources
        - Correlation of the sources
        - Closeness of the sources
        - The SNR
          <br>
        ... and compare the performance of different source reconstruction methods.
