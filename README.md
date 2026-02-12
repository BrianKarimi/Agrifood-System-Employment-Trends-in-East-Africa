# East Africa Agricultural Employment Analysis (2000–2023)

Analysis of employment indicators in agriculture across East African countries using ILO, FAO, labour force surveys, household surveys, and census data.

**Dataset source**: [FAOSTAT] (https://www.fao.org/faostat/en/#data/OEA) 
**File**: `Employment_Indicators_Agriculture_E_Africa_NOFLAG.csv`  
**Time period in focus**: 2000–2023  
**Geographic focus**: East Africa (Kenya, Ethiopia, Uganda, Tanzania, Rwanda, Burundi)

## Objectives

1. **Trend Analysis Over Time**  
   → Employment levels, shares (%), year-on-year changes, productivity trends

2. **Comparative Analysis Across Countries / Regions** 

3. **Gender and Demographic Breakdowns**   
   → Male vs Female shares over time  
   → Age distribution in agriculture by gender (sparse survey data)

## Key Visuals & Insights Created

### 1. Time Trends (2000–2023)

- Male agricultural employment (absolute, thousands) – line plots by country
- Share of employment in agriculture (%) – Male only, with YoY % change (dual axis)
- X-axis shows every year (rotated labels for readability)

**Main observations**:
- Absolute male employment generally rising slowly (population effect)
- Share % declining across most countries (structural transformation)
- YoY changes volatile; some years show sharp drops/recoveries

### 2. Gender Comparison

- Male vs Female share % over time (faceted by country)
- 2023 snapshot: bar chart comparing male/female shares per country

**Main observations**:
- Female shares often higher than male (especially Tanzania, Rwanda, Burundi)
- Both genders show long-term decline in agricultural dependence
- Gap (Female – Male) usually positive and relatively stable

### 3. Age Distribution by Gender

**Data source**: Labour force surveys, household surveys, population censuses (not modelled estimates)  
**Limitation**: Very sparse – only a few snapshots per country, not annual series


## Tools & Technologies Used

The analysis was performed using the following tools and libraries:

### Programming & Environment
- **Python** — Core language
- **Jupyter Notebook** — Interactive analysis & visualization

### Core Libraries
- pandas — Data manipulation
- numpy — Numerical support
- matplotlib — Plotting foundation
- seaborn — Statistical visualizations
