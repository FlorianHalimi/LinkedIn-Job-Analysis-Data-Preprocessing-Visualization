# LinkedIn-Job-Analysis-Data-Preprocessing-Visualization

## Overview
The "LinkedIn Job Postings" dataset sourced from Kaggle, [LinkedIn Job Postings - 2023](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data), contains information related to job postings, companies, skills, and more from LinkedIn's platform.

## Objectives

The primary objective of this data preprocessing assignment is to prepare the "LinkedIn Job Postings" dataset for subsequent analysis. The processed dataset will be utilized to visualize:

1. **Top 10 Companies with the Most LinkedIn Job Postings by cities**

    * Identifying and displaying the companies that have the highest number of job postings on LinkedIn.

2. **Top Skills Required by most Companies**

    * Analyzing and visualizing the most sought-after skills as specified in the job postings by various companies.

## Dataset Files
The dataset comprises several CSV files:

- **job_postings.csv:** Contains job-related information like job ID, company ID, title, description, salary details, location, skills required, etc.
- **companies.csv:** Includes details about companies such as ID, name, description, size, location, etc.
- **job_skills.csv:** Presents a mapping of job IDs to skill abbreviations.
- **skills.csv:**  Features a mapping of skill abbreviations to skill names.

### _Dataset Size_

The CSV files mentioned above have the following unique rows:

_job_postings:_ _33246_ _rows_,  
_job_skills_: _32422  _rows_,_  
_companies:_ _11361 _rows_,_  
_skills:_ _35 _rows__  

## Unused Tables
There are additional tables present in the dataset that were not utilized for this particular analysis, including benefits, job industries, salaries, company industries, company specialties, and employee count.

## Data Quality
The dataset's quality was assessed, and some data preprocessing was necessary before use. Some processing encountered included:

- Missing values in certain columns (e.g., experience levels, company names etc).
- Inconsistent formatting across fields like company details (e.g name and location).
- Duplicates or inconsistencies in job IDs.

## Attribute Types
The dataset contains various types of attributes, such as:
- **Numeric:** Salary-related fields (max_salary, med_salary, min_salary), views, zip codes, etc.
- **Categorical**: job titles, currencies, experience levels, etc.
- **Textual**: Job descriptions, company descriptions, skill names, etc.
- **Boolean**: Remote_allowed, sponsored,etc.

## Steps Taken for Data Preprocessing:
To achieve the above objectives, the following steps were undertaken during the data preprocessing phase:

* Data Cleaning:
    * Handling missing values, correcting inconsistencies, and ensuring data uniformity for accurate analysis.
* Feature Extraction:
    * Extracting and organizing relevant features such as company names and required skills.
* Aggregation:
    * Aggregating data to derive meaningful insights, such as grouping job_id's by skills.
* Integration:
    * Merging or integrating multiple datasets to create a unified and comprehensive dataset for analysis.
* Dimensionality Reduction:
    * Reducing the number of features or variables in the dataset to mitigate the curse of dimensionality, improve model efficiency, and avoid overfitting.
* Categorization: 
    * Assigning categorical labels or grouping values for better representation or analysis.

## Expected Outcome

Upon successful preprocessing of the "LinkedIn Job Postings" dataset, the following visualizations will be created:

- A graphic representation showcasing the top 10 companies with the highest number of job postings by cities on LinkedIn .
- A graphic representation depicting the most in-demand skills sought after by these companies in their job postings.

## Project Setup
To use the code, take the following steps:

1. Install Jupyter Extensions in VS Code:  
    Open VS Code and navigate to the Extensions view. Search for "Jupyter" and install the "Jupyter" extension provided by Microsoft.
2. Install Pandas Library:  
    Pandas is a crucial library for data analysis in Python. You can install it via the terminal or command prompt using pip.  
    Use the command:
    ```
    pip install pandas
    ```
3. To run the code, you'll open the file in Jupyter Notebook and execute the cells containing the code.

Here's a simple guide to running an .ipynb file:  
1. Navigate to the '.ipynb' file
2. Kernel Selection:   
    Ensure that the correct kernel corresponding to the programming language you're using is selected. For Python, the Python kernel should be active.
3. Execute Code Cells:   
    Once the notebook is open, you can run the code cells individually or all at once. Click on a cell containing code and use the "Run" button in the toolbar, or use Shift+Enter as a shortcut to execute the cell. The results (Output) will display directly below the cell. 

<hr>
    