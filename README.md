These data are the Cu-C-H nerual network potential from "Hydrocarbon Species on the Cu(111) Surface Studied with a Neural Network Potential" The Journal of Physical Chemistry C 2024, 128, 5697-5707.https://doi.org/10.1021/acs.jpcc.3c08138

These files were trained using a platform we developed, called DPTorch, but they are fully compatible with the DeepMD platform（DeePMD-kit’s documentation）. To integrate the software with LAMMPS, please use the following files:

1. The .pb files represent the neural network potential models.
2. The .pot file is an additional fitting for the D2 effects, which needs to be included when running LAMMPS.
3. The in.CuCH file is a LAMMPS input file and can be used as a reference.
