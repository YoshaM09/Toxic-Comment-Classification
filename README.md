# Toxic Comment Classification

A machine learning pipeline for detecting toxic comments in text using **LSTM-based neural networks**. This project demonstrates text preprocessing, tokenization, and sequence modeling for text classification tasks.  

## Features

- **Text Cleaning Pipeline**: Cleans input text using **Texthero**, removing digits, URLs, extra spaces, stop words, and other noise.  
- **Tokenization & Padding**: Converts cleaned text into tokens and applies padding to ensure uniform input size for the model.  
- **Deep Learning Model**: Builds a classification model using:  
  - **Cell-state LSTM layers** for sequence learning  
  - **Dense layers** for feature extraction  
  - **Batch normalization** to stabilize training  
  - **Dropout layers** to prevent overfitting  

## Tech Stack

- **Programming Language**: Python  
- **Libraries / Frameworks**: Texthero, TensorFlow / Keras, NumPy, Pandas  
- **Model Type**: LSTM-based Neural Network for text classification  

## Setup & Installation

1. ### Clone the repository
```bash
git clone https://github.com/YoshaM09/Toxic-Comment-Classification.git
cd Toxic-Comment-Classification
```

2. ### Install dependencies
```bash
pip install -r requirements.txt
```
3. ### Open the notebook
```bash
jupyter notebook notebook1_toxic_comment_classification.ipynb
jupyter notebook notebook2_toxic_comment_classification.ipynb
```
4. ### Run the Notebook
- Run the cells sequentially to reproduce the text preprocessing, tokenization, and model training steps, and to generate predictions on both **training, and test datasets**.

## Usage

- Input raw text comments into the notebook.  
- The model outputs predictions for the following categories: **toxic, severe toxic, obscene, threat, insult, identity hate**.  
- Each comment can belong to **one or more categories**, enabling multi-label classification.

## Contributing

- Contributions are welcome! Please submit a pull request or open an issue for suggestions.

## License

- This project is licensed under the MIT License.



