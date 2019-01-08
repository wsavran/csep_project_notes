

# CSEP2

Roadmap for CSEP2 and understood by me. This document contains my notes and progress on a collection of CSEP related things.
This represents my unofficial sounding board.

### Legend

**Bold text**: High Priority <br>
*Italic text*: Medium Priority <br>
Normal text: Low Priority <br>
~Strikethrough~: Complete <br>

## CSEP2 Roadmap
**Milestones**
1. [paper on testing stochastic event sets](#testing-stochastic-event-sets)
    * ucerf3 simulations in Landers sequence
    * ucerf3 simulations for other large eqs
    * implement n-test, m-test, s-test for stochastic event sets
    * determine power of statistical tests using simulation based approach
    - run csep1 ETAS simulations in csep2 experiment
2. [paper on testability of earthquake forecasts that involve faults](#testability-of-earthquake-forecasts-on-faults)
    * needs thought!
3. [release csep2 testing center distribution](#csep2-testing-center-release)
    * write docs for csep2 github
    * implement methods to run experiments (db, jobs to hpc, post-processing)

## Upcoming Conferences
1. EGU 2019 (Abstracts due: 01/11/19)
2. SSA 2019 (Abstracts due: 01/11/19)
3. Statistical Seismology 2019 (Abstracts due: Unknown)

## Project Overview

### Testing Stochastic Event Sets
* Read Gneiting work on proper scoring.
* Cramer-von Mises test
* Kolmogorov Smirnov test

### Testability of Earthquake Forecasts on Faults
* power of evaluations
* how long will we have to perform an experiement so that we

### CSEP2 Testing Center Release
* backend logic to store model data/parameters
* store catalogs
* store results
* store generated forecasts

## General To-do
* maximum likelihood estimation for b-values
* m-test and s-test
* documentation on csep (start with tools to run ucerf3-etas)
* build data model for csep2 runs
* revisit prototypes of end-to-end system; need more runs done before april.
