# PyTorch Medical ViT

This project implements a Vision Transformer (ViT) model for training and evaluating on a medical image dataset. The model is designed to classify medical images and visualize attention maps to understand the model's focus during predictions.

## Overview

The `pytorch_medical_ViT.ipynb` file contains the main code for the project, including:

- Data loading and preprocessing
- Model training and evaluation
- Visualization of attention maps
- Displaying predictions with corresponding labels

## Installation

To set up the project, ensure you have Python installed along with the necessary libraries. You can install the required packages using pip:

```bash
pip install torch torchvision transformers matplotlib scikit-learn kaggle
```

## Usage

1. **Download the Dataset**: The dataset is downloaded using the Kaggle API. Ensure you have your Kaggle API credentials set up.

2. **Run the Notebook**: Open the `pytorch_medical_ViT.ipynb` file in a Jupyter Notebook environment and execute the cells sequentially.

3. **Training**: The model will be trained on the medical image dataset. You can adjust the number of epochs and other hyperparameters as needed.

4. **Evaluation**: After training, the model's performance can be evaluated on a test set, and accuracy metrics will be displayed.

5. **Visualization**: The notebook includes functions to visualize attention maps and predictions, helping to interpret the model's decisions.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.