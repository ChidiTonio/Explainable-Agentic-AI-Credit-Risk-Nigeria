# Explainable-Agentic-AI-Credit-Risk-Nigeria
# An Explainable Agentic AI Framework for Credit Risk Prediction in Digital Finance Platforms

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/notebooks/colab_main_experiment.ipynb)

## 📌 Overview
This repository contains the official implementation for the paper: **"An Explainable Agentic AI Framework for Credit Risk Prediction in Digital Finance Platforms"**, tailored for emerging markets with a specific focus on the **Nigerian/Sub-Saharan African** digital lending ecosystem.

Traditional machine learning models in credit scoring operate as "black boxes" and lack autonomous regulatory compliance. We propose a **Multi-Agent System (MAS)** comprising:
1. **Predictive Agent:** A hybrid ensemble (XGBoost + LightGBM) utilizing alternative data (USSD volume, airtime spend, BVN scores).
2. **Explainability (XAI) Agent:** Leverages SHAP to provide post-hoc, human-interpretable risk attributions.
3. **Compliance Agent:** Autonomously enforces Central Bank of Nigeria (CBN) consumer protection frameworks and NDPR fairness constraints.

## 🚀 Quick Start (Google Colab)
You can run the entire experiment, generate synthetic Nigerian financial data, train the models, and reproduce all paper figures directly in your browser without installing anything locally.

👉 **[Click here to open in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/notebooks/colab_main_experiment.ipynb)**

## 🛠️ Local Installation
If you prefer to run the code locally:

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/Explainable-Agentic-AI-Credit-Risk-Nigeria.git
cd Explainable-Agentic-AI-Credit-Risk-Nigeria

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
