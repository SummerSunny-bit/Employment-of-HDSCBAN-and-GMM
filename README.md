# HDBSCAN and GMM application to identify stellar memberships

This python codes represents the basis of my bachelor's thesis (Physics) at the Uuniversity of Bremen, titled "Membership determination on stellar clusters using HDBSCAN and GMM".
It provides the employment of HDBSCAN and GMM using existing python packages, as well as theoretical isochrone fitting. Here, I make use of PARSEC v1.2S/ v2.0 and MIST, as well as employ BHAC15 and Dartmouth model grids. For detailed information of the use of all packages, I refer to my thesis.

The code provided is adapted to Lambda Ori.
The structure is as follow.
1. Loading and pre-filter Gaia DR3 data through astrometric quality cuts.
2. Employment of HDBSCAN and GMM with internal diagnostics including the Minumum Spanning Tree and Mutual Rechability Tree, as well as a representation of GMM components.
3. Analysis: - Plotting data in various spaces
             - Literature comparison (Mainly use of Hunt2024 Census 3 and Cantat-Gaudin 2020)
4. Theoretical Isochrone Fitting: - MIST and PARSEC v1.2S combined with a MCMC sampler
                                  - manaully fetched PARSEC v2.0 Isochrones
                                  - BHAC15 and Dartmouth model grids through MADYS

In order to use the code, you are required to have the requirements

# Attribution
If you make use of this code or parts of this code, please reference this repository.
