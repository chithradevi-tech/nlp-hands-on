Text Representation (Vectorization)

Vectorization is the process of converting text data into numeric data so that
future data analysis and machine learning techniques can be applied
• Most ML techniques require text data to be cleaned, normalized and in a numeric format
• Some techniques, such as sentiment analysis, require text data to be in its raw text form

Count Vectorization
TF-IDF Vectorization
Embeddings

DF
Clean, normalized text is vectorized as a Document-Term Matrix (DTM)
• Each row represents a document, and each column represents a term
• The values within the DTM can be word counts, TF-IDF scores, or other calculated values

A DTM is a bag of words representation of text, where each document is
represented by how often certain words appear, regardless of word order

🧠 What Are Word Embeddings?
Word embeddings are a way to turn words into numbers, so computers can understand them.

But not just any numbers — these numbers (called vectors) are smart:

Words with similar meanings get similar numbers.

Words like “cat”, “dog”, and “pet” will have vectors that are close together.

Words like “car” and “apple” will be far apart.

🧩 Why Use Word Embeddings?
Let’s say you want a computer to understand that:

“king” and “queen” are related

“king” and “apple” are not

Word embeddings make this possible by putting each word in a map of meaning.

🧺 What is Bag of Words?
Bag of Words is a basic way to turn text into numbers for machine learning.

It:

Ignores grammar and word order

Just counts how many times each word appears in the text

Imagine you put all the words from your sentences into a "bag", mix them up, and count each word. That’s why it’s called "Bag of Words".
