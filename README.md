# Project_rNA-MD

## 1. Input files in the repository:
main files:

`freqs_all.txt`: frequencies of NAC (odd row) and energy gap (even row) of each model.

`ampl_all.txt`:  amplitudes of corresponding frequencies for NAC (odd row) and energy gap (even row) of each model.

`run_namd.py`:   the code to execute the NA-MD run.

`ham.py`:        the module to generate the model Hamiltonian.

## 2. The example output directory:
`res_model1_102_100000_1000`

The directory contains the data of Model 1 (`model1`) with NAC scaled by 0.2 (`102`). The length of the original dataset is 1000 fs (`1000`), we repeat it 100 times to get the total length of 100000 fs (`100000`). 
