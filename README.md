# IMDb Movie Review Sentiment Analysis 🎬

A Deep Learning project that classifies IMDb movie reviews as **Positive (1)** or **Negative (0)** using pretrained Word2Vec embeddings and TensorFlow/Keras.

## 🚀 Project Overview

The project uses Google's pretrained **Word2Vec (Google News, 300-dimensional vectors)** to represent words as numerical vectors. These embeddings are used to build and train a neural network for binary sentiment classification.

The project also includes an interactive **Gradio Dashboard** that allows users to enter their own movie reviews and instantly receive a sentiment prediction along with a confidence score.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Gensim (Word2Vec)
- NumPy
- Matplotlib
- Gradio
- Google Colab

## 🧠 Model Architecture

The model consists of:

1. Pretrained Word2Vec Embedding Layer (frozen).
2. Global Average Pooling.
3. Dense Layer (64 neurons, ReLU).
4. Dropout (0.5).
5. Output Layer (Sigmoid).

## 📊 Features

- IMDb dataset preprocessing.
- Pretrained Word2Vec embeddings.
- Deep Learning model training and evaluation.
- Accuracy and loss visualization.
- Custom movie review predictions.
- Interactive dashboard for real-time sentiment analysis.

## 💻 Dashboard

The Gradio dashboard provides a simple interface where users can:

- Enter a movie review.
- Predict whether the sentiment is positive or negative.
- View the prediction confidence score.

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the cells in order to load the embeddings, prepare the dataset, and train the model.
3. Launch the Gradio dashboard.
4. Enter a movie review and get your prediction!

---

**Project Focus:** Natural Language Processing (NLP) | Deep Learning | Sentiment Analysis
