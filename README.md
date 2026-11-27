
This repository contains MATLAB code to compute the ECG and cerebral oximetry features used for automatic detection of return of spontaneous circulation (ROSC) during out-of-hospital cardiac arrest (OHCA).

The ECG reflects the electrical activity of the heart but gives no direct information on its mechanical function, so pulse-generating rhythms (PR) and pulseless electrical activity (PEA) can look very similar. To address this, the code extracts features from the ECG and from the oximetry circulation component (OCC), the pulsatile component of the cerebral oximetry signal (total hemoglobin concentration changes, ΔcHb) synchronized with the QRS complexes. ECG and OCC are decomposed with the Stationary Wavelet Transform (SWT), and a total of [N] features are computed from 5-s segments.

## Repository structure

## Input and output

No patient data are included in this repository.


## Citation
If you use this code in your work, please cite the following paper:
A Machine Learning Approach for Pulse Detection using Cerebral Oximetry Signals during Out-of-Hospital Cardiac Arrest
