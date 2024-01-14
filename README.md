# LLM-Generated-text-classifier
The objective of this notebook is to tell the probability of the text feeded into the model being AI generated . In this model , I have attempted to provied a solution to the problem of detection of AI generated text . I have utilised BERT , which is a Natural Language Processing Model and have used the Black box detection approach .

The gist of the project is to build a classifier using NLP concpets to classify the text as AI-generated or human written.

My model is based and backed upon the research paper on "Science of detection of LLM-generated texts by Ruixiang Tang, Yu-Neng Chuang, Xia Hu" .

My project started with importing the initial libraries necessary and then importing the data-set available on Kaggle .

This is the link to the datasert:"/kaggle/input/llm-detect-ai-generated-text/train_essays.csv".

This dataset would be further divided into testing and training classes . I preprocessed the text of the essays and checked for the class balance.

Now the labels are converted to tensors to feed them into the model and bert sequential model for classifiaction is enabled .

Now the model for the detection is trained which involes training the loop using pytorch for the corresponding neural network.

Further , Validaton accuracy and final results are printed .

In short my approach involves - 

1 - Importing a Data set and using it to train our model , this involves splitting of Data into training and test sets .

2- Checking for the Class Balance.

3- Pre-processing of data , which involves Cleaning and processing of Virtual Data . 

4- Using BERT tokenizer,encoding the preprocessed text to it for input into our detection model.

5- The final steps Involves training of the Model to a high accuracy , Result prediction and storing of the results .
