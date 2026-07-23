# 🚀 Automated Cold Email Generator

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Gradio](https://img.shields.io/badge/UI-Gradio-orange.svg)
![LangChain](https://img.shields.io/badge/Framework-LangChain-green.svg)
![OpenAI](https://img.shields.io/badge/LLM-OpenAI_GPT--4o--mini-black.svg)

> A rapid web application that leverages LangChain and OpenAI to instantly generate highly converting, personalized cold emails based on user-defined parameters and tones.

## 📸 See it in Action

*[Portfolio Tip: Take a screenshot of your Gradio app running and upload it to your repo. Replace the path below with your image file name.]*
<img src="screenshot.png" alt="App Screenshot" width="600">

## 🛠️ Tech Stack

This project demonstrates practical skills in prompt engineering, LangChain integration, and building rapid user interfaces.

* **Core Logic:** `langchain`, `langchain-openai`
* **Frontend UI:** `gradio`
* **Language Model:** OpenAI (`gpt-4o-mini`)

## ✨ Key Features

* **Dynamic Prompting:** Automatically structures user inputs (Company, Product, Audience, Benefits) into an optimized LLM prompt template.
* **Tone Adjustment:** Allows users to select the email's tone (Professional, Casual, Urgent, Friendly) via a dropdown menu, demonstrating LLM steering capabilities.
* **Clean UI:** Built with Gradio for a seamless, interactive user experience.

## 💻 How to Run (Local or Google Colab)

The easiest way to test this project is via Google Colab.

1. Open the `.ipynb` notebook in Google Colab.
2. Run the first cell to install dependencies:
   ```bash
   pip install -q langchain langchain-openai gradio
