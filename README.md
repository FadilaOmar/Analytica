# Sustainable Development Goal Analysis

## Africa Internet Users Analysis

##Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Analysis](#exploratory-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project aims to provide insights into the population of Africans with access to internet in the year 2020. by analyzing various aspects of African Internet Users data, I seek to identify trends,gain a deeper understanding of how accessible internet is to Africans, and as well make data-driven recommendations.

### Data Sources

Africa Internet Users Data: The primary dataset used for this analysis is the "AfricaInternetUsers.csv" file, containing detailed information about total internet user in various African countries.

### Tools

- Microsoft PowerBI [Download here](https://microsoft.com)
  - Power Query - Data Cleaning
  - Data Analysis Expression (DAX) - Data Analysis
  - Charts - Visualizations
 
### Data Cleaning and Preparation

In the initial data preparation phase, I performed the following tasks;
1. Data loading amd inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Analysis

- what are the top 10 African countries with the highest number of internet users?
- what are the bottom 10 African countries with the least number of internet users?
- what is the average and total population of africa as of the year 2020?
- what is the sum and average number of africans with access to internet?

### Data Analysis

```DAX
SUM (population2020)
AVERAGE (population2020)
SUM (AfricaInteretUsers)
AVERAGE (AfricaInteretUsers)
DIVIDE [SUM (AfricaInteretUsers)/SUM (population2020)] * %
```

### Results and Findings

Having interact with this dataset, my findings are as follows;

-	Africa as a continent is lagging behind in the adoption of technology.
-	East and North Africa region has the most countries with good numbers of internet users.

### Recommendations

Based on the analysis, i recommend the following actions;

- The usage of internet should be supported and encouraged more in every part of Africa, most especially in the rural areas.
- Use of internet should be encouraged in the education system for easy penetration and adoption.
- Workshops and seminars to educate Africans on the advantages using the internet should be organised by the governments more often.
- More internet gadgets and tools should be deployed into the education system.


