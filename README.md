# Nowak-Kalluri_TypeIISGN2026
Code and Data Repository for Nowak and Kalluri (2026)

This repository contains the datasets and Python notebooks used to reproduce selected analyses and computational modeling results presented in Nowak and Kalluri (2026). The notebooks were developed in Google Colab using the Brian2 neural simulator, allowing readers to run the code in a web browser without requiring a local Python installation.

The repository is intended to provide both (1) the data and code needed to reproduce key analyses presented in the manuscript and (2) a well-documented modeling framework that readers may adapt for their own investigations. It is not intended to reproduce every figure in the publication.

Repository Contents
1. TypeIIPaperUMAPdata.xlsx

This Excel file contains the raw electrophysiological measurements used for the UMAP analysis that classified spiral ganglion neurons into Type I and Type II groups. The dataset is used by the notebook TypeIandTypeIIUMAP.ipynb.

2. TypeIandTypeIIUMAP.ipynb

Performs the UMAP dimensionality reduction and clustering analysis using the raw electrophysiological dataset provided in TypeIIPaperUMAPdata.xlsx.

3. RealvsModelCClampTypeI.ipynb

Defines the computational models for representative Type I and Type II spiral ganglion neurons and compares simulated current-clamp responses with representative experimental recordings.

4. VClampRealvsModelFigures.ipynb

Uses the same neuron models to simulate voltage-clamp responses and compares the simulated currents with representative experimental recordings.

5. XXXX.ipynb

Demonstrates simulations in which model parameters are randomly varied to examine how ion channel density influences anode break spiking. (Replace "XXXX" with the final notebook name.)

6. TypeIandIIPulseTrain.ipynb

Reproduces the pulse-train simulations presented in Figure XX of the manuscript. (Update the figure number before publication.)

Notes

The computational notebooks are intended to illustrate the structure of the neuronal models, their parameterization, and representative simulation workflows. Readers are encouraged to use these notebooks as a starting point for reproducing the published analyses and for developing new simulations based on the modeling framework presented in the manuscript.
