
# Anomaly Detection in Logs using RoBERTa and MegatronBERT

This repository contains Jupyter Notebooks for fine-tuning and evaluating two transformer-based language models: **MegatronBERT** and **RoBERTa**. These models have been optimized for specific natural language processing (NLP) tasks, and the notebooks serve as guides for replicating the results or adapting the models for custom datasets.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
  - [MegatronBERT Notebook](#megatronbert-notebook)
  - [RoBERTa Notebook](#roberta-notebook)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository showcases two state-of-the-art NLP models:

- **MegatronBERT**: A large-scale variant of BERT designed to improve upon the original model's capabilities through extensive pretraining.
- **RoBERTa**: A robustly optimized BERT approach, further tuned to achieve superior performance on several benchmark datasets.

The notebooks included in this repository demonstrate the fine-tuning process, evaluation metrics, and the overall performance of these models on specified tasks.

## Installation

To run the notebooks, you will need to have Python installed along with the necessary libraries. Follow these steps to set up your environment:

1. Clone the repository:
   ```bash
   git clone https://github.com/DynamVraj/Anomaly-Detection-using-Logs.git
   cd Anomaly-Detection-using-Logs
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

### MegatronBERT Notebook

The `MegatronBERT (BEST).ipynb` notebook focuses on:

- Loading the pre-trained MegatronBERT model.
- Fine-tuning the model on a specific dataset.
- Evaluating the model's performance using various metrics.
- Saving and exporting the fine-tuned model for deployment.

### RoBERTa Notebook

The `RoBERTa(BEST).ipynb` notebook includes:

- Loading the pre-trained RoBERTa model.
- Fine-tuning the model on a specific task.
- Detailed evaluation and comparison with baseline models.
- Exporting the model for further use.

## Dependencies

Make sure the following dependencies are installed:

- Python 3.7+
- PyTorch
- Transformers (Hugging Face)
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

You can install these using the `requirements.txt` provided in the repository.

## Contributing

Contributions are welcome! If you have any suggestions, please feel free to fork the repository and submit a pull request. For major changes, please open an issue to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
