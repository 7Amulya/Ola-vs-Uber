# Analyzing Ola vs Uber reviews using ML
This project focuses on analyzing the customer reviews from google playstore and classifying them as positive, negative and neutral using sentiment analysis and models like Support Vector Machine(SVM) and Multimodel Naive Bayes.

### Methodology
## Pre-Processing:
The reviews of ola and uber were retrieved and cleaned sepaartely. The pre-processing performed on them included:
1. Dropping unnecessary coloumns
2. Replacing null values
3. Label encoding
4. Tokenization, Lemmetization and removing stop words

## Data Visualization:
Using sentiment analysis the data was viewed by dividing them into positive,negative or neutral. Both pie and bar charts were made.

## Model Training:
1. Support Vector Machine(SVM)
2. Multimodel Naive Bayes
The ola and uber data was trained separately by dividing the data into 80-20 ratio.

## Results:
The accuracies of the models was observed to be:
# Support Vector Machine(SVM):
1. Support Vector Machine(SVM) on Ola:91.46%
2. Support Vector Machine(SVM) on Uber: 91.10%

# Multimodel Naive Bayes :
1. Multimodel Naive Bayes on Ola: 90.15%
2. Multimodel Naive Bayes on Uber: 90.65%
   
