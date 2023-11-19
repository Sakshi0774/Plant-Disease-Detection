# Plant-Disease-Detection
## Introduction

It is very important to get an accurate diagnosis of plant diseases for global health and well being. In this ever changing environment, identifying the disease including early prevention is important to avoid problems that we might face otherwise. Some of these problems could have devastating impacts on humanity including global shortage of food. It is crucial to prevent unnecessary waste of financial resources achieving a healthier lifestyle, by addressing climate change from an ecological perspective. It is difficult for the naked eye of a human being to catch all sorts of problems with plant diseases. Also doing this time and time again is also laborious and unproductive work. In order to achieve accurate plant disease detection, a plant pathologist should possess good observation skills so that one can identify characteristic symptoms. An automated system designed to help identify plant diseases by the plant’s appearance and visual symptoms could be of great help. This can be deployed in agricultural fields so that the whole pipeline can be automated. This would not only lead to better efficiency as machines could perform better than humans in these redundant tasks but also improve the productivity of the farm. Our work solves the above mentioned problem of automating plant disease classification using deep learning and computer vision techniques.
## Building
'''
# clone the repo
git clone https://github.com/NischayGoyal1/WhatThe_hAIck.git .

# install dependecies
pip install -r requirements.txt

# run the python file
python app.py

'''
## Disease Detection

Disease detection in plants plays an important role in agriculture as farmers have often to decide whether the crop they are harvesting is good enough. It is of utmost importance to take these seriously as it can lead to serious problems in plants due to which respective product quality, quantity or productivity is affected. Plant diseases cause a periodic outbreak of diseases leading to large-scale death which severely affects the economy. These problems need to be solved at the initial stage, to save the lives and money of people. Automatic classification of plant diseases is an important research topic as it is important in monitoring large fields of crops and at a very early stage, if we can detect the symptoms of diseases when they appear on plant leaves. This enables computer vision algorithms to provide image-based automatic inspection. Comparatively, manual identification is labor intensive, less accurate and can be done only in small areas at a time. By this method, the plant diseases can be identified at the initial stage itself and the pest and infection control tools can be used to solve pest problems while minimizing risks to people and the environment.

## About Database

(https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
This dataset is recreated using offline augmentation from the original dataset. This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.
![git ss1](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/78402602-f611-4937-8046-f670aefe6da0)

![git ss2](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/146df982-1619-4a3b-bb7c-579da09240cc)

# Model Architecture

We used VGG19 for enhancing the accuracy of our model. 
![git ss3](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/00ba4424-611e-4332-91f4-56e7b6ccfa27)

# Loss of Accuracy Plot
![git ss4](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/2aa79998-7991-4e3b-bd9e-8c2c168edaa5)

![git ss5](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/452ddca1-4f6c-402d-9dbc-eb53a78403b5)

# Result

Now the best models with best accuracy detects the plant disease with accuracy

> Accuracy 85%
![git ss6](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/d14fd19f-ef26-46f3-99e4-14d873f9930e)

# DONUT CHART OF ACCURACY TABLE ->

![git ss7](https://github.com/Sakshi0774/Plant-Disease-Detection/assets/150219068/c8813fb7-f3a0-4269-b4d5-e91f6751f44e)

Challenges I ran into: 

1. Faced Diffilculty in finding a appropriate Data-set with large number of images.
2. As a newbie to Machine learning domain it is very difficult to work with huge number of functions and libraries.3)As we have used VGG 19 architure so most of the common inbuilt functions are not working , we have encounterd with number of errors , So finding new functions and there respective libraries is quite a troublesome.
3. Faced Pixel Related issue for showing false result for Feed images
4. Had Trouble in deployment of our model on website , and linking backend with the frontend.

 ## Conclusion

The model was successfully able to determine whether the plant whose image is provided has the disease or not and if yes,which disease the plant is suffering from.
Knowing if the plant is suffering with a disease we can conclude which pesticide should be selected for its further prevention.
