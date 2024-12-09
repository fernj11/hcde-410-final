Project Overview of COVID Data Analysis in Washington State

This project explores variables influencing COVID-19 case numbers and fatality rates across counties in Washington state. The primary goal was to analyze relationships between demographic, socioeconomic, and healthcare-related variables and their impact on case percentages and fatality rates.

**Datasets Used**

- https://doh.wa.gov/data-statistical-reports/health-behaviors/immunization/covid-19-vaccination-data
Covid vaccine coverage in Washington State Counties.

- https://www.census.gov/quickfacts/fact/table/
Demographic data for Washington State Counties.

- https://usafacts.org/visualizations/coronavirus-covid-19-spread-map/state/washington/
Washington State Covid cases and deaths datasets.

- https://doh.wa.gov/sites/default/files/legacy/Documents/2300/HospPatientData/HospDirPrint.pdf
Washington State hospital directory.

**Key Results**

**Case Numbers**

Positively Correlated:
- Household size (R = 0.75): Larger average household sizes resulted in more reported cases.

Negatively Correlated:
- Population 65+ (R=-0.68): Counties with older populations tended to have fewer cases.

Negligible Correlation:
- Vaccine coverage (R=-0.067) and population density (R=-0.028).

**Fatality Rates**

Positively Correlated:

- Older populations (R=0.45) and poverty levels (R=0.37) were associated with higher fatality rates.

Negatively Correlated:
- Vaccine coverage (R=-0.6): Counties with higher vaccine coverage had significantly lower fatality rates.

Negligible Correlation:
- Population density: More urban counties exhibited slightly lower fatality rates.

**Medical Availability**

Case percentages showed a weak positive correlation with the number of hospitals (R=0.23). Fatality rates also showed a weak negative correlation (R=-0.28), indicating slightly fewer deaths in counties with more hospitals.

**Visualization Highlights**

The visualizations in the study were primarily heat maps and scatterplots.

**Limitations and Implications**

Unaccounted Variables: Factors like healthcare access quality, public health policies, and behavior are not included in this analysis among many other variables are not used in the study

Correlation vs. Causation: Relationships identified do not imply direct causation but show potential trends, and as mentioned there are many variables that tie into pandemic spread and fatality rates.

**Conclusion**

This project illustrates how various factors influence COVID-19 outcomes, highlighting the importance of demographic and socioeconomic characteristics in public health planning. Where the findings can guide public health decisions, by focusing on vulnerable groups like those in poverty and older populations, and also by creating awareness.

ChatGPT was used for coding assitance and helped to format and refine writing (more so with the README).