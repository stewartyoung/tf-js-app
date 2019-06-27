# Tensorflow.js Application

## But why use a client side model?
* Keeps user data local
* No prerequisites or installs 
* Interactive and easy to use

## Dependencies for converting keras model to tf-js model
* keras
* tensorflowjs
***Use pip to install these***  
Ran into a big problem installing tensorflowjs, so used   
pip install tensorflow==1.11.0rc2 h5py numpy keras  
pip install --no-deps tensorflowjs  
Again the error persisted, turns out needed to change windows settings to install file with path greater than 260 characters.  
https://www.howtogeek.com/266621/how-to-make-windows-10-accept-file-paths-over-260-characters/

### More issues with installations
* Solved more problems with this fantastic tutorial: https://www.youtube.com/watch?v=59duINoc8GM
* Created Python 3.6 environment py36
  * Activate environment  
  `conda env list`  
  `conda activate py36
  * I then exported all packages in the environment to an environment.yaml file, which you can use to create the environment yourself using:   
  `conda env create -f environment.yaml`
  
## What is the VGG16 model?
It is a pre-trained image classification model

