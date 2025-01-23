# M3_PCV-ABMD

<div align="center">
  <img src="https://github.com/gmelisi/M3_PCV-ABMD/blob/main/TOC.jpg" alt="TOC" width="640">
</div>

In this repository, input files are provided to carry out Adiabatic Bias Molecular Dynamics ([ABMD](https://doi.org/10.1063/1.478259)) simulations of tiotropium unbinding from M3 and M2 receptors using Path Collective Variables ([PCVs](https://doi.org/10.1063/1.2432340)). 

## Input files

The zip file (deposited as egg in the Plumed-NEST, [plumID:25.002](https://www.plumed-nest.org/eggs/25/002/)) includes:
- Amber topologies (`M3_TIO.prmtop` and `M2_TIO.prmtop`) and equilibrated structure (`init.rst7`) files to use as initial configurations for launching the simulations.
- The PLUMED input file `plumed.dat` necessary to perform PCV-ABMD simulations.
- The Amber input file `pcv-abmd.in`, which contains MD settings.
- The `REPARAM.pdb` file, which provides the guess path necessary for PCVs definition.

## Authors and acknowledgements
- Adriana Coricello
- Anna Lisa Chiaravalle
- Maria Musgaard
- Benjamin Tehan
- Gian Marco Elisi
- Giovanni Bottegoni
