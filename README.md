# Analysing Covid cases in India from April 2020 to October 2021

## Data collection and cleaning

* I extracted the original data from covid19india.org (indian govt.'s website). It was an excel file wich had no of cases and tests data on an everyday basis from
april 2020 to October 2021. I made the data compact by storing all the columns(days) of a month in 1 column. I also added a population column for each state.
* Transformed the data from original uncleaned data to total cases and total cases 2. Both are uploaded in csv format in this repository.


## Data Analysis

* Analyzed the data with pandas and made visualisations like bar graph, scatter plot and pie charts with seaborn and matplotlib.  
* I then divided the total cases registered within this time period with population of that particular state to get a percentage value of the population positively infected with covid.
* Did the same for vaccination dataset to find the vaccinated  population for each state.

## Inferences
*  Spread of the number of cases in top 5 states contributed to approximately half of the country’s total cases in 2020 as well as in 2021.
*  There was only a single wave in the country till January 2020 (as seen from the upward trend in the graphs) but now as the no. of cases are on a steep rise, we can expect another lockdown soon enough.
* Positive percentage kept on reducing as the year 2020 progressed. But due to slow implementation of vaccination program as well as leniency in Covid protocols, India saw a huge spike in the 2nd wave.
* We saw a huge downfall in the no. of cases from the Month of June 2021 which gave the Govt. of India an opportunity to boost manufacturing and supply chain
* Goa, Chandigarh and Himachal had highest PoPV while it was the least in UP, Bihar.
* States like Kerala, Goa, Delhi were the major contributors for positive cases while states of Bihar, MP and UP contributed the least in 2021
* The maximum percentage of the total population that was infected with the virus among was 3.36% which was in Delhi while the least was in Bihar in 2020.
* According to my analysis Delhi had the highest perc. of it's population infected during this time period which was 3.36% and the min perc. of bihar with 0.2%
* States like Goa and Chandigarh had the most vaccinated population whereas states like Uttar Pradesh, Bihar, Jharkhand and Tamil Nadu were the least.
