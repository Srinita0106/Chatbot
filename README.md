# Chatbot

This project implements an **AI-powered chatbot** that can handle user interactions based on predefined **intents** (like greetings, job recruitment queries, or goodbyes). It leverages **Natural Language Processing (NLP)** and **Deep Learning** to understand user inputs and provide appropriate responses.

The workflow includes:

1. **Dataset Preparation** – Uses a `content.json` file defining *intents*, *sample user inputs*, and *responses*.
2. **Text Preprocessing** – Tokenization, stemming/lemmatization, and vocabulary creation.
3. **Model Training** – A neural network (using TensorFlow/Keras) is trained to classify user input into the correct intent.
4. **Response Generation** – Based on the predicted intent, the chatbot selects a response from the predefined list.
5. **Interactive Testing** – The chatbot interacts with users in a conversational loop.

---

## ⚙️ Tech Stack Used

### **Programming Language**

* **Python** – Core development language for chatbot logic and model training.

### **Libraries & Frameworks**

* **TensorFlow / Keras**

  * Used for building and training the deep learning model.
  * Layers include `Embedding`, `LSTM`, `Dense`, and pooling layers.
* **NLTK (Natural Language Toolkit)**

  * Tokenization, text preprocessing, and NLP utilities.
* **NumPy**

  * Numerical operations and handling data arrays.
* **Pandas**

  * Data manipulation and structuring training data.
* **Matplotlib**

  * Visualization of training results (accuracy/loss curves).

### **Model Architecture**

* **Tokenizer & Embedding Layer** – Converts words into vector embeddings.
* **LSTM Layer** – Captures sequential dependencies in text.
* **Dense Layer with Softmax** – Classifies the input into an intent category.

### **Data Handling**

* **JSON** – Stores intents, user inputs, and chatbot responses in `content.json`.
* **Custom preprocessing** – Converts JSON data into training-ready sequences.

---

## 🚀 Features

* Handles multiple intents (greeting, goodbye, recruitment info, etc.).
* Learns to classify unseen text inputs into the correct category.
* Provides predefined, contextually relevant responses.
* Easily extendable by updating `content.json` with new intents and responses.



