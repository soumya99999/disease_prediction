# Disease Prediction with BERT

This project uses a BERT-based model to predict diseases based on textual descriptions of symptoms. It leverages the `bert-base-uncased` model from Hugging Face's Transformers library, fine-tuned on a custom dataset (`Train_data.csv`) to classify diseases. The model processes symptom descriptions and outputs a predicted disease label.

## Features
- Preprocesses text data using `sklearn` and `pandas`.
- Fine-tunes a BERT model for sequence classification.
- Evaluates model performance with accuracy and loss metrics.
- Includes a prediction function for new symptom inputs.

## Prerequisites
- Python 3.8+
- Git (optional, for cloning the repository)
- A CUDA-enabled GPU (optional, for faster training)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/disease-prediction.git
   cd disease-prediction
