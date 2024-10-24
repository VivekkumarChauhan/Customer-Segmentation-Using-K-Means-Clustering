# Height and Weight Clustering Project

## Project Overview
This project performs clustering on a dataset that includes height and weight data. The primary goal is to group individuals based on their height and weight using K-Means Clustering. The dataset contains two main attributes:
- `Height(Inches)`: Height of individuals in inches
- `Weight(Pounds)`: Weight of individuals in pounds

### Features:
- Load data from a CSV file
- Preprocess and normalize the data
- Apply K-Means clustering algorithm
- Visualize the clusters

## Prerequisites

To run this project, you will need the following installed on your system:

1. **Python 3.6+**
2. **Jupyter Notebook** or **JupyterLab** (for interactive development)
3. **Required Python libraries**:
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `scikit-learn`

## Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/VivekkumarChauhan/Customer-Segmentation-Using-K-Means-Clustering.git
cd Customer Segmentation Using K-Means Clustering
```
### Step 2: Create a Virtual Environment (Optional but recommended)
If you want to create an isolated environment for the project:
# Create virtual environment
```bash
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On MacOS/Linux:
source venv/bin/activate
```
### Step 3: Install Required Libraries
```bash
# Install necessary packages
!pip install numpy pandas matplotlib seaborn scikit-learn
```

### Step 4: Run the Project
1.**Launch Jupyter Notebook from your terminal by running:**
```bash
jupyter notebook
```
2.**Open the notebook file Customer-Segmentation-Using-K-Means-Clustering.ipynb and run all cells.**
```bash
jupyter notebook
```
## Dataset
**The dataset is loaded from a remote URL:**
- URL: https://people.sc.fsu.edu/~jburkardt/data/csv/hw_200.csv
