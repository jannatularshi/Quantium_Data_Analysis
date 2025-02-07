# Forage Quantium Data Analytics Virtual Experience Program
This repository contains the submission for the **Forage Quantium Data Analytics Virtual Experience Program**. The project involves analyzing supermarket chip purchases to evaluate customer purchasing behaviors and assess the performance of trial stores with a new layout.

## Project Overview
The goal of the project was to:

- **Analyze different customers' purchasing behaviors**.
- **Evaluate trial store performance against control stores.**
- **Provide insights into customer preferences and assess whether the trial store layout was successful.**
  
## Tasks Overview
**Task 1: Data Preparation and Customer Analytics**
Files: QVI_task1.ipynb
Inputs: QVI_purchase_behaviour.csv, QVI_transaction_data.xlsx

- Data Cleaning: Converted date column to the correct datetime format, removed outliers.
- Analysis: Examined customer behavior segmented by:
   1. LIFESTAGE: Identifies family status and life stages.
   2. MEMBER_TYPE: Differentiates customers based on spending preferences.
   3. Focus: Analyzed the Mainstream Young Singles/Couples segment for product preferences (chip brand and packet size).
      
## Key Insights:

- Top three sales segments: Budget older families, Mainstream young singles/couples, and Mainstream retirees.
- Older families buy more packets, while young singles/couples have the largest population.
- Kettles chips and 175g packets are the most purchased across most segments.
  
**Task 2: Experimentation and Uplift Testing**
Files: QVI_task2.ipynb
Input: QVI_data.csv

- Analysis: Evaluated the performance of trial stores (77, 86, and 88) during the new layout trial period (Feb-Apr 2019).
- Metrics: Compared total sales and customer numbers between trial and control stores using Pearson correlations and magnitude distances.
- Hypothesis Testing: Determined if the differences in store performance were statistically significant.
  
**Key Insights:**

Trial and control store pairs:
- Store 77 with 233
- Store 86 with 155
- Store 88 with 40
1. Store 77 and 86 showed significant improvements in sales and customer numbers.
2. No significant changes were observed in store 88 during the trial.
   
**Task 3: Analytics and Commercial Application**
Output: A PowerPoint report summarizing key insights using the Pyramid Principle.
