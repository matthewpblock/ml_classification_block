# Midterm Project: Mushroom Classification Analysis
by Matthew Block
for Applied Machine Learning course in M.S in Data Analytics program at Northwest Missouri State University.  

This project focuses on building and evaluating a machine learning model to solve a classification problem: determining whether a mushroom is edible or poisonous based on its physical characteristics.

This repository contains the Jupyter Notebook with the complete analysis, as well as a peer review of another project.

## Files in this Repository

*   **[block_classification_midterm.ipynb](https://github.com/matthewpblock/ml_classification_block/blob/main/block_classification_midterm.ipynb)**: The main Jupyter Notebook containing the entire data science workflow. This includes:
    *   Data loading and initial inspection.
    *   Exploratory Data Analysis (EDA) to understand data patterns.
    *   Data cleaning, preprocessing, and feature engineering.
    *   Training and evaluation of multiple classification models (Logistic Regression and Decision Tree).
    *   Comparison of model performance to identify the best-performing model.

*   **[peer_review.md](https://github.com/matthewpblock/ml_classification_block/blob/main/peer_review.md)**: A peer review conducted on a fellow student's classification project.

## Getting Started

Follow these instructions to set up your local environment and run the notebook.

### Prerequisites

*   Python 3.x
*   `pip` and `venv`

### Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd ml_classification_block
    ```

2.  **Create and activate a virtual environment:**

    *   On Windows:
        ```bash
        python -m venv .venv
        .\.venv\Scripts\activate
        ```

    *   On macOS/Linux:
        ```bash
        python3 -m venv .venv
        source .venv/bin/activate
        ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook

1.  **Start JupyterLab:**
    ```bash
    jupyter lab
    ```

2.  Once JupyterLab opens in your browser, navigate to and open `block_classification_midterm.ipynb` to view and run the analysis.
