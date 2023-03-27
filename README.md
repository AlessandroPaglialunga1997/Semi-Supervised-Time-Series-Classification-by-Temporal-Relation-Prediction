# Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction
## Project Description
This work is based on the following [paper](https://haoyfan.github.io/papers/SemiTime_ICASSP2021.pdf). I tried to implement the SemiTime model from scratch to demonstrate the effectiveness of the self-supervised dataset in training the supervised classification model.
In the Jupyter Notebook you can find the implementation of two different models and their trainer. In particular, the semi-supervised trainer follows the SemiTime Mini-batch training algorithm, which can be found on page 3 of the mentioned document.
## Run Model Training and Evaluation
In the Jupyter Notebook there is everything you need to run the code, which can also be run in Google Colab, just run the code cells sequentially.
## Considered Dataset
[CricketX](https://github.com/haoyfan/SemiTime/tree/main/datasets/CricketX)
[InsectWingbeatSound](https://github.com/haoyfan/SemiTime/tree/main/datasets/InsectWingbeatSound) 
## Check Results
Average test accuracy on CricketX Dataset
![Supervised Accuracy](https://raw.githubusercontent.com/AlessandroPaglialunga1997/Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction/main/Accuracy%20using%20Semi-Supervised%20Model.png)
Average test accuracy on InsectWingbeatSound Dataset
![SemiTime Accuracy](https://raw.githubusercontent.com/AlessandroPaglialunga1997/Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction/main/Accuracy%20using%20Semi-Supervised%20Model.png)
