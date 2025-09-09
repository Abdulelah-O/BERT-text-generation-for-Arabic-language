# 📝 BERT-Arabic_Text_Generation: Fine-tuning AraBERT for Arabic Text Completion

This project fine-tunes a pre-trained Arabic BERT model, AraBERT, for the task of Masked Language Modeling (MLM). The model is trained on a custom Arabic text dataset to learn contextual representations specific to the provided data. The fine-tuned model is then used to predict and complete masked tokens in Arabic sentences, effectively performing a form of text generation.

---

## 📂 Project Structure

.
├── nlp_dataset/ # Dataset (not uploaded – see instructions below)
├── results/ # Training results & logs (not uploaded)
├── trained_model/ # Trained model weights (not uploaded)
├── src/
│ ├── data_preprocessing.py # Arabic text preprocessing functions
│ ├── model_training.py # Model training script
│ ├── text_generation.py # Text generation script
│ └── utils.py # Helper utilities
├── BERT-Arabic_Text_Genration.ipynb # Main notebook (step-by-step demo)
├── requirements.txt # Dependencies
├── .gitignore # Exclude large files/folders
└── README.md # Project documentation


- nlp_dataset/: Contains the raw Arabic text data, organized into different categories. This data is used for training the model.

- trained_model/: This directory stores the fine-tuned AraBERT model and its tokenizer after the training process is complete.

- results/: This folder holds the training outputs, including model checkpoints and training logs.

- BERT-Arabic_Text_Generation.ipynb: The main Jupyter Notebook containing the code for data loading, model training, and text completion.
