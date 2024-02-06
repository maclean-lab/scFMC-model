# Developmental hematopoietic stem cell fate decisions explain clonal dynamics over lifetime

### Citation
If you use FMCs_for_HSCs in your research, please cite the bioRxiv preprint avaible [here](https://doi.org/10.1158/2326-6066.CIR-22-0617):

J Kreger, JA Mooney, D Shibata, AL MacLean (2024).
Developmental hematopoietic stem cell fate decisions explain clonal dynamics over lifetime.

The bioRxiv version is available [here](https://doi.org/10.1101/2022.06.15.496246). 

### Overview 
This repository contains code used in the analysis of clonal dynamics of hematopoietic stem cells. The code is written in Julia (tested on versions 1.8.1) and is presented in Jupyter notebooks.

Data used in the analysis is included in the data folder and is all publicly available on GEO, see Table 1 in the main text for details.

### Requirements 
 - Julia (version 1.8.1) or newer
 - Jupyter notebook

### Package requirements 
 - [Statistics.jl](https://docs.julialang.org/en/v1/stdlib/Statistics/)
 - [LinearAlgebra.jl](https://docs.julialang.org/en/v1/stdlib/LinearAlgebra/)
 - [DataStructures.jl](https://juliacollections.github.io/DataStructures.jl/latest/)
 - [StatsBase.jl](https://juliastats.org/StatsBase.jl/stable/)
 - [StatsPlots.jl](https://github.com/JuliaPlots/StatsPlots.jl)
 - [Distributions.jl](https://juliastats.org/Distributions.jl/stable/)
 - [LsqFit.jl](https://github.com/JuliaNLSolvers/LsqFit.jl)
 - [Random.jl](https://docs.julialang.org/en/v1/stdlib/Random/)
 - [ColorSchemes.jl](https://juliagraphics.github.io/ColorSchemes.jl/stable/basics/)
 - [Plots.jl; pyplot()](https://docs.juliaplots.org/stable/)
 - [DelimitedFiles.jl](https://docs.julialang.org/en/v1/stdlib/DelimitedFiles/)
 - [DataFrames.jl](https://dataframes.juliadata.org/stable/)

### Project contents
 - `README.md` : this file with information about the repository and [paper](https://doi.org/10.1101/2022.06.15.496246)
 - `data_processing.ipynb` :  Jupyter notebook containing code for basic methylation data processing.
 - `model_simulation.ipynb` :  Jupyter notebook containing code for all model simulations and figures in the paper.
 - `data` : folder for data used in the analysis, see Table 1 in the main text for details (mz = monozygotic twins, dz = dizygotic twins, ur = unrelated individuals).
 - `simulation files` : folder for simulation files used in the analysis (mz = monozygotic twins, dz = dizygotic twins, ur = unrelated individuals). 

### Acknowledgments
We would like to thank... Figures... were created with [BioRender](https://biorender.com/).

### Contributors
<a href="https://github.com/maclean-lab/FMCs_for_HSCs/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=maclean-lab/FMCs_for_HSCs" />
</a>

