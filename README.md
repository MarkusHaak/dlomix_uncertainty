# dlomix_uncertainty

This repository contains the jupyter notebooks that were used to run the uncertainty estimation experiments described in the report "Confidence Prediction in the DLOmix Framework". They serve the purpose of reproducibility and to be used as reference.

## Usage

1. Set up an anaconda environment

Setup a python3 environment with anaconda.

2. Install https://github.com/MarkusHaak/dlomix

Install the forked, modified version of dlomix containing code for uncertainty prediction using Quantile Regression and Monte Carlo Dropout followed by Conformal Prediction.

3. Install additional requirements

Listed in the requirements.txt.

4. Download PROSIT dataset

Download all .parquet files from https://zenodo.org/record/6602020 to the ./data/ folder.

5. Run the jupyter notebooks under ./notebooks/

Run all notebooks in the order indicated by the prefix numbers.