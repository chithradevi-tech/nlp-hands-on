🧹 Text Preprocessing Pipeline To prepare raw text data for Natural Language Processing (NLP) tasks, the following preprocessing steps are commonly applied:

- Case Folding Convert all text to lowercase to ensure uniformity and to treat words like "Apple" and "apple" as identical.

- Remove Special Characters Eliminate non-alphanumeric characters to focus on meaningful words.(regular expression, pandas, spaCy)

- Tokenization Break text into individual words (tokens) for further processing.(SpaCy)

Remove Stop Words Filter out common words (e.g., "the", "is") that don't contribute significant meaning.

Generate N-Grams Create sequences of 'n' consecutive words to capture context.

Vectorization Convert text into numerical representations for machine learning models.

1. Vectorization
   Vectorization refers to the general process of converting data (often text, images, or other types of input) into a numerical vector (a list or array of numbers) that a computer can process.

   Example: Turning the word "cat" into a numerical format like [0, 1, 0, 0, ..., 0] using one-hot encoding.

   This can be simple and sparse, like one-hot encoding or bag-of-words.

   It's a broad term that applies to all types of data.

- Bag of Words (BoW): Represents text as a matrix of token counts.

TF-IDF (Term Frequency-Inverse Document Frequency): Adjusts token counts based on their frequency across documents.

Word Embeddings Represent words in dense vector spaces to capture semantic meanings.

2. Embedding
   An embedding is a specific kind of vectorization. It's a dense and low-dimensional representation of data (especially text, but also images or other entities), where similar items have similar vector representations.

Word Embedding: A word like "king" might be embedded as [0.21, 0.78, -0.34, ..., 0.09] — a real-valued vector.

These vectors capture relationships like:

vector("king") - vector("man") + vector("woman") ≈ vector("queen")

Embeddings are learned from data, often using neural networks (like Word2Vec, GloVe, or BERT).

| Term              | Meaning                                                 | Example                          |
| ----------------- | ------------------------------------------------------- | -------------------------------- |
| **Vectorization** | General process of converting data to numerical vectors | One-hot encoding of words        |
| **Embedding**     | Dense, learned vector representation capturing meaning  | Word2Vec, GloVe, BERT embeddings |

---

Linguistics is the scientific study of language — how it works, how it is structured, how it's used, and how it evolves.

- Phonetics & Phonology

  Sounds of speech (how they're produced and heard).

  Example: Why "cat" and "bat" sound different.

- Morphology

  The structure of words and how they’re formed.

  Example: "Unbreakable" = "un-" + "break" + "-able"

- Syntax

  How words are combined into sentences (grammar rules).

  Example: Why "She loves cats" is correct but "Loves she cats" is not.

- Semantics

  The meaning of words and sentences.

  Example: "Bank" can mean a place for money or a riverbank — context matters.

- Pragmatics

  How language is used in context (tone, intention, social rules).

  Example: "Can you pass the salt?" isn't a question—it's a polite request.

- Sociolinguistics & Psycholinguistics

  How language varies across groups (age, region, class) or how it’s processed in the brain.

---
