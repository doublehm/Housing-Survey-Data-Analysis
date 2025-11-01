
# 🏠 Housing Survey Data Analysis

## Project Overview

This repository contains a data analysis project focused on exploring and deriving insights from a **housing survey dataset**. The primary goal is to perform **Exploratory Data Analysis (EDA)**, cleaning, transformation, and statistical analysis on the survey responses to uncover trends, patterns, and correlations related to housing conditions, demographics, and public sentiment.

The entire analysis workflow, from data ingestion to visualization, is documented and executed within a **Jupyter Notebook**.

-----

## 📊 Repository Contents

| File/Folder | Type | Description |
| :--- | :--- | :--- |
| `housing_servey_data.ipynb` | **Jupyter Notebook** | The core analysis script. Contains all the Python code for data cleaning, statistical modeling, analysis, and visualization. |
| `OC_survey.sav` | Data File (SAV/SPSS) | The **raw housing survey data file** in proprietary SPSS format. This file is loaded and processed in the notebook. |
| `out.csv` | Output File (CSV) | Cleaned, processed, or final summarized data resulting from the analysis. |
| `output.png` | Output Image | A key **visualization or chart** generated during the analysis, showcasing a major finding or trend. |
| `out.zip` | Archive | Zipped archive of output files, likely containing `out.csv` or other generated reports. |

-----

## 🚀 Getting Started

Follow these steps to set up the project and run the analysis notebook locally.

### Prerequisites

You will need **Python 3.x** installed, along with several key data science libraries.

It is highly recommended to use a virtual environment.

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/doublehm/Housing-Survey-Data-Analysis.git
    cd Housing-Survey-Data-Analysis
    ```

2.  **Install dependencies:**
    The project relies on standard data science libraries, including a tool to read the proprietary `.sav` file. Create a `requirements.txt` file (if one is missing) and install the necessary packages.

    ```text
    pandas
    numpy
    matplotlib
    seaborn
    pyreadstat # Or another library capable of reading .sav files
    jupyter
    ```

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    Launch the Jupyter Notebook environment:

    ```bash
    jupyter notebook
    ```

    Open the file **`housing_servey_data.ipynb`** and execute the cells sequentially to reproduce the analysis and generate the output files.

-----

## 🛠️ Technologies Used

The project is built using the following core technologies:

  * **Jupyter Notebook**: The main environment for executing the analysis.
  * **Python**: The primary programming language.
  * **Pandas**: Used for data manipulation and analysis.
  * **NumPy**: Used for numerical operations.
  * **Matplotlib / Seaborn**: Used for data visualization.

-----

## 🤝 Contribution

Feel free to **fork** the repository and submit pull requests to suggest improvements to the analysis, add new visualizations, or enhance the documentation.
