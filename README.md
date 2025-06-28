# Propaganda-Detection-Using-Classical-ML-BERT
This project focuses on detecting propaganda in textual data using both classical machine learning techniques and transformer-based deep learning models. It compares the effectiveness of traditional algorithms like Naive Bayes and Logistic Regression with state-of-the-art models like BERT.

## Project Overview

Propaganda is often embedded subtly in text and detecting it requires careful understanding of both semantics and context. The goal of this project is to build a model that can classify whether a given piece of text contains propaganda or not. This problem lies at the intersection of natural language processing (NLP), machine learning, and social impact.

## Approach

The pipeline begins with standard NLP preprocessing steps such as text cleaning, tokenization, and transformation using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer.

To evaluate performance across different model families, I implemented and tested the following machine learning models:

- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

These classical models served as baseline comparisons and performed reasonably well on the training data. However, due to the nuanced nature of propaganda, classical models had limitations in capturing deeper contextual patterns.

To overcome this, I fine-tuned a **BERT (Bidirectional Encoder Representations from Transformers)** model (`bert-base-uncased`) using the HuggingFace Transformers library. The model was trained on the same dataset and showed significant improvement in performance.

## Results

- The best-performing model, **BERT**, achieved an accuracy of **64.36%**, outperforming all classical models.
- Classical models performed adequately but struggled with complex linguistic structures often found in propaganda.
- BERT’s contextual embeddings helped in better identifying implicit patterns of biased or manipulative language.

## Conclusion

This project demonstrates the effectiveness of modern transformer-based architectures like BERT in detecting propaganda in text, a task that traditional machine learning models find challenging. It also highlights the importance of experimentation and comparative model evaluation in real-world NLP tasks.

This work was developed as part of a broader learning journey to deepen my understanding of text classification problems, model evaluation, and the social implications of NLP.

---

Feel free to explore the notebook and reach out if you have suggestions or ideas to improve the model!
