🧹 Text Preprocessing Pipeline
To prepare raw text data for Natural Language Processing (NLP) tasks, the following preprocessing steps are commonly applied:

1. Case Folding
   Convert all text to lowercase to ensure uniformity and to treat words like "Apple" and "apple" as identical.

2. Remove Special Characters
   Eliminate non-alphanumeric characters to focus on meaningful words.

3. Tokenization
   Break text into individual words (tokens) for further processing.

4. Remove Stop Words
   Filter out common words (e.g., "the", "is") that don't contribute significant meaning.

5. Generate N-Grams
   Create sequences of 'n' consecutive words to capture context.

6. Vectorization
   Convert text into numerical representations for machine learning models.

Bag of Words (BoW): Represents text as a matrix of token counts.

TF-IDF (Term Frequency-Inverse Document Frequency): Adjusts token counts based on their frequency across documents.

7. Word Embeddings
   Represent words in dense vector spaces to capture semantic meanings.
