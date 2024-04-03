
## Overview

Our expertly trained MDN (Mixture Density Network) model is a cutting-edge computational framework specifically designed for accurately inferring the internal structures of rocky exoplanets. It is particularly tailored to analyze exoplanets with a wide range of compositional diversities, offering an efficient, quick, and user-friendly alternative to traditional methods such as Markov Chain Monte Carlo (MCMC) inversion techniques. The model excels in utilizing observable planetary parameters (mass, radius, and bulk elemental ratios) to predict the distribution of internal structures, from the core to surface layers.

The data files in `.parquet` format encompass datasets generated using a three-layer interior structure model, which are essential for training the MDN model. These datasets provide a simulated range of planetary compositions and observable parameters that our MDN model uses to learn the complex relationships needed to infer planetary interiors.

The `.h5` file contains the well-trained MDN model, capturing the nuanced understanding of planetary interior inferences. This file  contains the weights and biases that have been adjusted through the learning phase to maximize predictive accuracy. Our repository includes `.csv` files containing MCMC inversion results for several representative exoplanets.

## License

### Software
The code within this repository, including but not limited to `.ipynb` and `.py` files, is released under the MIT License. See the LICENSE file for more details.

### Data
Data files in this repository, such as `.parquet` and `.csv` files, are made available under the CC-BY license. When using these data, please cite the source accordingly.

## Quick Start Guide

### Step 1:
[Fork and clone](https://help.github.com/articles/fork-a-repo) a copy of the `Rocky_Exoplanets_v3` repository to your local machine.

### Step 2:
Download [`Anaconda`](https://www.anaconda.com/products/individual#Downloads) and install it on your machine.
Create a `conda` environment named `Rocky_Exoplanets` and install all the required dependencies:

```bash
conda create -n deepexo pip python=3.7.6 jupyter
```

### Step 3:
Activate the `deepexo` environment:

```bash
conda activate deepexo
```

### Step 4:
Navigate to your local copy of the `Rocky_Exoplanets_v3` repo:

```bash
cd /your/path/Rocky_Exoplanets_v3
```

### Step 5:
Install the requirements for prediction in the current Conda environment:

```bash
pip install -r requirements.txt
```

### Step 6:
Launch Jupyter Notebook:

```bash
jupyter notebook
```

### Step 7:
Open the notebook named `Applications_MDN vs MCMC.ipynb`.



Make sure to replace the placeholders like `/your/path/Rocky_Exoplanets_v3` with actual paths or additional instructions as needed for your specific repository.
