# DriveSafe Pharma

DriveSafe Pharma is a tool designed to analyze pharmaceutical documents to determine the safety of driving while under the influence of specific medications. The tool uses natural language processing to extract, clean, and analyze text data from PDF documents.

## Features

- **PDF Text Extraction**: Extracts text from PDF files for analysis.
- **Text Cleaning**: Normalizes and cleans extracted text to prepare it for processing.
- **Information Summarization**: Summarizes the relevant information from the documents.
- **Safety Analysis**: Uses BERT, a pretrained transformer model, to answer questions about the safety of driving when taking medication.

## Installation

Before you can run this project, make sure you have Python installed on your machine. Then, clone this repository and install the required dependencies:

```bash
git clone <repository-url>
cd DriveSafe-Pharma
pip install -r requirements.txt
```

## Usage

To use this tool, run the Jupyter Notebook:

```bash
jupyter notebook DriveSafe\ Pharma.ipynb
```
Follow the instructions within the notebook to upload a PDF file and analyze its contents regarding medication and driving safety.

## Dependencies
This project relies on several Python libraries:
```bash
nltk
pandas
PyPDF2
transformers
torch
```
Make sure to install these packages using the provided requirements.txt file.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
