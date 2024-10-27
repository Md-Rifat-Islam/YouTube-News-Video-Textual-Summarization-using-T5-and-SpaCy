<!--
## YouTube News Video Textual Summarization using T5 and SpaCy
### Research Article Presentation video on ICCIT 2023: https://youtu.be/I-Khius3hM8

#### -Developed two system pipelines to summarize any YouTube News video using only the video link as input.
#### -Conducted result comparison between Abstractive textual summarization of Google T5 and Extractive textual summarization of SpaCy using ROUGE scores.
-->

# YouTube News Video Textual Summarization using T5 and SpaCy

Research Article Presentation video on ICCIT 2023: [Watch here](https://youtu.be/I-Khius3hM8)

This project develops two system pipelines to summarize any YouTube news video using only the video link as input. It also conducts a comparison between two summarization techniques — **Abstractive Summarization** using Google T5 and **Extractive Summarization** using SpaCy — evaluated with ROUGE scores.

## 🔍 Overview

With the rapid growth of digital content, especially in the form of videos, there's an increasing need to extract relevant information quickly. This project focuses on summarizing YouTube news videos using state-of-the-art NLP models, Google T5, and SpaCy, allowing users to consume news in text format efficiently.

## ✨ Features

- **Text Extraction**: Extracts text from YouTube videos using the transcript data or via speech-to-text APIs.
- **Text Summarization**: Summarizes the extracted text using two approaches:
  - **Abstractive Summarization** with Google T5 Transformer model.
  - **Extractive Summarization** with SpaCy's NLP pipeline.
- **Evaluation**: Compares both summarization techniques using ROUGE scores to assess quality.

## 📋 Requirements

- Python 3.7+
- [Google T5](https://huggingface.co/transformers/model_doc/t5.html)
- [SpaCy](https://spacy.io/)
- [YouTube Data API](https://developers.google.com/youtube/v3)

## 🚀 Models and Frameworks
- **Google T5**: Transformer model for abstractive text summarization.
- **SpaCy**: NLP library used for extractive summarization and preprocessing.
- **BERT** (Optional): You can use BERT for additional processing steps if needed.

## 📈 Evaluation
We use ROUGE scores to evaluate and compare the performance of the two summarization methods:

- **Abstractive Summarization (T5)**: Generates human-like, rephrased summaries.
- **Extractive Summarization (SpaCy)**: Extracts key sentences directly from the text.

## 📧 Contact
For questions or feedback, reach out via [LinkedIn](https://www.linkedin.com/in/muhammad-rifat-islam-9ab376230/) or email at rifat010bushral@gmail.com.



