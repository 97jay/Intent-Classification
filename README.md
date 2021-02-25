# Intent-Classification
To perform intent classification given a sentence

Used NLTK library for performing preprocessing and feature extraction and Keras library to build neural network to be able classify the intent of each sentence. 

1. Open the file intent_classification.ipynb to run intent classification
2. The 'data_full.json' is the dataset. This dataset is found at https://github.com/clinc/oos-eval(data/data_full.json).
3. I use 20 random inscope intents for training the model.
4. The file 'model' is the pretrained model trained on classes in the 'intent.txt' file.
5. The intent.txt contains the intents that I used for training. However you can train on other intents by changing variable values in the code. 
Details are in the code.
