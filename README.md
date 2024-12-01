# Birth Rate Analysis of Australia, USA, and Russia

## Overview
This project analyzes the birth rates of Australia, the United States, and Russia across different time periods using a dataset sourced from **mortality.org**, which maintains population data for various countries. The dataset contains information on male and female birth populations for each year. This project involves visualizing and comparing birth rate trends, as well as identifying significant patterns and disruptions.

## Dataset
The dataset includes birth population data for:
- **Australia**: From 1860 to 2020
- **United States**: From 1933 to 2021
- **Russia**: From 1959 to 2014

### Dataset Columns
- **PopName**: Country name (AUS, USA, RUS).
- **Sex**: Gender (m = male, f = female).
- **Year**: Year of birth records.
- **Births**: Number of births for a given year and gender.

### Data Source
The dataset was sourced from [mortality.org](https://www.mortality.org/), a repository for demographic data across multiple countries.

## Objectives
1. Analyze and compare birth rates across Australia, USA, and Russia.
2. Identify significant trends, disruptions, and gender differences in birth rates.
3. Visualize population growth patterns using line plots.
4. Explore historical events that may have influenced birth rates.

## Tools and Libraries Used
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib**: Data visualization.

## Data Analysis and Results
### 1. Data Cleaning and Preparation
- The dataset was loaded and inspected for missing values.
- Columns relevant to the analysis (Year, Births, and Sex) were extracted for each country.
- Separate dataframes were created for male and female populations in each country.

### 2. Visualization and Findings
#### **Australia (1860–2020)**
- **Trends**:
  - Male births have consistently outnumbered female births.
  - Gradual and uninterrupted population growth since the 1860s.
- **Key Observations**:
  - No significant disruptions caused by global events such as wars.

#### **United States (1933–2021)**
- **Trends**:
  - Population growth has increased steadily since the 1950s.
  - Gender distribution of births has remained nearly equal over time.
- **Disruptions**:
  - Decline in birth rates around the 1960s attributed to:
    1. Vietnam War.
    2. Political and social movements.
    3. Increased availability of contraceptives.
  - Great Recession in 2007 led to another significant decline, influenced by:
    1. High student debt.
    2. High cost of raising children.
    3. Improved occupational opportunities for women.

#### **Russia (1959–2014)**
- **Trends**:
  - Initial gender gap reduced in the 1980s, followed by consistent trends in later years.
  - Decline in population during the mid-1980s due to socio-economic factors.
- **Disruptions**:
  - Fall of the Soviet Union and economic instability led to a significant drop in birth rates.
  - Partial maternity leaves for women and related policies further contributed to declining rates.

#### **Comparison Plot**
A combined plot of birth rates for all three countries highlights the differences in growth trends and disruptions:
- USA and Australia showed steady growth post-1950s.
- Russia experienced significant fluctuations due to historical and socio-economic factors.

## Conclusion
### Key Takeaways:
1. **Australia**:
   - Birth rates remained unaffected by global wars and economic downturns.
   - Consistent growth reflects stable socio-economic conditions.

2. **USA**:
   - Gender distribution is balanced.
   - Significant disruptions observed during the Vietnam War, Great Recession, and other socio-political events.

3. **Russia**:
   - Decline in birth rates during the 1960s and 1980s due to economic and political instability.
   - Recovery in birth rates post-2000 reflects stabilization of socio-economic conditions.

### Overall Observation:
- Males consistently outnumber females in birth counts across all three countries.

## References
1. [Mortality.org](https://www.mortality.org/)
2. Articles on USA birth rate declines:
   - https://www-jstor-org.proxy-bc.researchport.umd.edu/stable/2134321?seq=3
3. Articles on Russia's population trends:
   - https://pubmed.ncbi.nlm.nih.gov/12159342
   - https://www-jstor-org.proxy-bc.researchport.umd.edu/stable/20164190?seq=6

