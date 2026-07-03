# BloomForge---AI-Based-Question-Paper-Generation-System
# 📘 BloomForge: Smart Question Paper Generator

BloomForge is an AI-powered question paper generator built with **Streamlit** and **Ollama's Gemma 2B** model. It automatically generates university-level descriptive questions and multiple-choice questions (MCQs) from syllabus topics based on Bloom's Taxonomy. The application also exports the generated question papers as PDF files.

## ✨ Features

* **AI-Powered Question Generation:** Generates university-standard descriptive questions using the Gemma 2B language model.
* **MCQ Generation:** Creates 10 multiple-choice questions with four options and the correct answer.
* **Bloom's Taxonomy Support:** Produces questions based on different Bloom's cognitive levels and difficulty.
* **PDF Export:** Downloads descriptive and MCQ question papers in PDF format.
* **Easy-to-Use Interface:** Simple and user-friendly interface built with Streamlit.
* **Offline Execution:** Runs locally using Ollama without requiring an internet connection after model installation.

## 🛠️ Installation

### Prerequisites

* Python 3.8 or higher
* Ollama installed
* Gemma 2B model downloaded

### Required Dependencies

Install the required Python libraries:

```bash
pip install streamlit reportlab
```

### Install Ollama Model

```bash
ollama pull gemma:2b
```

### Run the Application

```bash
streamlit run app.py
```
