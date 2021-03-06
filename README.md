# Goal-Selection-PRIMs

This repository contains all the material used to write my master thesis (file MasterThesis.pdf).

## Types of files

### .prims

Tasks on which the model was tested. Tasks "category", "paired-associate", "press-key" and "recall" were designed by Dr Niels Taatgen.

### .bprims

Batch files. For the control simulations (control_noreset_test or task_control1430/10000) these are classical PRIMs batch files. 
For the random and the progress driven conditions (random.bprims and accuderiv.bprims) the files only contains the first sequence of tasks that the model performed, after that, autonomous goal selection took place.

### .ipynb

#### Preprocessing

Notebook dedicated to the creation of the csv files from the dat files generated by PRIMs_cmd.

#### Visualisation

Notebook dedicated to the creation of figures from the csv files generated the notebook "Preprocessing".

## .dat

Samples of files generated by the application PRIMs_cmd (see the corresponding repository: https://github.com/asedauphin/PRIMs_cmd). 

## .csv

csv files from which figures were generated. These files were generated using the code in Preprocessing.ipynb from the .dat files generated by the application PRIMs_cmd (see the corresponding repository: https://github.com/asedauphin/PRIMs_cmd).
I joined 10 of them for each condition.

## Contact

This version was developped until June 2020. You can email me at: asedauphin@gmail.com if needed.
