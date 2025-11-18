# LLM Instruction Data Preparation

This repository contains a Jupyter notebook for preparing an instruction–response
dataset and tokenizing it with Hugging Face `transformers` and `datasets`.
It demonstrates:

- Basic tokenization (single text and batches)
- Padding and truncation behavior
- Building an instruction dataset from a JSONL file (`lamini_docs.jsonl`)
- Applying a prompt template to questions
- Creating a Hugging Face `Dataset`
- Tokenizing the dataset and preparing it for finetuning (including labels and train/test split)

## Project structure

```text
.
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ data/
│  └─ lamini_docs.jsonl        # input JSONL file (not included by default)
└─ data_preparation.ipynb      # main notebook
