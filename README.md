# 📝 BERT-Arabic Text Generation

This project fine-tunes a pre-trained Arabic BERT model, AraBERT, for the task of Masked Language Modeling (MLM). The model is trained on a custom Arabic text dataset to learn contextual representations and is then used to complete masked tokens in Arabic sentences, effectively performing text generation.

## 🚀 Features

Data Processing: Loads and tokenizes a custom Arabic text dataset.

Model Fine-tuning: Fine-tunes the aubmindlab/bert-base-arabertv02 model for the MLM task.

Text Generation: Uses the fine-tuned model to predict and complete masked tokens in sentences.

## 📂 Project Structure
.
├── dataset/     # Contains the raw Arabic text data (excluded from Git)            
├── results/         # Stores the fine-tuned model and tokenizer (excluded from Git)                
├── trained_model/   # Holds model checkpoints and training logs (excluded from Git)              
├── BERT-Arabic_Text_Genration.ipynb    # The main Jupyter Notebook with the project code

Getting Started:

Prerequisites

Python 3.6+

PyTorch

Transformers library

Datasets library

You can install the required libraries by running:

pip install torch transformers datasets

1. Handling Large Files
The nlp_dataset/ and results/ directories contain files that exceed GitHub's file size limit. These directories are intentionally excluded from the repository using a .gitignore file.

Dataset: You can download the public dataset from the official website. Here's the link https://sourceforge.net/projects/kalimat/files/kalimat/document-collection/

Trained Model: You can re-run the BERT-Arabic_Text_Generation.ipynb notebook to train the model from scratch on your local machine after obtaining the dataset.

2. Running the Code
Clone the Repository:

git clone https://github.com/Abdulelah-O/BERT-text-generation-for-Arabic-language.git
cd BERT-text-generation-for-Arabic-language

Download or Set up the Data:

Follow the instructions in the "Handling Large Files" section to get the dataset/ directory.

Run the Notebook:

Open BERT-Arabic_Text_Generation.ipynb in your preferred Jupyter environment (e.g., Jupyter Notebook, JupyterLab, VS Code).

Run all the cells in the notebook sequentially. The training process will automatically save checkpoints and the final model in the results/ and trained_model/ directories, respectively.
