# 🦙 Running Llama 3.1 8B in Google Colab - Step-by-Step Tutorial

> Learn how to load and use an open-source language model in Python, no own GPU, no high costs, full control over your data.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D5gGLi_jFcXpS6km7VYUTPK-jFxclWmA?usp=sharing)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## What is this?

A **practical, beginner-friendly tutorial** for software engineers who want to get started with open-source Large Language Models (LLMs). You'll learn step by step how to load and use **Meta's Llama 3.1 8B Instruct** via **Google Colab** - including prompt engineering, parameter tuning, and a real-world spell-correction example.

This tutorial is aimed at developers who:
- Are **new to LLMs** and open-source AI
- Are building **privacy-sensitive applications** where data cannot leave your own infrastructure
- Want to be **independent** from paid services like ChatGPT or Gemini

---

## What you'll learn

- What LLMs are and the difference between open-source and closed models
- How to set up Google Colab with a free GPU
- How to load Llama 3.1 8B using Unsloth
- How to control the model using `system` and `user` prompts
- How to tune `temperature` and `max_new_tokens`
- How to apply the model to tasks like spell correction and Q&A

---

## Requirements

| What | Details |
|------|---------|
| **Prior knowledge** | Basic Python |
| **Google account** | For Google Colab |
| **Hardware** | No own GPU needed - free T4 GPU via Colab |
| **Cost** | Free (using the free tier of Google Colab) |

---

## Quickstart

1. Click the **Open in Colab** badge above
2. In Colab, go to **Runtime → Change runtime type → T4 GPU**
3. Run the cells step by step

Or clone the repo locally:

```bash
git clone https://github.com/codershiyar/llama-google-colab-tutorial.git
cd llama-google-colab-tutorial
```

---

## Repository structure

```
📁 llama-google-colab-tutorial/
├── tutorial.ipynb   # Main notebook with the full tutorial
└── README.md                # This file
```

---

## Tutorial overview

| Section | Topic |
|---------|-------|
| 1 | Introduction and learning goals |
| 2 | What are LLMs? Open-source vs. closed models |
| 3 | Setting up Google Colab with GPU |
| 4 | Installing Unsloth |
| 5 | Loading Llama 3.1 8B |
| 6 | First test: using the model |
| 7 | System and user roles in prompts |
| 8 | Parameters: `temperature` and `max_new_tokens` |
| 9 | Conclusion, next steps, and common issues |

---

## Common issues

**Hit the GPU limit?**  
The free Colab tier has a daily GPU limit. Wait 24 hours or upgrade to Colab Pro.

**Model won't load?**  
Hugging Face can occasionally be overloaded. Wait 5–10 minutes and try again.

**Model responding slowly?**  
Check if the GPU is active by running `!nvidia-smi` in a cell. If no GPU table appears, reconfigure the runtime.

---

## Next steps

After this tutorial, you can move on to:
- Other open-source models like Mixtral or DeepSeek-V2
- Building a REST API with Flask or FastAPI around the model
- Creating your own chatbot or virtual assistant
- Running larger Llama variants (70B) via Colab Pro or your own server

---

##  Author
Built with ❤️ by **[Coder Shiyar](https://codershiyar.com)**  
*Sharing knowledge about open-source AI, one tutorial at a time.*

[![GitHub](https://img.shields.io/badge/GitHub--blue)](https://github.com/codershiyar)
[![YouTube](https://img.shields.io/badge/YouTube--red)](https://youtube.com/@codershiyar)


