# mistral-qa-qlora
# 🧠 Mistral + QLoRA Fine-tuning on SAMSum

This project fine-tunes the [Mistral 7B](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1) model on the SAMSum dataset using QLoRA for efficient summarization of dialogues.

## 🚀 Features
- LoRA + 4-bit quantization (QLoRA)
- Hugging Face Transformers + Datasets
- Trainable on consumer GPUs (Colab/T4/RTX 4090)
- Evaluation with ROUGE metrics

## 🛠️ Setup
```bash
pip install -r requirements.txt
