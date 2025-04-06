# Sentiment Analysis Using NLP

This project is designed to perform **Sentiment Analysis** on text data using **Natural Language Processing (NLP)** techniques. The goal is to analyze the sentiments (positive/negative/neutral) behind user comments, particularly focusing on the video game **Borderlands** as an example.

The dataset consists of text samples, including phrases like:

- "I'm getting on Borderlands and I will murder you all"
- "I am coming to the borders and I will kill you"

The project utilizes several NLP techniques such as **tokenization**, **lemmatization**, **stemming**, and **stopword removal** to process and analyze the sentiment behind the text data. 

The project is implemented using popular libraries like **NLTK** (Natural Language Toolkit) and **Keras** (for building the deep learning model). The model is trained to classify the sentiment of the input text as either **Positive** or **Negative**.

---

## Table of Contents

1. [Project Description](#project-description)
2. [Dependencies](#dependencies)
3. [How to Run](#how-to-run)
4. [License](#license)

---

## Project Description

The sentiment analysis is performed using a **deep learning model**, which is trained on labeled text data. The model consists of layers like **Embedding**, **LSTM** (Long Short-Term Memory), and **Dense** layers. It aims to predict whether the sentiment of a sentence is positive or negative.

### Dataset

- **Input Data**: A dataset with sentences or phrases related to **Borderlands** along with their sentiment labels.
- **Labels**:
  - **Positive**: Sentences that express excitement, joy, or other positive emotions.
  - **Negative**: Sentences that express aggression, frustration, or other negative emotions.

### NLP Techniques Used:
- **Stopword Removal**: Filtering out common words that do not contribute much to the meaning of the sentence (e.g., "the", "is").
- **Lemmatization**: Reducing words to their base or root form.
- **Stemming**: Trimming words to their stem, though this technique is often more aggressive than lemmatization.

---

## Dependencies

To run this project, you'll need to install the following Python packages:

- **nltk**: Natural Language Toolkit for text preprocessing tasks like stopword removal, tokenization, etc.
- **keras**: Deep learning library for building the neural network model.
- **tensorflow**: Backend for Keras to run the neural network.
- **scikit-learn**: For machine learning utilities like splitting data.
- **numpy**: For numerical operations.
- **matplotlib**: For plotting the accuracy and loss graphs during model training.

You can install the dependencies using the following command:

```bash
pip install nltk keras tensorflow scikit-learn numpy matplotlib
```
---
## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Ankitach780/Twitter-Sentiments-Analysis-Using-NLP.git
```
2. Navigate to the project directory:
```bash
cd Twitter-Sentiments-Analysis-Using-NLP
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
4. Run the script to start the training and testing:
```bash
python Twitter-Sentiments-Analysis-Using-NLP.py
```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

