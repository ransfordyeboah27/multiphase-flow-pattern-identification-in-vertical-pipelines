# Multiphase Flow Pattern Identification in Vertical Pipelines

## Overview
This repository contains the implementation of Convolutional Neural Network (CNN), Physics-Informed Neural Network (PINN), and Transformer Neural Network (TNN) models for identifying multiphase flow patterns in vertical pipelines. The project utilizes deep learning techniques to classify flow patterns such as annular, bubbly, churn, slug, and transition states.

## Project Structure
```
multiphase-flow-pattern-identification/
│
├── models/                  
│   ├── cnn_model.keras
│   ├── tnn_model.keras
│   └── pinn_best_flow_classifier.pt
│
├── notebooks/
|   ├── cGAN.ipynb
│   ├── training/
│   │   ├── 1_training_cnn.ipynb
│   │   ├── 2_training_tnn.ipynb
│   │   └── 3_training_pinn.ipynb
│   │
│   └── testing/
│       ├── 1_testing_cnn.ipynb
│       ├── 2_testing_tnn.ipynb
│       └── 3_testing_pinn.ipynb
│
├── results/                   
│   ├── figures/
│   └── Classification Report.xlsx
│
├── requirements.txt           
├── LICENSE                    
└── README.md                  
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
