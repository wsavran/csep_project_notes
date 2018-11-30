

# CSEP2

Roadmap for the Collaboratory for the Study of Earthquake Predictability.

### Legend

**Bold text**: High Priority <br>
*Italic text*: Medium Priority <br>
Normal text: Low Priority <br>
~Strikethrough~: Complete <br>

## CSEP2 Roadmap
**Milestones**
1. [agu poster](#agu-poster) (due: 07 Dec 2018)
    * ucerf3 simulations in Landers sequence
    * implement n-test, m-test, s-test for stochastic event sets
2. [paper on testing stochastic event sets](#testing-stochastic-event-sets)
    * ucerf3 simulations in Landers sequence
    * ucerf3 simulations for other large eqs
    * implement n-test, m-test, s-test (others) for stochastic event sets
    * determine power of statistical tests
    - run csep1 ETAS simulations in csep2 experiment
3. [paper on testability of earthquake forecasts that involve faults](#testability-of-earthquake-forecasts-on-faults)

4. [release csep2 testing center distribution](#csep2-testing-center-release)
    * write docs for csep2 github
    * implement methods to run experiments (db, jobs to hpc, post-processing)

## Project Overview
### AGU Poster
Will contain the following sections:
* **Introduction to CSEP2**
* **Testing Stochastic Event Sets**
  * **csep1 style tests on stochastic event sets**
  * **explanation of tests**
  * ~n-test~
  * *inter-event time test*
  * *global mfd test*
* **Beginning Retrospective experiment involving UCERF3 and UCERF3-NoFaults**
  * ~simulations after big bear (need to run NoFaults)~
  * ~simulations 1 mo after big bear (need to run NoFaults)~
  * monthly simulations following (at least 1 month possibly up to 1 year after)
  * ~simulations following landers [complete]~
  * figures:
    * ~global mfd (https://github.com/SCECcode/csep2/blob/master/notes/mfd_calc_and_plot.ipynb)~
    * ~n-test visualization** (https://github.com/SCECcode/csep2/blob/master/notes/n_test_prototype.ipynb)~
    * *spatial map of landers and big bear ruptures*
    * map of cell-averaged (median) forecast numbers
    * ~magnitude vs. time [complete]~
    * ~cumulative numbers [complete]~

### Testing Stochastic Event Sets
* Read Gneiting work on proper scoring.
* Cramer-von Mises test
* Kolmogorov Smirnov test

### Testability of Earthquake Forecasts on Faults
* power of evaluations

### CSEP2 Testing Center Release
* backend logic to store model data/parameters
 * store catalogs
 * store results
 * store generated forecasts

## General To-do
