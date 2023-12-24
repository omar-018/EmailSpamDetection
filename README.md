# EmailSpamDetection

## Project Overview

This project embarks on the intricate journey of email spam detection, employing cutting-edge machine learning techniques to distinguish between legitimate and spam emails. The process begins with meticulous text pre-processing, where basic cleaning, stop words removal, and lemmatization with POS tags are employed to refine the raw text data. This step ensures that the subsequent analysis is conducted on a standardized and meaningful textual foundation.

The feature extraction phase introduces the TF-IDF vectorizer, a powerful tool in NLP, to analyze the significance of terms within each document. This step plays a crucial role in transforming raw text into a format suitable for machine learning algorithms, enabling the model to discern patterns and associations effectively.

Exploratory Data Analysis (EDA) unfolds as a pivotal step, uncovering insights that guide subsequent model refinement. The identification of the top 20 words in each category (spam or ham) is a key facet of EDA. Removing common words and potential overfitting candidates enhances the model's ability to generalize effectively. Additionally, examining the correlation between the length of a message and its category provides valuable insights into potential relationships that can influence the classification process.

The project delves further into the model tuning phase with a Grid Search. This exhaustive hyperparameter tuning method explores various permutations to identify the optimal configuration for the Naïve Bayes model. This meticulous approach ensures that the model is fine-tuned to achieve optimal performance, contributing to accurate spam detection.

## Learning Through Practical Application

This comprehensive email spam detection project was meticulously crafted as part of an educational endeavor aimed at teaching students the intricacies of Python programming and machine learning. By incorporating real-world applications and hands-on projects, students gain practical insights into the application of theoretical concepts in a professional setting. This project serves as a practical illustration of text pre-processing, feature extraction, exploratory data analysis, and model tuning—a holistic approach that mirrors the challenges and methodologies encountered in real-world data science projects.

The project is featured in a book titled "Python Programming and Machine Learning for Beginners," providing learners with a structured and accessible resource to enhance their skills. Readers can explore the project in-depth, following step-by-step instructions and gaining a deeper understanding of the methodologies employed. For those eager to delve into the realms of Python and machine learning education, this book offers a valuable learning experience.

<a href="https://www.igi-global.com/book/_/315132" target="_blank">Explore the book here.</a>

## Results

The results of the email spam detection models are summarized below, showcasing the accuracy scores achieved by the Naïve Bayes model variants:

- Bernoulli Naïve Bayes:
Accuracy: 99.25%
- Multinomial Naïve Bayes:
Accuracy: 99.62%
- Gaussian Naïve Bayes:
Accuracy: 97.87%

These accuracy scores highlight the effectiveness of the Naïve Bayes models in accurately distinguishing between spam and non-spam emails. The Multinomial Naïve Bayes model emerges as the top performer, showcasing its robustness in handling the complexities of email spam detection. These results underscore the practical applicability of machine learning techniques in enhancing email security and streamlining communication channels.

<p align="left"><img src="https://github.com/omar-018/EmailSpamDetection/blob/main/results.png" alt="GIF 1", width="100%"></p>
