## MTUQ_PSO

This repository contains the Particle Swarm Optimization (PSO) implementation developed for moment tensor inversion using the [MTUQ](https://github.com/mtuqorg/mtuq) framework.

## 1. Prerequisite: Install MTUQ

Before using the scripts in this repository, **MTUQ must be installed**.

Please install MTUQ by following the official installation instructions provided in the MTUQ repository:

https://github.com/mtuqorg/mtuq

After successfully installing MTUQ, verify that MTUQ can be imported in your Python environment before proceeding with the scripts provided here.

The scripts in this repository implement Particle Swarm Optimization (PSO) for moment tensor inversion within the MTUQ framework.

## 2. Installation

Clone this repository using:

```bash
git clone https://github.com/iitrseismo/mtuq_pso.git
```

## 3. Usage 
Activate the environment in which MTUQ is installed:
```bash
conda activate your_mtuq_env
```
After activating the MTUQ environment, the scripts can be run directly from the command line using 
```bash
python PSO.Double.Couple.py
```
or
```bash
mpirun -n <number_of_processors> python script_name.py
```
## 5. Data

Example data can be downloaded and prepared using **PySEP**.

PySEP is a Python-based tool for downloading and preprocessing seismic waveform data and associated station/event information. Please refer to the official PySEP documentation and GitHub repository for installation, usage, and data preparation:

- **PySEP Documentation:** https://pysep.readthedocs.io/en/latest/
- **PySEP GitHub Repository:** https://github.com/adjtomo/pysep



