

# Healthcare Exploratory Data Analysis 

## 📊 Overview

This project performs **Exploratory Data Analysis (EDA)** on a **synthetic healthcare dataset** to identify trends, patterns, and insights into healthcare operations. The dataset includes information about patient admissions, treatments, billing, and more. By using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**, this project aims to generate meaningful insights to improve healthcare management and decision-making.

## 🎯 Objective

The objective of this project is to:
1. **Perform Exploratory Data Analysis (EDA)** on the synthetic healthcare dataset.
2. **Identify trends and patterns** related to medical conditions, length of stay, billing amounts, patient demographics, and more.
3. **Visualize the data** using Python libraries to provide better insights into healthcare operations and patient management.
4. **Make data-driven recommendations** for improving patient care, hospital efficiency, and financial management.

## 📥 Dataset

The dataset used in this analysis is a **synthetic healthcare dataset** that simulates real-world healthcare data for patients admitted to various hospitals. The dataset contains **fictional records** of patients, including details like **personal information, medical conditions, treatments, admission dates, billing amounts**, etc.

### Dataset Features:
- **Patient ID**: Unique identifier for each patient.
- **Patient Name**: Name of the patient.
- **Age**: Patient's age.
- **Gender**: Patient's gender.
- **Admission Type**: Type of admission (e.g., urgent, elective).
- **Hospital Name**: Name of the hospital.
- **Health Condition**: The patient's primary health condition (e.g., diabetes, hypertension).
- **Length of Stay (LOS)**: Number of days the patient stayed in the hospital.
- **Billing Amount**: Total amount billed for treatment.
- **Insurance Provider**: Insurance provider covering the treatment.
- **Medication**: List of medications given to the patient.
- **Test Results**: Test results relevant to the patient’s condition.
- **Admission Date**: The date of patient admission.
- **Discharge Date**: The date of patient discharge.
- **Blood Group**: Patient’s blood group.

## 🔑 Key Features

The dataset includes several important features for analysis:
- **Health Conditions**: Information about the patient's health conditions.
- **Billing Information**: Total billing amounts and insurance details.
- **Length of Stay (LOS)**: Number of days the patient stayed in the hospital.
- **Admission Type**: Indicates whether the admission was urgent or elective.
- **Patient Demographics**: Age, gender, and admission details.

## 📈 Key Visualizations and Insights

Here are some key visualizations and the insights they provide:

### 1. **Bar Chart of Negative Bills Per Hospital**

This chart shows the total negative billing amounts for each hospital. It provides insight into:
- **Financial discrepancies** or **billing errors** in hospitals.
- **Hospitals with consistent billing issues** that might require a review of their billing processes or patient treatment records.
- **Trends of negative billing** indicating potential data entry issues, disputes, or refunds.

 <img src= https://github.com/user-attachments/assets/bd8893e3-fea1-4396-9eaa-b5e581746dc7 width=650 height=400/>
 
### 2. **Admissions by Gender and Age Group**

This bar chart shows the number of admissions across different **gender** and **age groups**. Insights include:
- **Gender-specific healthcare needs**: The gender distribution of patients and how it might differ by medical conditions.
- **Age-based healthcare trends**: Older or younger patients might have different health concerns or admission frequencies.

<img src= https://github.com/user-attachments/assets/5b6c98f5-22cf-446e-bbc1-60d230c6722b width=500 height=400/>

### 3. **Bar Graph for Most Common Medical Conditions**

This bar chart visualizes the frequency of the most common medical conditions (e.g., diabetes, hypertension). Key insights include:
- **Prevalence of certain conditions**: The most commonly diagnosed conditions in the hospital, which could influence healthcare priorities.
- **Distribution across demographics**: Identifying patterns such as certain conditions being more prevalent in specific age or gender groups.

  <img src= https://github.com/user-attachments/assets/2b3e3302-f159-44c5-af56-d6e86db61f8e width=500 height=400/>

### 4. **Boxplot on Medical Condition and Days Admitted**

A boxplot is used to show the distribution of **Length of Stay (LOS)** for each **medical condition**. Insights include:
- **Average and range of hospital stays** for each condition, which can help understand the severity of illnesses.
- **Outliers** or cases where the patient's length of stay was unusually long or short for their condition, which may require investigation.

<img src= https://github.com/user-attachments/assets/be27f878-c2a8-449f-927f-7772b258781b width=500 height=400/>

### 5. **Heatmap for Correlation Between Age, Days Admitted, and Billing Amount**

This heatmap visualizes the correlation between **age**, **days admitted**, and **billing amount**. It provides insights into:
- **How age impacts treatment costs**: Older patients may incur higher medical costs due to longer stays or more complex conditions.
- **Length of stay and billing correlation**: Longer hospital stays may lead to higher billing amounts, which can be used for hospital resource planning.
<img src= https://github.com/user-attachments/assets/cdd853a7-e20a-4886-ac4c-5e61015ec86d width=500 height=400/>

### 6. **Line Graph for Length of Stay Over the Years**

A line graph depicting the **trends in length of stay (LOS)** over the years. Insights include:
- **Trends in patient recovery times**: If average LOS is increasing or decreasing, it might reflect changes in patient care, medical advancements, or hospital procedures.
- **Impact of healthcare policies**: How changes in hospital policies or treatment protocols may affect patient stays.
<img src="https://github.com/user-attachments/assets/a3b12150-9d5a-4861-b665-6acca85f3ee1" width=600 height=400/>

## 🛠️ Tools and Technologies

This project uses the following tools and technologies:

- **Python Libraries**:
  - **Pandas**: Used for data manipulation, cleaning, and processing.
  - **Matplotlib**: Used for creating basic visualizations like line graphs, bar charts, and histograms.
  - **Seaborn**: Used for creating more advanced visualizations, such as boxplots, heatmaps, and distribution plots.
  

