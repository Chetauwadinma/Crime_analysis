# Crime_analysis
This in my first analysis on a crime dataset i got on kaggle
#Crime Data Analysis
This repository contains a crime data analysis project, exploring various aspects of crime incidents using Python's data science libraries. The analysis focuses on understanding crime distribution, offender and victim demographics, and relationships between different crime attributes.

###

Table of Contents
Project Overview

Dataset

Analysis and Visualizations

Most Common Crime Categories

Gender Breakdown for Offenders and Victims

Relationship Between Offender Race and Crime Category

Relationship Between Offender Age and Victim Age

How to Run the Analysis

Libraries Used

###

Project Overview
This project aims to provide insights into crime data by performing exploratory data analysis (EDA) and generating visualizations. The key questions addressed include:

What are the most prevalent crime categories?

What is the gender distribution among offenders and victims?

Is there a correlation between offender race and the type of crime committed?

What is the relationship between the ages of offenders and victims?

Dataset
The analysis uses the crime_data.csv dataset. This dataset contains various attributes related to crime incidents, including Category, Offender_Gender, Victim_Gender, Offender_Race, Offender_Age, and Victim_Age.

**Analysis and Visualizations**
The following analyses were performed, and their corresponding visualizations are saved in the output/ directory.

**Most Common Crime Categories**
This analysis identifies the categories of crime that occur most frequently in the dataset.

**Visualization: Distribution of Crime by Category**


![image](https://github.com/user-attachments/assets/16a1e830-3cbb-441e-96b2-27b534d806c0)


The chart above indicates that Violence is the most common crime category, followed by Theft and Miscellaneous crimes.

Gender Breakdown for Offenders and Victims
This section examines the gender distribution of both offenders and victims in the crime incidents.

Visualization: Offender and Victim Gender Breakdown
![image](https://github.com/user-attachments/assets/50b1912d-1100-4c4b-966d-8727aee8f1b5)


The charts show that Male offenders significantly outnumber female offenders, and similarly, Female victims are more numerous than male victims. Specifically, for offenders, there are approximately 5000 male offenders compared to around 1500 female offenders. For victims, there are about 4000 female victims and around 2500 male victims. There's also an 'UNKNOWN' category for victims.

Relationship Between Offender Race and Crime Category
This analysis explores whether certain crime categories are more prevalent among specific offender racial groups.

Visualization: Heatmap of Crime Category by Offender Race
This heatmap provides a visual representation of the number of incidents for each combination of offender race and crime category. Darker shades indicate a higher number of incidents. It reveals the varying frequencies of different crime types across different racial groups of offenders.

Relationship Between Offender Age and Victim Age
This analysis investigates any patterns or correlations between the ages of offenders and victims. A hexbin plot is used to visualize dense data points effectively.

Visualization: Relationship Between Offender Age and Victim Age (Hexbin Plot)
(Note: The actual chart image is 'image_0bb41c.png' as provided.)

This hexbin plot illustrates the density of incidents based on offender and victim ages. Denser areas (darker hexagons) indicate a higher concentration of incidents involving offenders and victims within those age ranges. It helps to identify common age pairings in crime incidents.

How to Run the Analysis
To replicate this analysis, follow these steps:

Clone the repository:

git clone <your-repository-url>
cd <your-repository-name>

Ensure you have the dataset: Place crime_data.csv in the specified path (or update the path in the script). For this analysis, the path used was r"C:\Users\HomePC\Downloads\archive (3)\crime_data.csv".

Install the required libraries:

pip install pandas numpy seaborn matplotlib

Create an output directory:

mkdir output

This directory will store the generated charts.

Run the Python script:

python your_analysis_script_name.py

**Libraries Used**
The following Python libraries were used for this analysis:

pandas: For data manipulation and analysis.

numpy: For numerical operations.

os: For operating system interactions (e.g., creating directories, though not explicitly used in the provided snippet beyond pathing).

seaborn: For creating aesthetically pleasing statistical graphics.

matplotlib.pyplot: For plotting and visualization.

warnings: To manage warning messages.
