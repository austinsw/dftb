# dftb
 Testing for dftbplus packages

## History

### Test with Example

`dftb+ | tee output` input file must be called *dftb_in.hsd*

(ERROR: SK file '../../slakos/mio-ext/O-O.skf' does not exist') Easy solve by changing the directory path

Example: https://dftbplus-recipes.readthedocs.io/en/latest/index.html


### Installation

`conda info --envs` check envs

`conda create --name <env_name>` to create new env

`conda activate <env_name>` to activate env

`conda deactivate` to deactivate env

To rename env
```
conda create --name <new_name> --clone <old_name>
conda remove --name <old_name> --all
```

`conda config --add channels conda-forge` enable conda-forge


`conda install 'dftbplus=*=nompi_*'`  obtaining DFTB+ via the conda package (failed on Windows)

`conda install -c conda-forge dftbplus` To install this package with conda run https://anaconda.org/conda-forge/dftbplus (Worked on Mac, failed on Windows)

(Search results from https://anaconda.org/search?q=dftbplus suggest that conda-forge / dftbplus 21.2 only supports Linux and osx)

