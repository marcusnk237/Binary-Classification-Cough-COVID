# Binary-Classification-Cough-COVID
A binary classification of cough of person which are tested positive to COVID-19 and those who are tested negative to COVID-19
We use the  Coswara Dataset to train our two models :
- An Artifical Neural Network
- A Convolutionnal Neural Network
Both of them were developped using Tensorflow Keras. 
In this case, Each model was trained by recognize sigal feature of an audio signal, and then guess if these features are related to a person carrying the virus ou not.

Process:

 - Download and separate the dataset from kaggle
 - Create a DataFrame from the filenames to have an overview of the stats
 - Extract features from the audio files and parse it as a new dataframe
 - Pass the features through an ANN and a CNN
 - Evaluate both models

Credits : Coswara - A Database of Breathing, Cough, and Voice Sounds for COVID-19 Diagnosis (https://arxiv.org/abs/2005.10548)
Shuvaev, Sergey, Hamza Giaffar, and Alexei A Koulakov. “Representations of Sound in Deep Learning of Audio Features from Music,” n.d., 5.

