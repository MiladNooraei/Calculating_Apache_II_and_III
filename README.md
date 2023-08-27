
#  ICU Severity Scoring System - APACHE II

Analyzing patient data sets and calculating their Apache II scores to get some insights.
## Overview

The ICU Severity Scoring System - APACHE II is a comprehensive and well-documented implementation of the Acute Physiology and Chronic Health Evaluation (APACHE II) scoring system. The primary objective of this project is to provide a reliable tool for healthcare professionals, medical researchers, and developers to assess the condition of patients admitted to an Intensive Care Unit (ICU).

## APACHE II Scoring System

The Acute Physiology and Chronic Health Evaluation (APACHE II) scoring system is a widely recognized method used to quantitatively assess the severity of a patient's illness upon admission to the ICU. By considering various physiological measurements, laboratory values, age, and chronic health conditions, the APACHE II score provides an objective assessment of the patient's condition and helps predict their risk of mortality.

**Due to privacy considerations, the patient identifiers "Patient_Identifier" and "National_Code" have been anonymized and replaced with the numerical value "0".**

- For more information about scoring system, please visit [msdmanuals](https://www.msdmanuals.com/professional/multimedia/table/acute-physiologic-assessment-and-chronic-health-evaluation-apache-ii-scoring-system).

The ensuing histogram illustrates the frequency distribution of Apache II scores among patients admitted to the intensive care units (ICUs) across a confluence of four distinct hospitals. The Apache II scoring system, a well-regarded tool for gauging disease severity and prognosticating clinical outcomes within critical care domains, was employed for this assessment. The amalgamated dataset utilized for this analytical endeavor encompasses a total of 6098 patients, thereby affording a comprehensive and robust examination of the distribution of Apache II scores within the purview of these medical institutions.

![all_hospitals](https://github.com/MiladNooraei/Calculating_Apache_II/assets/108691050/93137a81-3231-4520-91ed-71482e0cb8d6)

## Input and Output

The provided Excel file comprises four distinct sheets, each corresponding to patients affiliated with four disparate hospital institutions. The resultant Excel file mirrors the structure of the input file, retaining the four original sheets and their respective columns. In addition to replicating the existing content, the output file introduces a pair of supplementary columns denoted as final "APACHE II Score" and "Estimated Mortality" for every individual patient entry.

To visualize a histogram, it is imperative to execute the provided code.
