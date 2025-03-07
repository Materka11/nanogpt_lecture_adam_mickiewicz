# NanoGPT Lecture - Adam Mickiewicz

This repository contains a lecture-style implementation of NanoGPT, applied to text generation based on the works of Adam Mickiewicz. It serves as an educational resource for training and fine-tuning small-scale GPT models.

## Features
- Uses NanoGPT, a minimalistic implementation of a GPT-like model.
- Trains on text data from Adam Mickiewicz's works.
- Provides scripts for preprocessing data, training, and generating text.
- Simple and readable PyTorch implementation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Materka11/nanogpt_lecture_adam_mickiewicz.git
   cd nanogpt_lecture_adam_mickiewicz
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Usage

### Data Preparation
Ensure you have the dataset ready in the appropriate format. You can preprocess the text using the provided scripts.

### Training the Model
Run the training script:
```bash
python train.py
```

## Requirements
- Python 3.8+
- PyTorch
- NumPy
- Tokenizers

Install dependencies using:
```bash
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License.

