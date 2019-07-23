# SOLPS-scripts
Various scripts for SOLPS
## Description
This is a collection of shell scripts developed to facilitate the usage of SOLPS code.
- SOLPS5.1 In this folder are shell scripts for the old version SOLPS5.1 code. The data analysis scripts consist of both a general purpose big script that outputs a set of general results from the simulation and a set of small scripts for special analysis. The job submission scripts are for running batch jobs on the TACC Lonestar5 super computer. Since SOLPS5.1 is serial, a job wrapper comes in handy such that it wrapps upto 16 serial jobs for one submission that run simultaneously on one computing node.
- SOLPS-ITER In this folder are shell scripts for the new version SOLPS-ITER. These scripts facilitate compiling the source code, setting up the environment and running jobs on the TACC Stampede2 super computer. Data analysis scripts for SOLPS-ITER are located in a separate repository: 
