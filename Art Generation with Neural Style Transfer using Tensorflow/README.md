# Art Generation with Neural Style Transfer using Tensorflow
`John Khuc`

## Table of Contents
- [Overview](#overview)
- [Download Pretrained Models](#download-pretrained-models)
- [Highlights](#highlights)
- [Installation](#installation)
- [Usage - Running Jupyter notebook](#usage---running-jupyter-notebook)
	- [Running in a local installation](#running-in-a-local-installation)
	- [Running in a remote installation](#running-in-a-remote-installation)

## Overview
- Implement the neural style transfer algorithm 
- Generate novel artistic images using the algorithm 

# Download Pretrained Models
- I used `imagenet-vgg-verydeep-16` and `imagenet-vgg-verydeep-19`. 
- Both collectively about ~1 GB.
- [Link](https://drive.google.com/file/d/1pBOTqdt-aUlTNpFmoxBBMu9LnIIPnmVO/view?usp=sharing) to download.
	- After downloading, create a folder called `pretrained-model` and place the pretrained models inside. 

## Highlights
![output1](https://i.gyazo.com/61f020556532e5ed940709815918073f.png)
![output2](https://i.gyazo.com/2825cfe318a6d6899932c2fc9961cfc2.png)
![output3](https://i.gyazo.com/986d4d93722845aaaf07e073a9b98a31.png)

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
