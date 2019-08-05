# Deep Source

This is the Github repository for the Deep Source project.

## To-Do:
1. - [ ] Define head model (e.g. single sphere, overlapping spheres or single shell)
2. - [ ] Calculate lead field matrix after sensor locations are specified. Fortunately this step is done for us by the MEG scanner, as long as we are in the same co-ordinate system, i.e. we have done co-registration.
3. - [ ] Given our newly calculated lead field matrix, we can “make up” some ground truth source space data.
4. - [ ] We then multiply this ground truth data by the lead field, to get synthetic sensor space data. We can then add some noise to this to get a more feasible/realistic sensor space data set.
5. - [ ] We then run the inversion algorithm to estimate the sources.
6. - [ ] We compare the accuracies 

## Possibilities:

### Simulation
- Deep sources
- Correlated sources
- Close sources
- Different SNR
- Co-registration error

### Source reconstruction method
- Minimum norm estimation (MNE)
- Beamformer
- HMM Beamformer (Maximum Likelihood)

### Accuracy measures
- Crosstalk-to-Signal Ratio (CSR)
- Neural Activity Index (NAI)
- Point-Spread Functions
