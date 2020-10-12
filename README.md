# 2D Wound Segmentation
This project aims at wound area segmentation from natural images in clinical settings. The architectures tested so far includes: U-Net, MobileNetV2, SegNet, VGG16.
![Intro_Image](https://raw.githubusercontent.com/Pele324/ChronicWoundSeg/master/figures/Intro.png)
## Install requirements
     pip install -r requirements.txt
     
## Data
The training dataset is built by our lab and collaboration parties and will be updated shortly. For a sample dataset please try the [Medetec Wound Database](http://www.medetec.co.uk/files/medetec-image-databases.html) in the data folder.
    
## Run
    python3 train.py
    python3 predict.py
