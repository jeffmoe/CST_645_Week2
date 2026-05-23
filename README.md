# CST_645_Week2
Assignment working with spaCy and NLTK to perform common text pre-processing tasks.

## Overview
This project demonstrates fundamental text preprocessing techniques for Natural Language Processing (NLP) using Python. It compares implementations using **NLTK** and **spaCy** libraries across multiple preprocessing stages, including tokenization, stop word removal, normalization, lemmatization, and stemming.

---
## Features

- **Tokenization** with NLTK and spaCy
- **Stop word removal** using both libraries
- **Normalization** (lowercasing, punctuation removal, contraction expansion)
- **Lemmatization** with spaCy
- **Stemming** with NLTK PorterStemmer
- **Performance benchmarking** using `timeit`
- **Pipeline optimization** for better preprocessing results

---

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/text-processing-python.git
cd text-processing-python

# Install required packages
pip install nltk spacy pandas numpy contractions

# Download spaCy English model
python -m spacy download en_core_web_sm

# Download NLTK data
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt_tab')"
```

---

## Dependencies
 - Python 3.10+
 - NLTK
 - spaCy
 - pandas
 - numpy
 - contractions

---
