# ReconNN

This project tries to use neural networks to do TPC trajectory position reconstruction, given the PMT readouts and the raw TPC track (incorrect position in particle drifting direction, usually the `x` axis). Compared to [XOptimizer](https://github.com/CIDeR-ML/siren-pfmatch/blob/develop/pfmatch/apps/xoptimizer.py), ReconNN is faster but the reconstruction accuracy could be lower, given its current form. Another benefit of ReconNN is that it can be trained with a differentiable forward model to increase its performace on the real neutrino detector data.

## Prerequisites

- python 3.10+
- [photonlib](https://github.com/CIDeR-ML/photonlib)
- [siren-pfmatch](https://github.com/CIDeR-ML/siren-pfmatch)
- [MinkowskiEngine](https://github.com/NVIDIA/MinkowskiEngine)

An `environment.yml` is provided to help setup the base packages that support the above packages.

## Usage

### GNN

Open the `GNN.ipynb`, follow the steps there.

### CNN

Open the `CNN.ipynb`, follow the steps there.

### Sparse CNN

Open the `SparseCNN.ipynb`, follow the steps there.
