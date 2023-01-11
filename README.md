# EDIPI Workshop tutorial on predictabilty with qgs

This series of notebooks are part of a tutorial given during the EDIPI workshop at RMI in January 2023.
In this tutorial, you will learn:

1. How to install the [qgs](https://github.com/Climdyn/qgs) framework for low-order climate and weather modeling
2. How to run the model
3. How to compute the correlation properties of the underlying dynamical model
4. How to compute the largest Lyapunov exponent in the model
5. How to compute the full Lyapunov exponent spectrum

The notebooks of this training are organized as follow:

- [Introduction](https://github.com/Climdyn/EDIPI-qgs-tutorial-on-predictability/blob/main/EDIPI%20workshop%20qgs%20tutorial%20-%20Introduction.ipynb) : A notebook to check that qgs is well installed on your system by performing a first model configuration and run. You can change the model parameters and investigate the resulting effect.
- [Part I](https://github.com/Climdyn/EDIPI-qgs-tutorial-on-predictability/blob/main/EDIPI%20workshop%20qgs%20tutorial%20-%20Part%20I.ipynb): A notebook to learn how to compute the time correlation properties of the model.
- [Part II](https://github.com/Climdyn/EDIPI-qgs-tutorial-on-predictability/blob/main/EDIPI%20workshop%20qgs%20tutorial%20-%20Part%20II.ipynb): A notebook to learn how to estimate the Largest Lyapunov Exponent of the model, and the corresponding most unstable spatial field to perturb it.
- [Part III](https://github.com/Climdyn/EDIPI-qgs-tutorial-on-predictability/blob/main/EDIPI%20workshop%20qgs%20tutorial%20-%20Part%20III.ipynb): A notebook to learn how to use the qgs toolbox to compute the full Lyapunov spectrum.

## Installation

First, clone the current repository:

    git clone https://github.com/jodemaey/EDIPI-qgs-tutorial-on-predictability.git

Then, to install qgs, clone the qgs repository

    git clone https://github.com/Climdyn/qgs.git

and follow the [installation instructions](https://github.com/Climdyn/qgs#installation). 
After that, you can copy the tutorial notebooks in `EDIPI-qgs-tutorial-on-predictability` in the `qgs` folder and you are ready.
Simply go in the `qgs` folder and start the notebook server by typing:

    jupyter notebook
  
This should open your favorite browser and there you can load and run the notebooks. Have fun !
