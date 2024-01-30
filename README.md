# Healthcare Appointment No-Show Analysis

## Overview
This project focuses on analyzing healthcare appointment data to understand the factors influencing patient no-shows. The dataset includes information about patient demographics, medical conditions, appointment details, and whether the patient attended the appointment or not.

## Contents
1. [Dataset](#dataset)
2. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
4. [Data Visualization](#data-visualization)
5. [Bivariate Analysis](#bivariate-analysis)
6. [Findings](#findings)
7. [Conclusion](#conclusion)

## Dataset
The dataset contains information about 110,527 healthcare appointments, including details such as patient gender, scheduled day, appointment day, age, medical conditions (scholarship, hypertension, diabetes, alcoholism, handicap), SMS received, and the appointment outcome (show or no-show).

## Data Cleaning and Preprocessing
- Converted date and time columns to standard datetime format.
- Renamed and dropped columns for better clarity.
- Checked for missing values (none found).

## Exploratory Data Analysis (EDA)
- Explored the distribution of variables.
- Analyzed the count of appointments for each day of the week.
- Calculated the percentage of no-show appointments.

## Data Visualization
- Plotted bar charts to visualize the count of appointments for various factors.
- Created a correlation matrix to identify relationships between variables.

## Bivariate Analysis
- Explored the relationship between variables and the likelihood of a no-show.
- Analyzed the distribution of age and gender for patients who attended or missed appointments.

## Findings
- Female patients have a higher appointment count than male patients.
- Patients aged 80 to 121 show a different no-show ratio.
- Scholarship recipients have a slightly lower attendance rate.
- Patients without hypertension or diabetes have a higher attendance rate.
- The majority of appointments are on weekdays, with very few on Saturdays.

## Conclusion
This project provides insights into factors affecting healthcare appointment attendance. The findings can be valuable for healthcare providers in optimizing scheduling and improving patient attendance rates.

Feel free to explore the Jupyter notebook for detailed code and visualizations.

**Note:** Ensure that you have the required libraries installed by running `pip install -r requirements.txt` before running the notebook.
