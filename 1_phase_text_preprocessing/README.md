🧹 Text Preprocessing Pipeline To prepare raw text data for Natural Language Processing (NLP) tasks, the following preprocessing steps are commonly applied:

- **Case Folding:** Convert all text to lowercase to ensure uniformity and to treat words like "Apple" and "apple" as identical (using Pandas .str.lower() or Python .lower()).
- **Remove Special Characters:** Eliminate non-alphanumeric characters to focus on meaningful words (using regular expressions, Pandas .str.replace()).
- **Tokenization:** Split text into smaller units, like words or sentences (using nltk.word_tokenize, nltk.sent_tokenize or str.split())
- **Stemming / Lemmatization:**  Reduce words to their root or base form (using NLTK's token.lemma_)
- **Stop Words:** Remove common, non-essential words (e.g., "the", "and", "is") (using NLTK’s stopwords corpus)
- **POS Tagging:** Identify grammatical roles of words (nouns, verbs, adjectives, etc.) (using NLTK’s pos_tag or spaCy’s token.pos_ / token.tag_ attributes).
- **Expand Contractions:** Replace contractions like "don't" with "do not" to standardize text (using the contractions package or custom mapping).
---
