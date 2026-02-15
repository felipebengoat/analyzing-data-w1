# Week 1: NLP Analysis with NLTK and spaCy

## Course
Analyzing Data - University of Groningen

## Description
This project contains NLP exercises including:
- **Part 1.1**: Sentence splitting, word tokenization, and word frequency analysis
- **Part 1.2**: Stemming comparison (Porter vs Lancaster)
- **Part 1.3**: POS-tagging analysis on multilingual texts (English, Dutch, German)
- **Part 2**: Named Entity Recognition (NER) evaluation

## Project Structure
```
├── data/
│   ├── Part_1/          # 5 story texts
│   └── Part_2/          # Tom Sawyer translations (EN, NL, DE)
├── notebooks/
│   └── W1_NLP_Analysis.ipynb
├── requirements.txt
└── README.md
```

## Setup

### 1. Create conda environment
```bash
conda create -n nlp-analysis python=3.11
conda activate nlp-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download spaCy models
```bash
python -m spacy download en_core_web_sm
python -m spacy download nl_core_news_sm
python -m spacy download de_core_news_sm
```

### 4. Run Jupyter
```bash
jupyter notebook