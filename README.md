# Practical Deep Learning
The following installation guidelines have been tested for a Linux machine
## General Installation
- Download Anaconda Python from https://www.anaconda.com/products/individual
- Verify installation with: conda list anaconda
- Clone/Download this repo to your machine
- Create virtualenv in repo folder with: conda create -n DLenv pip python=3.7
- Activate virtualenv with: conda activate DLenv
## Installation Object Detection
- Make sure you followed the general installation and have the virtualenv activated
- Then install the packages with:
pip install tensorflow==1.14.0 opencv-python==4.2.0.34 keras==2.2.4 imagai==2.1.5
- Download resnet50 weights from https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5
- Place weights in repo/ObjectDetection folder
- Place an image you want to be classified in the ObjectDetection folder as jpg, name it image.jpg
- cd into repo/ObjectDetection then run: python Detection.py
--> Object should be classified
### Credits and source: https://github.com/OlafenwaMoses/ImageAI
## Installation Reinforcement Learning
- Make sure you followed the general installation and have the virtualenv activated
- cd into ReinforcementLearning folder
- Then install packages with:
pip install torch==1.5.0 numpy==1.18.4 gym=0.17.2 matplotlib==3.2.2
- Run script with: python Reinforce.py
