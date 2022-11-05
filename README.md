# Deep Learning Environment Installation Window (or Linux)
## Python 3.6, Pytorch & cudatoolkit 10.0, Tensorflow 1.14  
Python Anaconda Environment Setup For Deep Learning Development <br/>
Install Anaconda to D:\ [ https://repo.anaconda.com/.../Anaconda3-2021.05-Windows... ] <br/>
Open Anaconda Prompt Command Line window <br/>
(base) C:\Users\pc>conda create -n dl python=3.6 <br/>
(base) C:\Users\pc>conda activate dl <br/>
(dl) C:\Users\pc>conda install pytorch torchvision cudatoolkit=10.0 -c pytorch <br/>
(dl) C:\Users\pc>conda install tensorflow==1.14 ## For NVIDIA GPU change "tensorflow" to "tensorflow-gpu" ## <br/>
(dl) C:\Users\pc>conda install -c conda-forge scikit-learn <br/>
(dl) C:\Users\pc>conda install pandas <br/>
(dl) C:\Users\pc>conda install spyder <br/> ## conda install -c anaconda jupyter
(dl) C:\Users\pc>conda install seaborn <br/>
# Ubuntu 20.04
## Clean Installing CUDA 11.2 on Ubuntu 20.04
https://gist.github.com/hiraksarkar/b4aff12ccb0f1f1a7cb301f365892f6a <br/>
https://towardsdatascience.com/installing-multiple-cuda-cudnn-versions-in-ubuntu-fcb6aa5194e2
## GPU Status for Ubuntu
$ pip install gpustat   ## https://pypi.org/project/gpustat/
## How to Custom Dataset Yolo4 Installation
https://github.com/anil-bit/yolov4-darkflow-ubuntu-customdataset
## Clean Installing CUDA 10.1 on Ubuntu 20.04 
Install CUDA 10.1 packages, including the CuDNN library <br/>
https://medium.com/@stephengregory_69986/installing-cuda-10-1-on-ubuntu-20-04-e562a5e724a0
## YOLOv4-darknet installation and usage on your system (Windows & Linux)
https://techzizou.com/yolo-installation-on-windows-and-linux/#install_linux
