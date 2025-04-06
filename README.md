# News-Article-Classification

![nc](https://github.com/user-attachments/assets/4482a66f-ab1b-42d7-b7aa-480401a84509)

### Task 1: Data Collection and Preprocessing
- **Data Collection:** A dataset containing labeled news articles across various categories like sports, politics, and technology was collected. This step ensures a diverse set of articles to train the model.
- **Cleaning and Preprocessing:** The collected text data was cleaned and preprocessed to remove any unwanted noise such as special characters, HTML tags, and non-relevant information. This step helps in refining the data for more effective feature extraction.
- **Handling Missing Data:** Any missing data within the dataset was identified and handled appropriately, either by filling or removing them, to ensure the dataset's integrity.

### Task 2: Feature Extraction
- **Feature Engineering:** Textual data was transformed into numerical features using techniques like TF-IDF, word embeddings (Word2Vec, GloVe), or bag-of-words. These features represent the text in a way that machine learning algorithms can process.
- **Exploratory Data Analysis (EDA):** An analysis was conducted to understand the distribution of different categories in the dataset. This analysis helps in identifying any imbalances or patterns in the data which could influence the model training and its outcomes.

### Task 3: Model Development and Training
- **Model Development:** Different machine learning models such as Logistic Regression, Naive Bayes, and Support Vector Machines were built to classify the news articles into their respective categories.
- **Training:** The models were trained on the preprocessed and feature-engineered data. During this phase, hyperparameters were tuned as necessary to optimize the models' performance.
- **Cross-Validation:** To ensure the models were robust and not just fitted to a particular subset of data, cross-validation was used during training. This technique helps in evaluating the model's performance more reliably by using different subsets of the dataset.

### Task 4: Model Evaluation
- **Performance Evaluation:** After training, the models were evaluated using metrics appropriate for classification tasks, such as accuracy, precision, recall, and F1-score.
- **Model Comparison:** The performance of different models was compared to select the best one for the task of classifying news articles. This comparison helps in determining the most effective model in handling the diversity of the dataset and achieving high accuracy.
