# Network-Intrusion-Detection-Systems

## Abstract

Modern networking has a wider range of uses, which puts network infrastructures at danger from breaches and cyberattacks. Machine Learning (ML) based Network Intrusion Detection Systems may be built using a variety of datasets that have been suggested in the literature (NIDS). Many of these datasets, however, exhibit subpar performance and fail to accurately and completely reflect all varieties of intrusions. The low precision of tail classifications in these datasets is another issue. We suggest the University of Nevada - Reno Intrusion Detection Dataset (UNR-IDD), which offers researchers a greater range of samples and situations, to solve these problems.

## Problem Formulation
* Expanded applications of modern-day networking, 
network infrastructures 
* Risk from cyber-attacks and intrusions
* The usage of machine learning (ML) for NIDS 

##  conceptual Figure

![image](https://user-images.githubusercontent.com/60587913/209298757-63782cde-46d6-49c6-af4c-4eb312e33120.png)

## Dataset
using https://www.kaggle.com/datasets/tapadhirdas/unridd-intrusion-detection-dataset dataset

Data Features

* Port Statistics
* Delta Port Statistics
* Flow Entry and Flow Table Statistics

Labels

* TCP-SYN Flood
* Port scan
* Flow Table Overflow
* Blackhole
* Traffic Diversion

## Methodology
* Build an MLP classifier using the provided dataset 
* Find the best value for n_components based on the test accuracy of the MLP classifier using PCA
* Choose the method that achieves the best test accuracy results using feature selection (ANOVA,Mutual)
*  Compare dimensionality reduction to feature selection!
* Tuning MLP Calssifier with different number of batch size , hidden layers, learning rate and different optimizers
* Bulid final model using best parameters after tuning

## Conclusion
1. Using machine learning to solve network attacking .
2. Use MLP model with feature selection “ANOVA, mutual” and Dimensionality reduction “PCA” to select best  number of component.
3. Select best parameters for MLP model that can achieve highest accuracy.
4. It can help to distingue between Anomaly users and attackers.


## contact 
![image](https://user-images.githubusercontent.com/60587913/209285099-911ab4b9-604a-45e5-8c96-ce618df56870.png)https://www.linkedin.com/in/%D9%90%D9%90alaa-elkhashap/





