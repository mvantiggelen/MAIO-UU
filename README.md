# MAIO
 Notebooks for opening AWS data

### Python installation
See [Anaconda Installation](https://docs.anaconda.com/anaconda/) to install Anaconda. Then, [verify your installation](https://docs.anaconda.com/anaconda/install/verify-install/).


Open a terminal (macOS) or an anaconda prompt (Windows):
* Windows: Start -> search “Anaconda Prompt”
* macOS: Launchpad -> Terminal

Create a new conda environment named "sebmodel" with python installed, and activate it:
```bash
conda create -n sebmodel python=3.9.2
conda activate sebmodel
```
Note that Python version 3.9.2 is required for compatilibity with the numba package (on March 2022).

Install the required Python packages:

```bash
conda install numpy pandas xarray netcdf4 scipy
```
This can take a few minutes.
