
#  ICU Severity Scoring System - APACHE II and APACHE III

Analyzing patient data sets and calculating their Apache II and Apache III scores to get some insights.
## Overview

The ICU Severity Scoring System - APACHE II is a comprehensive and well-documented implementation of the Acute Physiology and Chronic Health Evaluation (APACHE II) scoring system. The primary objective of this project is to provide a reliable tool for healthcare professionals, medical researchers, and developers to assess the condition of patients admitted to an Intensive Care Unit (ICU).

## APACHE II Scoring System

The Acute Physiology and Chronic Health Evaluation (APACHE II) scoring system is a widely recognized method used to quantitatively assess the severity of a patient's illness upon admission to the ICU. By considering various physiological measurements, laboratory values, age, and chronic health conditions, the APACHE II score provides an objective assessment of the patient's condition and helps predict their risk of mortality.

**To address privacy concerns, we are unable to share patient data directly. Instead, we will provide code for discussion and analysis.**

- For more information about scoring system, please visit [msdmanuals](https://www.msdmanuals.com/professional/multimedia/table/acute-physiologic-assessment-and-chronic-health-evaluation-apache-ii-scoring-system).

*Please note that both the APACHE II and APACHE III scoring systems have been tailored to align with the healthcare practices and data from the Iranian healthcare system. As a result, certain scores may exhibit variations when compared to scores derived from other sources and articles.*

The ensuing histogram illustrates the frequency distribution of Apache II scores among patients admitted to the intensive care units (ICUs) across a confluence of four distinct hospitals. The Apache II scoring system, a well-regarded tool for gauging disease severity and prognosticating clinical outcomes within critical care domains, was employed for this assessment. The amalgamated dataset utilized for this analytical endeavor encompasses a total of 6098 patients, thereby affording a comprehensive and robust examination of the distribution of Apache II scores within the purview of these medical institutions.

![all_hospitals](https://github.com/MiladNooraei/Calculating_Apache_II/assets/108691050/93137a81-3231-4520-91ed-71482e0cb8d6)

## Input and Output for APACHE II Scoring System

The provided Excel file comprises four distinct sheets, each corresponding to patients affiliated with four disparate hospital institutions. The resultant Excel file mirrors the structure of the input file, retaining the four original sheets and their respective columns. In addition to replicating the existing content, the output file introduces a pair of supplementary columns denoted as final "APACHE II Score" and "Estimated Mortality" for every individual patient entry.

To visualize a histogram, it is imperative to execute the provided code.

## APACHE III Scoring System

The APACHE III (Acute Physiology and Chronic Health Evaluation III) score is a severity of illness scoring system used in healthcare settings, particularly in intensive care units (ICUs), to assess the severity of illness and predict the risk of mortality for critically ill patients. It's a more advanced version of the earlier APACHE II scoring system.

The APACHE III score takes into account a variety of clinical and physiological variables, including vital signs, laboratory values, and patient demographics, to provide a numerical score that reflects the patient's overall condition. This score is then used to estimate the patient's risk of mortality during their stay in the ICU.

The goal of the APACHE III score is to assist healthcare providers in making clinical decisions, allocating resources, and evaluating the effectiveness of interventions for critically ill patients. It is a valuable tool for risk assessment and quality improvement in critical care settings.

It's important to note that while the APACHE III score is a useful tool in critical care medicine, it should be used in conjunction with clinical judgment and not as the sole determinant of patient care decisions. Additionally, its usage and implementation may vary among healthcare institutions.

- For more information about scoring system, please visit [slideshare](https://www.slideshare.net/drimangalal/icu-scoring-systems).

*Please note that both the APACHE II and APACHE III scoring systems have been tailored to align with the healthcare practices and data from the Iranian healthcare system. As a result, certain scores may exhibit variations when compared to scores derived from other sources and articles.*

**In this project, we computed the APACHE III-J score, an alternative iteration of the APACHE III scoring system.**
- APACHE III: APACHE III is a scoring system developed in the United States and is widely used in various healthcare settings around the world. It was developed based on data from North American ICUs and includes variables that may be specific to the North American patient population.

- APACHE III-J: APACHE III-J, on the other hand, is a version of the APACHE III scoring system specifically adapted for use in Japan. It was developed to better suit the Japanese patient population and healthcare practices. APACHE III-J incorporates adjustments to variables and weights to make the scoring system more relevant and accurate in the Japanese context.

## Input and Output for APACHE III Scoring System

The input file is an Excel spreadsheet consisting of a single sheet, while the output file retains the same structure as the input but includes two additional columns: one for the Apache 3-J Score and the other for the percentage of missing data.

## Comparing APACHE II and APACHE III: Differences in Critical Care Severity Scoring Systems

1 - Overview

This document provides a comparison of the APACHE II (Acute Physiology and Chronic Health Evaluation II) and APACHE III (Acute Physiology and Chronic Health Evaluation III) scoring systems commonly used in healthcare, especially in intensive care units (ICUs), to assess the severity of illness and predict patient outcomes.

2 - Key Differences

2.1 - Complexity and Components

- APACHE II:
  - Includes 12 physiological variables and 2 disease-related variables.
  - Provides a patient's severity of illness score based on these variables.

- APACHE III:
  - More complex, encompassing 17 physiological variables, 2 disease-related variables, and 8 additional variables.
  - Offers a more detailed assessment of a patient's condition.

2.2 - Weighting of Variables

- APACHE II: Variables are assigned weights based on their predictive significance.

- APACHE III: Variables are assigned weights based on statistical analyses of large datasets, resulting in more refined predictions.

2.3 - Mortality Prediction

- APACHE II: Provides predicted mortality rates for groups of patients with similar scores.

- APACHE III: Provides both group-based and individualized mortality predictions based on specific patient data.

2.4 - Data Collection

- APACHE II: Introduced in 1985, based on data from that era.

- APACHE III: Introduced in the early 1990s, incorporates more recent data and statistical methods.

3 - Conclusion

Both APACHE II and APACHE III are valuable tools for assessing the severity of illness in critically ill patients. APACHE III offers greater complexity and individualized predictions, while APACHE II remains in use and may be chosen based on institutional preferences and historical data availability.

*Please note that the choice of scoring system should be made based on the specific needs and practices of the healthcare institution.*
