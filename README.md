# I. Requiremtents:
* CUDA 10.0  
* CUDNN 7.6  
* OpenCV  
* Tensorflow 1.14.0  
* Keras 2.1.3  
# II. About the Code
## 1. Train Network
* Folder 'data/A' and Folder 'data/B' containing hazy and clean images, respectively
* Each image in a clean-hazy image pair must have the same name
* Run train.py to train the network
## 2. Test Data
* The test data should be in the folder 'data/test'
* The network's parameters should be in the folder 'weights/g'
* Run test_on_images.py then you can get the outputs in the folder 'outputs'
