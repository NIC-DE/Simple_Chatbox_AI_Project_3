

## Simple Chatbot (Rule-based + Retrieval)

This project implements a **simple chatbot** built in Google Colab, combining **rule-based logic** with **information retrieval techniques**.

### Features

* **Rule-based responses**

  * Handles greetings (e.g. *hi, hello*)
  * Handles help requests
  * Handles exit / goodbye commands

* **Retrieval-based responses**

  * Answers questions using a custom **mini knowledge base (FAQ)**
  * Uses **TF-IDF vectorization** and **cosine similarity**
  * Returns the most relevant answer based on user input

* **Short-term memory**

  * Stores the last **N user–bot interactions**
  * Simulates basic conversational context

### Technologies used

* Python
* scikit-learn (TF-IDF, cosine similarity)
* Google Colab

### Purpose

The goal of this project is to demonstrate the core concepts behind chatbots:
intent detection, text similarity, retrieval-based answering, and basic conversational memory — without using large language models or external APIs.


