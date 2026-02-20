# Log-Loss Example

This project demonstrates the implementation of the Statistical Classification Log-Loss (Cross Entropy) using a Hours studied vs. Final scores dataset. The example involves predicting the likelihood of a patient having a certain condition based on diagnostic test results.

## Contents

- **Notebook**: The Jupyter Notebook `LogLoss_Example.ipynb` contains:
  - An explanation of the Log-Loss formula.
  - Implementation of the Log-Loss function.
  - A healthcare dataset for demonstration.
  - Visualization of results.
  - Talking points about the code and its design.

## Key Features

1. **Log-Loss Function**:
   - Measures the performance of a classification model.
   - Ensures numerical stability with `np.clip`.

2. **Healthcare Dataset**:
   - Diagnostic test results vs. condition presence.
   - Simulated probabilities for demonstration.

3. **Visualization**:
   - Graphical comparison of predicted probabilities and actual outcomes.


## How to Use


## Setting Up the Virtual Environment

To ensure a clean and isolated environment for running the notebook, follow these steps to set up a virtual environment:

1. **Create a Virtual Environment**:
   ```bash
   python3 -m venv venv
   ```

2. **Activate the Virtual Environment**:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

3. **Install Required Libraries**:
   ```bash
   pip install -r requirements.txt
   ```

## Requirements File

Ensure you have a `requirements.txt` file in the project directory with the following content:
```
numpy
matplotlib
```
1. Open the `Healthcare_LogLoss_Example.ipynb` notebook in Jupyter.
2. Run the cells step-by-step to:
   - Understand the Log-Loss formula.
   - See the implementation and results.
3. Modify the dataset or predictions to test with your own data.