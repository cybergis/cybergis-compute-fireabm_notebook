CyberGIS-Compute FireABM Monte Carlo Notebook

Author: Rebecca Vandewalle rcv3@illinois.edu
Created: 8-16-21

This notebook provides an example of running a Monte Carlo style computation using CyberGIS-Compute. CyberGIS-Compute is service for running High Performance Computing (HPC) jobs from a Jupyter Notebook within CyberGISX. In this example, the FireABM simulation script is run twice, each separately using two different tasks. This small example demonstrates how to run a serial script with no in-built parallelization multiple times on CyberGIS-Compute, how to pass parameters from a notebook to CyberGIS-Compute, how to access standard HPC variables (such as node_ids) from within a CyberGIS-Compute job, and how to specify the correct working and results directories for running the job script and downloading the results. The goal of this example is to demonstrate how to use CyberGIS-Compute with no or very little adjustments to the original serial script. The custom job in this notebook uses this repository: https://github.com/cybergis/cybergis-compute-fireabm.git .
