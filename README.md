# Flu-Epidemic-Simulation Project

## Overview
Python simulation of a flu outbreak in a population of 1,000 people, testing how different daily vaccination rates change the number of infections and deaths.

## Model Components
- Susceptible, Infected, Recovered, Dead, and Vaccinated groups tracked each day
- Each infected person has 8 daily contacts with a 3% chance of transmission per contact
- Infected people recover (8% daily chance) or die (1% daily chance)
- Vaccination moves people out of the susceptible group and lowers transmission and death rates
- Randomized day-by-day simulation over 100 days

## Steps Performed
- Set up population, infection, recovery, and death parameters
- Built a baseline outbreak model with no vaccination
- Plotted susceptible, infected, recovered, and dead groups over time
- Added a vaccination parameter to the model
- Compared daily vaccination rates of 0%, 2%, and 5% side by side using a multi-panel Matplotlib figure

## Results
- No vaccination: infections peaked at about 590 people on day 33, with about 75 total deaths
- 2% daily vaccination: infections peaked at about 60 people on day 80, with about 5 total deaths
- 5% daily vaccination: infections peaked at about 40 people on day 20, with about 0 total deaths

## Tools & Libraries
- Python
- Matplotlib
- random module

## Key Takeaway
Vaccination had a large effect on the outbreak. Without it, infections peaked near 590 of 1,000 people and about 75 people died. A 2% daily vaccination rate cut the peak to about 60 and deaths to 5, and a 5% rate nearly stopped the outbreak, with no deaths. Even a small daily vaccination rate kept the flu from spreading widely, since each vaccinated person both removes a potential host and lowers transmission and death rates for everyone else.
