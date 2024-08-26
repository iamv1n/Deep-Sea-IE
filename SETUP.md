# Deep Sea Image Enhancement - Setup Guide

This guide will walk you through setting up the project on your local machine, including creating a Python virtual environment, setting up Jupyter Notebook, and managing datasets.

## 1. Prerequisites

Make sure you have the following software installed:

- **Python 3.8+**: Download it from [python.org](https://www.python.org/downloads/).
- **pip**: Python's package installer, bundled with Python 3.x.
- **virtualenv**: To create an isolated Python environment.

You can install `virtualenv` using the following command:

```bash
pip install virtualenv
```

## 2. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/iamv1n/Deep-Sea-IE.git
cd ./Deep-Sea-IE
```

## 3. Set Up the Python Virtual Environment

Create a virtual environment to avoid conflicts with other Python projects:

```bash
python3 -m venv dsie-env
```

Activate the virtual environment:

- **Windows**:

  ```bash
  .\dsie-env\Scripts\activate
  ```

- **macOS/Linux**:

  ```bash
  source dsie-env/bin/activate
  ```

## 4. Install the Required Dependencies

After activating the virtual environment, install the project's dependencies:

```bash
pip install -r requirements.txt
```

## 5. Set Up Jupyter Notebook

To use Jupyter Notebook, install it by running:

```bash
pip install jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

This will open a new tab in your web browser where you can access the project's notebooks.
<!-- 
## 6. Working with Datasets

### Dataset Acquisition

For deep sea image enhancement, the project requires specific datasets of underwater images. Follow these steps to manage datasets:

1. **Download the Dataset**: You can obtain relevant datasets from online repositories such as:
   - [Kaggle](https://www.kaggle.com/datasets)
   - [NOAA Marine Debris Program](https://marinedebris.noaa.gov/)
   - Custom datasets curated for underwater imagery. -->

<!-- ## 7. Running the Project

To enhance deep-sea images:

1. Open the relevant notebook in Jupyter.
2. Follow the instructions in the notebook, starting from dataset loading, preprocessing, model training (if applicable), and image enhancement.
3. View the results of enhanced images directly in the notebook. -->

## 6. Deactivating the Virtual Environment

After working on the project, deactivate the virtual environment with:

```bash
deactivate
```

## 7. Additional Notes

- **Missing Dependencies**: If you encounter missing dependencies, you can add them to `requirements.txt` using:

  ```bash
  pip freeze > requirements.txt
  ```

- **Updating Datasets**: If you are working with new datasets, adjust the dataset paths and preprocessing code in the notebooks accordingly.
