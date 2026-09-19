# Chicago Crime Analysis

A Python-based exploratory data analysis project focused on understanding crime patterns, trends, and characteristics using the Chicago crime dataset.

## Project Overview

This project analyzes Chicago crime data to identify meaningful patterns and trends across crime types, time periods, locations, arrests, and domestic incidents.

The project covers the complete data analysis workflow, including data loading, data familiarization, data cleaning, exploratory data analysis, visualization, and interpretation of results.

## Objectives

The main objectives of this project are to:

- Clean and prepare the crime dataset for analysis
- Understand the structure and characteristics of the data
- Identify the most common crime types
- Analyze crime patterns across different time periods
- Examine crime distribution across months and days
- Analyze arrest patterns
- Explore domestic and non-domestic incidents
- Identify areas with higher numbers of reported crimes
- Generate meaningful insights through data visualization

## Dataset

The dataset used in this project is the Chicago Crimes dataset provided by the City of Chicago Data Portal.

### Dataset Features

The dataset contains information related to reported crime incidents, including:

- Case Number
- Date
- Block
- IUCR
- Primary Type
- Description
- Location Description
- Arrest
- Domestic
- Beat
- District
- Ward
- Community Area
- FBI Code
- Year
- Latitude
- Longitude
- Location

## Technologies and Libraries

The project was developed using Python and Jupyter Notebook.

### Technologies

- Python
- Jupyter Notebook

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

### 1. Data Import and Familiarization

- Import the required Python libraries
- Load the Chicago crime dataset
- Examine the dataset structure
- Inspect columns and data types
- Review basic statistical information

### 2. Data Cleaning

The dataset is prepared for analysis by:

- Identifying and handling missing values
- Removing unnecessary columns
- Standardizing data types
- Creating additional columns where required
- Checking for duplicate records
- Preparing the data for exploratory analysis

### 3. Exploratory Data Analysis

The cleaned dataset is analyzed to answer questions related to:

- Predominant crime types
- Crime distribution over time
- Monthly crime patterns
- Daily crime patterns
- Arrest trends
- Domestic incident trends
- Crime distribution across different areas
- Areas with higher numbers of reported crimes

### 4. Data Visualization

Matplotlib and Seaborn are used to create visualizations that make crime patterns and trends easier to understand.

### Examples of Visualizations

- Bar charts
- Count plots
- Line charts
- Distribution plots
- Comparative visualizations

## Key Analysis Areas

### Crime Types

Identify the most frequently reported crime categories and examine their distribution.

### Temporal Analysis

Analyze crime occurrences across:

- Years
- Months
- Days of the week

### Arrest Analysis

Explore arrest rates across different crime categories and examine how arrest patterns vary.

### Domestic Incidents

Analyze crime incidents classified as domestic and compare them with non-domestic incidents.

### Geographic Analysis

Examine the distribution of reported crimes across different police districts, communities, and locations.

## Repository Structure

text
Chicago-Crime-Analysis/
│
├── 01-Chicago Crime - Python Project Activities.ipynb
├── README.md
├── requirements.txt
└── .gitignore
