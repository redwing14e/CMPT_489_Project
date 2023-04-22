# CMPT_489_Project
CMPT 489 Final project - VizWiz Salient Object Detection
Eric Buell
11256033

--- Most if not All Path Variables/References need to be changed to fit the users file structure ---

How Files were used:


Create_Ground_Truth.ipynb - used to create the ground truth images 
Create_Subset.ipynb - used for the creation of my subsets
Dataset_setup.ipynb - used for analyzing the datasets
Create_Boundaries.ipynb - used for creation of boundry masks needed for VST

u2net: https://github.com/xuebinqin/U-2-Net

mostly the same as on their github but there are some key changes I needed to make to be able to get it runing
The main changes you will see is that i converted the test script and the train script to .ipynb The originals are uploded but are unused
There are some minor changes made to the .py files to fix errors that I had run into but otherwise they are relitivly the same
The full sized pretrained model was too large to upload so if you want to get it you can go to their github to find the download link



VST: https://github.com/nnizhang/VST

the Model was too large for github so it is avalible on my google drive at: https://drive.google.com/file/d/1gkRsbDuJ-x3Bv3ungiixfYA4RRYgn4ZG/view?usp=sharing
download the model and place it in the checkpoint folder

ran into far fewer problems with this so it is mostly unchanged to run it you can look on there github for how they sugest doing it but I used Pycharm and manualy ajusted the defults in train_test_eval.py 


To evaluate I used: https://github.com/zzhanghub/eval-co-sod
with only the slighest change to better adapt my file structure (so litle changes that if you want to use it you can get it off their gethub)