
# Summarization of Legal and News Documents

This project fine-tunes transformer-based models to perform abstractive summarization on two domains: legal texts (e.g., court judgments) and news articles. The goal is to generate concise and accurate summaries using pre-trained models like BART and T5.

---

## 📌 Objectives

- Preprocess legal and news datasets (e.g., BillSum, MultiNews).
- Fine-tune pre-trained models (`facebook/bart-base`, etc.).
- Evaluate model performance using ROUGE, BLEU, and BERTScore.
- Analyze domain-specific summarization challenges and outputs.

---

## 📁 Project Structure

```
legal-news-summarization/
├── Summarization of Legal and News Documents.ipynb
├── README.md
└── requirements.txt
```

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/legal-news-summarization.git
cd legal-news-summarization
pip install -r requirements.txt
```

### 2. Open the Notebook

```bash
jupyter notebook "Summarization of Legal and News Documents.ipynb"
```

---

## 📊 Technologies Used

- **Python 3**
- **Hugging Face Transformers** – for pre-trained summarization models
- **Datasets (BillSum, MultiNews)** – for training and evaluation
- **Scikit-learn** – for metrics
- **Matplotlib & Seaborn** – for analysis
- **Jupyter Notebook** – for experimentation

---

## 📈 Workflow

1. **Data Preparation**
   - Load legal/news datasets
   - Text cleaning and formatting

2. **Model Fine-Tuning**
   - Load pre-trained transformer
   - Train on custom dataset

3. **Evaluation**
   - ROUGE-1, ROUGE-2, ROUGE-L
   - BLEU score
   - BERTScore

4. **Analysis**
   - Compare results across domains
   - Visualize summary quality

---

## ✅ Sample Output

- Model-generated summaries of court decisions and articles
- Evaluation metrics (ROUGE, BLEU, BERTScore)
- Visual inspection of sample predictions

---

## 🔄 Future Work

- Introduce domain adaptation techniques
- Integrate summarization into legal case search tools
- Improve factual consistency with knowledge-augmented models

---

## 🙌 Acknowledgements

- Hugging Face for pre-trained models and dataset APIs
- BillSum and MultiNews datasets for legal/news summarization
