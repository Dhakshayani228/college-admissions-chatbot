# college-admissions-chatbot
AI-powered College Admissions &amp; Career Chatbot | Retrieval-Augmented Generation | Built with Pandas, FAISS, SBERT, FLAN-T5, and Gradio

## Overview

I selected the **Education Industry** because students and parents face challenges in getting reliable information about **admissions, courses, campus facilities, and placements**.

This project is a **College Admissions & Career Chatbot** designed to provide **accurate, 24/7 answers** to repetitive queries. It helps reduce staff workload while ensuring students and parents get quick, consistent responses.

The dataset is organized into **5 main categories**:

* 📖 Admissions
* 📚 Courses
* 🏫 Campus Facilities
* 💼 Placements
* ❓ General Queries

---

## Features

✅ Provides instant answers to frequently asked questions (FAQs)
✅ Organized into structured categories for easy navigation
✅ Uses **retrieval + generative AI hybrid approach** for better accuracy
✅ Built with a **user-friendly Gradio interface**
✅ Saves staff time and improves student experience

---

## Tech Stack & Libraries

* **Python** – Core programming language
* **Pandas** – Handles dataset and preprocessing
* **FAISS** – Efficient similarity search for retrieval
* **Sentence-Transformers (SBERT)** – Encodes questions into embeddings for semantic search
* **Transformers (Hugging Face)** – For generative AI models
* **PyTorch** – Backend for AI models
* **Gradio** – Interactive chatbot interface

---

## How It Works

1. **Retrieval-based approach**

   * Uses **FAISS + Sentence-BERT** to quickly find the most relevant FAQ from the dataset.

2. **Fallback generative model**

   * If no exact match is found, the system falls back to a **FLAN-T5** model to generate a natural response.

3. **Hybrid RAG approach**

   * Combines the **accuracy of retrieval** with the **flexibility of generation**, ensuring both reliable and adaptive answers.

---

## My Learning Experience (RAG)

While building this project, I explored **Retrieval-Augmented Generation (RAG)**.

* RAG enhances chatbot performance by **retrieving relevant information first** and then using a **generative model** for unseen queries.
* This approach ensures the chatbot remains **fact-based** (from FAQs) but also **creative and flexible** when needed.

This was my first hands-on experience with RAG, and it gave me a clear understanding of how modern chatbots combine **search + generation** for real-world use cases.

---

##  Demo

👉 (You can see my demo video)


## How to Run in Jupyter Notebook
1. Clone the repository & open Jupyter

git clone https://github.com/your-username/college-admissions-chatbot.git
cd college-admissions-chatbot
jupyter notebook


2. Open the notebook

Navigate to chatbot.ipynb (or whichever notebook file you create).

3. Open it in Jupyter.

Install required libraries (inside a Jupyter cell):

!pip install pandas faiss-cpu sentence-transformers transformers torch gradio


4. Run the notebook cells step by step:

Import libraries

Load dataset (pandas)

Build embeddings (sentence-transformers)

Create FAISS index

Load generative model (FLAN-T5)

Launch chatbot interface (gradio)

5. Start the chatbot
At the last cell, Gradio will give you a local URL → Click it to open chatbot in your browser.


## ⚡ How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/college-admissions-chatbot.git
   cd college-admissions-chatbot
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the chatbot:

   ```bash
   python chatbot.py
   ```
4. Open the Gradio link in your browser to interact with the chatbot.

## 👨‍💻 Author

**G. Dhakshayani**
B.Tech (Information Technology)


