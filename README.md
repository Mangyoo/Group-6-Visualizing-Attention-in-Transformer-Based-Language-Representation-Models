# 🔍 Visualizing Transformer Attention — Demo Notebook

This repository contains a **Jupyter Notebook demo** created for a presentation on the paper:

> **Visualizing Attention in Transformer-Based Language Representation Models**  
> *Jesse Vig*

The demo builds on **[BERTViz](https://github.com/jessevig/bertviz)**, an interactive visualization tool for inspecting attention mechanisms in transformer-based language models such as **BERT**, **GPT**, and related architectures.

The goal of this repository is to provide a **lightweight, presentation-friendly walkthrough** of transformer attention visualizations, with minimal setup and a focus on intuition and interpretability.

---

## 📄 Background

Transformer models rely on **self-attention** to model relationships between tokens in a sequence. While powerful, these attention patterns are often opaque.

**BERTViz**, introduced alongside Jesse Vig’s paper, provides interactive visualizations that help answer questions such as:

- What tokens does a word attend to?
- How does attention differ across layers and heads?
- How do attention patterns evolve through the model?

This demo notebook:
- Reproduces key ideas from the paper
- Shows practical examples using BERTViz
- Is designed to be **easy to run live during a presentation**

---

## 🚀 Quick Start (Recommended: Google Colab)

Since **Google Colab already includes PyTorch**, using Colab can significantly reduce setup time compared to local installation.

➡️ **Open the demo notebook in Google Colab:**  
👉 **[Google Colab Notebook (link placeholder)]**  


*(Replace the link above with your actual notebook.)*

### Why Colab?
- PyTorch is preinstalled
- No GPU setup required
- Faster startup for demos and workshops
- No local environment conflicts

---

## 🧪 What’s in This Repo?

- 📓 **Jupyter Notebook demo**
  - Step-by-step attention visualizations
  - Examples using pretrained transformer models
  - Interactive widgets powered by BERTViz
- 📚 Conceptual explanations aligned with the paper
- 🎤 Presentation-oriented structure (clear sections, minimal boilerplate)

---

## 🛠 Local Installation (Optional)

If you prefer running the notebook locally, follow the standard BERTViz installation instructions.

### 1. Clone this repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
