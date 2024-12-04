# MoMA-project
This is a capstone project for the Code:You Data Analytics course. This project will analyze MoMA (Museum of Modern Art) data to explore the gender diversity of their artists, and to uncover whether or not their artist gender diversity has improved over time. In addition, to compare MoMA artists' data with prominent art history textbook data. 

**Goals:**
1. Determine the percentage of male, female, transgender and non-binary artists represented at MoMA from 1929 to 2024, and the percentage of each gender represented at MoMA after the museum's 2019 renovation and expansion. 
2. Compare MoMA artists' data with artists' data from two popular art history textbooks: *Janson's History of Art* and *Gardner's Art Through the Ages*.

**Steps:**
1. Research overall artist demographics in the U.S., and gender disparities in U.S. art museums.
2. Research MoMA's mission statement and goals for their 2019 renovation and expansion. 
3. Research popular art history textbooks.
4. Determine data needed to support.
5. Review available data.
6. Identify the type of analysis that can be done and list the questions that can be answered.
7. Clean the data.
8. Analyze the data and answer the questions.
9. Visualize the analysis.

## Getting Started

1. Clone this repo.
2. Create a virtual environment and install the packages listed in the `requirements.txt` file.
3. Run the `src/01_discover.ipynb` file to view the raw data.
4. Run the `src/02_clean_moma.ipynb` script to clean the raw MoMA data.
5. Run the `src/03_clean_textbook.ipynb` script to clean the raw art history textbook data.
6. Run the `src/04_analyze.ipynb` file to view the analysis and visualizations.

## Capstone Project Criteria

1. **Loading Data:** per project criteria, I was required to read in two data files. I read in the artworks.csv and art_history.csv files in my `src/01_discover.ipynb` notebook.
2. **Clean and Combine Data:** per project criteria, I was required to clean data and perform a pandas merge of two data sets, and then calculate new values based on the new data set. My cleaning scripts can be found in the `src/02_clean_moma.ipynb` notebook and the `src/03_clean_textbook.ipynb` notebook, and I join the data sets in my `src/04_analyze.ipynb` notebook. This is also where I calculate unique counts, percentages and a summary based on the new joined data set. 
3. **Visualize/Present your data:** per project criteria, I was required to make at least 3 matplotlib or seaborn visualizations. In addition, I had the option of creating a Tableau dashboard to display my data. My six matplotlib/seaborn visualizations can be found in my `src/04_analyze.ipynb` notebook, and my Tableau dashboard can be found [here](https://public.tableau.com/views/MoMAProject/MoMAProjectDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
4. **Best practices:** per project criteria, I was required to utilize a virtual environment and include instructions in my README. These instructions are listed above. In addition, I had the option of creating a custom data dictionary. This data dictionary can be found in my `data/README.md` file.
5. **Interpretation of data:** per project criteria, I was required to annotate my code with markdown cells and code comments. These markdown cells and code comments can be found throughout my project. Note: to create my code I referred to class materials, pluralsight and YouTube videos, official Pandas documentation, stack overflow posts, and ChatGPT. In two instances (in my `src/04_analyze.ipynb`), I used code from ChatGPT. However, I had to make adjustments and changes in the code to make it work. These two instances are noted in my code comments.  


## Project Layout

At a high level, all data is stored in the `data/` directory and all python/pandas code is stored in the `src/` directory.

| File | Description |
| ---- | ----------- |
| `README.md` | General information about the project |
| `data/raw` | Raw data files |
| `data/clean` | Cleaned data files |
| `data/README.md` | Data dictionary for all data sets used in the project. |
| `src/01_discover.ipynb` | Jupyter notebook for data discovery: This notebook shows the thought process for the analysis, it includes research on the project topic, identification of data needed, and identification of cleaning needed. |
| `src/02_clean_moma.ipynb` | The MoMA data cleaning script: This script takes in the raw MoMA data file and performs cleaning, including removing unnecessary columns, renaming columns, separating multiple artist listings, and removing unnecessary rows, etc. |
| `src/03_clean_textbook.py` | The Art History Textbook data cleaning script: This script takes in the raw art history textbook data file and performs cleaning including removing unnecessary columns, and removing unnecessary rows, etc. |
| `src/04_analyze.ipynb` | Jupyter notebook for data analysis and visualization: Aggregates and plots the data to answer the project questions. It includes six matplotlib/seaborn visualizations. |


