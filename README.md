# CNN_PoF
Code and data from paper in Physics of Fluids: "Convolutional neural networks for compressible turbulent flow reconstruction".
This paper investigates deep learning methods in the framework of convolutional neural networks for reconstructing
compressible turbulent flow fields. The aim is to develop methods capable of up-scaling coarse turbulent data into fine-
resolution images. The method is based on a parallel computational framework that accepts five image sets of various
resolutions, trained to correspond to the respective fine resolution. The network architecture mainly consists of convo-
lutional layers, constructing an encoder/decoder network. Based on the U-Net scheme, three different implementations
are presented, with residual and skip connections. The methods are implemented in a supersonic shock-boundary-layer
interaction problem. Results suggest that simple networks perform better when trained on limited data, and this can be
a practical and fast solution when dealing with turbulent flow data, where the computational burden is most of the time
difficult to decrease. In such a way, a coarse simulation grid can be upscaled to a fine grid.

There is a python-tensorflow Jupyter file to reproduce methods in the paper. Simulation data for training and validation are also provided.
