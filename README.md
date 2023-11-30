# Fluid catalytic cracking unit dataset for evaluation of process monitoring techniques

## What the repository is about?
This repository provides data from fault-free and faulty operations of a fluid catalytic cracking unit (FCCU). The open source model provided by Santander et al. (https://doi.org/10.1016/j.compchemeng.2022.107900) has been used for simulation; the model's github repository is [here](https://github.com/Baldea-Group/FCC-Fractionator). FCCUs are critical units in oil refineries and are used for breaking heavy hydrocarbons into lighter gasoline, LPG, etc. It is a complex process and therefore, a worthy candidate to experiment with the different fault detectiona and diagnosis (FDD) techniques out there. The picture below shows the five faulty conditions that have been simulated.

![](/Faults_PFD.png)

## Some details on the repository files
In this repository there are three categories of files.
- <ins>*CSV files*</ins>: 2 files containign data from normal operation conditions (NOCs) and 5 files containing data from faulty conditions
- <ins>*Data exploration notebooks*</ins>: These notebooks provide quick look into the data from the five faulty conditions. Relevant variables that are expected to show deviations under the imapct of the corresponding faults have been plotted.
- <ins>*FDD implementation notebooks*</ins>: These notebooks provide quick implementation of classical PCA for each of the five faulty conditions.

## Where to find more details?
Complete details on the FCCU system, measured signals, CSV file contents, and the simulated faults are available at https://mlforpse.com/. 





