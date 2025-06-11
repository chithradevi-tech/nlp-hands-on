🧹 Text Preprocessing Pipeline To prepare raw text data for Natural Language Processing (NLP) tasks, the following preprocessing steps are commonly applied:

- **Case Folding:** Convert all text to lowercase to ensure uniformity and to treat words like "Apple" and "apple" as identical (using Pandas .str.lower() or Python .lower()).

- **Remove Special Characters:** Eliminate non-alphanumeric characters to focus on meaningful words (using regular expressions, Pandas .str.replace()).

- Tokenization Break text into individual words (tokens) for further processing.(SpaCy)

- Remove Stop Words Filter out common words (e.g., "the", "is") that don't contribute significant meaning.

---
