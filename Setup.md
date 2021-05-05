# how to run the code in your computer
I run the code successfully along with the following steps.
## system
I cannot run it on Windows 10 and I chose the Ubuntu16.04 later.
- Nvidia grapic driver 384.130, which can be easily found in the software & update interface.
- CUDA9.0(cuda_9.0.176_384.81_linux.run) with cudNN(cudnn-9.0-linux-x64-v7.6.5.32.tgz)
the installing steps can be found [here](https://blog.csdn.net/anshidashen/article/details/106425771)
- Anaconda, I use the Anaconda3-2018.12-Linux-x86_64.sh.
## setup the enviroment
you can run the following commands
```
conda create -n tf_gpu_1 python=3.5.4
conda activate tf_gpu_1
pip install tensorflow-gpu==1.12.0
```
then check the numpy version, if >=1.17, you should reduce it to 1.16 or earlier with the following commands
```
pip uninstall numpy
pip install numpy==1.16.0
```
then OpenCV, matplotlib and pillow
```
pip install opencv-python==3.4.2
pip install matplotlib
pip install pillow
```
## run the code
I think both [this](https://www.freesion.com/article/7791192282/) and [this](https://blog.csdn.net/qq_37258787/article/details/87876405) are very good tutorials to run the code.