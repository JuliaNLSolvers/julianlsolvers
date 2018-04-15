## Welcome to JuliaNLSolvers

JuliaNLSolvers is a collection of packages that solve problems faced by many researchers and analysts: nonlinear optimization, nonlinear systems of equations, and nonlinear least squares. 

### Optim.jl
Optim.jl is a package for solving nonlinear optimization problems. The main focus is on unconstrained optimization, but some constrained support is available.

#### Citation

If you use `Optim.jl` in your work, please cite the following.

```tex
@article{mogensen2018optim,
  author  = {Mogensen, Patrick Kofod and Riseth, Asbj{\o}rn Nilsen},
  title   = {Optim: A mathematical optimization package for {Julia}},
  journal = {Journal of Open Source Software},
  year    = {2018},
  volume  = {3},
  number  = {24},
  pages   = {615},
  doi     = {10.21105/joss.00615}
}
```
### NLsolve.jl
NLsolve.jl is a package for solving systems of nonlinear equations.
### LsqFit.jl
LsqFit.jl is a package for fitting nonlinear least squares problems.
### Other packages
#### LineSearches.jl
LineSearches.jl provides a suite of line searches to be used for solving optimization problems or system of equations.
#### NLSolversBase.jl
NLSolversBase.jl holds common infrastructure for the various packages above. The package is not meant for public consumption as such, but of you're interested in understanding the internals of the JuliaNLSolvers packages, you need to know what's in this package.
