# ASD-DiagNet
This repository contains the implementation of ASD-DiagNet algorithm.

## Research article 
Please cite the following paper if you use our work: 


Taban Eslami, Fahad Saeed, Vahid Mirjalili, Alvis Fong and Angela Laird (2019) **ASD-DiagNet: A hybrid learning approach for detection of Autism Spectrum Disorder using fMRI data**, Frontiers in Neuroinformatics, 13 (2019): 70. [Paper link](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2019.00070/full)

## Enviroment Setup
### Hardware requirements
- A server containing CUDA enabled GPU with compute capability 3.5 or above. 

### Software requirements
- Python version 3.5 or above
- Pytorch version 0.4.1
- CUDA version 8 or above
- Jupyter notebook

## Parameter setting
Please provide the parameters in the first cell of Jupyter notebook as follows:

- Atlas name: ("cc200", "aal", or "dosenbach160")

  e.g. `p_ROI = "cc200"`


- Number of k for k-fold cross-validation:

  e.g. `p_fold = 10`


- Classification mode: ("whole" or "percenter")

  e.g. `p_mode = "percenter"`


- Name of the center: (in case of performing per-center classification)

  e.g. `p_center = "Stanford"`


- Classification method: ("ASD-DiagNet", "rf" or "SVM))

  e.g. `p_Method = "ASD-DiagNet"`


- Utilizing augmentation technique: (in case of using ASD-DiagNet, True or False)

  e.g. `p_augmentation = False`
  

In case of any questions please contact: fsaeed@fiu.edu

