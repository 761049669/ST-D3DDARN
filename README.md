# ST-D3DDARN  in pytorch
The PyTorch implementation of Spatio-temporal Decoupled 3D DenseNet with Attention ResNet(ST-D3DDARN) form the paper "Urban Traffic Flow Prediction based on Spatio-temporal Decoupled 3D DenseNet with Attention ResNet ". These files include all the code and datasets supporting the experimental data presented in this paper.

## Model architecture

<p align="center"> 
<img src="ST-D3DDARN model structure.png">
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
* 'BJ13_M32x32_T30_InOut.zip': Taxi inflow and outflow data in Beijing in 2013.
* 'BJ14_M32x32_T30_InOut.zip': Taxi inflow and outflow data in Beijing in 2014.
* 'BJ15_M32x32_T30_InOut.zip': Taxi inflow and outflow data in Beijing in 2015.
* 'BJ16_M32x32_T30_InOut.zip': Taxi inflow and outflow data in Beijing in 2016.
* 'BJ_Holiday.txt': Beijing holiday data.
* 'BJ_Meteorology': Meteorological data of Beijing.
* 'BikeNYC': Bike-sharing inflow and outflow data in New York.
* 'ST-D3DDARN.zip': This zipped file contains all the code for the experiments in the paper.
