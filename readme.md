# Simple Chat Setup Guide for Windows 10

## Overview
Ollama is a program that runs in the background, designed to facilitate various operations involving the llama large language models. This guide will walk you through the steps to download, install, and set up Ollama, as well as creating a Python environment for running a Streamlit application with the newest llama 3.1 model.

## Steps

### 1. Download and Install Ollama
1. **Download the executable file for Windows**:
   [Ollama Installation Download](https://ollama.com/)
2. **Install Ollama**:
   Follow the on-screen instructions to complete the installation.

### 2. Set Up Ollama and Download Llama3.1 Model
1. **Start PowerShell in Windows**:
   Open PowerShell from the Start menu or by pressing `Win + X` and selecting PowerShell.
2. **Download the Llama3.1 model**:
   ```powershell
   ollama pull llama3.1:8b
3. **Exit PowerShell:**
   Simply type exit and press Enter.

### 2. Install Python, Set Up Environment, Run the Chat Application

1. **Download and Install Python**:
   Download the executable installation file for [Python 3.11](https://python.org/) and install Python.
2. **Open File Explorer**
   Open File Explorer and go into directory
3. **Start Terminal in Windows**:
   Open Terminal by typing the following command in the adress bar
   ```cmd
   cmd
4. **Create a new Python environment**:
   ```cmd
   "C:\Users\nicol\AppData\Local\Programs\Python\Python311\python.exe" -m venv venv
5. **Activate your environment**:
   ```cmd
   .\venv\Scripts\activate
6. **Install requirements**:
   Ensure you have a requirements.txt file in your project directory and run:
   ```cmd
   pip install -r requirements.txt
7. **Run the Streamlit application**:
   ```cmd
   streamlit run llama_chat.py
