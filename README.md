# Text Generation with Markov Chains

This project explores a fundamental concept in NLP: generating text using a **Markov chain**. Specifically, it builds a **bigram language model** that learns the probability of one word following another from a given text.

### **How It Works**

-   **Model Building**: The script reads an input text file and creates a dictionary where each word is a key, and its value is a list of all words that follow it in the original text.
-   **Sentence Generation**: The model then generates new sentences by randomly selecting a starting word and then using the learned probabilities to pick the next word, and so on.
-   **Analysis**: The project concludes by comparing the length of the generated sentences to the sentence length distribution in the original text, demonstrating how well the model captures the structural patterns of the source material.


