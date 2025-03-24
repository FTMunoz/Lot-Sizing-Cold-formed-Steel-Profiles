# Lot-Sizing-Cold-formed-Steel-Profiles

Model and data used in:
Lot-Sizing Optimization Model for the Cold-formed Steel Profiles Production Planning.
[doi ???]


The instances are grouped by demand factor and stored in separate files named "demand factor XX.7z". Each file contains seven groups, with a total of 700 instances. 
Inside each "demand factor XX.7z" file are seven folders, each containing 100 instances corresponding to a specific number of orders.
For a total of 4,900 instances.

The Summary of results.xlsx file contains the results for each experiment-instance, including Objective Value, Runtime, and Status.

The model implementation is provided in LotSizing.ipynb, developed using:

    Programming Language: Julia
    Platform: JupyterLab
    Modeling Language: JuMP
    Solver: HiGHS
