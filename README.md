# 📘 Prompt Engineering

This repository contains **practical exercises** and **examples** from the **Prompt Engineering**.
The goal is to explore different **types of prompts**, frameworks, and techniques to build intelligent applications powered by **LLMs (Large Language Models)**.

---

## 🚀 Project Structure

The project is organized into directories showcasing the main prompt types and techniques:

* **1-tipos-de-prompts/**

  * `1-zero-shot.py` → Example of **Zero-Shot Prompting**
  * `2-few-shot.py` → Example of **Few-Shot Prompting**
  * `3-CoT.py` → Example of **Chain of Thought**
  * `4-self-consistency.py` → Example of **Self-Consistency**
  * `5-active-prompt.py` → Example of **Active Prompting**
  * `6-ReAct.py` → Example using **ReAct** framework (Reasoning + Acting)
  * `7-Prompt-chaining.py` → Example of **Prompt Chaining**

---

## ⚙️ Setup Instructions

### 1. Create and Activate Virtual Environment

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# macOS/Linux:
source venv/bin/activate

# Windows:
venv\Scripts\activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Environment Configuration

Copy the example file and configure your API key:

```bash
cp .env.example .env
```

In the `.env` file, add your OpenAI API key:

```env
OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Running the Scripts

Run any script using the following command:

```bash
python 1-tipos-de-prompts/<script_name>.py
```

### Examples

```bash
# Zero-Shot
python 1-tipos-de-prompts/1-zero-shot.py

# Chain of Thought
python 1-tipos-de-prompts/3-CoT.py

# ReAct Framework
python 1-tipos-de-prompts/6-ReAct.py

# Prompt Chaining
python 1-tipos-de-prompts/7-Prompt-chaining.py
```

---

## 📂 Output Files

Some scripts generate output files, such as:

* `prompt_chaining_result.md` → Output of the prompt chaining script, containing detailed results of each step in the pipeline.

---

## 📌 Requirements

* Python **3.8+**
* OpenAI API key
* Internet connection

---

## 📦 Dependencies

Main libraries used in this project:

* [langchain](https://www.langchain.com/) → Framework for LLM applications
* [langchain-openai](https://pypi.org/project/langchain-openai/) → OpenAI integration for LangChain
* [python-dotenv](https://pypi.org/project/python-dotenv/) → Environment variable management
* [openai](https://pypi.org/project/openai/) → Official OpenAI Python client

For the full list of dependencies, check the `requirements.txt`.

---

## 🎯 Project Goal

* Explore the main **Prompt Engineering types**
* Demonstrate **hands-on examples** of LLM usage
* Build a **practical guide** for applications based on prompt techniques
