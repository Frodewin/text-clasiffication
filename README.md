# **NLP Model Evaluation**

## 📌 **Project Overview**
This project focuses on evaluating various deep learning models for text classification. Different word embedding techniques (**Word2Vec, FastText, TF-IDF**) were tested along with recurrent neural network architectures (**LSTM, GRU, SimpleRNN**). The objective is to determine the best-performing model in terms of accuracy and generalization.

## 🏆 **Best Model**  
✅ **FastText + GRU (70/30)**  
- Achieved the highest test accuracy, making it the best-performing model.

## 📂 **Project Structure**
```
├── dictionary/                                               # list of dictionary word (get from wolgarbe SymSpell)
│   ├── frequency_bigramdictionary_en_243_342.txt               # bigram dictionary word
│   ├── frequency_dictionary_en_82_765.txt                      # monogram dictionary word
├── lexicon_slangwords/                                       # list of lexicon MOBA Game and Slangwords
│   ├── lexicon_moba.json                                       # list word and it's score for sentiment (1 positive; 0 neutral; -1 negative)
│   ├── slangwords.json                                         # list of slangwords
├── main_code/                                                # contain source code for training data
│   ├── scraping_code.ipynb                                     # code for scraping review from google-play-scraper
│   ├── submission.ipynb                                        # main code for training data
├── output/                                                   # results get from main_code folder
│   ├── scraping_review_MLBB.csv                                # contain table of review get from scraping
│   ├── typo_words.txt                                          # list of words appears only once in a collection of reviews
│   ├── word_dictionary_fixed.py                                # list of words get from scraping_review_MLBB.csv after correcting typos and writing errors
│   ├── word_dictionary.py                                      # list of words get from scraping_review_MLBB.csv
├── README.md                                                 # Project documentation
├── requirements.txt                                          # Required dependencies
```

## 🚀 **How to Use**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/Frodewin/text-classification.git
cd nlp-model-evaluation
```

### 2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3️⃣ **Run the Model Training & Evaluation**
```bash
python src/submission.py
```

⭐ **Feel free to fork this repository, improve the models, and contribute!** 🚀
