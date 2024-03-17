# Question Generation using NLP

## Overview

This project aims to generate various types of questions from given text or context using Natural Language Processing (NLP) techniques. It encompasses three main functionalities:

1. **False Statement Generation:** Given a true statement, this part of the project generates false statements by splitting sentences, completing them using the GPT-2 language model, and altering the context to create deceptive alternatives.

2. **Fill-in-the-Blanks Question Generation:** It extracts important keywords from the text, replaces them with blanks, and presents the resulting fill-in-the-blank questions.

3. **Text-to-MCQ Question Generation:** Summarizes the text, extracts keywords, generates multiple-choice questions (MCQs) from them, and provides distractors to accompany the correct answers.

## Algorithms Used

- **False Statement Generation:**
  - NLP Constituency Parsing
  - Sentence Splitting
  - GPT-2 Sentence Completion

- **Fill-in-the-Blanks Question Generation:**
  - Keyword Extraction (PKE Library)
  - Keyword Replacement
  - HTML Display

- **Text-to-MCQ Question Generation:**
  - Summarization with Paraphrasing (T5 Transformer)
  - MCQ Question Generation (T5 Masked Language Modeling)
  - Distractor Generation (Sense2Vec)

## Screenshot

Here are some screenshots of the Movie Recommender System as per input:

   <img src='MovieRecommender/Screenshot (352).png' >
  <img src='MovieRecommender/Screenshot (353).png' >

## Examples

- **False Statement Generation:**
  - Input: "The sky is blue."
  - Output: "The sky is not blue."

- **Fill-in-the-Blanks Question Generation:**
  - Input: "The capital of France is Paris."
  - Output: "The capital of ___ is Paris."

- **Text-to-MCQ Question Generation:**
  - Input: "Albert Einstein was a famous physicist."
  - Output: "Who was a famous physicist?"
    - A. Albert Einstein
    - B. Isaac Newton
    - C. Marie Curie
    - D. Nikola Tesla

## Contributors

- Rohit Raj
## Acknowledgments

We'd like to express our gratitude to the Streamlit, Scikit-learn, Pandas,NumPy,NLP,AllenNLP,wordvector,sense2vec,T5 transformer,TFGPT2LMHeadmodel, GPT2tokenizer,communities for their invaluable open-source contributions and support.

## Contact

If you have any questions, suggestions, or need assistance, please feel free to reach out.Please open an issue on the GitHub repository or contact us at rohitra.iitd4@gmail.com
