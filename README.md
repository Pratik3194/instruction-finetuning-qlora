# Instruction Finetuning with QLoRA

This repository contains an implementation of **instruction finetuning** using **QLoRA (Quantized Low-Rank Adaptation)** for **CodeLlama**.  
The goal is to perform **Supervised Finetuning (SFT)** on function-calling tasks using **PEFT (Parameter-Efficient Fine-Tuning)** methods.

---

## 🚀 Features
- Fine-tuning CodeLlama with QLoRA for instruction-following tasks  
- Parameter-efficient approach using PEFT  
- Demonstrates function-calling use cases  
- Google Colab-compatible implementation  

---

## 📂 Project Structure
- `instruction-finetuning-qlora-assignment.ipynb` : Main notebook with the complete workflow  

---

## ⚙️ Installation
Clone the repository and install the requirements:

```bash
git clone https://github.com/Pratik3194/instruction-finetuning-qlora.git
cd instruction-finetuning-qlora
pip install -r requirements.txt

▶️ Usage
Run the notebook step by step:
Mount Google Drive (if using Colab)
Install dependencies
Login to Weights & Biases (W&B) for experiment tracking
Load dataset and preprocess
Fine-tune CodeLlama using QLoRA + PEFT
Evaluate and test the model

📊 Results
Successfully fine-tuned CodeLlama for function-calling tasks
Demonstrates efficient training with reduced GPU memory usage

📌 Requirements
Python 3.9+
PyTorch
Hugging Face Transformers
PEFT
bitsandbytes
accelerate
wandb
