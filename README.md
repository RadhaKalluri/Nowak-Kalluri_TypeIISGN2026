# Nowak-Kalluri_TypeIISGN2026
# Code and Data Repository for Nowak and Kalluri (2026)

This repository contains the datasets and Python notebooks used to reproduce selected analyses and computational modeling results presented in **Nowak and Kalluri (2026)**. The notebooks were developed in **Google Colab** using the **Brian2 neural simulator**, allowing readers to run the code in a web browser without requiring a local Python installation.

The repository is intended to provide both (1) the data and code needed to reproduce key analyses presented in the manuscript and (2) a modeling framework that readers may adapt for their own investigations. It is not intended to reproduce every figure presented in the publication.

## Repository Contents

### 1. TypeIIPaperUMAPdata.xlsx

This Excel file contains the raw electrophysiological measurements used for the UMAP analysis that classified spiral ganglion neurons into Type I and Type II groups. The dataset is used with the notebook **TypeIandTypeIIUMAP.ipynb**. 

### 2. TypeIandTypeIIUMAP.ipynb

Performs the UMAP dimensionality reduction and clustering analysis using the raw electrophysiological dataset provided in **TypeIIPaperUMAPdata.xlsx**.  (Figures 4 & 5)

### 3. VClampRealvsModelFigures.ipynb

Uses the same Type I and Type II neuron models to simulate voltage-clamp responses and compares simulated currents with representative experimental recordings. (Figure 9 A,B,E)

### 4. RealvsModelCClampTypeI.ipynb

Defines the computational models for representative Type I and Type II spiral ganglion neurons and compares simulated current-clamp responses with representative experimental recordings. (Figure 9 C,D,F)

### 5. AnodeBreak_BulkDraw.ipynb

Demonstrates simulations in which model parameters are randomly varied to examine the impact of ion channel density on anode break spiking. (Figure 9H)

### 6. TypeIandIIPulseTrain.ipynb

Reproduces the pulse-train simulations presented in Figure 10 of the manuscript. 

## Model Use and Reproducibility

The computational notebooks provide the model architecture, simulation parameters, and example workflows used to generate representative simulations presented in Nowak and Kalluri (2026).

The notebooks are intended to facilitate understanding and reuse of the neuronal models. Readers can use these examples as a starting point for exploring how variations in neuronal parameters influence excitability and firing behavior.

## Software Requirements

The computational notebooks were developed and tested using Google Colab with Python 3.12.

Required Python packages include:

- Brian2 (v2.9.0)
- Brian2Tools (v0.3)
- NumPy (v2.0.2)
- pandas (v2.2.2)
- matplotlib (v3.10.0)
- matplotlib-venn (v1.1.2)
- SciPy (v1.16.2)

Package installation commands are included at the beginning of each notebook. The notebooks are designed to run directly in Google Colab.
last updated (7/24/2026)
