# Machine Learning Core Concept Practicals

Practicals on Machine Learning to understand how to use each and every Core Principals and Concepts with real scenarios (examples) for each.

Each '.ipynb' file has a separated example practical which is associated(usage) of a Core concept.

###### This repository contains the practicals which have been done in the Machine Learning module in BSc. (Hons) in Software Engineering degree program at Kotelawala Defence University. 

### File Structure

```
/
├── requirements.txt
├── .gitignore
├── README.md
├── Resources/
│   └── titanic.csv (for titanic.ipynb | Download from Kaggle)
│   └── image.png (for README.md)
└── Notebooks/
    ├── 1. titanic.ipynb
    ├── 2. housing_price.ipynb
    ├── 3. unsupervised_learning.ipynb
    ├── 4. principal_component_analysis.ipynb
    └── 5. support_vector_machines.ipynb
```

---
## Documentation

For a detailed explanation of the core machine learning concepts applied in each practical, please refer to [project wiki](https://github.com/TYehan/ML-Practiacal/wiki):

| Practical                                                                                      | Documentation Link                                                                                           |
|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| Core Machine Learning Concepts in Data Cleaning, Feature Engineering, and Classification (Titanic)                | [Titanic Practical](https://github.com/TYehan/ML-Practiacal/wiki/TITANIC)                                    |
| Core Machine Learning Concepts in Data Preprocessing and Regression Analysis (Housing Price Prediction)             | [Housing Price Prediction](https://github.com/TYehan/ML-Practiacal/wiki/HOUSING_PRICE)                         |
| Core Machine Learning Concepts in Unsupervised Learning via Clustering (Unsupervised Learning)                     | [Unsupervised Learning](https://github.com/TYehan/ML-Practiacal/wiki/UNSUPERVISED_LEARNING)                    |
| Core Machine Learning Concepts in Dimensionality Reduction and Eigenfaces (Principal Component Analysis)           | [Principal Component Analysis](https://github.com/TYehan/ML-Practiacal/wiki/PRINCIPAL_COMPONENT_ANALYSIS)      |
| Core Machine Learning Concepts in Support Vector Machines for Classification (Support Vector Machines)             | [Support Vector Machines](https://github.com/TYehan/ML-Practiacal/wiki/SUPPORT_VECTOR_MACHINES)                |              |

---

## Table of Contents

- [Machine Learning Core Concept Practicals](#machine-learning-core-concept-practicals)
        - [THIs](#this)
    - [File Structure](#file-structure)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Initialization](#initialization)
    - [Clone the Repository](#clone-the-repository)
    - [Create and Activate the Virtual Environment](#create-and-activate-the-virtual-environment)
    - [Install the Required Packages](#install-the-required-packages)
    - [Select the Kernel in Visual Studio Code](#select-the-kernel-in-visual-studio-code)
      - [If the kernel is not available, follow these steps:](#if-the-kernel-is-not-available-follow-these-steps)
    - [Run the Notebook Cells](#run-the-notebook-cells)


---
## Prerequisites

- Install Python (version 3.6 or later) and configure a virtual environment.
- Install Visual Studio Code.
- Install the Python extension for Visual Studio Code.
- (Optionally) Install the Jupyter extension for enhanced notebook support.
- Ensure ipykernel is installed for running notebooks in the selected virtual environment.

---
## Initialization 

### Clone the Repository
```bash
git clone https://github.com/TYehan/ML-Practiacal.git
```

- Open the repository in Visual Studio Code.
- Open the terminal in Visual Studio Code (Ctrl + `).

### Create and Activate the Virtual Environment

```bash
python -m venv .venv
```

- For Windows, activate with:
  
```bash
.venv\Scripts\activate
```

- For macOS/Linux, activate with:
  
```bash
source .venv/bin/activate
```

### Install the Required Packages

Install the dependencies before selecting the kernel to ensure that all necessary packages are available:

```bash
pip install -r requirements.txt
```

### Select the Kernel in Visual Studio Code

Since the IPython kernel is installed using the VS Code Jupyter Notebook extension, follow these steps:
- Open any `.ipynb` file and click on the kernel selection in the top right corner of the notebook
<img src="resources\image.png" alt="alt text" style="width:200px;">

- Select the kernel with the name of the virtual environment you created.
#### If the kernel is not available, follow these steps:
- Press Ctrl + Shift + P (Cmd + Shift + P on macOS) to open the Command Palette.
- Type “Python: Select Interpreter” or “Jupyter: Select Interpreter to start Jupyter server” and select the virtual environment you just created.

### Run the Notebook Cells

Open any `.ipynb` file and execute the cells to view the output.

<hr style="border: 0; height: 2px; background: linear-gradient(to right, rgba(0,0,0,0), #3498db, rgba(0,0,0,0));" />

<div align="center">
    <a href="https://github.com/TYehan">
        <img src="https://img.shields.io/badge/Crafted by-Tharindu Yehan-blue?style=flat-square">
    </a>
</div>