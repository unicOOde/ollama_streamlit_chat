# Ollama Setup Guide

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
   Download the executable installation file for [Python 3.11](https://python.org/) and install Python, or alternatively order via the IT-Shop.
2. **Start PowerShell in Windows**:
   Open PowerShell from the Start menu or by pressing `Win + X` and selecting PowerShell.
3. **Create a new Python environment**:
   ```powershell
   python -m venv llama_chat --python=python3.11
4. **Activate your environment**:
   ```powershell
   .\llama_chat\Scripts\activate
5. **Install requirements**:
   Ensure you have a requirements.txt file in your project directory and run:
   ```powershell
   pip install -r requirements.txt
6. **Run the Streamlit application**:
   ```powershell
   streamlit run llama_chat.py
