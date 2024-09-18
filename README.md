# ENGR4450 - Applied Artificial Intelligence (AI) Tutorials

Welcome to the official repository for **ENGR4450 - Applied Artificial Intelligence (AI)**, a course offered at **Işık University**. This repository contains six Jupyter notebooks (tutorials) prepared by **Burak KILIC**, the course assistant, under the supervision of **Assoc. Prof. Ali Taner KUZU**.

## Course Tutorials

This repository contains the following tutorials, each focusing on key topics in applied artificial intelligence:

- **1_intro_to_scikit_learn-linear_models.ipynb**  
   An introduction to linear models and an overview of the `scikit-learn` library for AI and machine learning in Python.

- **2_linear_models.ipynb**  
   Detailed exploration of bias vs. variance tradeoff and underfitting vs. overfitting.

- **3_k_nearest_neighbors.ipynb**  
   Explanation and implementation of the K-Nearest Neighbors (KNN) algorithm.

- **4_support_vector_machines.ipynb**  
   A guide to Support Vector Machines (SVMs) for classification and regression tasks.

- **5_neural_networks.ipynb**  
   Introduction to artificial neural networks (ANNs), covering the basics of perceptrons and multi-layer perceptrons (MLPs).

- **6_convolutional_neural_networks.ipynb**  
   An introduction to Convolutional Neural Networks (CNNs), designed for image classification tasks.

## Installation

To run these notebooks locally, follow the steps below:

### 1. Clone the repository

```bash
git clone https://github.com/burakai/ENGR4450.git
cd ENGR4450
```
### 2. Set up a virtual environment (optional but recommended)

It is recommended to create a virtual environment to isolate dependencies.
```bash
python -m venv env
source env/bin/activate   # On Windows use `env\Scripts\activate`
```
### 3. Install dependencies

All required dependencies are listed in the `requirements.txt` file. You can install them using `pip`:
```bash
pip install -r requirements.txt
```
### 4. Launch Jupyter Notebook

Once dependencies are installed, launch Jupyter Notebook to access the tutorials:
```bash
jupyter notebook
```
or use Jupyter Lab instead:

```bash
jupyter lab
```
This will open Jupyter in your default web browser. You can navigate to the notebooks and run them interactively.

Alternatively, you can click  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> button to open notebook in Google Colab.

## Sources

The primary source of reference for the tutorials is the official [scikit-learn documentation](https://scikit-learn.org/stable/documentation.html). Other sources have also been used where necessary, and appropriate references are provided within the relevant sections of the tutorials.

## Usage

You are welcome to use and adapt the content in these tutorials for your learning or teaching purposes, as long as you provide proper attribution to the author. Please ensure that any referenced material is properly credited.

If you notice any unreferenced content, mistakes, or have any feedback, feel free to contact me (Burak KILIC) or open an issue in this repository.

## License

Feel free to use these materials, but please give proper credit to **Burak KILIC** for the work.

### Additional Notes:
- Make sure to include a `requirements.txt` file with the necessary libraries, like `scikit-learn`, `numpy`, `matplotlib`, and any other dependencies used in the notebooks.
- The provided installation instructions assume basic familiarity with Git, Python virtual environments, and Jupyter Notebook.
