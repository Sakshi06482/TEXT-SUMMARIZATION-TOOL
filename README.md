# TEXT-SUMMARIZATION-TOOL

*COMPANY* : CODTECH IT SOLUTIONS.

*NAME* : SAKSHI PRAKASH PATIL.

*INTERN ID* : CT6MDG1923

*DOMAIN* : Artificial Intelligence

*DURATION* : 6 MONTHS

*MENTOR* : NEELA SANTOSH
 
**Description**

**Project Overview** :

Text summarization is the process of distilling the most important information from a source to produce an abridged version for easier consumption. With the explosion of digital content,
automatic summarization tools are increasingly important in applications like news aggregation, academic research, and report generation.This project uses classic frequency-based summarization 
methods. It tokenizes the text, removes stop words, scores each sentence based on word frequency, and then extracts the top N sentences as the summary.They help users save time, extract critical information, and enhance productivity.
This project demonstrates a basic, frequency-based text summarization approach using Python. The technique focuses on identifying the most significant sentences from the input text using word frequency analysis. The system tokenizes the text, removes common stop words, calculates word frequencies, scores each sentence based on these frequencies, and then selects the top N sentences as the final summary. This makes it a lightweight, beginner-friendly solution ideal for educational use or quick summarization tasks.
This project presents a simple yet effective frequency-based text summarization tool built using Python and classical Natural Language Processing (NLP) techniques. The summarizer works by identifying the most important sentences from a given text using word frequency scoring methods. The final output is a short, readable summary that captures the essential information without needing to process the entire document.

**Importing Libraries**:

Utilizes nltk, re, and heapq for natural language processing, regular expressions, and priority queues respectively.

**Tokenization**:

Splits the text into individual sentences and words using sent_tokenize() and word_tokenize().

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

Open Text_Summarization.ipynb in VS Code and run each cell to test the summarization tool.








