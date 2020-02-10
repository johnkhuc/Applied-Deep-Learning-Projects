# Trigger Word Detection using Keras
`John Khuc`

## Table of Contents
- [Overview](#overview)
- [Highlights](#highlights)
- [Installation](#installation)
- [Usage - Running Jupyter notebook](#usage---running-jupyter-notebook)
	- [Running in a local installation](#running-in-a-local-installation)
	- [Running in a remote installation](#running-in-a-remote-installation)

## Overview
- Structure a speech recognition project
- Synthesize and process audio recordings to create train/dev datasets
- Train a trigger word detection model and make predictions
    - A convolutional layer
    - Two GRU (Gated Reccurent Unit) layers
    - A dense layer

## Highlights
- Download `chime_output.wav`. It chimes everytime someones says "activate"!
![prob](https://i.gyazo.com/aaa2c79bdeaaed53d66a46d43bfb4a01.png)

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
