# Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction
## Project Description
This work is based on the following [paper](https://haoyfan.github.io/papers/SemiTime_ICASSP2021.pdf).<br /> 
I tried to implement the SemiTime model from scratch to demonstrate the effectiveness of the self-supervised dataset in training the supervised classification model.<br />
In the Jupyter Notebook you can find the implementation of two different models and their trainer. <br />
In particular, the semi-supervised trainer follows the SemiTime Mini-batch training algorithm, which can be found on page 3 of the mentioned document.
## Run Model Training and Evaluation
In the Jupyter Notebook there is everything you need to run the code, which can also be run in Google Colab, just run the code cells sequentially.
## Considered Dataset
[CricketX](https://github.com/haoyfan/SemiTime/tree/main/datasets/CricketX)<br />
[InsectWingbeatSound](https://github.com/haoyfan/SemiTime/tree/main/datasets/InsectWingbeatSound) 
## Check Results
Each row represents a different _label ratio_, while each column determines the _alpha value_. <br />
Green box shows when Semi-Supervised Model Accuracy is higher then Supervised one.
 
Average test accuracy (CricketX Dataset)<br />

![CricketX](https://raw.githubusercontent.com/AlessandroPaglialunga1997/Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction/main/Accuracy%20using%20Semi-Supervised%20Model%20on%20CricketX.png) <br />
<br />
Average test accuracy (InsectWingbeatSound Dataset) <br />

![InsectWingbeatSound](https://raw.githubusercontent.com/AlessandroPaglialunga1997/Semi-Supervised-Time-Series-Classification-by-Temporal-Relation-Prediction/main/Accuracy%20on%20InsectWingbeatSound.png)<br />
