# N-Gram Language Modeling and Story Generation using NLTK, RAG and Google Gemini

## Project Description
This project involves building an n-gram language model using NLTK's Brown corpus and extends to modern NLP techniques such as Retrieval-Augmented Generation (RAG). The workflow covers:

- Creating an n-gram language model (bigram or trigram).
- Predicting the next word given an input phrase.
- Generating multiple sentences starting with a given phrase.
- Calculating the probabilities of generated sentences.
- Computing the perplexity of the language model.
- Using Retrieval-Augmented Generation (RAG) techniques to improve language understanding and generation.
- Integrating the Google Gemini API to generate a story based on generated sentences, ensuring the story contains no derogatory, toxic, violent, hateful, or sexual content.

---

## Skills Demonstrated

- **Natural Language Processing (NLP):** Statistical language modeling, sentence generation, probability and perplexity calculations.
- **Retrieval-Augmented Generation (RAG):** Combining retrieval techniques with generative models to enhance contextual relevance.
- **Python Programming:** Using NLTK, NumPy, and requests for API calls.
- **Corpus Handling:** Using NLTK’s Brown corpus as the base dataset.
- **API Integration:** Working with Google Gemini API for controlled story generation.
- **Model Evaluation:** Calculating and interpreting perplexity of language models.
- **Content Safety:** Ensuring generated text is free from toxic or harmful language.

---

## Project Structure

- `ngram_model.py` — Code for building the n-gram language model and sentence generation.
- `probability_calculation.py` — Functions for calculating sentence probabilities and perplexity.
- `story_generation.py` — Code to interface with Google Gemini API to generate stories.
- `main.py` — Main script running all steps in sequence.

---

## How to Run

1. Install required Python packages:

   ```bash
   pip install nltk numpy requests
2. Download the Brown corpus if not already downloaded:

    ```bash
    import nltk
    nltk.download('brown')

3. Run the main script:
      ```bash
      python main.py

## References
- NLTK Brown corpus documentation: https://www.nltk.org/howto/corpus.html

- Analytics Vidhya comprehensive guide on n-gram language models:
https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-language-model-nlp-python-code/

- Google Gemini API documentation and usage examples (internal/Lab reference)
