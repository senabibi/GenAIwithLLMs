# GenAIwithLLMs: Advanced Agentic AI & Large Language Models

<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" alt="IBM" height="100" style="margin: 0 40px;" />
<img src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg" alt="AWS" height="100" style="margin: 0 40px;" />
<img src="https://cdn.vanderbilt.edu/vu-news/files/20230520091241/2022-Vanderbilt-University-wordmark_fi.jpg" alt="Vanderbilt" height="100" style="margin: 0 40px;" />
<!-- DeepLearning.AI logo placeholder or text badge if SVGs are elusive, mostly they partner with Coursera/AWS -->
<br/>

<h3>Joint Project: DeepLearning.AI | AWS | IBM | Vanderbilt University</h3>

<p>
    <b>A comprehensive 4-month research and development project showcasing advanced capabilities in Generative AI, Agentic Systems, and LLM Orchestration.</b>
</p>

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/Hugging%20Face-Transformers-yellow?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![AWS](https://img.shields.io/badge/AWS-SageMaker-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)

</div>

---

## 📖 Project Overview

This repository hosts a portfolio of advanced work developed over a 4-month intensive period, demonstrating mastery in **Agentic AI**, **Natural Language Processing (NLP)**, and **Large Language Model (LLM) fine-tuning**. 

The project is divided into three specialized modules, each targeting a specific domain of Generative AI, developed in collaboration with or following the curriculum of leading institutions:

1.  **DeepLearning.AI & AWS**: Generative AI with Large Language Models.
2.  **IBM**: Advanced RAG and Agentic Frameworks.
3.  **Vanderbilt University**: Prompt Engineering and Custom Agent Architectures.

This work serves as a foundational component for my PhD application in the field of **Agentic AI & Natural Language Models**.

---

## 📂 Project Structure

### 1. DeepLearning.AI & AWS: Generative AI Lifecycle
> **Focus**: Full-cycle LLM development, from pre-training concepts to fine-tuning and deployment.

Located in `DeepLearningAI/`, this module explores the practical application of LLMs using **AWS SageMaker** and **Hugging Face Transformers**.

*   **Key Implementations**:
    *   **Dialogue Summarization**: Comparing Zero-shot, One-shot, and Few-shot inference techniques using FLAN-T5.
    *   **PEFT & LoRA Fine-Tuning**: Efficiently fine-tuning Large Language Models (LLMs) on consumer hardware to improve task-specific performance while reducing computational costs.
    *   **RLHF & Detoxification**: Implementing Reinforcement Learning from Human Feedback (RLHF) to reduce toxicity and align model outputs with human values.

🛠 **Tech Stack**: `Transformers`, `PEFT`, `LoRA`, `PyTorch`, `Datasets`, `Evaluate`.

### 2. IBM: Agentic AI & RAG Systems
> **Focus**: Building autonomous agents capable of reasoning, tool use, and retrieving real-time information.

Located in `IBM/`, this section demonstrates the power of **Agentic Workflows** using the **Agno** framework.

*   **Key Implementations**:
    *   **Autonomous Research Agents**: Agents capable of browsing the web (DuckDuckGo), parsing content (Newspaper4k), and synthesizing reports.
    *   **RAG (Retrieval-Augmented Generation)**: Integrating knowledge bases (SQLAlchemy, PDF processing) to ground agent responses in factual data.
    *   **Multi-Agent Orchestration**: Coordinating multiple specialized agents to solve complex queries.

🛠 **Tech Stack**: `Agno`, `Groq`, `DuckDuckGo Search`, `Newspaper4k`, `SQLAlchemy`.

### 3. Vanderbilt University: Prompt Engineering & Custom Frameworks
> **Focus**: Low-level understanding of agent mechanics and advanced prompt engineering patterns.

Located in `VanderbiltUNiversity/`, this module delves into the mechanics of how agents "think" and act.

*   **Key Implementations**:
    *   **Function Calling from Scratch**: Building the logic for LLM tool use without high-level abstractions.
    *   **Tool Decorators**: Creating Pythonic interfaces for LLMs to interact with external code.
    *   **Agent Loops**: Implementing the core reasoning loops (Observation -> Thought -> Action) manually to understand the underlying architecture of Agentic AI.

🛠 **Tech Stack**: `LiteLLM`, `Python Standard Library`, `Custom Agent Frameworks`.

---

## 🛠 Tools & Technologies

This project leverages a cutting-edge stack of AI tools:

| Category | Tools & Libraries |
|----------|-------------------|
| **Models & Inference** | ![Groq](https://img.shields.io/badge/Groq-Fast_Inference-orange?logo=groq) ![HuggingFace](https://img.shields.io/badge/Hugging_Face-Models-yellow?logo=huggingface) `FLAN-T5` `LiteLLM` |
| **Frameworks** | `Agno` `LangChain` `PyTorch` |
| **Data & RAG** | `Datasets` `Newspaper4k` `SQLAlchemy` `DuckDuckGo` |
| **Techniques** | `PEFT/LoRA` `RLHF` `Prompt Engineering` `CoT (Chain of Thought)` |

---

## 🚀 Getting Started

To explore the notebooks and reproduce the results:

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/GenAIwithLLMs.git
    cd GenAIwithLLMs
    ```

2.  **Install Dependencies**:
    Each folder may contain specific requirements. Generally, identifying the core tools:
    ```bash
    pip install transformers torch datasets peft agno-ai litellm groq
    ```

3.  **Run the Notebooks**:
    Navigate to the desired module (e.g., `IBM/`) and launch Jupyter Lab or Notebook.
    ```bash
    jupyter lab
    ```

---

<div align="center">
    <i>Developed by Nursena | PhD Candidate & AI Researcher</i>
</div>
