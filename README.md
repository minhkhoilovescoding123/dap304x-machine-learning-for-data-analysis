# Machine Learning for Data Analysis

This repository contains materials for the Machine Learning for Data Analysis course.

## Getting Started with Jupyter Notebooks

To work with the notebooks in this repository, you should use a Python virtual environment. This keeps your project dependencies isolated and prevents conflicts. The `.venv` folder in this repository is your virtual environment.

You have two primary options for running notebooks:

### Option 1: Visual Studio Code (Recommended)

This approach integrates your notebooks directly into your code editor for a seamless workflow.

1.  **Install Extensions:** Make sure you have the [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extensions installed in VS Code.
2.  **Open the Project Folder:** Open the entire `dap304x-machine-learning-for-data-analysis` folder in VS Code.
3.  **Select the Kernel:** Open any `.ipynb` notebook file. In the top-right corner, click "Select Kernel". Choose the Python interpreter that has `('.venv': venv)` in its name. This tells VS Code to use your project's virtual environment.
Install Dependencies: If prompted, allow VS Code to install `ipykernel` or other required packages. Open the integrated terminal (`Ctrl+` ` ` ``), activate the environment (`.venv\Scripts\activate`), and then install all project dependencies:
```bash
pip install -r requirements.txt
```
5.  **Run Cells:** Click the "play" icon next to any cell to run it.

### Option 2: Local Jupyter Server

This is the classic, browser-based Jupyter experience.

1.  **Activate the virtual environment:** Open a terminal and run:

    For Windows:
    ```bash
    .venv\Scripts\activate
    ```

    For macOS and Linux:
    ```bash
    source .venv/bin/activate
    ```

2.  **Install dependencies:** With the virtual environment active, install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Start the Jupyter Server:** In the same terminal, run:
    ```bash
    jupyter notebook
    ```
    This will open a new tab in your web browser with the Jupyter interface.

## Running Python Scripts

To run any Python script (`.py` file) in this project, first ensure your virtual environment is activated, then use the `python` command:

1.  **Activate the virtual environment:**
    For Windows:
    ```bash
    .venv\Scripts\activate
    ```
    For macOS and Linux:
    ```bash
    source .venv/bin/activate
    ```
2.  **Run the script:**
    ```bash
    python your_script_name.py
    ```
