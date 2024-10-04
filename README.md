Parkinson's Disease Prediction

This project aims to predict Parkinson's disease status based on a range of biomedical voice measurements. 
The dataset used contains multiple biomedical voice measurements from people with and without Parkinson's disease, and the goal is to classify 
whether a person has Parkinson's based on these measurements.

Table of Contents:

Introduction
Dataset
Features
Installation
Usage
Model Building
Results
Contributing
License

Introduction:

Parkinson's disease is a progressive nervous system disorder that affects movement. 
One of the symptoms is changes in the voice. This project applies machine learning to predict the presence of Parkinson's disease 
using various voice-related attributes such as jitter, shimmer, and harmonics-to-noise ratio (HNR).


Dataset:

The dataset contains the following columns:

name: Identifier of the voice recording sample.
MDVP:Fo(Hz): Average vocal fundamental frequency.
MDVP:Fhi(Hz): Maximum vocal fundamental frequency.
MDVP:Flo(Hz): Minimum vocal fundamental frequency.
MDVP:Jitter(%): Measure of variation in pitch.
MDVP:Jitter(Abs): Absolute jitter.
MDVP:RAP: Relative amplitude perturbation.
MDVP:PPQ: Five-point period perturbation quotient.
Jitter:DDP: Average absolute difference of differences between consecutive periods.
MDVP:Shimmer: Measure of variation in amplitude.
MDVP:Shimmer(dB): Shimmer in decibels.
Shimmer:APQ3: Three-point amplitude perturbation quotient.
Shimmer:APQ5: Five-point amplitude perturbation quotient.
MDVP:APQ: Amplitude perturbation quotient.
Shimmer:DDA: Average absolute difference of differences between consecutive amplitudes.
NHR: Noise-to-harmonics ratio.
HNR: Harmonics-to-noise ratio.
status: Target variable (1 for Parkinson’s disease, 0 for healthy).
RPDE: Recurrence period density entropy.
DFA: Detrended fluctuation analysis.
spread1: Non-linear measure of fundamental frequency variation.
spread2: Non-linear measure of frequency variation.
D2: Non-linear dynamical complexity measure.
PPE: Pitch period entropy.

Results:
The model's performance will vary depending on the algorithm and hyperparameters used. 
In our experiments, the Random Forest classifier achieved around X% accuracy (replace "X" with your results).
