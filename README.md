# LangChain Article Series - Code Repository

Welcome! This repository contains the **code examples** used in my Medium article series on **LangChain**, a framework for building applications with **Large Language Models (LLMs)**.

The series is beginner-friendly and walks step by step from LLM basics to more advanced topics like memory, RAG, and agents.

---

## Article Series & Notebooks

| Article | Medium Link | Notebook |
|---------|------------|----------|
| **Your First Steps with LLMs and Inference APIs Using LangChain** | [Read Article](https://medium.com/@induwaragayashan/getting-started-with-langchain-first-steps-with-llms-and-inference-apis-f9d7a10e7c03) | [Models.ipynb](./Models.ipynb) |
| **Prompt Templates and Chains in LangChain** | [Read Article](https://medium.com/@induwaragayashan/prompt-templates-and-chains-in-langchain-writing-smarter-llm-workflows-59fb41d524dd) | [Prompt_Templates_&_Chains.ipynb](./Prompt_Templates_&_Chains.ipynb) |
| **Adding Memory to LLMs with LangChain** | [Read Article](https://medium.com/@induwaragayashan/memory-in-langchain-teaching-llms-to-remember-conversations-b29c770c79c2) | [Memory.ipynb](./Memory.ipynb) |
| **Retrieval-Augmented Generation (RAG) with LangChain** | [Read Article](https://medium.com/@induwaragayashan/when-llms-need-to-look-it-up-rag-with-langchain-c40b11407e99) | [RAG.ipynb](./RAG.ipynb) |
| **Building Agents and Tools with LangChain** | [Read Article](https://medium.com/@induwaragayashan/when-llms-take-action-building-agents-and-tools-with-langchain-443ce8e0475a) | [Agents_&_Tools.ipynb](./Agents_&_Tools.ipynb) |


You can also view the **complete series** in one place:  
[The LangChain Journey: From LLM Basics to Agents & Tools](https://medium.com/@induwaragayashan/list/the-langchain-journey-from-llm-basics-to-agents-tools-bc8660cb8dc8)

---

## Environment Setup & Configurations

All notebooks are designed to run in **Google Colab**, making it easy to experiment without a local setup.

### 1. Hugging Face Hub

Hugging Face provides hosted LLMs accessible via an access token. Steps to generate a token:

1. Create an account and log in to Hugging Face Hub.  
2. Click your profile → **Access Tokens** → **Create new Access Token**.  
3. Select **Read access**, provide a token name, and click **Create Token**.  
4. Copy the token immediately (it won’t be shown again).

Add the Hugging Face token to Colab:

1. Click the **key icon (Secrets)** in the left sidebar.  
2. Click **Add a new secret**.  
3. Set the name to `HF_TOKEN` and paste your token as the value.

### 2. GitHub Marketplace

GitHub Marketplace provides limited access to some LLMs using a **GitHub personal access token**.

1. Go to **GitHub Settings → Developer Settings → Personal Access Tokens → Generate new token (classic)**.  
2. Provide a token name and generate the token. Copy it immediately.  
3. Add it to Colab using the same steps as Hugging Face, naming it `GITHUB_TOKEN`.

> Free inference tokens are for learning/testing. For production, use paid APIs due to limitations like request/day limits, token limits per request, and model-specific constraints.

---
