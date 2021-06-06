# Spam or Non Spam Email Classification

In this project, I have trained a model using Naive Bayes algorithm while applying PCA, to classify if an email is spam or non spam. The text processing has been done applying the following tasks:

![alt text](https://media.tenor.com/images/d38f1739be77aaf1b1a825f6899788cb/tenor.gif)

1. Removing the Subject of emails
2. Word tokenization
3. Normalize tokens
4. Contracted word expansion
5. Removing Waste Words
6. Removing Stop Words
7. Adding pos(parts of speech) tags
8. Token lemmatization
9. Finding TF-IDF matrix
10. Applying filterfalse

All these tasks have been done via [Lazy Evaluation](https://www.geeksforgeeks.org/scala-lazy-evaluation/), which makes it possible for a main memory to process data which could be much bigger than the memory itself. 
