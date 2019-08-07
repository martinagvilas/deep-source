# Deep Source

This is the Github repository for the Deep Source project.

## Goal
- Simulate MEG source data with deep sources (e.g. hippocampal activity) and estimate which source reconstruction method performs better.
- For a detailed overview of our project, see our [project- outline](../project_outline.ipynb)

## Contributors
**\*(in alphabetic order**)
- Azeez Adebimpe
- Ryan Timms
- Martina G. Vilas


## To-Do:
1. - [X] Define head model (e.g. single sphere, overlapping spheres or single shell)
2. - [X] Calculate lead field matrix after sensor locations are specified.
3. - [X] Create ground truth source space data.
4. - [ ] Multiply ground truth data by the lead field, to get synthetic sensor space data.
5. - [ ] Add some noise to synthetic data to be more realistic.
6. - [ ] Run the different inversion algorithm to estimate the sources.
7. - [ ] Compare accuracies for the different algorithms.
