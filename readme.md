Financial News Sentiment Distillation 📊

This repository contains everything you need to run knowledge distillation from a large “teacher” model (Orkhan/llama-2-7b-absa) into a smaller “student” model (bigscience/bloom-1b1) on the zeroshot/twitter-financial-news-sentiment dataset. All steps — data augmentation, tokenization, distillation, and evaluation — are fully automated in a single Jupyter notebook.


File	Description
distil.ipynb	End‑to‑end distillation pipeline (data loading → evaluation)
requirements.txt	Python dependencies
README.md	This documentation
📦 Automatically Loaded Resources


Dataset	zeroshot/twitter-financial-news-sentiment
Teacher Model	Orkhan/llama-2-7b-absa
Student Model	bigscience/bloom-1b1
No manual downloads required — the notebook handles everything.

⚙️ Requirements

Python ≥ 3.9
Jupyter Notebook or JupyterLab
GPU with ≥ 16GB VRAM recommended

Launch Jupyter:
jupyter notebook distil.ipynb
Run all cells in order.
Review results in the final evaluation cell.
