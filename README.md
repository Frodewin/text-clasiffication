# **NLP Model Evaluation**

## 📌 **Project Overview**
This project focuses on evaluating various deep learning models for text classification. Different word embedding techniques (**Word2Vec, FastText, TF-IDF**) were tested along with recurrent neural network architectures (**LSTM, GRU, SimpleRNN**). The objective is to determine the best-performing model in terms of accuracy and generalization.

## 🏆 **Best Model**  
✅ **FastText + GRU (70/30)**  
- Achieved the highest test accuracy, making it the best-performing model.

## 📂 **Project Structure**
```
├── data/                 # Dataset files
├── models/               # Saved trained models
├── notebooks/            # Jupyter notebooks for exploration
├── src/                  # Source code for training and evaluation
│   ├── train_model.py    # Model training script
│   ├── evaluate.py       # Model evaluation script
│   ├── preprocess.py     # Data preprocessing utilities
├── requirements.txt      # Required dependencies
├── README.md             # Project documentation
```

## 🚀 **How to Use**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/nlp-model-evaluation.git
cd nlp-model-evaluation
```

### 2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 3️⃣ **Run the Model Training & Evaluation**
```bash
python src/train_model.py
```

## 📜 **License**
This project is open-source and available under the **MIT License**.

---

⭐ **Feel free to fork this repository, improve the models, and contribute!** 🚀
