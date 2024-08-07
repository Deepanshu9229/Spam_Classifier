# Spam_Classifier

This project involves building a spam classifier using Python. The notebook contains detailed steps for data analysis, preprocessing, and model building to detect spam messages.

# 1. Importing Libraries
The project starts by importing necessary libraries for data manipulation and model building.

![Screenshot 2024-08-07 083036](https://github.com/user-attachments/assets/cb8d9ab4-331c-4580-aefc-148cbc91f562)

# 2. Loading the Dataset
The dataset is loaded into a Pandas DataFrame to facilitate data manipulation.

![Screenshot 2024-08-07 083059](https://github.com/user-attachments/assets/0735078b-c00b-47e1-9b78-4141a03f5b85)

# 3. Exploratory Data Analysis (EDA)
EDA is performed to understand the structure of the dataset, identify any anomalies, and visualize distributions. This step includes:

  1)  Checking the distribution of spam and ham messages.
  2)  Visualizing the length of messages.
  3)  Identifying common words in spam and ham messages.
# 4. Data Preprocessing
Data preprocessing is crucial for preparing the text data for model building. The steps include:

   Converting to Lower Case: Ensures uniformity by converting all text to lower case.
   Tokenization: Splits text into individual words or tokens.
   Removing Special Characters: Eliminates unwanted characters that do not contribute to the meaning.
   Removing Stop Words and Punctuation: Removes common words and punctuation that do not add significant value.
   Stemming: Reduces words to their base or root form.

# 5. Model Building
Several machine learning algorithms are implemented and evaluated to find the best performing model. This section includes:

   Splitting the Data: Divides the dataset into training and testing sets.
   Training Models: Includes algorithms like K-Nearest Neighbors (KN), Naive Bayes (NB), Random Forest (RF), Extra Trees Classifier (ETC), Support Vector Classifier (SVC), Logistic Regression (LR), AdaBoost, Gradient 
   Boosting Decision Trees (GBDT), Bagging Classifier (BgC), and Decision Tree (DT).
   Evaluating Models: Measures the performance of each model using accuracy and precision metrics.

# 6. Results
The model evaluation includes metrics such as accuracy and precision. Below are the comparison results before and after model improvements:

![Screenshot 2024-08-06 191813](https://github.com/user-attachments/assets/58b9849a-c0a2-426d-bbfb-82d31f002398)

Improved result - 

![Screenshot 2024-08-06 192624](https://github.com/user-attachments/assets/bb05f4fe-47e7-4a94-9895-23593105b195)

As seen from the results, there were improvements in accuracy and precision across several algorithms after refining the model. Notably, the Naive Bayes algorithm performed the best on this dataset with the highest accuracy and precision.



