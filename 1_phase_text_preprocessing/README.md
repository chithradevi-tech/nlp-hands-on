**Linguistics**

Linguistics is the scientific study of language — how it works, how it is structured, how it is used, and how it evolves.

**Key Subfields:**

**Phonetics & Phonology**

Study of the sounds of speech — how they are produced and perceived.
Example: Why “cat” and “bat” sound different.

**Morphology**

The structure of words and how they are formed.
Example: “Unbreakable” = “un-” + “break” + “-able”.

**Syntax**

How words are combined into sentences according to grammar rules.
Example: Why “She loves cats” is correct but “Loves she cats” is not.

**Semantics**

The meaning of words and sentences.
Example: “Bank” can mean a place for money or a riverbank — context matters.

**Pragmatics**

How language is used in context, including tone, intention, and social rules.
Example: “Can you pass the salt?” isn’t really a question — it’s a polite request.

**Sociolinguistics & Psycholinguistics**

Study of how language varies across social groups (age, region, class) and how it is processed in the brain.

---

🧹 Text Preprocessing Pipeline To prepare raw text data for Natural Language Processing (NLP) tasks, the following preprocessing steps are commonly applied:

- **Case Folding:** Convert all text to lowercase to ensure uniformity and to treat words like "Apple" and "apple" as identical (using Pandas .str.lower() or Python .lower()).
- **Remove Special Characters:** Eliminate non-alphanumeric characters to focus on meaningful words (using regular expressions, Pandas .str.replace()).
- **Tokenization:** Split text into smaller units, like words or sentences (using nltk.word_tokenize, nltk.sent_tokenize or str.split())
- **Stemming / Lemmatization:**  Reduce words to their root or base form (using NLTK's token.lemma_)
- **Stop Words:** Remove common, non-essential words (e.g., "the", "and", "is") (using NLTK’s stopwords corpus)
- **POS Tagging:** Identify grammatical roles of words (nouns, verbs, adjectives, etc.) (using NLTK’s pos_tag or spaCy’s token.pos_ / token.tag_ attributes).
- **Expand Contractions:** Replace contractions like "don't" with "do not" to standardize text (using the contractions package or custom mapping).
---
