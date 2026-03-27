#  Medical LLM From Scratch

A domain-specific Large Language Model (LLM) built from scratch for the medical domain.  
This project focuses on learning how LLMs work internally by implementing tokenizer, training pipeline, and model architecture from the ground up.


## Overview

This project aims to build a **medical domain language model** that can understand and generate context-aware medical text.

Instead of using pre-trained models, the entire pipeline is developed from scratch:
- dataset preparation  
- tokenizer training  
- model architecture  
- training & evaluation  

This is an **ongoing project**, and I am continuously improving it by training on larger and more diverse datasets.


## Current Results

- **Model Size:** 16.9 Million parameters  
- **Dataset:** Med-Alpaca  
- **Training Tokens:** ~2.5 Million  
- **Validation Loss:** 2.22  
- **Perplexity:** 9.2  

These results show that the model is learning meaningful patterns from medical text, with scope for further improvement.


## Features

- Custom tokenizer trained on medical corpus  
- End-to-end LLM training pipeline  
- Transformer-based architecture  
- Dataset preprocessing and cleaning  
- Modular notebook-based workflow  
- Evaluation using loss and perplexity  


## Project Structure

```
medical-llm-from-scratch/
│── notebooks/
│ ├── Build_Architecture.ipynb
│ ├── Dataset_prepration.ipynb
│ ├── Tokenizer.ipynb
│ ├── training_done_llm.ipynb
│ ├── Testing_1.ipynb
│
│── tokenizer/
│ └── medical_tokenizer.json
│
│── requirements.txt
│── README.md
```

## Model Details

- Built a **transformer-based language model from scratch**  
- Trained on domain-specific medical dataset  
- Focused on improving contextual understanding in medical terminology  
- Evaluated using validation loss and perplexity  


## Dataset & Model Weights

- Dataset: https://huggingface.co/datasets/medalpaca/medical_meadow_medical_flashcards
- Model Weights: https://drive.google.com/file/d/1w9IpV43ZTa6Dcu8lE6WVTvxQSMGNnYoq/view?usp=sharing 


## What I Have Done

- Prepared and cleaned medical dataset  
- Built a custom tokenizer  
- Designed and implemented model architecture  
- Trained LLM on medical text data  
- Evaluated model performance  


## Future Improvements

- Train on larger and more diverse medical datasets  
- Improve accuracy and reduce validation loss  
- Implement Retrieval-Augmented Generation (RAG)  
- Add better evaluation metrics  
- Scale model size and optimize training  
- Deploy as API or web application  


## Contributions

Suggestions and improvements are welcome.

📌 Note

This project is part of my learning and research in LLMs and is actively being improved with more data and better training techniques.
