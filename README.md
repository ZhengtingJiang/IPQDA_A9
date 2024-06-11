# Project for Group Assignment --------- Group 9
Author: Zhengting Jiang, Wenjie Zhang, Wenjie Gu.

## Installation
First we should create a new environment for the assignment.
'''
  $ conda env create --ipqda python==3.11.0 -y
  $ conda activate ipqda
'''
Next we should load necessary packages
'''
  $ pip install cellpose[\gui\]
  $ pip install devbio-napari
'''
The step above already contains PyTorch, we have no necessary to install PyTorch manually.
After all the process, we could check the cellpose and napari gui's using
'''
  $ python -m cellpose
''' 
and 
''' 
  $ python -m napari
'''
If everything works, then the installation is compelete.
