# Ehtical Finance Hackathon 2025 

This step-by-step chain-of-thought (ST-COT) and (Fin-COT)approach for financial question answering using LLM via Hugging Face Transformers and PyTorch.

## Features
- Loads financial questions from a CSV file.
- Uses a Hugging Face LLM (scb10x/llama3.2-typhoon2-t1-3b-research-preview).
- Prompts the model with a detailed system prompt for structured financial reasoning.
- Extracts and saves model answers for each question.
- Batch inference and CSV export for submissions.

## Workflow Overview
1. **Environment Setup**: Installs required packages and authenticates with Hugging Face.
2. **Data Loading**: Reads the test dataset into a pandas DataFrame.
3. **Model Loading**: Loads tokenizer and model from Hugging Face.
4. **Prompt Engineering**: Defines a system prompt for financial reasoning.
5. **Inference**: Generates model responses and extracts final answers [A, B, C, D, E, Fall, Rise].
6. **Batch Processing**: Iterates over all questions from csv , generates answers, and saves results to CSV.

## How to Use
1. Run the notebook in an environment with GPU support for best performance.
2. Authenticate with your Hugging Face token.
3. Place your test CSV file in the specified path.
4. Execute all cells in order to generate and save answers.

## Output
- The notebook produces a CSV file  (`submission.csv`) with model answers for each question.

## Requirements
- Python 3.8+
- PyTorch
- transformers
- pandas
- tqdm

---
**Note:** Adjust file paths as needed for your environment. The notebook is designed for  educational purposes in Ethical Finance  tasks.
