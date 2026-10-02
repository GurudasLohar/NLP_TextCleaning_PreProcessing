# NLP Text Preprocessing Assignment

## File to submit
NLP_Text_Preprocessing.ipynb

## Dataset
25 product-review style texts (synthetic sample).
Source: created for this assignment (similar to Kaggle review datasets).

## Tasks
1. Inspect raw text, lengths, common issues
2. Basic cleaning -> clean_text_basic
3. Advanced noise removal -> clean_text_advanced
4. Stopword removal -> text_no_stopwords
5. Optional: repeated characters + slang
6. Word & sentence tokenization (3 samples)
7. Porter stemming + comparison
8. WordNet lemmatization + stem vs lemma
9. nlp_preprocess() pipeline -> final_clean_text
10. Observations

## Run
```
pip install nltk pandas
python -c "import nltk; nltk.download('punkt'); nltk.download('punkt_tab'); nltk.download('stopwords'); nltk.download('wordnet'); nltk.download('omw-1.4')"
jupyter notebook NLP_Text_Preprocessing.ipynb
```
