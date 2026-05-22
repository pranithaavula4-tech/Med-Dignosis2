# MedPharmAI Drug Discovery Models

AI-powered drug discovery and protein analysis models using Reinforcement Learning, Transformers, and Protein Structure Visualization.

---

# Included Models

## 1. Reinforcement Learning Drug Generator

A generative AI model that creates novel drug-like molecules using reinforcement learning and SMILES generation.

### Features
- De-novo drug molecule generation
- SMILES sequence generation
- Reinforcement learning optimization
- Molecular property prediction
- Drug candidate generation

### Technologies
- Python
- PyTorch
- RDKit
- NumPy
- Pandas

### Dataset
- ChEMBL Dataset
- JAK2 Dataset
- logP Dataset

---

## 2. Protein 3D Structure Visualizer

AI-powered protein structure visualization system for rendering and analyzing 3D protein structures.

### Features
- Protein structure rendering
- PDB visualization
- 3D molecular interaction view
- Protein folding visualization
- ESMFold integration

### Technologies
- Python
- Py3Dmol
- Biopython
- ESMFold
- Flask

### Supported Formats
- `.pdb`
- Protein sequences
- FASTA

---

## 3. Protein to SMILES Converter

Transformer-based sequence-to-sequence model that converts protein sequences into SMILES molecular structures.

### Features
- Protein sequence encoding
- SMILES generation
- Transformer encoder-decoder architecture
- Molecular structure prediction
- Drug discovery support

### Technologies
- PyTorch
- Transformers
- RDKit
- Tokenizers
- Flask

### Dataset
- BindingDB
- Protein-SMILES paired datasets

---

# Project Structure

```bash
project/
│
├── reinforcement_learning/
│   ├── train.py
│   ├── generate.py
│   └── model/
│
├── protein_visualizer/
│   ├── app.py
│   ├── viewer.py
│   └── pdb_files/
│
├── protein_to_smiles/
│   ├── train.py
│   ├── inference.py
│   └── transformer/
│
├── requirements.txt
└── README.md
```

---

# Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

# requirements.txt

```txt
flask
flask-cors
numpy
pandas
matplotlib
torch
torchvision
transformers
tokenizers
rdkit
scikit-learn
biopython
py3Dmol
esm
tqdm
```

---

# Environment Setup

## Step 1 — Clone Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

---

## Step 2 — Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Step 3 — Install Requirements

```bash
pip install -r requirements.txt
```

---

# How to Start Models

---

# 1. Reinforcement Learning Drug Generator

## Train Model

```bash
python reinforcement_learning/train.py
```

## Generate Molecules

```bash
python reinforcement_learning/generate.py
```

### Output
- Generated SMILES strings
- Optimized drug candidates
- Molecular property scores

---

# 2. Protein 3D Structure Visualizer

## Start Flask Server

```bash
python protein_visualizer/app.py
```

Server runs on:

```txt
http://127.0.0.1:5000
```

## Upload Protein File
Upload:
- `.pdb`
- FASTA sequence

to visualize protein structures.

---

# 3. Protein to SMILES Converter

## Train Transformer Model

```bash
python protein_to_smiles/train.py
```

## Run Inference

```bash
python protein_to_smiles/inference.py
```

### Input
Protein sequence

### Output
Predicted SMILES notation

---

# Model Workflow

| Model | Input | Output |
|---|---|---|
| Reinforcement Learning | SMILES seed | Generated drug molecules |
| Protein Visualizer | PDB / FASTA | 3D protein structure |
| Protein to SMILES | Protein sequence | SMILES molecule |

---

# Applications

- Drug Discovery
- Protein Engineering
- Molecular Design
- Pharmaceutical Research
- Computational Biology
- AI-assisted Chemistry

---

# Future Improvements

- Docker deployment
- AWS hosting
- Real-time inference API
- Multi-protein prediction
- Molecular optimization
- Attention visualization

---

# Author

Avula Pranitha

---

# License

MIT License
