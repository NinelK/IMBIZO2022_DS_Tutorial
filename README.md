# Tutorial on Dynamical Systems for Neuroscience

[Solutions available here](https://github.com/NinelK/IMBIZO2022_DS_tutorial_solutions)

Clone this repo and go INTO the IMBIZO2022_DS_Tutorial folder

Linux installation:
```
conda config --add channels conda-forge
conda env create -n DS_tutorial environment.yml
```

Windows installation:

```
conda config --add channels conda-forge
conda env create -f environment_windows.yml
conda activate DS_Tutorial
set CONDA_DLL_SEARCH_MODIFICATION_ENABLE=1 
pip install "jax[cpu]===0.3.14" -f https://whls.blob.core.windows.net/unstable/index.html --use-deprecated legacy-resolver
```
