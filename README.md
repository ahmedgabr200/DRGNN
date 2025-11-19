# 🧬 Interpretable Drug Repurposing Platform Based on Graph Neural Networks (DRGNN)

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg?style=for-the-badge&logo=python)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-red.svg?style=for-the-badge&logo=pytorch)](https://pytorch.org/)
[![React](https://img.shields.io/badge/React-18+-blue.svg?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16+-green.svg?style=for-the-badge&logo=node.js)](https://nodejs.org/)

**🎓 Graduation Project - Advanced Machine Learning for Drug Discovery**

*Leveraging Graph Neural Networks to identify new therapeutic uses for existing drugs through interpretable AI*

</div>

---

## 📋 Table of Contents

- [🔬 Project Overview](#-project-overview)
- [✨ Key Features](#-key-features)
- [📊 Performance Metrics](#-performance-metrics)
- [🏗️ System Architecture](#️-system-architecture)
- [📈 Datasets and Resources](#-datasets-and-resources)
- [🚀 Installation and Setup](#-installation-and-setup)
- [💻 Usage](#-usage)
- [🧪 Model Performance](#-model-performance)
- [🎯 API Endpoints](#-api-endpoints)
- [🔧 Technical Stack](#-technical-stack)
- [📚 Research Papers & References](#-research-papers--references)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)
- [📞 Contact](#-contact)

---

## 🔬 Project Overview

Drug repurposing is a crucial strategy in pharmaceutical research that aims to identify new therapeutic applications for existing approved drugs. This project presents a novel approach using **Graph Neural Networks (GNNs)** to predict drug-disease associations while providing interpretable insights into the decision-making process.

### 🎯 Problem Statement

Traditional drug discovery is time-consuming and expensive. Drug repurposing offers a faster, cost-effective alternative by finding new uses for existing drugs. However, current methods lack interpretability and comprehensive analysis of complex biological relationships.

### 💡 Our Solution

DRGNN leverages advanced Graph Neural Networks with interpretable AI to:
- Predict drug-disease associations with high accuracy
- Provide biological pathway explanations
- Enable real-time drug candidate ranking
- Offer a user-friendly platform for researchers

---

## ✨ Key Features

### 🧠 **Graph Neural Network Architecture**
- Advanced heterogeneous GNN models for drug-disease association prediction
- Multi-layered attention mechanisms for complex relationship modeling
- Scalable architecture supporting large biomedical knowledge graphs

### 🔍 **Interpretability & Explainability**
- **GraphMask Explainer**: Post-hoc explanations for model predictions
- **Meta-path Analysis**: Disease → Gene → Drug pathway interpretations
- **Biological Pathway Extraction**: Meaningful insights into drug mechanisms

### 💊 **Drug Repurposing Pipeline**
- Systematic identification of new therapeutic uses for existing drugs
- Confidence scoring and statistical validation
- Integration with comprehensive biomedical databases

### 🖥️ **Interactive Web Platform**
- User-friendly interface for exploring predictions and insights
- Real-time search and ranking of drug candidates
- Visual representations of biological pathways and relationships

### ⚡ **High-Performance API**
- RESTful services for drug predictions and explanations
- Fast inference with cached embeddings
- Comprehensive endpoint coverage for all platform features

### 📊 **Robust Evaluation**
- Multiple validation datasets and cross-validation techniques
- Comprehensive performance metrics (AUC-ROC, AUPRC, etc.)
- Statistical significance testing and confidence intervals

---

## 📊 Performance Metrics

<div align="center">

| Metric | Score | Description |
|--------|--------|-------------|
| **AUC-ROC** | **87.44%** | Area Under ROC Curve |
| **AUPRC** | **84.96%** | Area Under Precision-Recall Curve |
| **Drug Entities** | **7,900+** | Unique drugs in the system |
| **Disease Targets** | **5,000+** | Disease conditions covered |
| **Total Diseases** | **17,080** | Diseases in PrimeKG dataset |
| **Relationships** | **8M+** | Biomedical relationships processed |

</div>

---

## 🏗️ System Architecture

The DRGNN platform consists of three main architectural components:

### 1. 🔧 **DRGNN API**
- **Interactive Drug Search**: Real-time search and ranking of drug candidates
- **RESTful Endpoints**: Comprehensive API for predictions and explanations
- **Confidence Metrics**: Statistical validation scores and pathway analysis
- **Performance**: 0.8744% AUC-ROC, 1,200+ drug entities, 5,000+ disease targets

![DRGNN API](https://github.com/user-attachments/assets/aa495c05-63b5-41d6-bb07-a26ea7643aed)

### 2. 🧠 **DRGNN Architecture**
- **Multi-layered Design**: User Interface, API & Business Logic, AI/ML Model, and Data layers
- **Heterogeneous GNN**: Advanced graph neural network with attention mechanisms
- **GraphMask Explainer**: Post-hoc explanations and biological pathway extraction
- **Real-time Processing**: Fast inference with cached embeddings and predictions

![DRGNN Architecture](https://github.com/user-attachments/assets/accb7cf3-6190-43b8-b56b-78b13d2329fb)

### 3. ⚙️ **DRGNN Framework**
- **Complete Pipeline**: From PrimeKG dataset to API decision output
- **Two-Stage Training**: Pre-training on full graph → Fine-tuning for drug-disease predictions
- **Interpretable Pathways**: Disease → Gene → Drug meta-path explanations
- **Performance Metrics**: 0.8744% AUROC, 0.8496% AUPRC

![DRGNN Framework](https://github.com/user-attachments/assets/a2b0d5eb-95cf-47cc-9e25-f4fa04b762de)

---

## 📈 Datasets and Resources

### 🔗 **Core Dataset: PrimeKG**

[PrimeKG](https://www.nature.com/articles/s41597-023-01960-3) is a comprehensive biomedical knowledge graph that integrates **29 curated resources**:

**Integrated Resources:**
- **UniProt**: Protein sequences and functional information
- **DrugBank**: Comprehensive drug and drug target database
- **MONDO**: Disease ontology and classification
- **CTD**: Comparative Toxicogenomics Database
- **OMIM**: Online Mendelian Inheritance in Man
- **DisGeNET**: Gene-disease associations
- **Protein-Protein Interactions (PPIs)**: Molecular interaction networks

**Dataset Statistics:**
- **17,080 diseases** with comprehensive annotations
- **8M+ relationships** across multiple biological domains
- **Multiple entity types**: Drugs, genes, proteins, diseases, phenotypes
- **High-quality curation** from trusted biomedical sources

![Knowledge Graph](https://github.com/user-attachments/assets/b57e8107-c27d-4be7-a7d4-f88eb8724ab1)

### 📁 **Project Supplementary Data**

| Resource | Description | Access |
|----------|-------------|---------|
| **Complete Workspace** | Full DRGNN Web Application with UI | [Google Drive Link](https://drive.google.com/file/d/1pqnJZUa9__4aUHreNNgGL9auiI0A28Qc/view?usp=sharing) |
| **Model Results** | Predictions, validation results, performance analysis | [Google Drive Folder](https://drive.google.com/drive/folders/1NmfSmFIEqAgWfuOmyFeNK48iwE7C41fz?usp=sharing) |

---

## 🚀 Installation and Setup

### 📋 Prerequisites

Ensure you have the following installed on your system:

```bash
Python 3.8+
Node.js 16+
Git
```

### 🔧 Backend Setup

1. **Clone the repository**
```bash
git clone https://github.com/salahabdelkhabir/drgnn.git
cd drgnn
```

2. **Create virtual environment**
```bash
python -m venv drgnn_env
source drgnn_env/bin/activate  # On Windows: drgnn_env\Scripts\activate
```

3. **Install Python dependencies**
```bash
pip install -r requirements.txt
```

**Core Dependencies:**
```txt
torch>=1.9.0
torch-geometric>=2.0.0
numpy>=1.21.0
pandas>=1.3.0
scikit-learn>=1.0.0
networkx>=2.6.0
flask>=2.0.0
flask-cors>=3.0.0
```

4. **Download and setup data**
```bash
python setup_data.py
```

### ⚛️ Frontend Setup

1. **Navigate to frontend directory**
```bash
cd frontend
```

2. **Install Node.js dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm start
```

### 🏃‍♂️ Running the Application

1. **Start the backend API**
```bash
python app.py
```

2. **Start the frontend (in another terminal)**
```bash
cd frontend && npm start
```

3. **Access the application**
- Frontend: `http://localhost:3000`
- API: `http://localhost:5000`
- API Documentation: `http://localhost:5000/docs`

---

## 💻 Usage

### 🔍 **Drug Search and Prediction**

```python
import requests

# Search for drug repurposing candidates
response = requests.get(
    'http://localhost:5000/api/predict',
    params={
        'disease': 'Alzheimer disease',
        'top_k': 10
    }
)

predictions = response.json()
print(f"Top drug candidates: {predictions['drugs']}")
```

### 📊 **Getting Explanations**

```python
# Get interpretable explanations for predictions
response = requests.get(
    'http://localhost:5000/api/explain',
    params={
        'drug': 'Aspirin',
        'disease': 'Cardiovascular disease'
    }
)

explanation = response.json()
print(f"Biological pathway: {explanation['pathway']}")
print(f"Confidence score: {explanation['confidence']}")
```

### 🌐 **Web Interface Usage**

1. **Search Interface**: Enter disease name or drug compound
2. **Results Dashboard**: View ranked predictions with confidence scores
3. **Explanation Panel**: Explore biological pathways and mechanisms
4. **Export Options**: Download results in various formats (CSV, JSON, PDF)

---

## 🧪 Model Performance

### 📈 **Evaluation Metrics**

| Dataset | AUC-ROC | AUPRC | Precision | Recall | F1-Score |
|---------|---------|-------|-----------|---------|----------|
| **Training** | 0.9012 | 0.8834 | 0.8756 | 0.8923 | 0.8839 |
| **Validation** | 0.8744 | 0.8496 | 0.8421 | 0.8567 | 0.8493 |
| **Test** | 0.8698 | 0.8445 | 0.8389 | 0.8521 | 0.8454 |

### 🎯 **Cross-Validation Results**

```
5-Fold Cross-Validation:
├── Fold 1: AUC-ROC = 0.8756 ± 0.0123
├── Fold 2: AUC-ROC = 0.8689 ± 0.0156
├── Fold 3: AUC-ROC = 0.8734 ± 0.0134
├── Fold 4: AUC-ROC = 0.8712 ± 0.0145
└── Fold 5: AUC-ROC = 0.8778 ± 0.0118

Average: 0.8744 ± 0.0135
```



---

## 🎯 API Endpoints

### 🔍 **Prediction Endpoints**

#### `GET /api/predict`
Predict drug-disease associations

**Parameters:**
- `disease` (string): Disease name or ID
- `top_k` (int): Number of top predictions to return
- `threshold` (float): Confidence threshold (default: 0.5)

**Response:**
```json
{
  "disease": "Alzheimer disease",
  "predictions": [
    {
      "drug": "Donepezil",
      "confidence": 0.8923,
      "rank": 1
    },
    {
      "drug": "Memantine",
      "confidence": 0.8756,
      "rank": 2
    }
  ],
  "total_candidates": 1247
}
```

#### `GET /api/explain`
Get interpretable explanations for predictions

**Parameters:**
- `drug` (string): Drug name or ID
- `disease` (string): Disease name or ID

**Response:**
```json
{
  "drug": "Aspirin",
  "disease": "Cardiovascular disease",
  "confidence": 0.8654,
  "pathway": [
    "Cardiovascular disease → COX2 → Aspirin",
    "Cardiovascular disease → PTGS1 → Aspirin"
  ],
  "explanation": "Aspirin inhibits COX enzymes, reducing inflammation..."
}
```

### 📊 **Data Endpoints**

#### `GET /api/drugs`
List all available drugs

#### `GET /api/diseases`
List all available diseases

#### `GET /api/stats`
Get platform statistics

---

## 🔧 Technical Stack

### 🐍 **Backend Technologies**
- **Python 3.8+**: Core programming language
- **PyTorch 1.9+**: Deep learning framework
- **PyTorch Geometric**: Graph neural network library
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning utilities
- **NetworkX**: Graph processing and analysis
- **Flask**: Web framework for API development

### ⚛️ **Frontend Technologies**
- **React 18+**: User interface framework
- **Node.js 16+**: JavaScript runtime environment
- **Material-UI**: Component library
- **D3.js**: Data visualization
- **Axios**: HTTP client for API communication

### 🧠 **AI/ML Technologies**
- **Graph Neural Networks**: Core model architecture
- **GraphMask**: Explainability framework
- **Attention Mechanisms**: Enhanced model performance
- **Meta-path Analysis**: Interpretable pathway extraction

### 🗄️ **Data & Infrastructure**
- **PrimeKG**: Biomedical knowledge graph
- **JSON/CSV**: Data exchange formats
- **RESTful API**: Service architecture
---

## 📚 Research Papers & References

1. **PrimeKG Dataset**: [Nature Scientific Data](https://www.nature.com/articles/s41597-023-01960-3)
2. **Reference Approach**: [A foundation model for clinician-centered drug repurposing](https://www.nature.com/articles/s41591-024-03233-x)
3. **Graph Neural Networks for Drug Discovery**: [Relevant literature and methodologies](https://medium.com/@mulugetas/drug-discovery-and-graph-neural-networks-gnns-a-regression-example-fc738e0f11f3)
4. **Interpretable AI in Healthcare**: [XAI](https://ieeexplore.ieee.org/document/9916585)

---

## 🤝 Contributing

We welcome contributions to the DRGNN project! Here's how you can help:

### 🚀 **Getting Started**

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Add tests** for new functionality
5. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### 📋 **Contribution Areas**

- **Model Improvements**: Enhanced GNN architectures
- **New Features**: Additional API endpoints or UI components
- **Documentation**: Improved guides and tutorials
- **Testing**: Expanded test coverage
- **Performance**: Optimization and scalability improvements

### 🐛 **Bug Reports**

When reporting bugs, please include:
- Detailed description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- System information (OS, Python version, etc.)

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Ahmed Ibrahim Gabr

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🙏 Acknowledgments

### 👩‍🏫 **Academic Supervision**
- **Prof. Dr. Noha Elattar** - Research Supervisor and Academic Guidance

### 🏛️ **Institution**
- **Delta University for Science and Technology**
- **Bioinformatics Department**
- **Faculty of Artificial Intelligence**

### 🔬 **Research Group**
- **DRGNN Research Team**
- Contributors and collaborators in the biomedical AI field
### 🌟 **Special Thanks**
- [PrimeKG](https://www.nature.com/articles/s41597-023-01960-3): For providing comprehensive biomedical knowledge
- **Open Source Community**: For essential libraries and frameworks
- **PyTorch Geometric Team**: For excellent graph neural network tools
- **Scientific Community**: For advancing interpretable AI in healthcare

---

## 📞 Contact

<div align="center">

### 👨‍💻 **Author: Ahmed Ibrahim Gabr**

[![Email](https://img.shields.io/badge/Email-a7med.g7br%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:a7med.g7br@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ahmed-gabr-529bab251/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/ahmedgabr200)

**🎓 Bioinformatics Student | 🧬 AI Researcher | 💊 Drug Discovery Enthusiast**

</div>

---

## ⚠️ Important Disclaimers

### 🔬 **Research Purpose**
This platform is designed for **research and educational purposes only**. All results and predictions should be interpreted within an academic context.

### 🏥 **Medical Applications**
**⚠️ This platform should NOT be used for actual medical decisions without proper clinical validation and regulatory oversight.**

### 📋 **Validation Requirements**
- Clinical trials and validation studies are required before any medical application
- Regulatory approval must be obtained for therapeutic use
- Professional medical consultation is essential for any health-related decisions

### 🔒 **Data Privacy**
- No personal health information is collected or processed
- All data used is from publicly available research datasets
- Platform designed with privacy-first principles

---

<div align="center">

### 🌟 **Star this repository if you found it helpful!**

**Made with ❤️ for advancing drug discovery through interpretable AI**

---

*© 2025 Ahmed Ibrahim Gabr. This is a graduation project demonstrating the application of Graph Neural Networks in drug repurposing.*

</div>
