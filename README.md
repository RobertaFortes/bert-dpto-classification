# Fine-tuning department classification
Message Classification: Support vs. Sales (BERT PT-BR)

Training a BERT model (Portuguese) to classify customer messages into two categories:
• Support: questions, problems, exchange, warranty, installation, etc.
• Sales: purchase intent, price, promotion, availability, etc.

The project uses Hugging Face Transformers + Datasets and reads data directly from JSONL.

## 🗂 Project Structure

```
.
├── notebooks/
│   └── fine_tuning.ipynb           # notebook (Colab-ready) do treino/avaliação
├── data/
│   ├── treino.jsonl                # dataset de treino (prompt, completion)
│   └── teste.jsonl                 # dataset de teste/validação
├── requirements.txt
├── README.md
└── .gitignore
```

## 🧰 Requirements
- Python 3.10+
- requirements.txt

 ## 📦 Installation

```bash
pip install -r requirements.txt
```
