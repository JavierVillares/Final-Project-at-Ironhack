## Overpopulation Analysis Project done at Ironhack Spain 2024 as final project

### Project Overview
This project addresses the concern of whether overpopulation will become a significant problem in the future. Through extensive research and analysis of various datasets spanning the last 40 years, I aimed to understand global trends and predict future outcomes.

### Initial Observations
After examining the birth rates data, my initial reaction highlighted a need for deeper investigation. I began by identifying commonalities among countries with low birth rates, noting that many are highly westernized. This led me to analyze several factors, including GDP per capita, average age, growth rates, death rates, and education levels.

### Data Analysis Process
To ensure a comprehensive analysis, I cleaned the data meticulously, addressing any null values and confirming that all countries were accounted for. Utilizing machine learning techniques, I aimed to find the best model with the highest R² score and the lowest MSE. Linear regression with a standard scaler emerged as the most effective model. Predictions indicate that we are approximately 43 years away from reaching a negative growth rate. However, these projections are speculative and should be interpreted with caution due to the long-term nature of the forecast.

### Results Presentation
The results of this analysis are presented through Tableau visualizations for clear and interactive data exploration.

### Next Steps
The next phase involves identifying outliers with high birth rates. If no countries exhibit both high birth rates and high average education levels, the focus will shift to individual family analysis to uncover deeper insights.

### Data Sources and Licensing
This project utilized data from the following sources:

1. [World Bank - Crude Death Rate](https://data.worldbank.org/indicator/SP.DYN.CDRT.IN?end=2021&start=1960&view=chart)
   - Licensed under Creative Commons Attribution 4.0 International (CC-BY 4.0).

2. [Our World in Data - Population and Demography](https://ourworldindata.org/explorers/population-and-demography?facet=none&Metric=Birth+rate&Sex=Both+sexes&Age+group=Total&Projection+Scenario=None&country=CHN~IND~USA~IDN~PAK~NGA~BRA~JPN)
   - Data processed by Our World in Data from United Nations, World Population Prospects (2022).

3. [Our World in Data - Gender Gap in Education Levels](https://ourworldindata.org/grapher/gender-gap-education-levels?country=~JPN)
   - Multiple sources compiled by World Bank (2024) and processed by Our World in Data.

4. [Our World in Data - Age Structure](https://ourworldindata.org/age-structure)
   - Data sourced from United Nations, World Population Prospects (2022).

5. [Our World in Data - Economic Growth](https://ourworldindata.org/economic-growth)
   - Data sourced from Feenstra et al. (2015), Penn World Table (2021).

All datasets used are under the Creative Commons Attribution 4.0 International license, allowing for copying, modifying, and distributing data for any purpose, provided appropriate credit is given and changes are indicated.

### Contact Information
For further inquiries, please contact me via LinkedIn: https://www.linkedin.com/in/javier-villares-zabalza-4713311a2/
