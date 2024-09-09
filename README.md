# Fake Job Posting Classification

### Project Overview
The Fake Job Posting Classification project is aimed at detecting fraudulent job postings using machine learning techniques. With the rise of online job portals, fraudulent job listings have also become more prevalent, posing risks to job seekers. This project seeks to build a classification model to automatically identify and filter out such fraudulent postings, helping users avoid scams and enhancing the overall reliability of online job platforms.

### Motivation
Job seekers often fall victim to fake job advertisements that lead to phishing scams or identity theft. Identifying fraudulent job postings manually is not only time-consuming but also inefficient given the vast number of listings online. The goal of this project is to use machine learning to build a robust system that can automatically classify job postings as either legitimate (ham) or fraudulent (spam), making job platforms safer for users.

### Approach

##### Data Collection and Exploration:

The dataset consists of real-world job postings, labeled as either fraudulent or legitimate. Exploratory Data Analysis (EDA) was conducted to understand the distribution of the data and identify key features that could be indicative of fraud.

##### Data Preprocessing:

The text data from job postings (e.g., job descriptions, company profiles, and requirements) was cleaned and preprocessed. This involved tokenization, stopword removal, and lemmatization to ensure the data was in a suitable format for modeling.

##### Feature Engineering:

Important textual and categorical features such as company_profile, description, requirements, and telecommuting were transformed using techniques like Bag of Words & Word2Vec,AvgWord2Vec vectorization. These features help capture the patterns and characteristics of fraudulent vs. legitimate job postings.

##### Model Selection:

Various machine learning classifiers were explored, including Logistic Regression,Naive Bayes,DecisionTreeClassifier,KNeighborsClassifer to identify the best model for detecting fraudulent job postings.

##### Model Evaluation:

The models were evaluated using accuracy, precision, recall, and F1-score. Special emphasis was placed on minimizing false negatives (i.e., falsely classifying a fraudulent post as legitimate), as they pose a high risk to users.

##### Tools and Technologies

1. Python: The core programming language used for building the project.
2. Scikit-learn: Used for building and evaluating machine learning models.
3. Pandas & NumPy: For data manipulation and analysis.
4. NLTK: Libraries used for natural language processing tasks like text cleaning and tokenization.

### Conclusion
This project demonstrates the effectiveness of machine learning in identifying fraudulent job postings. By using advanced classification techniques, the system helps online job portals maintain their integrity and improves the experience of job seekers by reducing the risk of scams.