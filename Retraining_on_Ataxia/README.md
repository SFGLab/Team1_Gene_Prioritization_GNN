# geneDRAGNN – Ataxia Variant Prediction

This repository applies the geneDRAGNN graph neural network pipeline to predict gene associations with Hereditary Ataxia.

## 🚀 How to Run

### Train the model
```bash
python train_gnn_model.py

### OR load Trained model
🧪 Model
GNN architecture: SGConv

Input features: 107D Node2Vec embeddings

Output: Binary classification (pathogenic / non-pathogenic)

###📦 Dependencies
Install all packages:

bash
Copy
Edit
pip install -r requirements.txt

###🔁 Reproducibility
To reproduce results:

Download data & embeddings into data/ataxia/

Run training and prediction scripts

Compare output CSVs to your saved copies

