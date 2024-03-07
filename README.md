# GermanRAG Dataset Enhancement

This repository contains the code and documentation for enhancing the germanrag dataset, specifically designed for fine-tuning Language Models (LLMs) for German-language Retrieval-Augmented Generation (RAG) applications. The project focuses on introducing easy negatives, ensuring unique combinations of contexts, and preparing the dataset with a suitable prompt template for LLM fine-tuning.

## Project Overview

The germanrag dataset, available on Hugging Face, is an invaluable resource for developing advanced NLP models tailored to the German language. My enhancement efforts are directed towards improving the dataset by:

- Adding easy negatives to provide a broader range of training challenges.
- Implementing checks to ensure no combination of contexts appears more than once, enhancing dataset uniqueness.
- Preparing the dataset for LLM fine-tuning with a custom prompt template suitable for RAG applications.

## Suggested Future Features

- **Dynamic Difficulty Scaling:** Algorithm that adjusts the difficulty level of questions and negatives based on the model's performance, addressing the "lost in the middle" problem.
- **Advanced Negative Selection:** Enhanced selection of hard and easy negatives using deep learning techniques to better simulate real-world misinformation challenges.
- **MetaData Inclusion:** Augmentation of the dataset with metadata to provide context about the source and reliability of information.

## Getting Started

To get started with this project, clone this repository and install the required dependencies:

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt

Follow the notebook steps: 
- Download the original germanrag dataset from Hugging Face.

- Run the Enhancement Script: Execute the script to add easy negatives and apply the uniqueness checks.

- Prepare for Fine-Tuning: Use the provided script to format the dataset according to the specified prompt template.

- Evaluate and Adjust: Review the enhanced dataset and adjust parameters in the script as necessary to optimize the training data
