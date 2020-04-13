# Identifying heart pathologies with ECG data and machine learning

## Objective
Find a machine learning model that can predict with the best accuracy possible if a patient has some different arrhythmias or myocardial infarction, based on his or her ECG signals.

Dataset used: [this](https://www.kaggle.com/shayanfazeli/heartbeat) dataset compiled by kaggle, which is based on the data published by physionet.org [here](https://www.physionet.org/content/ptbdb/1.0.0/).
Please see the citations below.

The following models were evaluated:
1. Gradient Boosted Machine (GBM)
2. Convolutional Neural Network (CNN) with 3 conv layers and 2 fully connected layers
3. Convolutional Neural Network (CNN) with 4 conv layers and 2 fully connected layers

Several hyperparameters were tested, and the configuration that produced the best accuracy was:

- CNN with 4 conv layers and 2 FC layers
- batch size = 128
- epochs = 250
- Please see the code, file ptb_cnn_0990.ipynb for details on the other hyperparameters used.

```
Citations:

Original publication:
Bousseljot R, Kreiseler D, Schnabel, A. Nutzung der EKG-Signaldatenbank CARDIODAT der PTB über das Internet. Biomedizinische Technik, Band 40, Ergänzungsband 1 (1995) S 317

PhysioNet:
Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals (2003). Circulation. 101(23):e215-e220.
```
