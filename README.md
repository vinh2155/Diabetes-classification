# Diabetes-classification
## How to Run the Project Locally

You don't need to be a developer to try this project! Follow these simple steps:

### 1. Prerequisites

- **Python**: Make sure you have Python installed. You can download it from [python.org](https://www.python.org/downloads/).
- **Git** (optional): If you want to clone the project using Git. Download it from [git-scm.com](https://git-scm.com/downloads/).

### 2. Download the Project

You have two options:
- **Option 1: Download ZIP**
  1. Click the green `Code` button at the top right of the repository page.
  2. Select `Download ZIP` and extract the files to a folder on your computer.
- **Option 2: Clone with Git**
  1. Open your terminal or command prompt.
  2. Run:
      ```
      git clone https://github.com/vinh2155/Diabetes-classification.git
      ```

### 3. Open a Terminal in the Project Folder

- Navigate to the folder where you extracted or cloned the project.

### 4. Install Required Packages

You'll need some Python packages. Install them using pip:
```
pip install -r requirements.txt
```
*If there is no `requirements.txt`, you might need to install these packages manually:*
```
pip install numpy pandas scikit-learn matplotlib
```

### 5. Run the Project

- If there's a main script (for example, `main.py`, `knn.py`, or `notebook.ipynb`), run it:
    - For `.py` files:
      ```
      python knn.py
      ```
    - For Jupyter Notebook files (`.ipynb`):
      1. Install Jupyter if you don't have it:
          ```
          pip install notebook
          ```
      2. Start Jupyter:
          ```
          jupyter notebook
          ```
      3. Open the notebook file in your browser.

### 6. View Results

- Follow any instructions printed in the terminal or inside the notebook.
- The script should output results or display plots about diabetes classification.

---
### Why did I do this project?

I did this project to test out a new model K-Nearest Neighbors (KNN) and use the cross validation evaluation method. I also learned how to replace missing values, to interpret data using a confusion matrix, to analyze informations using correlation functions. 

**Need help?**  
If you get stuck, please open an issue in this repository or ask for help!
