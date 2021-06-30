# par-protein-transport-model
This repository contains code for our PAR protein transport paper: <a href="https://doi.org/10.1101/2021.06.28.450200">https://doi.org/10.1101/2021.06.28.450200</a>

## Authors

- Cole Zmurchok https://zmurchok.github.io
- William R. Holmes https://holmeslab.home.blog/

## Requirements

- We used Python 3.8.7 available from https://www.python.org/
- A list of required packages is available in 'reqs.txt'

## Contents

- README and LICENSE
- reqs.txt: contains a list of Python packages and versions
- Jupyter notebooks for all figures in the paper:
  - FigX.ipynb produces (all or part of) Figure X in the paper
  - ABM_Validation.ipynb makes Supplemental Figure 1
  - Fig2.ipynb also makes Supplemental Figures 2--5
  - DiffusionEstimation.ipynb makes Supplemental Figure 6
  - Model_ParamSweep.ipynb makes Supplemental Figures 7--10
  - Fig3-4.ipynb also makes Supplemental Figure 11

## Running

Some notebooks require directories '/data' and '/figures' to be placed in main working directory. After running these notebooks, data and parameter sets will be saved in these folders in a pickle format (.pkl). This allows for easy plotting adjustments since the stochastic simulations will not be re-run if the data exists.
