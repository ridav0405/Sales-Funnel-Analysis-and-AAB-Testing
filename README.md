# Sales-Funnel-Analysis-and-AAB-Testing
This project analyzes user behavior in an application developed by a food startup.
### 🎯 Project Description
This project analyzes user behavior in an application developed by a food startup. The analysis is divided into two main parts:

Sales Funnel Analysis: Investigation of the user journey from first contact to purchase
A/A/B Testing: Evaluation of the impact of changes to the application's sources
### 🔍 Objectives
Sales Funnel:
- Identify at which stages users abandon the purchase process

- Calculate conversion rates between stages

- Determine what percentage of users complete the entire journey

### A/A/B Test:
- Evaluate whether changing fonts affects user behavior.

- Validate the testing methodology with control groups (A/A).

- Make data-driven decisions about the application design.

### 📁 Data Structure
The dataset contains user event records with the following columns:

EventName: Name of the event performed.
DeviceIDHash: Unique user identifier
EventTimestamp: Event timestamp
ExpId: Experimental group (246, 247: control; 248: test)

### 🛠️ Methodology
##### 1. Data Preparation

- Data cleaning and transformation

- Creation of date and time columns

- Data type validation

##### 2. Exploratory Analysis
- Analysis of data completeness over time

- Distribution of users by experimental groups

- Frequency of events

##### 3. Funnel Analysis
- Identification of the sequence of events

- Calculation of conversion rates per stage

- Identification of critical drop-off points

##### 4. A/A/B Testing
- Validation of control groups (A/A testing)

- Statistical comparison between groups

- Analysis of statistical significance

### 🔧 Technologies Used
Python: Main analysis language

Pandas: Data manipulation and analysis

NumPy: Numerical calculations

Matplotlib/Seaborn: Data visualization

SciPy: Statistical testing

Jupyter Notebook: Development environment

### 📊 Visualizations Included
Temporal distribution histograms

Conversion funnel charts

Comparisons between experimental groups

Statistical significance analysis

### 🎓 Proven Skills
Conversion funnel analysis

A/B testing design and analysis