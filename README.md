These files were trained using a platform we developed, called DPTorch, but they are fully compatible with the DeepMD platform（DeePMD-kit’s documentation）. 
To integrate the software with LAMMPS, please use the following files:

The .pb files represent the neural network potential models.
The .pot file is an additional fitting for the D2 effects, which needs to be included when running LAMMPS.
The in.CuCH file is a LAMMPS input file and can be used as a reference.
