# NILM_sensordata
Non intrusive load monitoring or NILM is a process of analysis of disaggregation of electric appliances connected to a power within a certain area. 

Dataset consists of power load data collected using current(mA) sensor attached to the wire of main power supply. Objective is to identify the individual device states(on/off/idle) for each combined load. Dataset is private and hence its not shared.

This is a multilabel classification problem .

Clustering techniques and multi label tree based models were used for the solving the problem.

Execute following commands to install necessary packages:-

pip install scikit-multilearn

pip install iterative-stratification

pip install pandas-profiling

pip install scipy
