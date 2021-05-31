# SpeechRecognizer


# This repository aimed at building your own Speech Recognizer and a classifier as well. This will enable an idea where human natural language is understood and classified in one of the category based on the context of the text spoken by the human.

The categories considered in this repository are as follows : 

0: Politics
1: Technology
2: Entertainment
3: Business

# Guide to execute the project successfully:

  1. Install all the requirements mentioned in requirements.txt file, using pip3 install -r requirements.txt

  2. Execute the Jupyter notebook one by one, during the process you will build a model trained on 30% of the total dataset, if you wish to train on large set, please update the fraction mentioned: 

      ```
      #considering 20% to train the model
      train = train.sample(frac=0.30)
      ```
  
  
 Happy learning! 
