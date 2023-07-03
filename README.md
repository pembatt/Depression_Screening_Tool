# Depression_Screening_Tool
Using ML to create a screening tool for depression
dataset_1 , dataset_2, dataset_3 are raw datsets from Kaggle
Datasets labelled Processed are cleaned and added extra attributes. 
Using the model="j-hartmann/emotion-english-distilroberta-base" from hugging face attributes 'anger	,disgust,	fear,	joy	,neutral	,sadness	,surprise' was added to each body of text. 
Using the model="paulagarciaserrano/roberta-depression-detection" from hugging face attributes 'depression_model_label and depression_score'  was added to each body of text. 
