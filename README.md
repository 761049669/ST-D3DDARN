# ST-D3DDARN  in pytorch
The PyTorch implementation of Spatio-temporal Decoupled 3D DenseNet with Attention ResNet(ST-D3DDARN) form the paper "Urban Traffic Flow Prediction based on Spatio-temporal Decoupled 3D DenseNet with Attention ResNet ". These files include all the code and datasets supporting the experimental data presented in this paper.

## Model architecture

<p align="center"> 
<img src="Fig 6.tif">
</p>  

# Prerequisites

- Python3.9
- PyTorch (version 1.13.1)
- Cuda version12.2
- jupyter notebook
# Usage

To create the PyTorch computation graph of the ST-D3DDARN architecture run:

    ST-D3DDARN.ipynb

## Code Organization

* `ST-D3DDARN.py`: This file contains the main program. The computation graph for ST-D3DDARN is built, launched in a session, trained, and tested here.
