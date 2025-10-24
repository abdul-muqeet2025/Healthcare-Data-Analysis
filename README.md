# Healthcare Data Analysis Project 🏥

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📊 Project Overview

This project demonstrates a comprehensive analysis of healthcare data using Python. The analysis explores patient records, hospital operations, and medical trends to derive actionable insights that can improve healthcare delivery and resource management.

**Dataset Size:** 55,000+ patient records  
**Analysis Type:** Exploratory Data Analysis (EDA)  
**Domain:** Healthcare Analytics

## 🎯 Business Problem

Healthcare institutions face challenges in:
- Optimizing resource allocation and bed management
- Understanding patient demographics and medical conditions
- Analyzing billing patterns and insurance coverage
- Improving patient care pathways and treatment effectiveness

This analysis addresses these challenges by transforming raw healthcare data into meaningful insights.

## 📁 Dataset Description

The dataset contains comprehensive patient information including:

| Feature | Description | Data Type |
|---------|-------------|-----------|
| `Name` | Patient's name | Object |
| `Age` | Patient's age | Integer |
| `Gender` | Patient's gender | Object |
| `Blood Type` | Patient's blood group | Object |
| `Medical Condition` | Primary diagnosis | Object |
| `Date of Admission` | Admission date | DateTime |
| `Doctor` | Attending physician | Object |
| `Hospital` | Hospital name | Object |
| `Insurance Provider` | Insurance company | Object |
| `Billing Amount` | Treatment cost | Float |
| `Room Number` | Assigned room | Integer |
| `Admission Type` | Emergency/Urgent/Elective | Object |
| `Discharge Date` | Discharge date | DateTime |
| `Medication` | Prescribed drugs | Object |
| `Test Results` | Lab test outcomes | Object |

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📈 Project Workflow

### 1. Data Loading & Initial Exploration
- Loaded the dataset using Pandas
- Examined data structure, shape, and basic statistics
- Identified data types and initial quality assessment

### 2. Data Cleaning & Preprocessing
- Handled duplicate records (534 duplicates removed)
- Standardized text formats (patient names capitalization)
- Converted date columns to DateTime objects
- Verified no missing values in the dataset

### 3. Feature Engineering
Created new features to enhance analysis:
- **Stay Duration (Days)**: Calculated from admission and discharge dates
- This feature enables analysis of hospital efficiency and resource utilization

### 4. Exploratory Data Analysis (EDA)

#### Univariate Analysis
- Distribution of patient age, billing amounts, and room numbers
- Frequency analysis of medical conditions, admission types, and test results

#### Key Analysis Areas:
- **Patient Demographics**: Age distribution, gender analysis, blood type prevalence
- **Medical Analysis**: Common conditions, medication patterns, test results
- **Operational Insights**: Admission types, stay duration, room utilization
- **Financial Analysis**: Billing amount distribution across different providers and conditions
- **Hospital Performance**: Doctor and hospital-level analysis

## 💡 Key Insights

### Operational Insights
- **Stay Duration Patterns**: Identified average hospitalization periods across different medical conditions
- **Admission Type Distribution**: Understanding emergency vs. elective admission patterns
- **Room Utilization**: Analysis of room number allocation and potential optimization opportunities

### Financial Insights
- **Billing Analysis**: Distribution of treatment costs across different insurance providers
- **Cost by Condition**: Understanding which medical conditions incur highest costs
- **Insurance Patterns**: Distribution of patients across different insurance providers

### Medical Insights
- **Condition Prevalence**: Most common medical conditions in the dataset
- **Medication Patterns**: Relationship between medical conditions and prescribed medications
- **Test Results**: Analysis of normal vs. abnormal test outcomes

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/healthcare-data-analysis.git
   cd healthcare-data-analysis
