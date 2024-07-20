# Finetuning phi_1_5 model using QLoRA
The model is pre-trained on a diverse corpus of text data and subsets of Python codes for a diverse array of tasks such as code generation, summarization, and question-answering, among others.

Read the official documentation here: https://huggingface.co/microsoft/phi-1_5

This model has been finetuned on the https://huggingface.co/datasets/xlangai/DS-1000 dataset. 

The dataset comprises 1,000 datapoints of unique data science questions and corresponding code solutions, covering concepts such as Pandas, NumPy, and other relevant topics. 
The model has been quantized and loaded in 4-bit format using QLoRA configurations through the bitsandbytes library, thereby optimizing memory usage. 
LoRA configurations have been applied to specific target modules within the model, facilitating its efficient utilization. 
Subsequently, the model is fine-tuned on this dataset to assist in addressing data science-related queries.

Run this notebook: https://colab.research.google.com/drive/1a_XJbnu21xxmWw4YvNWfpz6fRpcc3q8h?usp=sharing







