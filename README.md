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
(dl) C:\Users\pc>conda install spyder <br/>
