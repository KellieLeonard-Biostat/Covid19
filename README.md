# A Comprehensive Analysis of Clinical Trial COVID-19 Enrolment Across Leading Countries Using Python

**Abstract**
This report investigates clinical trial enrolment across the top 10 leading countries in COVID-19 clinical trials, focusing on study types, enrolment size distribution, and the characteristics of enrolment patterns. By using Python and data visualisation tools such as pandas, seaborn, and matplotlib, this analysis provides insights into global participation in COVID-19 clinical trials, highlighting disparities across different countries. The visualisations include bar plots, count plots, and median enrolment figures, each answering specific questions about clinical trial participation patterns across nations.

**Introduction**
Clinical trials are pivotal in understanding treatments, vaccines, and therapeutic strategies. During the COVID-19 pandemic, countries worldwide participated in clinical trials to address the urgent need for treatments and vaccines. The findings from these trials significantly influenced global healthcare policies and outcomes.
This report focuses on analysing clinical trial data for COVID-19-related studies from the top 10 leading countries, emphasising study types, enrolment sizes, and country-specific patterns. By utilising Python and its robust data science libraries, the report demonstrates advanced skills in data preparation, analysis, and visualisation, providing a reproducible methodology for exploring similar datasets.

**Methods**

The analysis was conducted using the following methodology:

1.	Data Acquisition and Preparation:

    •	The dataset was retrieved from Kaggle’s COVID-19 Clinical Trials Dataset (Pandey, 2020).

    •	The data underwent preprocessing to remove missing values and irrelevant columns. The focus was on enrolment sizes, study types, and country-level data.

2.	Data Filtering and Aggregation:

    •	Countries were ranked based on their total enrolment in clinical trials. The top 10 countries were selected for further analysis.

    •	Study type distribution (interventional vs. observational) was analysed for the top 5 countries.

    •	Median enrolment sizes were calculated for the top 5 countries to identify trends in trial sizes.

3.	Visualisation Techniques:

  	•	Bar plots were used to visualise total enrolment and median enrolment sizes.

  	•	Count plots highlighted the distribution of study types across countries.

  	•	All visualisations employed a pastel colour palette for aesthetic and scientific clarity.

**Results**

**1. Top 10 Countries Contributing to COVID-19 Clinical Trials**

The United States, France, and United Kingdom lead global participation in COVID-19 clinical trials. The total enrolment numbers for these countries demonstrate their strong research infrastructure and active participation in combating the pandemic.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/77029a38-e774-4328-a65f-ee81a0a1df39" />

Figure 1. Top 10 countries contributing to COVID-19 clinical trials 

**Findings:**

•	The United States ranks first with the highest total enrolment, reflecting its robust infrastructure for conducting clinical trials.

•	France and United Kingdom follow, showcasing significant contributions to vaccine and therapeutic development.

•	Other countries, such as Spain and Italy, also demonstrate notable participation, likely due to coordinated European efforts.


**2. Study Type Distribution in the Top 5 Countries**

The study type distribution was analysed to compare the prevalence of interventional and observational trials in the top 5 countries.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/326cc891-9f68-477c-8eca-53586e161950" />

Figure 2.  Study type distribution in top 5 countries 

**Findings:**

•	The United States has the highest number of interventional trials, aligning with its active focus on developing vaccines and treatments.

•	Other countries, like the United Kingdom and Spain, maintain a balance between interventional and observational studies.

•	The prevalence of observational studies in France highlights its focus on understanding the epidemiological and societal impacts of COVID-19.


**3. Median Enrolment in Clinical Trials in the Top 5 Countries**
The median enrolment sizes for the top 5 countries provide insights into the scale of clinical trials.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/79f7e82f-484f-4ba3-bbcb-cded4eba8778" />

Figure 3. Median enrolment in clinical trials (top 5 countries)

**Findings:**

•	The United Kingdom has the largest median enrolment size, indicating a focus on conducting large-scale trials with broad participation.

•	In contrast, the United States has the lowest median enrolment, suggesting a focus on numerous smaller trials targeting specific interventions.

•	These differences reflect varied research strategies: larger trials provide more generalisable results, while smaller trials enable rapid, targeted research.


**Discussion**

The findings emphasise the significant contributions of the United States, France, and United Kingdom to global COVID-19 research. The dominance of interventional studies reflects the urgency of developing treatments and vaccines during the pandemic. The United Kingdom's focus on large-scale trials is noteworthy, as it ensures robust statistical power and generalisability of findings.

The United States, despite having the highest total enrolment, conducts many smaller trials. This strategy enables faster data collection and rapid response but may limit the generalizability of individual studies.

**Limitations**

•	The analysis is based on publicly available data, which may not capture all clinical trials conducted worldwide.

•	Variability in reporting standards and trial registration across countries may introduce biases.

**Conclusion**

This analysis demonstrates how Python can be used to extract meaningful insights from clinical trial datasets. By leveraging bar plots and count plots, the report highlights the contributions of leading countries in COVID-19 clinical trials. The findings underscore the importance of collaborative efforts and diverse research strategies in addressing global health challenges.

