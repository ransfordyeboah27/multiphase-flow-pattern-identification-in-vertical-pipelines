# Multiphase Flow Pattern Identification in Vertical Pipelines

## Overview
This repository contains the implementation of Convolutional Neural Network (CNN), Physics-Informed Neural Network (PINN), and Transformer Neural Network (TNN) models for identifying multiphase flow patterns in vertical pipelines. The project utilizes deep learning techniques to classify flow patterns such as annular, bubbly, churn, slug, and transition states.

## Project Structure
```
multiphase-flow-pattern-identification/
│
├── models/                    # Directory for trained model files
│   ├── cnn_model.h5
│   ├── transformer_model.h5
│   └── pinn_model.h5
│
├── notebooks/
│   ├── training/
│   │   ├── 1_CNN_Training.ipynb
│   │   ├── 2_Transformer_Training.ipynb
│   │   └── 3_PINN_Training.ipynb
│   │
│   └── testing/
│       ├── 1_CNN_Testing.ipynb
│       ├── 2_Transformer_Testing.ipynb
│       └── 3_PINN_Testing.ipynb
│
├── results/                   # (Optional) For output images, graphs, reports
│   ├── figures/
│   └── performance_metrics.csv
│
├── requirements.txt           # Python dependencies
├── LICENSE                    # License for usage
└── README.md                  # This file
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/multiphase-flow-pattern-identification.git
   cd multiphase-flow-pattern-identification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Run the training notebooks in the `notebooks/training/` directory to train the models.
- Use the testing notebooks in `notebooks/testing/` to evaluate the trained models.
- Models are saved in the `models/` directory, and results can be found in `results/`.

## Models
- **CNN**: Convolutional Neural Network for flow pattern classification.
- **PINN**: Physics-Informed Neural Network incorporating physical constraints.
- **TNN**: Transformer-based Neural Network for sequence-based pattern recognition.

## Acknowledgments
- Developed using Google Colab with GPU acceleration.
- Dataset extraction and model training are handled within the notebooks.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.