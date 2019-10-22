# Autonomous Driving

<p align="center">
  <img src="https://github.com/giuliobz/AutonomousDriving/blob/master/videos/models.gif ">
</p>



The aim of this project is to predict the trajectory from a series of frames to emulate the autonomous drive in a radio controlled machine.
For more details [read the report](Report.pdf) and watch [the video in this link](https://www.dropbox.com/sh/c1vkzonmgs7p8dj/AADxyoHSPLqB_TsW7DxyKKpJa?dl=0).

## Table of Contents

- [Preprocessing](datasets/image_dataset/README.md)
- [Create csv files](datasets/csv_dataset/README.md)
- [Training and Testing](models/README.md)
- [Video creation](videos/README.md)

All the settings, path and configurations are in **config/config.py** file. Please read all sections to make sure all work correctly.

## Dependancies

- PyTorch
- numpy
- opencv
- mathplotlib
- pil

For detailed steps to install PyTorch, follow the [PyTorch installation instruction](https://pytorch.org/get-started/locally/). A typical user can install PyTorch using the following commands:

```bash
# Create virtual environment
conda create -n pytorch python=3.7

# Activate virtual environment
conda activate pytorch

# Install PyTorch
conda install pytorch torchvision cudatoolkit=10.1 -c pytorch

```

The other packet can be installed using pip:

```bash

conda activate pytorch
pip install numpy
pip install mathplotlib
pip install Pillow==2.2.2
pip install opencv-python
pip install tqtm

```
    
