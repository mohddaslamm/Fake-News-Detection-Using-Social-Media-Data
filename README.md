# Fake News Detection using Machine Learning

## Project Description

This project is about detecting whether a news article is real or fake using machine learning and natural language processing (NLP). The system analyzes the text of a news article and predicts whether the news is genuine or fake.

Fake news spreads very quickly on social media and other online platforms. Because of this, it is important to build systems that can automatically identify misleading information.

---

## Features

- Detects fake news articles using machine learning
- Uses NLP techniques to preprocess text data
- Converts text into numerical features using TF-IDF
- Trains a classification model
- Allows users to test news articles through the command line

---

## Dataset

The dataset used for this project contains both real and fake news articles.

Source: Kaggle – Fake and Real News Dataset

The dataset includes:
- News title
- News text
- Label (Real or Fake)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

---

## Project Structure

```
fake-news-detection/

data/              # dataset files
notebooks/         # experiments and testing
src/               # source code
models/            # trained models

train.py           # script to train the model
predict.py         # script to predict news authenticity
requirements.txt   # project dependencies
README.md          # project documentation
```

---

## Installation

Clone the repository:

```
git clone https://github.com/your-username/fake-news-detection.git
```

Go to the project folder:

```
cd fake-news-detection
```

Install the required dependencies:

```
pip install -r requirements.txt
```

---

## How to Run

Train the model:

```
python train.py
```

Predict whether a news article is real or fake:

```
python predict.py
```

Then enter the news text when prompted.

---

## Model

This project uses **TF-IDF (Term Frequency – Inverse Document Frequency)** to convert text data into numerical features.

After feature extraction, a machine learning classifier such as:

- Logistic Regression
- Naive Bayes

is used to classify the news articles.

---

## Evaluation

The model performance is evaluated using common classification metrics such as:

- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## Future Improvements

Possible improvements for this project include:

- Implement deep learning models like LSTM or BERT
- Build a web interface for easier interaction
- Improve accuracy using larger datasets
- Deploy the model as a web application

---

## Author

mohammed aslam

---

## License

This project is open source and available under the MIT License.
