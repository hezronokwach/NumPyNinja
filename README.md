# NumPy Ninja Notebook

This repository contains the `Notebook_ex00.ipynb` Jupyter Notebook, a collection of exercises designed to showcase various data manipulation and analysis capabilities of the NumPy library in Python.

## Notebook Contents

The notebook is structured as a series of data analysis tasks that progressively increase in complexity. Key concepts and exercises include:

*   **Basic Array Manipulation**: Creating and reshaping NumPy arrays.
*   **Data Loading**: Loading data from text files (`.csv`, `.txt`) using `np.genfromtxt` and handling different delimiters.
*   **Data Cleaning**: Working with and handling missing values (`np.nan`).
*   **Slicing and Indexing**: Using slicing and boolean masking to filter and select specific subsets of data.
*   **Statistical Analysis**: Calculating descriptive statistics such as mean, min, max, and percentiles using functions like `np.nanmean` and `np.nanpercentile`.
*   **Combinatorial Optimization**: Solving a complex pairing problem by generating permutations with `itertools.permutations` and using a custom cost function to find the optimal solution that minimizes the sum of squared differences.

## Datasets

*   `winequality-red.csv`: A dataset containing chemical properties and quality scores for red wines.
*   `model_forecasts.txt`: A matrix of predicted score differences for a fictional football tournament.

## Requirements

To run this notebook, you will need Python and the following libraries:

*   NumPy
*   Jupyter Notebook or Jupyter Lab

The `requirements.txt` file lists the necessary Python packages.

## How to Run the Notebook

1.  **Clone or Download:**
    Get a local copy of this repository.

2.  **Create a Virtual Environment (Recommended):**
    It is a best practice to create a virtual environment for the project. Open your terminal in the project directory and run:
    ```bash
    # Create a virtual environment named 'venv'
    python -m venv venv
    ```

3.  **Activate the Virtual Environment:**
    *   **On Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    *   **On macOS and Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install Dependencies:**
    With the virtual environment active, install the required packages from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

5.  **Launch Jupyter:**
    Start the Jupyter environment from your terminal.
    ```bash
    # For Jupyter Lab
    jupyter lab

    # Or for the classic Jupyter Notebook
    jupyter notebook
    ```

6.  **Open and Run:**
    Once the Jupyter interface opens in your web browser, navigate to and open the `Notebook_ex00.ipynb` file. You can run the cells sequentially to see the results of each exercise.
