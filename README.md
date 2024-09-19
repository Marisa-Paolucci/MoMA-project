# MoMA-project
This is a capstone project for the Code:You Data Analytics course. This project will analyze MoMA(Museum of Modern Art) data to explore the gender diversity of their artists, and to uncover whether or not their artist gender diversity has improved over time. 

**Goal:**
Determine the percentage of male, female and nonbinary artists represented at MoMA from 1929 to 2024, represented in each department at MoMA, and represented at MoMA after the museum's 2019 renovation and expansion. 

**Steps:**
1. Research overall artist demographics in the U.S., and gender disparities in U.S. art museums.
2. Research MoMA's mission statement and goals for their 2019 renovation and expansion. 
3. Determine data needed to support.
4. Review available data.
5. Identify the type of analysis that can be done and list the questions that can be answered.
6. Clean the data.
7. Analyze the data and answer the questions.
8. Visualize the analysis.

## Getting Started

1. Clone this repo.
2. Create a virtual environment and install the packages listed in the `requirements.txt` file.
3. Open the `src/01_discover.ipynb` file to view the raw data.
4. Run the `src/02_clean.py` script to clean the raw data.
5. Run the `src/03_analyze.ipynb` file to view the analysis.

## Capstone Project Criteria

1. This README file provides information about the project and how to use the code.
2. `data/README.md` provides the data dictionary for the data used in the project.
3. `src/01_discover.ipynb` is a jupyter notebook using pandas to understand the raw data files.
4. `src/02_clean.py` uses pandas to clean a dataset.
5. `src/03_analyze.ipynb` uses pandas to aggregate and plot the data.

## Project Layout

At a high level, all data is stored in the `data/` directory and all python code is stored in the `src/` directory.

| File | Description |
| ---- | ----------- |
| `README.md` | general information about the project |
| `data/raw` | raw data files |
| `data/clean` | cleaned data files |
| `data/README.md` | Data dictionary for the raw data used in the project. |
| `src/01_discover.ipynb` | Jupyter notebook for data discovery: This notebook shows the thought process for the analysis, it includes research on the project topic, identification of data needed, and identification of cleaning needed. |
| `src/02_clean.py` | Automates the data cleaning script: This script takes in the raw data files and performs cleaning including removing unnecessary columns, renaming columns, and removing unnecessary rows, etc. |
| `src/03_analyze.ipynb` | Jupyter notebook for data analysis: Aggregates and plots the data to answer the project questions. |

