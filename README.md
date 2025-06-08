# 🤖 Simple Intent-Based Chatbot Using TensorFlow

This project implements a basic chatbot in Python using **TensorFlow**. It is built around **predefined intents** and **custom responses**, classified via a feedforward neural network.

---

## ⭐ Features

- ✅ **Intent classification** – Understands user messages based on intents defined in `intents.json`.
- ✅ **Custom responses** – Provides appropriate replies for each recognized intent.
- ✅ **Data-driven design** – Easily extendable by adding more intents or example phrases.
- ✅ **Two-script flow**:
  - `new.py` – Trains the model on intent-response pairs.
  - `chatbot.py` – Loads the trained model and interacts with users.
