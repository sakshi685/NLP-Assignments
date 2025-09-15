# NLP Assignments

This repository contains my solutions for three natural language processing (NLP) assignments covering character-level analysis, text classification, and text generation.

---

## Assignment 1: Character-Level NLP

This assignment focuses on fundamental character-level text processing. The tasks include:

-   **Tokenization:** Breaking down a paragraph into individual characters.
-   **Frequency Analysis:** Counting the frequency of each character using `collections.Counter`.
-   **Data Cleaning:** Removing punctuation and digits to keep only alphabetical characters.
-   **Visualization:** Plotting a bar chart of the top 10 most frequent characters using `matplotlib`.

---

## Assignment 2: News Classification with TF-IDF + SVM

This project implements a complete machine learning pipeline for text classification. The key steps are:

-   **Preprocessing:** Cleaning and preparing a news dataset.
-   **Vectorization:** Converting text into numerical TF-IDF (Term Frequency-Inverse Document Frequency) vectors.
-   **Model Training:** Training a Support Vector Machine (SVM) classifier on the vectorized data.
-   **Evaluation:** Printing accuracy, a confusion matrix, and a classification report to evaluate the model's performance.

---

## Assignment 3: Text Generation with Markov Chains

This assignment explores a simple probabilistic approach to text generation using a Markov chain. The core tasks are:

-   **Model Building:** Constructing a bigram language model from a text file.
-   **Text Generation:** Using the model to generate five new, random sentences.
-   **Distribution Comparison:** Comparing the length distribution of the generated sentences with the original text to see how well the model mimics the source's structure.
