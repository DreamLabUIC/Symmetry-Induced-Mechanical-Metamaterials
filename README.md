Symmetry-Induced Mechanical Metamaterials
---------------------------------------------------------------------------------------------------------------------------------------------
This repository contains the data utilized in the paper titled "A Dataset Generation Framework for Symmetry-Induced Mechanical Metamaterials."

The samples topologies are generated utilizing the planes of symmetry from crystallography. The mechanical properties are computed using a numerical homogenization framework. The underlying solid base material has a Young’s modulus (Es) of 200 GPa, a Poisson’s ratio (νs) of 0.3, and a truss diameter of 0.025.

There are two main files in this repository:

1. The first file contains samples that can be represented parametrically for machine learning. This file includes samples in .csv format and another .txt file that includes:
   - Stiffness Tensor
   - Relative effective elastic properties (Young's modulus, shear modulus, Poisson's ratio in the three directional primary axes)
   - Nodal positions
   - Bar connectivities


2. The second file is related to all different symmetries and also includes samples in .csv format that can be represented in a graph representation (see the supplementary material of the main paper). It also includes .txt files that include:
   - Stiffness Tensor
   - Relative effective elastic properties (Young's modulus, shear modulus, Poisson's ratio in the three directional primary axes)
   - Nodal positions 
   - Bar connectivities

     
Please refer to the paper for detailed information on how the dataset was generated and how it can be utilized.
