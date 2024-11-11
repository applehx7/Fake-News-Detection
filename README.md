# Fake News Detection

A Python project that classifies news articles as **real** or **fake** using machine learning. The script utilizes **text preprocessing**, **TF-IDF vectorization**, and several **classification algorithms** to predict fake news.

## Features

- **Text Preprocessing**: Tokenization, stopword removal, and text normalization.
- **TF-IDF**: Converts text data into numerical features for machine learning models.
- **Classification Models**: Logistic Regression, Naive Bayes, and Support Vector Machines (SVM).
- **Model Evaluation**: Accuracy, precision, recall, and F1-score.

  
## Dataset

This project uses the **Fake News Classification** dataset available on Kaggle. You can download it from the following link:

- [Fake News Classification Dataset on Kaggle](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/data)

Ensure the dataset has columns like `text` (article content) and `label` (fake/real). You may need to adjust the dataset path or modify the data loading code based on the file format you use.


## Requirements

To run this project, you'll need Python and some additional libraries. You can install them using `pip`.

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Fake-News-Detection.git
   cd Fake-News-Detection
