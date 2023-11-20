# Structure-Preserving Numerical Methods for Dispersive Shallow Water Equations
[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)

This is the reproducibility repository for the master thesis "Structure-Preserving Numerical Methods for Dispersive Shallow Water Equations" (2023)
by Joshua Lampert. It uses the Julia package [DispersiveShallowWater.jl](https://github.com/JoshuaLampert/DispersiveShallowWater.jl), which
was initiated as part of the master thesis.

## Reproduce figures
In order to reproduce all figures from the master thesis, you first need to install [Julia](https://julialang.org/). The results were obtained
using Julia v1.9.3.

After downloading this repository, e.g., by cloning it with `git`, you need to start Julia in this directory and execute the script located
at `code/create_figures.jl`, which can be done by

```julia
julia> include("code/create_figures.jl")
```

This will create a folder `out` that contains all the figures used in the master thesis.

## Author
The master thesis, the package DispersiveShallowWater.jl and this reprodicability repository is written by Joshua Lampert (University of Hamburg).
