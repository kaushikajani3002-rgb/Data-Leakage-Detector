** Data Leakage Detection in ML Pipelines

* Overview

This project detects data leakage and bad practices in machine learning pipelines using Python AST (Abstract Syntax Tree) analysis. It analyzes code structure to identify issues such as preprocessing before train-test split, train-test contamination, cross-validation misuse, and temporal leakage.


* Features

Detects common data leakage issues
Provides warnings and suggestions
Analyzes Python ML pipeline code automatically
Supports single file and folder analysis
Saves results in CSV format
Generates labeled dataset (good vs bad pipelines)

* Technologies Used

Python
AST (Abstract Syntax Tree)
Scikit-learn
Pandas
CSV


* Installation
  
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt

* How to Run
  
python your_script_name.py

Then enter:

Path of Python file OR
Folder containing multiple .py files

* Output

Displays analysis report in terminal
Generates a CSV file with:
file name
leakage presence
type of issues detected

* Example Issues Detected

Preprocessing before train-test split
Train-test contamination
Cross-validation misuse
Temporal leakage
Missing evaluation

 * Objective

 To help developers and students detect data leakage, improve machine learning workflows, and ensure models perform reliably in real-world scenarios.

* Future Improvements

GUI interface (Streamlit)
Support for more ML libraries
Automated code correction suggestions
