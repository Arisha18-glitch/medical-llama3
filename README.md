# Medical LLaMA 3 — Fine-Tuned on Medical Q&A

Llama 3 8B fine-tuned on 8,000 medical Q&A pairs using QLoRA and 
Unsloth on Google Colab T4 GPU.

## Results
- Only 0.26% of parameters trained via LoRA adapters
- Training loss reduced from 1.154 to 0.763 across 1,000 steps
- Deployed publicly on HuggingFace Hub

## Model
https://huggingface.co/SyedaArisha/medical-llama3-lora

## Tech Stack
Python, Unsloth, QLoRA, PEFT, TRL, Llama 3, HuggingFace
