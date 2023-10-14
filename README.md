# CS4622-ml-wave2vec

## Project - Speaker, Age, Gender and Accent Recognition using wav2vec base

The Wav2vec base model serves as a crucial feature extraction tool for our project. Specifically, we have employed the features extracted from transformer layers 7 and 12

#### Dataset

To get our feature set, we used the AudioMNIST dataset. For more detailed insights into this dataset, please visit the following Link. (https://github.com/soerenab/AudioMNIST).

#### Approach

Our project is structured around the development of various classification models for each label. We have trained and assessed multiple models, and it was the Support Vector Classifier (SVC) that stood out as the optimal choice for each label. To tackle the dimensionality challenge, we explored feature reduction techniques like "PCA" and "K-Best". For robust model evaluation, we leveraged 5-fold cross-validation. Furthermore, we utilized random search to fine-tune hyperparameters, ensuring the models' best performance. All the accuracy metrics and visualizations can be found in the accompanying notebook code.
