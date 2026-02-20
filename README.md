# Log-Loss Example Notebook

This README provides instructions for setting up the environment, installing dependencies, and running the `LogLoss_Example.ipynb` notebook.

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
scikit-learn
```

## Running the Notebook

1. Activate the virtual environment:
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```

2. Install the required libraries (if not already installed):
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open the `LogLoss_Example.ipynb` notebook in Jupyter.

5. Run the cells step-by-step to:
   - Understand the Log-Loss formula.
   - See the implementation and results.
   - Visualize the sigmoid curve.

## Notes

- The notebook demonstrates the implementation of the Statistical Classification Log-Loss (Cross Entropy) using a predicting pass-fail outcomes based on the number of hours studied dataset.
- The dataset has been refined to better demonstrate the sigmoid curve and its relationship with the Log-Loss function.
- Feel free to modify the dataset or predictions to test with your own data.