# PRECISE-1K - Analyze New Data

This is a lightweight repository facilitating analysis of _E. coli_ RNA-seq data against the PRECISE-1K expression knowledgebase and its associated iModulons ([publication](https://www.biorxiv.org/content/10.1101/2021.04.08.439047v2))

Here are the steps needed to get started with analysis using this resource:

## Setup

Ensure you have Python 3.6+, Jupyter (`pip install jupyterlab`), and the iModulon analysis package `pymodulon` installed (`pip install pymodulon`). 

`pymodulon` documentation can be found [here](https://pymodulon.readthedocs.io/en/latest/index.html).

Installing `pymodulon` using `pip` will install all other needed packages.

Then, clone this repository onto your local machine by executing the following command in your command prompt/terminal: `git clone https://github.com/SBRG/precise1k-analyze.git`. This command will copy this repository to a folder called `precise1k-analyze` in the directory from which the command was executed.

## Test Analysis Notebook

The lone notebook in this repository, `analyze_new_data.ipynb`, can be opened using Jupyter. Once open, execute all cells to ensure that the example data is loading properly and all required packages have been installed. ModuleNotFound errors can likely be addressed by `pip install <missing module>`

## Add Your Data

Now, you are ready to analyze your new data with PRECISE-1K. Replace the example contents of the `project_metadata.csv` and `project_log_tpm.csv` files with your metadata and RNA-seq data.

Detailed instructions for the required format of these files, along with instructions and code for combining these data with PRECISE-1K, inferring iModulon activities, and analyzing your data with iModulons, can all be found within the `analyze_new_data.ipynb` notebook.

## Additional Information

The [main PRECISE-1K repository](https://github.com/SBRG/precise1k) contains the data and notebooks used to generate PRECISE-1K, its iModulons, and analyses/figures for the associated publication. 

Please cite our [Biorxiv preprint](https://www.biorxiv.org/content/10.1101/2021.04.08.439047v2) if you find this repository useful! This link will be updated when this work is published.
