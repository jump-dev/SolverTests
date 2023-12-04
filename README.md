**This repo is archived and no longer used. The actions have been integrated into JuMP and MathOptInterface.**

# Solver tests for MOI

This packages is used to tests solver implemented the [MathOptInterface](https://github.com/JuliaOpt/MathOptInterface.jl).
The tests on Github Actions: [![][build-img]][build-url]

We test all solvers in the [list of supported solvers](https://www.juliaopt.org/JuMP.jl/dev/installation/#Getting-Solvers-1)
that can be tested on Github Actions (e.g. some proprietary solvers cannot be tested on Github Actions unless special support is provided).

[build-img]: https://github.com/blegat/SolverTests/workflows/CI/badge.svg?branch=master
[build-url]: https://github.com/blegat/SolverTests/actions?query=workflow%3ACI
