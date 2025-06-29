# 😄 Text Emotion Detection App

This is a simple and interactive web application that detects emotions from user-inputted text using a machine learning model.

Built with **Python**, **Streamlit**, and a pre-trained **machine learning model**, this app helps users understand the emotional tone of a given message or sentence.

---

## 🚀 Features

- 🔤 Input any text and detect its emotion
- 😊 Displays the predicted emotion along with an emoji
- 📊 Visualizes confidence levels across all possible emotions using a bar chart
- 🧠 Uses a pre-trained model (`text_emotion.pkl`) for inference

---

## 📦 Tech Stack

- [Streamlit](https://streamlit.io/) — Frontend UI
- `joblib` — For loading the trained model
- `scikit-learn` — Model was likely trained with it
- `Pandas`, `NumPy` — Data handling
- `Altair` — For plotting prediction probabilities

---

## 🔍 How It Works

1. User enters a sentence in the text area.
2. The model predicts the emotion using the input text.
3. Output includes:
   - The **detected emotion** and emoji.
   - A **confidence score**.
   - A **bar chart** showing all emotion probabilities.

---

## 📂 Project Structure

├── app.py # Streamlit app
├── model/
│ └── text_emotion.pkl # Pre-trained emotion detection model


---
