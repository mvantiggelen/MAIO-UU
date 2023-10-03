# MAIO
 Notebooks for opening AWS data

### Python installation
See [Anaconda Installation](https://docs.anaconda.com/anaconda/) to install Anaconda. Then, [verify your installation](https://docs.anaconda.com/anaconda/install/verify-install/).


Open a terminal (macOS) or an anaconda prompt (Windows):
* Windows: Start -> search “Anaconda Prompt”
* macOS: Launchpad -> Terminal

Create a new conda environment named "sebmodel" with python installed, and activate it:
```bash
conda create -n MAIO python=3.9.2
conda activate MAIO
```
Note that Python version 3.9.2 is required for compatilibity with the numba package (on March 2022).

Install the required Python packages:

```bash
conda install numpy pandas xarray netcdf4 scipy ipykernel 

```
This can take a few minutes.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mvantiggelen/MAIO-UU/HEAD)
