# Mammals Analysis
---
## Problem Statement
I was inspired by reading Matthew Walker's book Why We Sleep to analyze some sleep data for myself. This exploratory data analysis looks at home body weight, brain weight, gestation period, and life span interplay with predation, exposure, and danger indices to affect total average sleep time, average dreaming time, and average non-dreaming time per night in 62 different mammals including humans.

## Executive Summary
The analysis does not show anything conclusive about the benefits or detriments of sleep but has a number of counter-intuitive findings - life span and total sleep are moderately negatively correlated, body weight and total sleep are moderately and negatively correlated, and that brain weight and dreaming time are moderately and negatively correlated. These are further explored and discussed in the kernel itself.

## Analysis
Initial exploratory data analysis found strong postive correlations between total_sleep, dreaming, and non_dreaming which is to be expected but also moderate negative correlations between life span and total sleep, body weight and total sleep, and brain weight and dreaming time which is surprising and warrants further investigation.

## Data Description
The data utilized for this project came from Open Intro, please see the data dictionary below:

| Feature Name | Description |
|    -----     |   -------   |
| species | species identifier for 62 different mammal species|
| body_wt | body weight in kg for 62 different mammal species |
| brain_wt | brain weight in grams (though listed on website as kg) for 62 different mammal species |
| non_dreaming | average amount of hours per night in non-dreaming sleep for 62 different mammal species |
| dreaming | average amount of hours per night in dream sleep for 62 different mammal species |
| total_sleep | average amount of hours per night in total  sleep for 62 different mammal species |
| life_span | life span in years for 62 different mammal species |
| gestation | time in days for gestation (period of time forming before birth) for 62 different mammal species |
| predation | an index for how likely an animal is to be preyed upon with 1 being the least likely and 5 being the most likely for 62 different mammal species |
| exposure | an index for how likely an animal is to be exposed during sleep with 1 being the least likely and 5 being the most likely for 62 different mammal species |
| danger | an index for how likely an animal is to be danger from other animals with 1 being the least likely and 5 being the most likely for 62 different mammal species |

**Data Sources**
###### https://www.openintro.org/data/index.php?data=mammals

## Conclusions and Recommendations
There are no surprising correlations to dreaming, non-dreaming, or total sleep time, but it is interesting how life span and total sleep are moderately negatively correlated, body weight and total sleep are moderately and negatively correlated, and that brain weight and dreaming time are moderately and negatively correlated; all three of these correlations are counter-intuitive to me. Further questions that I have would need more data to answer include how is life span and likelihood to pass on genes affected as individuals get sleep that varies from the species mean.
