# Description.
- Python Code for learning basic concepts of data-driven modelling.
- Ipython notebooks format to discuss individual concepts.
  

# Requirements
- Basic knowe

# Installation Requirement:
# Step-by-Step Guide to Create a Conda Environment and Set Up Essential Packages


## Step 1: Install Anaconda or Miniconda
If you haven't installed Anaconda or Miniconda on your machine, you need to do that first. You can download and install them from the following links:
- [Anaconda Distribution](https://www.anaconda.com/products/distribution)
- [Miniconda Distribution (lighter version)](https://docs.conda.io/en/latest/miniconda.html)

## Step 2: Open a Terminal or Command Prompt
Once Anaconda or Miniconda is installed, open your terminal (Linux/macOS) or Command Prompt (Windows).

## Step 3: Create a New Conda Environment
Run the following command to create a new Conda environment. Replace `myenv` with your desired environment name:

```sh
conda create --name myenv python=3.9
```

This will create a new environment named `myenv` with Python 3.9 installed. You can specify other versions of Python if needed.

## Step 4: Activate the Environment
Activate the Conda environment you just created using the following command:

```sh
conda activate myenv
```

On Windows, the command might look like this instead:

```sh
activate myenv
```

## Step 5: Install the Required Packages
Now that your environment is activated, you can install the required packages (`numpy`, `pandas`, `matplotlib`, `scipy`, and `scikit-learn`) using the following command:

```sh
conda install numpy pandas matplotlib scipy scikit-learn
```

Conda will resolve dependencies and install all the specified packages.

## Step 6: Verify the Installation
To make sure the packages are installed correctly, you can start a Python session and try importing them:

```sh
python
```

Then, in the Python shell, run:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import scipy
import sklearn
```

If no errors are thrown, it means the packages have been installed successfully.

## Step 7: (Optional) List Installed Packages
To see a list of all the packages installed in your environment, you can use the following command:

```sh
conda list
```

## Step 8: Deactivate the Environment
Once you are done working in your environment, you can deactivate it using the following command:

```sh
conda deactivate
```

This will return you to the base Anaconda environment.

## Summary:
1. Install Anaconda or Miniconda.
2. Open Terminal or Command Prompt.
3. Create a new Conda environment.
4. Activate the environment.
5. Install `numpy`, `pandas`, `matplotlib`, `scipy`, and `scikit-learn` packages.
6. Verify the installation.
7. (Optional) List installed packages.
8. Deactivate the environment when done.

That's it! Your Conda environment is now set up and ready for data science or machine learning tasks.


## Contact:
Himanshu Sharma
email: himanshu90sharma@gmail.com
