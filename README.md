# TEXT-SUMMARIZATION-TOOL

*COMPANY* : CODTECH IT SOLUTIONS.

*NAME* : SAKSHI PRAKASH PATIL.

*INTERN ID* : CT6MDG1923

*DOMAIN* : Artificial Intelligence

*DURATION* : 6 MONTHS

*MENTOR* : NEELA SANTOSH
 
**Description**

**Project Overview** :

Text summarization is the process of distilling the most important information from a source to produce an abridged version for easier consumption. With the explosion of digital content, automatic summarization tools have become increasingly important in applications such as news aggregation, academic research, and report generation.

This project uses classic frequency-based summarization methods to automatically extract key points from any given text. It tokenizes the input, removes stop words, calculates word frequencies, scores each sentence based on those frequencies, and then extracts the top N sentences as the final summary.

Automatic summarization helps users save time, extract critical information efficiently, and improve overall productivity. This project demonstrates a basic, yet practical, frequency-based summarization approach implemented in Python. It focuses on identifying the most significant sentences by analyzing word importance across the document. The approach is lightweight, beginner-friendly, and ideal for educational or personal use.

This summarizer leverages classical Natural Language Processing (NLP) techniques without relying on machine learning or deep learning models. The result is a short, readable summary that effectively captures the essential information from the original content without needing to read the entire document.

**Importing Libraries**:

nltk – Natural Language Toolkit for tokenization and stop word removal.

re – Regular expressions module for text preprocessing.

heapq – Python’s heap queue algorithm to efficiently retrieve top scoring sentences.

**Tokenization**:

Sentence Tokenization: Using sent_tokenize() to divide text into sentences.

Word Tokenization: Using word_tokenize() to split sentences into individual words.

**Stop Word Removal**:

Common English words (like the, is, at) are removed using NLTK's stopwords to retain only meaningful words.

**Word Frequency Calculation**:

Counts the frequency of each word and normalizes it.

**Sentence Scoring**:

Each sentence is scored based on the sum of normalized word frequencies.

Only sentences shorter than 30 words are considered (to avoid overly long summaries).

**Summary Generation**:

The top N highest-scoring sentences are selected using heapq.nlargest() and combined into the final summary.

**Features**:

Simple and beginner-friendly.

Based on classic NLP methods.

Adjustable number of output sentences.

Lightweight – no deep learning or complex models required.

**Launch Notebook**:

To run the project:

Open Text_Summarization.ipynb in Visual Studio Code or Jupyter Notebook.

Run each cell step-by-step.

Enter your input text and specify how many sentences you'd like in the summary.

View the generated summary output.





