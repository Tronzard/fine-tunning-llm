# Fine-Tuning My First LLM — Llama 2 7B

My first hands-on **LLM fine-tuning project**, exploring how to customize a pretrained language model using **QLoRA (4-bit quantization + LoRA)** on Google Colab.

## What I Did
- Fine-tuned **Llama-2-7B-Chat** on the Guanaco conversational dataset.
- Used **Hugging Face Transformers, PEFT, TRL, and bitsandbytes**.
- Trained only **0.5% of the model's parameters** using LoRA.
- Compared responses from the original and fine-tuned models.

## Training Results

| Metric | Result |
|---|---|
| Trainable parameters | 33.55M (0.5%) |
| Training steps | 250 |
| Epochs | 1 |
| Training loss | 1.3804 |
| Training time | ~21 minutes |

## Tech Stack

`Python` `PyTorch` `Hugging Face` `QLoRA` `PEFT` `TRL` `Google Colab`

## Key Takeaway

Learned the fundamentals of parameter-efficient LLM fine-tuning, 4-bit quantization, LoRA adapters, and running large language models on limited GPU resources.
