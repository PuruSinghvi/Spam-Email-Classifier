# Spam Email Classifier
A program that can classify emails as spam or not spam using machine learning algorithms. </br>
This project was made during the Compozent internship in Machine Learning and Artifical Intelligence.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Datasets-Used">Datasets Used</a>
    </li>
    <li>
      <a href="#Algorithms-Used">Algorithms Used</a>
      <ul>
        <li><a href="#TF-IDF-Vectorizer">TF-IDF Vectorizer</a></li>
        <li><a href="#Support-Vector-Machine">Support Vector Machine</a></li>
      </ul>
    </li>
    <li><a href="#License">License</a></li>
  </ol>
</details>


## Datasets Used
The combined dataset was built using these two datasets:
  1. <b>2007 TREC Public Spam Corpus</b> </br>
  File name: email_text.csv </br>
  Original link: https://plg.uwaterloo.ca/cgi-bin/cgiwrap/gvcormac/foo07 </br>
  Preprocessed download link: https://www.kaggle.com/datasets/bayes2003/emails-for-spam-or-ham-classification-trec-2007 </br> </br>
  2. <b>Enron-Spam Dataset</b> </br>
  File name: enron_spam_data.csv </br>
  Original link: https://www2.aueb.gr/users/ion/data/enron-spam/ </br>
  Preprocessed download link: https://github.com/MWiechmann/enron_spam_data/ </br> </br>


## Algorithms Used
### TF-IDF Vectorizer
TF-IDF is an abbreviation for Term Frequency Inverse Document Frequency. This is a very common algorithm to transform text into a meaningful representation of numbers which is used to fit machine learning algorithms for prediction.  </br>
In a CountVectorizer, we only count the number of times a word appears in the document which results in biasing in favour of most frequent words. This ends up in ignoring rare words which could have helped in processing our data more efficiently. </br>
A TF-IDF Vectorizer gives more importance to words that are unique and more likely to be indicative of spam or non-spam content. </br>
Therefore, TF-IDF Vectorizer is often preferred for spam email classification due to its ability to capture the relative importance of words and distinguish between spam and non-spam content more effectively.

### Support Vector Machine
Support Vector Machine (SVM) is a supervised machine learning algorithm used for both classification and regression. They are known for their ability to learn complex patterns from data and perform well on both linear and non-linear problems. </br>
SVMs are widely used in spam filtering to distinguish between legitimate emails and spam messages. This is because it generally achieves higher classification accuracy and is robust to noise and outliers in the data. </br> </br>


## License
Distributed under the MIT License. See `LICENSE.txt` for more information. </br> </br>

<p align="right">(<a href="#Spam-Email-Classifier">back to top</a>)</p>
