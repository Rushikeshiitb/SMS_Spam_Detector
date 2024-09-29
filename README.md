# SMS Spam Detection System
This project demonstrates an SMS Spam Detection system built using Logistic Regression for binary classification of spam (unwanted) and ham (legitimate) messages. The model was trained using a labeled dataset of SMS messages, which were preprocessed and converted into feature vectors using the TfidfVectorizer.
## Accomplishments
- **Implemented SMS Classification:** Built a model to classify SMS messages as spam or ham.
  
- **Data Preprocessing:**
  - Loaded the dataset from a CSV file and performed label encoding to convert 'spam' and 'ham' labels into binary values.
  - Separated input (SMS messages) and output (labels) for training and testing.

- **Feature Extraction:**
  - Utilized `TfidfVectorizer` to convert SMS messages into feature vectors suitable for classification.
  
- **Model Training:**
  - Trained a Logistic Regression model on the training dataset.
  - Achieved high accuracy on both training and testing datasets.

- **Model Evaluation:**
  - Evaluated model performance using accuracy metrics on training and test data.

- **Model Serialization:**
  - Saved the trained model using `joblib` for future predictions.

- **User Interface for Predictions:**
  - Developed a simple interface to classify new SMS messages as spam or ham based on user input.

## Results

- **Accuracy on Training Data:** 96.70%
- **Accuracy on Testing Data:** 96.77%

## Conclusion
This project showcases my ability to preprocess text data, apply machine learning models, and deploy them for real-world use cases. The implementation of the SMS Spam Detection system demonstrates my proficiency in Python and machine learning techniques.
