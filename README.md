# Project for Group Assignment --------- Group A9
Author: Zhengting Jiang, Wenjie Zhang, Wenjie Gu.

## Installation
When you are using Ubuntu (Linux), please follow the process below. If you are using Windows please press the Windows icon,
then type 'Anaconda', there should be a matching entry called Anaconda Prompt, select it and it will show a new command window.
First we should create a new environment for the assignment.
```
  $ conda env create --ipqda python=3.8.0 -y
  $ conda activate ipqda
```
Next we should load necessary packages
```
  $ pip install cellpose
  $ pip install cellpose[gui]
  $ pip install devbio-napari
```
The step above already contains PyTorch, we have no necessary to install PyTorch manually.
After all the process, we could check the cellpose and napari gui's using
```
  $ python -m cellpose
``` 
and 
``` 
  $ python -m napari
```
If everything works, then the installation is compelete.
