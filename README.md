# NLP

Initial feature extraction

Each vocabulary that appears in the text will be considered as a feature plus 1 for bias.
To reduce these features two just 3 values in a vector you use sentimental analysis
where [1, positiive word feature, negative word feature]
it is calculated by summing of frequency of words that appear in a text for positive feed back and similarly for negative feedback

preprocessing

stemming - reducing the word to its base word - working, worked - work, captial to lower case
Iliminating stop words, punctuations, handels and URL  ---  has, is, and, it , a.. etc, .,:!"'  @twitter, Http://*****

$ import nltk 
package for natural langueage toolkit
