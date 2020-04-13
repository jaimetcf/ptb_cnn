# Predicting Heart malfunctioning with ECG signals

## Objective
Find a machine learning model that can predict with the best accuracy possible if a patient has some different arrhythmias or myocardial infarction, based on his or her ECG.

This analysis used the dataset compiled by kaggle [link](https://www.kaggle.com/shayanfazeli/heartbeat), based on the data published by physionet.org [here](https://www.physionet.org/content/ptbdb/1.0.0/). Please see the citations below.

The following models were evaluated:
1. Gradient Boosted Machine (GBM)
2. Convolutional Neural Network (CNN) with 3 conv layers and 2 fully connected layers
3. Convolutional Neural Network (CNN) with 4 conv layers and 2 fully connected layers

Several hyperparameters tested, and the configuration that produced the best accuracy was:

- CNN with 4 conv layers and 2 FC layers
- batch size = 128
- epochs = 250
- Please see the code, file ptb_cnn_0990.ipynb for details on the other hyperparameters used.

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jaimetcf/ptb_cnn/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
