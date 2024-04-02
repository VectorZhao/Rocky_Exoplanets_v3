## Overview

Our expertly trained MDN (Mixture Density Network) model represents a cutting-edge computational framework specifically designed for accurately inferring the internal structures of rocky exoplanets. It is particularly tailored to analyze exoplanets with a wide range of compositional diversities, offering an efficient, quick, and user-friendly alternative to traditional methods such as Markov Chain Monte Carlo (MCMC) inversion techniques. The model shines in utilizing observable planetary parameters (mass, radius, and bulk elemental ratios) to predict the distribution of internal structures, spanning from the core to surface layers.

## Quick Start Guide
### Step 1:
[Fork and clone](https://help.github.com/articles/fork-a-repo) a copy of the `Rocky_Exoplanets_v3` repository to your local machine.

### Step 2:
Download [`Anaconda`](https://www.anaconda.com/products/individual#Downloads) and install it on your machine.
Create a `conda` environment named `Rocky_Exoplanets` and install all the required dependencies:

    conda create -n deepexo pip python=3.7.6 jupyter
    
### Step 3:
Activate the `deepexo` environment:

    conda activate deepexo

### Step 4:
Navigate to your local copy of the `Rocky_Exoplanets_v3` repo:

    cd /your/path/Rocky_Exoplanets_v3

### Step 5:
Install the requirements for prediction in the current Conda environment:

    pip install -r requirements.txt

### Step 6:
Launch Jupyter Notebook:

    jupyter notebook

### Step 7:
Open the notebook named `Applications_MDN vs MCMC.ipynb`.
