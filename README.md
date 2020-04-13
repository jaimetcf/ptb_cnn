# Identifying heart pathologies with ECG data and deep learning

## Objective
Find a machine learning model that can predict, with the best accuracy possible, if a patient has certain arrhythmias or myocardial infarction, based on his or her ECG signals.


## Dataset
[ECG Heartbeat dataset](https://www.kaggle.com/shayanfazeli/heartbeat) compiled by kaggle, based on the data published by physionet.org [here](https://www.physionet.org/content/ptbdb/1.0.0/). (Citations below)

- 10,506 ECG signals with some type of arrhythmia
-  4,046 ECG signals with normal heartbeat


## Models evaluated
1. Gradient Boosted Machine (GBM)
2. Convolutional Neural Network (CNN) with 3 conv layers and 2 fully connected layers
3. Convolutional Neural Network (CNN) with 4 conv layers and 2 fully connected layers


## Best results achieved
- Validation Accuracy       => 0.990
- Validation ROC AUC Score  => 0.985


## Best model
The configuration that produced the best accuracy was:

- CNN with 4 conv layers and 2 FC layers
- batch size = 128
- epochs = 250

Please check the code for hyperparameter values


```
Citations:

Original publication:
Bousseljot R, Kreiseler D, Schnabel, A. Nutzung der EKG-Signaldatenbank CARDIODAT der PTB über das Internet. 
Biomedizinische Technik, Band 40, Ergänzungsband 1 (1995) S 317

PhysioNet:
Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, 
Moody GB, Peng C-K, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: 
Components of a New Research Resource for Complex Physiologic Signals (2003). 
Circulation. 101(23):e215-e220.
```
