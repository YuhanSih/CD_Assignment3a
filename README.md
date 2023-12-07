# CD_Assignment3a

## Topic
The topic of this research is to explore the prevalence of suicide worldwide and its relationship with generation and gender, as well as the patterns of these trends over time.


## Research Questions
1. Which generation is more likely to commit suicide?

2. How has the suicide rate changed from 1985-2020?

3. Suicides are more common among men or women?

4. Which are the top ten countries in terms of population and number of suicides?


## Dataset
This datadet is downloaded from [Kaggle](https://www.kaggle.com/datasets/omkargowda/suicide-rates-overview-1985-to-2021/data).

Here is the list of the variables and a brief description.

| Header       | Description                              | Data Type |
| ------------ | ---------------------------------------- | --------- |
| `country` | The name of the country for which the suicide rate data is recorded | object |
| `year` | The year in which the suicides occurred | int |
| `sex` | The gender of the individuals for whom suicide rates are recorded | object |
| `age` | The categorization of individuals into specific age groups to analyze suicide rates across different demographics | object |
| `suicides_no` | The number of recorded suicides | float |
| `population` | The total population of the country | int |
| `suicides/100k pop` | The suicide rate per 100,000 population | float |
| `country-year` | A composite that combines both the country and the year | object |
| `HDI for year` | The Human Development Index (HDI) value corresponding to the given year | float |
| `gdp_for_year ($)` | TThe Gross Domestic Product (GDP) of the country for the specified year | object |
| `gdp_per_capita ($)` | The Gross Domestic Product (GDP) per capita, calculated by dividing the total GDP by the population, providing a measure of economic output per person | float |
| `generation` | A categorization based on average age grouping, representing the birth generations | object |
| `Name` | The precise text used for who is being nominated | string |
