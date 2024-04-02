## Overview

Our well-trained MDN (Mixture Density Network) model is an innovative computational framework designed for the precise inference of the interior structures of rocky exoplanets. It caters specifically to analyzing exoplanets with a broad range of compositional diversity, presenting an efficient, rapid, and user-friendly alternative to conventional approaches such as Markov Chain Monte Carlo (MCMC) inversion methods.The model excels in processing observable planetary parameters (mass, radius, and bulk elemental ratios) to predict the distribution of internal structures, from core to surface layers.

## Quick Start
### Step 1:
[Fork and clone](https://help.github.com/articles/fork-a-repo) a copy of the `Rocky_Exoplanets_v2` repository to your local machine.

### Step 2:
Download [`Anaconda`](https://www.anaconda.com/products/individual#Downloads) and install it on your machine.
Create a `conda` environment called `Rocky_Exoplanets` and install all the necessary dependencies:

    conda create -n deepexo pip python=3.7.6 jupyter
    
### Step 3:
Activate the `deepexo` environment:

    conda activate deepexo

### Step 4:
Change into your local copy of the `Rocky_Exoplanets_v2` repo:

    cd /you own path/Rocky_Exoplanets_v2

### Step 5:
Install the requirments for predicing in the current Conda environment:

    pip install -r requirements.txt

### Step 6:
Open Jupyter Notebook:

    jupyter notebook

### Step 7:
Open the file Applications_MDN vs MCMC.ipynb
