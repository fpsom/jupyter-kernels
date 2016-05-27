[![Build Status](https://travis-ci.org/fpsom/jupyter-kernels.svg?branch=master)](https://travis-ci.org/fpsom/jupyter-kernels) [![](https://imagelayers.io/badge/fpsom/jupyter-kernels:latest.svg)](https://imagelayers.io/?images=fpsom/jupyter-kernels:latest 'Get your own badge on imagelayers.io')

## Docker image for Jupyter notebook with multiple kernels

The Dockerfile has been created based on the official Jupyter docker file that includes R (available [here](https://hub.docker.com/r/jupyter/r-notebook/) )

- **R kernel**.
- **Python 3 kernel**.
- **Nodejs kernel**. This kernel was included using parts of the official Nodejs Docker file (v6.2) available from [here](https://github.com/nodejs/docker-node)
- **Bash kernel**. This kernel was included using the guideline provided [here](https://github.com/takluyver/bash_kernel)
