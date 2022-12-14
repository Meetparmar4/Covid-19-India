# What is Corona Virus(COVID-19)?

**Coronavirus is a family of viruses that can cause illness, which can vary from common cold and cough to sometimes more severe disease. SARS-CoV-2 (n-coronavirus) is the new virus of the coronavirus family, which first discovered in 2019, which has not been identified in humans before. It is a contiguous virus which started from Wuhan in December 2019. Which later declared as Pandemic by WHO due to high rate spreads throughout the world. Currently (on date 27 March 2020), this leads to a total of 24K+ Deaths across the globe, including 16K+ deaths alone in Europe.Pandemic is spreading all over the world; it becomes more important to understand about this spread. This NoteBook is an effort to analyze the cumulative data of confirmed, deaths, and recovered cases over time. In this notebook, the main focus is to analyze the spread trend of this virus all over the india.**

# History of COVID-19 in India

**On January 30, India reported its first case of COVID-19 in Kerala, which rose to three cases by February 3; all were students who had returned from Wuhan, China.No significant rise in cases was seen in the rest of February.**

**On 22 March 2020, India observed a 14-hour voluntary public curfew at the instance of the prime minister Narendra Modi.The government followed it up with lockdowns in 75 districts where COVID cases had occurred as well as all major cities.Further, on 24 March, the prime minister ordered a nationwide lockdown for 21 days, affecting the entire 1.3 billion population of India.**

**The transmission escalated during March, after several cases were reported all over the country, most of which were linked to people with a travel history to affected countries. On 12 March, a 76-year-old man who had returned from Saudi Arabia became the first victim of the virus in the country.On 4 March, 22 new cases came to light, including those of an Italian tourist group with 14 infected members.But number of cases start increasing dramtically after 19th March, but in the month of April it has been its peak.**

**Experts suggest the number of infections could be much higher as India's testing rates are among the lowest in the world.The infection rate of COVID-19 in India is reported to be 1.7, significantly lower than in the worst affected countries.**

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
