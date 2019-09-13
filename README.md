# 2019-soa-pa-jupyter-notebooks
### Supporting materials for presentation on Jupyter Notebooks given at the 2019 SOA Predictive Analytics Symposium

[Try Jupyter Prior to Installing](https://jupyter.org/try)

Jupyter notebook installation instructions: [https://jupyter.org/install](https://jupyter.org/install)

How to run notebooks: [https://jupyter.readthedocs.io/en/latest/running.html](https://jupyter.readthedocs.io/en/latest/running.html)

Please note that the demo was run on a Windows machine using the Anaconda distribution of Python and R. For those new to data science, especially on Windows, using Anaconda is the easiest way to get started: [Anaconda](https://www.anaconda.com/distribution/)

If using Anaconda, the environment can be replicated by running: ```conda env create -f environment.yml``` in the terminal. For help: [Managing Environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

Using the same package versions as indicated in the environment.yml file is important for reproducability across systems. For example, this environment uses rpy2 version 2.9.4 rather than the newer, 3.1.0 version that breaks some Windows compatability. 