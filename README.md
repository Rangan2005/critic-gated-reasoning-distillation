# Critic-gated-reasoning-distillation

## 📚 Datasets & Notebooks

### 1. **Crictic-Gated_Path_VQA.ipynb**
Investigation of causal pathways in visual question answering, analyzing how image regions contribute to answer generation.

### 2. **Critic-Gated_SLAKE.ipynb**
Causal analysis applied to the SLAKE dataset (Chinese medical VQA dataset). Explores causal relationships in multilingual medical QA scenarios.

### 3. **Critic-Gated_VQA_RAD.ipynb**
Causal inference experiments on the RAD (Radiology) dataset, focusing on radiology-specific visual question answering tasks.

## 🎯 Key Research Areas

- **Medical VQA**: Domain-specific visual understanding for medical images
- **Knowledge Distillation**: Transferring knowledge from larger models to smaller, more efficient ones
- **Multi-dataset Analysis**: Evaluation across diverse medical VQA benchmarks (PathVQA, SLAKE, RAD)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries (see individual notebooks for imports):
  - PyTorch
  - torchvision
  - pandas, numpy
  - matplotlib, seaborn

### Usage

1. Clone the repository:
```bash
git clone repository_link
cd critic-gated-reasoning-distillation
```

2. Open and run the notebooks in Jupyter:
```bash
jupyter notebook
```

3. Select the notebook corresponding to your dataset of interest:
* Causal_Path_VQA.ipynb - for PathVQA dataset experiments
* Causal_SLAKE.ipynb - for SLAKE dataset experiments
* Causal_VQA_RAD.ipynb - for RAD dataset experiments
