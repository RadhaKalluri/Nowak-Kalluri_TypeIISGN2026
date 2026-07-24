# Nowak-Kalluri_TypeIISGN2026
This code set will allow readers to reproduce key analysis and modeling figures in Nowak and Kalluri 2026.  The python code was developed in google colab to facilitate conventient and low-overhead adoptation of the code.  Five files are shared in this repository.
1) The excel spread sheet (TypeIIPaperUMAPdata.xlsx) shows the raw electrophysiological parameters that are used to produce the multivariate UMAP analysis used to cluster data into Type I and Type II groups.  This data set should be used with the python code in TypeIandTypeIIUMAP.ipynb
   
The remaining Python code (developed in Google Colab with the Brian Simulator) is intended to help interested readers both reproduce the key published results and provide the reference modeling parameters and framework to facilitate their own simulations.  As such the code does not reproduce every figure presented in the paper but provides examples of how the code can be used.
3) RealvsModelCClampTypeI:  provides the modeling parameters for simulated Type I and Type II SGN and compares model response to a representative recordings from Type I and Type II SGN.
4) VClampRealvsModelFigures: provides the modeling parameters for simulating the same  Type I and Type II SGN models evaluated in voltage clamp.
5) xxxx.ipynb: Shows the model simulation where parameters settings are drawn from a random distribution to test for the impact of ion channel density Anode Break spiking.
6) TypeIandIIPulseTrain is used to recreate the simulation responses in Figure xx
