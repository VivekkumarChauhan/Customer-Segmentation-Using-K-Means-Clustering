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
**The dataset consists of the following columns:**
- index: Data index
- Height(Inches): Height of the person in inches
- Weight(Pounds): Weight of the person in pounds
### Step 5: Visualizing the Clusters
**Once the K-Means algorithm is applied, the clusters will be visualized using a 2D scatter plot with colors indicating different clusters.**
## Project Structure
```bash
height-weight-clustering/
│
├── README.md                # This readme file
├── clustering_project.ipynb  # Main project notebook
├── requirements.txt          # Python dependencies file
```
## Project Walkthrough
1.**Data Loading**: The dataset is loaded from the URL into a pandas DataFrame.
2.**Data Preprocessing **: The Height(Inches) and Weight(Pounds) features are normalized using StandardScaler.
3.**K-Means Clustering**: K-Means is applied to the normalized data, and clusters are formed based on height and weight similarities.
4.**Visualization**: The results are visualized using a scatter plot where each point represents an individual, and different colors represent different clusters.
## Conclusion
The K-Means clustering successfully groups individuals based on height and weight. This project demonstrates the power of unsupervised machine learning in identifying patterns in data without labels.
## Troubleshooting
**If you encounter issues while running the project**:
1.Ensure all dependencies are installed correctly.
2.Check the Python version (should be 3.6 or higher).
3.Verify that the dataset URL is accessible from your system.
For further support, feel free to open an issue in the GitHub repository.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

### Key Points:
- **Project Overview**: Explains the goal and features of the project.
- **Prerequisites and Installation**: Guides users through the setup process, including cloning the repository, setting up a virtual environment, and installing dependencies.
- **Project Structure**: Provides a simple directory layout for clarity.
- **Walkthrough**: Explains what the project does step by step.
- **Troubleshooting**: Helps users resolve common issues.

Let me know if you'd like any modifications or additional details!


