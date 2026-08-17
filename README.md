# Using GitHub Actions for Computational Communication Research

This repository accompanies the paper *Using GitHub Actions for Computational Communication Research*. It provides the executable files and workflow configuration used to demonstrate the workflow described in the paper. The paper provides the detailed methodological and technical documentation for setting up and running the workflow. Citation:

>De Angelis, I. (2026). Using GitHub Actions for Computational Communication Research. Forthcoming, *Computational Communication Research*. Pre-print: https://doi.org/10.31235/osf.io/uqf6n_v1

## Repository contents

- `.github/workflows` contains the `bluesky.yaml` file used to configure the GitHub Actions workflow
- `requirements.txt` outlines the software and R package versions used at the time of data collection
- `01-download_Bluesky_data.R` contains the R script to collect Bluesky data used in this workflow
- `last_run_time.txt` contains the time (in UTC) of the most recent workflow execution and is automatically updated each time
- `LICENSE` contains the license for this repository