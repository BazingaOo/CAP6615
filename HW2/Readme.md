HW2

Important!!!!:

Due to the NON-FREE version of SIFT descriptor of OpenCv with version above 3.4.2.

To run the notebook, you have to create a new environment in anaconda in following step.



1.in default anaconda CMD.app,run
```console
conda create -n p36 python=3.6.8
```

2.switch anaconda to 'p36', the default is called 'base',


3.install CMD.exe Prompt after switching environment by clicking the CMD symbol in GUI.

4.install required python package below by opening the CMD.exe, 
```console
pip install Pillow
pip install torch
pip install numpy
pip install matplotlib
```
<span style="color:red">Most Importantly!</span>.
you have to use this line below to install opencv, otherwise, you will encounter the NON-FREE issue when you calling SIFT descriptor
```console
pip install opencv-contrib-python==3.4.2.16
```


5.install jupyternotebook in this environment by clicking the jupyternotebook symbol in GUI.



6.after this, you should be able to run all the codes in all jupyter notebook under HW2 folder