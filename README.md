# SMS Spam Detection
## Task:
  To identify whether the incoming sms is spam or not.
## Dataset:
  The dataset has been obtained from UCI machine learning repsitory. 
## Approach:
   1. Imported the dataset.
   2. From nltk library imported stopwords and PorterStemmer (to get the stem words).
   3. Performed text cleaning
       - removed the symbols and numbers, leaving only the alphabets in place
       - converted the entire text to lowercase
       - splitted entire text into words to identify the stem words
       - Replaced words with stem words
       - Removed stopwords
       - concatenated the remaining text   
   4. Text document is ready for further processing
   5. Vectorized the text using Bag of Words
   6. Did the train test split
   7. Applied Naive Bayes Algorithm
   8. Created a model with 99% accuracy
