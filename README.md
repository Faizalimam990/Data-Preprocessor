# Data Preprocessor Tool

## Overview

The Data Preprocessor Tool is a Python application designed to preprocess CSV files through a user-friendly graphical interface. This tool handles missing values, encodes categorical variables, normalizes numerical features, and detects/removes outliers, making data preparation easier and more efficient.

## Features

- **Load CSV Files**: Easily select and load CSV files for preprocessing.
- **Handle Missing Values**: Fills missing values with mean (for numerical columns) or mode (for categorical columns).
- **Encode Categorical Variables**: Encodes categorical variables using Label Encoding.
- **Normalize Numerical Features**: Standardizes numerical features using Z-score normalization.
- **Detect and Remove Outliers**: Identifies and removes outliers based on the IQR method.
- **Save Processed Data**: Save the cleaned data to a new CSV file.
- **Professional GUI**: A modern Tkinter-based graphical user interface.

## Installation

To use the Data Preprocessor Tool, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/faizalimam990/data-preprocessor-tool.git
   cd data-preprocessor-tool
## Usage

1. **Launch the Tool**: 
   - Run the `data_preprocessor.py` script to open the Data Preprocessor GUI.

2. **Select CSV File**: 
   - Click the **"Select CSV and Process"** button to choose your input CSV file.

3. **Process the Data**: 
   - The tool will automatically handle the following preprocessing tasks:
     - Fill missing values.
     - Encode categorical variables.
     - Normalize numerical features.
     - Detect and remove outliers.

4. **Save Cleaned Data**: 
   - Provide a file path to save the processed data to a new CSV file.

5. **View Results**: 
   - The results of the preprocessing steps will be displayed in the GUI. This includes:
     - Information about missing values.
     - List of categorical columns.
     - List of numerical columns.
     - Details about detected outliers.
