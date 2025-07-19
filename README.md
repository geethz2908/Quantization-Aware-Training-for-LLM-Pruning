🚀 Quantization-Aware Training for LLM Pruning
This project explores an integrated approach to compressing Large Language Models (LLMs) using Quantization-Aware Training (QAT) combined with model pruning. The primary goal is to enable efficient deployment of LLMs on resource-constrained devices without significantly sacrificing performance.

🔍 Project Summary
Traditional model compression techniques like quantization and pruning are often applied independently. This project combines them during training, allowing the model to:

Adapt to low-precision weights

Undergo structural sparsity

Maintain accuracy on downstream tasks

Benefits:

🚀 Reduced memory and computation cost

⚡ Lower latency and energy consumption

✅ Minimal accuracy degradation

This is especially effective for deploying transformer-based LLMs on edge devices or low-VRAM GPUs.

📘 What This Notebook Covers
✅ Loading and preparing transformer models using 🤗 Hugging Face

✂️ Implementing structured pruning (removing redundant neurons or heads)

🧠 Integrating Quantization-Aware Training via PyTorch

📊 Evaluating performance trade-offs: accuracy vs. compression

📈 Visualizing model sparsity and accuracy trends

📌 Key Techniques Used
Component	Description
Pruning	Structured/unstructured removal of unnecessary weights
Quantization-Aware Training	Simulates low-precision inference (e.g., INT8) during training
Transformer Models	BERT, DistilBERT, and other Hugging Face-based models
PyTorch	For model training, pruning, and quantization APIs
Matplotlib / Seaborn	Visualization of sparsity and performance

🧪 Results
✅ Achieved 50–80% model sparsity

📉 Enabled INT8-ready inference with quantized weights

⚖️ Maintained performance on downstream NLP tasks with minimal accuracy loss

🛠 Tools & Libraries
🐍 Python 3.x

🔦 PyTorch

🤗 Hugging Face Transformers

🖼 TorchVision

📊 NumPy, Matplotlib, Seaborn
