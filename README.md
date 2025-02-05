# Natural-Language-Processing-NPL

## NLP Tasks Using NLTK & spaCy
This repository contains Jupyter notebooks that implement various **Natural Language Processing (NLP)** tasks using two different Python libraries:
- **NLTK (Natural Language Toolkit)**: A traditional NLP library with rule-based approaches.
- **spaCy**: A modern, optimized NLP library with a robust ML-based pipeline.

---
## Repository Contents

### 1**NLTK-Based NLP Tasks**
**File:** `nlp_tasks_using_nltk.ipynb`

This notebook implements core NLP techniques using **NLTK**, including:
- **Sentence Tokenization**: Splitting text into individual sentences.
- **Word Tokenization**: Breaking sentences into words.
- **Stop Word Removal**: Removing common words that add little meaning (e.g., 'the', 'is').
- **Stemming**: Reducing words to their root form (e.g., "running" → "run").
- **Lemmatization**: Using dictionary-based normalization (e.g., "better" → "good").
- **POS Tagging**: Assigning grammatical roles (noun, verb, adjective, etc.).
- **Named Entity Recognition (NER)**: Extracting named entities like people, places, organizations.
- **Frequency Distribution**: Identifying the most common words in a text.
- **Synonyms & Antonyms Extraction**: Finding related words using WordNet.

**How to Run:** Open the Jupyter Notebook and execute each cell in sequence.

---

### 2️**spaCy-Based NLP Tasks**
**File:** `nlp_tasks_using_spaCy.ipynb`

This notebook performs the same NLP tasks as above but using **spaCy**, which offers a more optimized and ML-driven approach.

Implemented tasks:
- **Lemmatization**: Extracting base forms of words using spaCy's built-in lemmatizer.
- **Tokenization**: Efficiently splitting text into tokens (words, punctuation, etc.).
- **Named Entity Recognition (NER)**: Detecting and classifying named entities in text.
- **Sentence Segmentation**: Identifying individual sentences in a document.
- **Stop Word Removal**: Filtering out common words using spaCy's predefined list.
- **POS Tagging**: Assigning part-of-speech labels to each token.
- **Complete NLP Pipeline**: Combining all tasks into a single workflow.

---

## Comparison: NLTK vs. spaCy

| Feature               | **NLTK**  | **spaCy**  |
|----------------------|----------|------------|
| **Processing Speed** | Slower, multiple function calls | Faster, optimized NLP pipeline |
| **Ease of Use**      | Requires manual preprocessing | Simple `nlp(text)` handles everything |
| **NER Accuracy**     | Less accurate, rule-based | More accurate, ML-based |
| **Lemmatization**    | Uses WordNet | Built-in ML-based lemmatizer |
| **POS Tagging**      | Uses predefined rules | Context-aware tagging |
| **Scalability**      | Handles small datasets well | Suitable for large-scale applications |

🔹 **Conclusion:** If we need a **quick rule-based approach**, use **NLTK**. If you need **efficient, scalable, and ML-powered NLP**, use **spaCy**.

---
## Some Important Notes
- **Optimized NLP Pipeline**: An optimized NLP pipeline refers to an efficient and structured workflow that processes raw text through multiple NLP techniques while minimizing computational overhead. In modern NLP libraries like spaCy, the pipeline is pre-optimized to run multiple processing steps (e.g., tokenization, lemmatization, named entity recognition) in a single pass over the text, making it faster and memory-efficient compared to traditional methods.
- In the provided script, spaCy's NLP pipeline is invoked whenever nlp(text) is used in processing steps.
