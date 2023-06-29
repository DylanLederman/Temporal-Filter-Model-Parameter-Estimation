# Temporal-Filter-Model-Parameter-Estimation
Estimation of parameters for a model capturing synaptic depression and facilitation using Simulation Based Inference (SBI) Python library, which implements Bayesian inference. 

Requires Simulation Based Inference Python Library
For Installation go to https://www.mackelab.org/sbi/install/  however in most server based notebooks running "pip install sbi" without setting up a virtual environment is easiest.

Please keep in mind this notebook is to be used as a tool for exploring how model degeneracy impacts parameter estimation. Several estimation protocols can be used (ie. # of simulations, summary_stats function, 
parameter ranges, # of parameters estimated for), so please don't expect to get an interpretable result in the returned distrubutions without an understanding of how these factors contribute to the output.

If you would like to learn more about my methodology or how you could make a similar implementation please email me at dylan.m.lederman@gmail.com
