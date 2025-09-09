# 📝 BERT-Arabic_Text_Generation: Fine-tuning AraBERT for Arabic Text Completion

This project fine-tunes a pre-trained Arabic BERT model, AraBERT, for the task of Masked Language Modeling (MLM). The model is trained on a custom Arabic text dataset to learn contextual representations specific to the provided data. The fine-tuned model is then used to predict and complete masked tokens in Arabic sentences, effectively performing a form of text generation.

---

## 📂 Project Structure

.
├── nlp_dataset/         
│     ├──  articles-culture/    
│     ├──  articles-economy/  
│     ├──  ...    
├── trained_model/ 
│     ├── config.json
│     ├── pytorch_model.bin  
│     ├── tokenizer.json
│     ├── special_token_map.json
│     ├── ...
├── resutls/
│     ├── checkpoint-1000/
│     ├── chechpoint-2000/
│     ├── ...
│
└── BERT-Arabic_Text_Generation.ipynb

- nlp_dataset/: Contains the raw Arabic text data, organized into different categories. This data is used for training the model.

- trained_model/: This directory stores the fine-tuned AraBERT model and its tokenizer after the training process is complete.

- results/: This folder holds the training outputs, including model checkpoints and training logs.

- BERT-Arabic_Text_Generation.ipynb: The main Jupyter Notebook containing the code for data loading, model training, and text completion.
