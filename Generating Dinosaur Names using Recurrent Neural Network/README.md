# Generating Dinosaur Names using Recurrent Neural Network
`John Khuc`

## Table of Contents
- [Overview](#overview)
- [Highlights](#highlights)
- [Installation](#installation)
- [Usage - Running Jupyter notebook](#usage---running-jupyter-notebook)
	- [Running in a local installation](#running-in-a-local-installation)
	- [Running in a remote installation](#running-in-a-remote-installation)

## Overview
- How to store text data for processing using an RNN 
- How to synthesize data, by sampling predictions at each time step and passing it to the next RNN-cell unit
- How to build a character-level text generation recurrent neural network
- Why clipping the gradients is important

## Highlights
![iter0](https://i.gyazo.com/b2de18515e3430da40774b5e53d542cf.png)
![iterN](https://i.gyazo.com/2bde66160e3c7d295c09fc96929f5a8c.png)

## Installation
The Jupyter notebook is a web-based notebook environment for interactive computing. 
You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook

## Usage - Running Jupyter notebook

### Running in a local installation

Launch with:

    $ jupyter notebook

### Running in a remote installation

You need some configuration before starting Jupyter notebook remotely. See [Running a notebook server](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).
