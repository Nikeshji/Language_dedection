#Language Dedector 

Dependencies:
This project requires the following Python libraries:
pandas - for data manipulation and analysis.
numpy - for numerical operations.

Dataset
The dataset used for training and testing the model consists of text samples in various languages. You can find the dataset in the data/ directory of this repository.
Ensure that the dataset is structured properly, with each row containing a text sample and its corresponding language label.

Usage
To run the language detection model, execute the following command in your terminal:

How It Works
Data Preprocessing: The raw text data is loaded using Pandas, cleaned, and prepared for analysis.

Feature Extraction: Text data is transformed into numerical format using techniques such as TF-IDF or Count Vectorization.

Model Training: The Gaussian Naive Bayes model is trained on the processed dataset to learn patterns associated with different languages.

Language Prediction: Given an input text, the trained model predicts its language based on learned features.




