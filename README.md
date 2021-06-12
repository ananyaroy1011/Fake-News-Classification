# Fake News Classification

Given the title of a fake news article A and the title of a coming news article B, program classifies B into one of the three categories:
* agreed : B talks about the same fake news as A.
* disagreed : B refutes the fake news in A.
* unrelated : B is unrelated to A.

Basic preprocessing steps are required before using the data:
1. Convert to Lowercase
2. Remove punctuations
3. Remove single character if any
4. Remove stop words
5. Convert numbers to words
6. Lemmatization to get root words

Feature extraction approaches:
* Bag of words
* Similarity between text
* TF-IDF

Data modeling approaches:
* Naive Bayes
* Multinomial Logistic Regression
* Multi Layer Perceptron Classifier

Refer the report for further implementation details, approach, data preprocessing, feature extraction, data modeling and evaluation:
<a href="https://github.com/chandnii7/Fake-News-Classification/blob/main/OSNA_FakeNews_Report.pdf">View Report</a>
<br/><br/>

### Results:
<br/>
<img src="https://github.com/chandnii7/Fake-News-Classification/blob/main/evaluation.jpg" height="200" width="700"/>
<br/>
