# **Semantic Book Recommender with LLMs**

This repository contains the full code for the project.
Here’s a brief breakdown of the components:

## **1. Text Data Cleaning**  
In **`data-exploration.ipynb`**, to clean and preprocess the text data to make it ready for further analysis. This includes removing unnecessary noise, handling missing values, and performing basic text transformations.

## **2. Semantic Search and Vector Database**  
In **`vector-search.ipynb`**, to dive into building a **vector search system**. This allows to search for similar books based on **semantic meaning**, rather than just keywords. The vector database is built to answer queries like **"a book about a person seeking revenge"** and return the most relevant books.

## **3. Text Classification Using Zero-Shot Classification**  
In **`text-classification.ipynb`**, to use **zero-shot classification** with LLMs to classify books as either **"fiction"** or **"non-fiction"**. This provides a useful filter for users looking to sort books by genre or category.

## **4. Sentiment Analysis and Emotion Extraction**  
In **`sentiment-analysis.ipynb`**, to leverage LLMs to analyze the **emotional tone** of book descriptions. Whether a book is **joyful**, **suspenseful**, or **sad**, this module helps users to discover books based on their emotional appeal.

## **5. Web Application with Gradio**  
Finally, **`gradio-dashboard.py`** brings all the features together in a **user-friendly web application** built with **Gradio**. This allows users to interact with the system and get personalized book recommendations with just a few clicks!

---

## **Acknowledgements**

- [Hugging Face](https://huggingface.co/) for their **transformers library**  
- [Gradio](https://gradio.app/) for creating the easy-to-use web interface  
- [OpenAI](https://openai.com/) for providing powerful LLMs that make it all possible
- [freeCodeCamp](https://www.youtube.com/@freecodecamp) course for the detailed explaination
