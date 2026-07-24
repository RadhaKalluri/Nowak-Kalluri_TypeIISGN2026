# Nowak-Kalluri_TypeIISGN2026
This code set will allow readers to reproduce key analysis and modeling figures in Nowak and Kalluri 2026.  

1) The excel spread sheet (TypeIIPaperUMAPdata.xlsx) shows the raw electrophysiological parameters that are used to produce the multivariate UMAP analysis in Figures xx and xx.  This data set should be used with the python code in TypeIIUMAPZdataSimlified
2) The remaining python code (developed in google Colab) is intended to help interested readers reproduce the key model parameters to test against the published results and if needed to use the code set for their own simulations.  As such the code does not reproduce every figure presented in the paper.
3) RealvsModelCClampTypeI:  provides the modeling parameters for simulated Type I and Type II SGN and compares model response to a representative recordings from Type I and Type II SGN.
4) VClampRealvsModelFigures: provides the modeling parameters for simulating the same  Type I and Type II SGN models evaluated in voltage clamp.
5) TypeIandIIPulseTrain is used to recreate the simulation responses in Figure xx.
