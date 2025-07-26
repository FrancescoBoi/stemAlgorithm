# stemAlgorithm
This project tries to isolate the stem separation algorithm of the Spleeter application.
The Spleeter project can be found here: https://github.com/deezer/spleeter.
The first step is to reproduce the step in jupyter notebook.

## Spleeter installation
To install spleeter on Ubuntu one can follow these steps:
- create a conda env with ptyhon3.9
- activate the environment
- follow the installation guidelines of Spleeter installing also pip dependencies inside the environment

If facing problems with jax and jaxlib versions do `<miniconda-env-path>/bin/pip show jax jaxlib`: if you see that jax is required by tensorflow2 and has version 4.13, on the contrary jaxlib is required by noone and has higher version you can downgrade the version: pip install jaxlib==0.4.13

You can check if everything works by running the commands in the Spleeter repository

## PyCharm settings
Install gcc. For debugging the tests in Pycharm, if they are not running the workaround is to copy the audio files in the test folder (or change Pycharm settins)

# Python notebook
Install ipython kernel in the conda env.
Follow this guide to use the conda env in the notebook.


