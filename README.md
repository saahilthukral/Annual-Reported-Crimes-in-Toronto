![R](https://img.shields.io/badge/R-Used-blue)

# Toronto Crime Analysis

This project analyzes the reported crimes in Toronto from the years 2014 to 2019. The dataset used in this analysis is retrieved from the City of Toronto Open Dataset, specifically from the [Police Annual Statistical Report - Reported Crimes](https://open.toronto.ca/dataset/police-annual-statistical-report-reported-crimes/) dataset, last refreshed on November 18, 2022. The dataset provides a comprehensive overview of reported crimes, including details such as year, division, crime category, subtype, count, and count cleared.

## Grade
[Grade Link](https://app.crowdmark.com/score/20aa56e2-9574-44e9-ab68-a18d5e3da005)

## Dataset Overview

The dataset consists of 2701 reported entries with 8 important variables. Here is a breakdown of what each variable represents:

- X_id: (int) Unique row identifier for Open Data database
- ObjectId: (int) Unique identifier from the source system
- ReportedYear: (int) Year crime was reported
- GeoDivision: (chr) Geographic division where the crime took place
- Category: (chr) Crime category
- Subtype: (chr) Crime category subtype
- Count: (int) Total number of crimes
- CountCleared: (int) Total number of crimes identified as cleared

## Background and Significance

The Annual Statistical Report (ASR) of the Toronto Police Service plays a crucial role in providing detailed insights into various police-related statistics. The dataset used in this project focuses on reported crimes between 2014 and 2019, aggregated by division and reported date. It is important to note that the dataset includes crimes that were later deemed unfounded, occurred outside Toronto's limits, or had no verified location.

The Toronto Police Service takes privacy seriously and complies with the Municipal Freedom of Information and Protection of Privacy Act. Personal information related to the reported occurrences is protected to ensure confidentiality. The data is divided into groups based on year, category, subtype, and region.

## Data Collection

The Toronto Police Service collects information through various tools such as incident reports, service requests, officer notes, and other paperwork. This data is then used to produce reports and statistics, which are eventually entered into a central database for the creation of the Annual Statistical Report. Data entry is done manually by police officers or through automated methods, depending on the type of information. Additionally, the Toronto Police Service collaborates with other agencies, including hospitals and community organizations, to gather data.

## Analysis and Research Question

The project aims to answer the following research question: How do the reported crime rates and cleared crimes vary across different GeoDivisions in Toronto every year?

To answer this question, the analysis focuses on examining the reported crime rates and cleared crimes across different GeoDivisions in Toronto for each year. By analyzing the dataset, we can gain insights into the variations in crime rates and cleared crimes, providing a comprehensive understanding of the crime landscape in different regions of Toronto.

The mean values of Count and CountCleared are 374 and 161.3, respectively, which are higher than the median. This indicates the presence of some very high values in both variables, which contribute to the increased mean. The distribution of Count and CountCleared appears to be heavily skewed to the right, as the maximum values are much larger than the mean and median. This suggests the existence of outliers in the data.

In conclusion, this project utilizes the City of Toronto Open Dataset to analyze reported crimes in Toronto. The goal is to understand the variations in crime rates and cleared crimes across different GeoDivisions in the city. The findings from this analysis can contribute to a better understanding of crime patterns and aid in developing strategies for crime prevention and law enforcement.
