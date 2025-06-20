# Predictive Coding MNIST Classifier

A PyTorch implementation of a minimal predictive‑coding model for image classification on the MNIST dataset. This project demonstrates how to translate predictive‑coding theory into a working training pipeline, running iterative inference to refine hidden states and two‑phase learning to update both feedforward and lateral weights.
## Installation & Setup

1. **Clone the repository** or download the project files.
   ```
   git clone https://github.com/dagemawinegash/MNIST-digit-classifier
   ```

3. **Set up a Python environment** (recommended: Python 3.8+).

4. **Install dependencies**  
   Open a terminal in the project directory and run:
   ```
   pip install -r requirements.txt
   ```

5. **Download the MNIST dataset**  
   The dataset will be downloaded automatically when you run the notebook for the first time.

## Usage
1. **Open `task.ipynb`**  
   Follow the notebook cells in order. The notebook covers:
   - Data loading and preprocessing
   - Visualizing MNIST samples
   - Defining the predictive coding model
   - Training the model using predictive coding
   - Evaluating and visualizing results

2. **Modify and Experiment**  
   You can adjust model parameters, number of epochs, or experiment with different architectures within the notebook.
3. **How to run?**
-   **Shift + Enter** to run the current cell and advance to the next.
-   **Ctrl + Enter** (or Cmd + Enter on macOS) to run the current cell and stay
- Hit the execute button at the top left of each cell 

## Results
Example results after 5 epochs:

| Epoch | Prediction Error | Test Accuracy |
|-------|------------------|--------------|
|   1   |      0.1232      |    0.6213    |
|   2   |      0.0908      |    0.7401    |
|   3   |      0.0688      |    0.8003    |
|   4   |      0.0560      |    0.8268    |
|   5   |      0.0481      |    0.8402    |

## Requirements

All dependencies are listed in `requirements.txt`. Key packages include:
- torch
- torchvision
- numpy
- matplotlib
- tqdm

## License

This project is for educational and research purposes.

