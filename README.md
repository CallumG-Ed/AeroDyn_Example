# AeroDyn Example Case

This repository contains a selection of files that are inputs to run on the standalone AeroDyn module as supplied with OpenFAST (https://github.com/OpenFAST/openfast).

The case files are based on the NREL 15MW reference turbine (https://www.nrel.gov/docs/fy20osti/75698.pdf), and have been adapted from @gbarter 's repository here: https://github.com/IEAWindTask37/IEA-15-240-RWT/blob/master/README.md.

The sole idea of this repository is to show on a very basic level how to run an AeroDyn case. You will need to have installed OpenFAST and to run this case in a bash terminal run command:

path_to_executable/aerodyn_driver driver.dvr
