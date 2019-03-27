# ASD-DiagNet
This repository contains the implementation of ASD-DiagNet algorithm.


## Hardware requirements
A server containing CUDA enabled GPU with compute capability 3.5 or above. 

We used Tesla k40c GPU for conducting experiments.

## Software requirements
Python version 3.5 or above

Pytorch version 0.4.1

CUDA version 8 or above

Jupyter notebook

-----------------------------
Please provide the parameters in the first cell of Jupyter notebook as follows:

Atlas name: ("cc200", "aal", or "dosenbach160")
p_ROI = "cc200"

Number of k for k-fold cross-validation:
p_fold = 10

Classification mode: ("whole" or "percenter")
p_mode = "percenter"


Name of the center: (in case of performing per-center classification)
p_center = "Stanford"

Classification method: ("ASD-DiagNet", "rf" or "SVM))
p_Method = "ASD-DiagNet"

Utilizing augmentation technique: (in case of using ASD-DiagNet, True or False)
p_augmentation = False

