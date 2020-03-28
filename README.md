# Covid-19 few shot learning from CT scan images


### Dataset

* Download dataset from https://drive.google.com/open?id=1Rrysw7QOulYnZ8PiWiYV2aBP8V4aRwnH
* positive samples are collected from https://github.com/ieee8023/covid-chestxray-dataset
* negative samples are collected from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia (only train split is used)
* positive samples are cleaned by removing images from any region except chest


### Installation

1. Install Anaconda
2. pip install -r requirements.txt
3. conda install tensorflow-gpu


### Result & Visualization

Look into `baseline_siamese` notebook
