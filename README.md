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
## GPU Status for Ubuntu
$ pip install gpustat   ## https://pypi.org/project/gpustat/
## Ubuntu 20.04 install CUDA 11.1, cuDNN 8.0.5, Tensorflow 2.4
https://pinkwink.kr/1339
## Ubuntu 20.04 nVidia driver Installation
https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-ubuntu-20-04-focal-fossa-linux
