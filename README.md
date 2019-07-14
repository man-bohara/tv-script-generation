# Udacity DLND TV Script Generation Project

## Overview
This is Udacity's DLND project to generate TV script using Recurrent Neural Netowrks.

## Instructions
1. Install Anaconda and create conda environment.
2. Activate conda environment and install numpy, matplotlib, pytorch.

3. Clone the repository
```
git clone https://github.com/man-bohara/tv-script-generation.git
```

4. run following command 
```
jupyter notebook tv_script_generation.ipynb
```
5. Follow instructions on the notebook

## Model Architecture
This model consists of 1 embedding layer, 2 lstm layers and 1 fully connected layer.

## Training
Its recommended to train this model on GPU as it takes long time to train this model on large images. You can use utilize GPU provided by AWS cloud.
