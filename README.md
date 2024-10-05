# wikis

Welcome to the wikis wiki!

# vnpy

## installation

1. vnpy3.9.2 supports `python 3.6 - 3.11`
2. clone vnpy
  - latest version `3.9.2`
  - `git clone https://github.com/vnpy/vnpy.git`
3. use conda to create a virtual ENV with python3.10
  - `conda create -n vnpy python=3.10`
  - `activate vnpy`
4. install ta-lib 
  - NOTE. VSCode terminal is not working, use anaconda terminal instead.
  - `conda install -c conda-forge ta-lib`
5. run `install.bat`
6. other vnpy dependencies
  - [vnpy_ctp](https://github.com/vnpy/vnpy_ctp) `pip install vnpy_ctp`
  - [vnpy_ctastrategy](https://github.com/vnpy/vnpy_ctastrategy) `pip install vnpy_ctastrategy`
  - [vnpy_ctabacktester](https://github.com/vnpy/vnpy_ctabacktester) `pip install vnpy_ctabacktester`
  - [vnpy_datamanager](https://github.com/vnpy/vnpy_datamanager) `pip install vnpy_datamanager`
  - [vnpy_sqlite](https://github.com/vnpy/vnpy_sqlite) `pip install vnpy_sqlite`

# virtual ENV
## [Conda virtual ENV](https://docs.conda.io/projects/conda/en/4.6.0/user-guide/tasks/manage-environments.html)
- list ENVs `conda info --envs` or `conda env list`
- list packages in ENV that's not activated `conda list -n myenv`, for activated ENV `conda list`
- create virtual ENV, in this case for vnpy `conda create -n vnpy python=3.10`
- activate ENV on Windows: `activate myenv` on MAC: `source activate myenv`