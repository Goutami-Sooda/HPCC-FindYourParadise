# HPCC Systems Hackathon - Find Your Paradise

## Problem Overview

Have you ever envisioned creating an application that guides individuals to locations where they can achieve the highest quality of life and happiness? The challenge at hand involves analyzing diverse datasets across different domains using the HPCC Systems platform. Participants are tasked with designing an interface to query this data, establish a scoring system, and ultimately deliver personalized recommendations to users via ROXIE, highlighting the most desirable living places. The goal is to provide users with an intuitive form to select preferences, generating unique location scores, possibly categorized by state.

Defining what brings happiness varies from person to person. For this challenge, we've identified four crucial categories:

- **Crime:** Utilizing a dataset spanning 2018-2021, this includes crime statistics by US State, encompassing both overall and violent crimes.

- **Environment (Weather):** Leveraging a dataset covering the last decade, this involves Storm Data in the US, detailing the number of storms by state, as well as injuries and fatalities resulting from weather incidents.

- **Health:** Utilizing a mortality rate dataset from 1980 to 2020, this covers total and average mortality rates by year and state.

- **Education:** This dataset includes the number of public and private schools by state, encompassing total schools, the percentage of private schools, enrollment, and student-to-teacher ratios.

## Solution Approach - Team Believers

Our solution revolves around an extensive analysis of parameter fields within five datasets linked to Education, Health, Crime, Weather, and Population. The process unfolds as follows:

1. **Dataset Analysis:** Thoroughly scrutinizing datasets related to Education, Health, Crime, Weather, and Population.

2. **Data Filtering:** Carefully curating datasets to include only the parameters essential for a comprehensive analysis.

3. **Weighted Scores:** Calculating weighted scores for crucial parameters, emphasizing factors contributing to a superior quality of life.

4. **Cumulative Score:** Deriving a cumulative score for each state based on user-selected parameters.

5. **ROXIE Query:** Designing a dynamic ROXIE query that takes user input to determine parameters for the final score calculation.

6. **Population Density:** Introducing a new dataset considering the population of states, calculating population density, and incorporating it as an additional weighted score.

7. **Conclusion:** Following the analysis, the results indicate that New York emerges with the highest score, making it the most favorable state to reside in within the US.

## Video Solution

Check out our solution in action on YouTube:

[Watch the video](https://youtu.be/VYjG0QSOrVU)

## Hackathon Certificate

Here is my certificate of participation for the hackathon:

![Hackathon Certificate](https://drive.google.com/file/d/1oyt1j9ipAc8MMokbOXKTdeFnd435I7HP/view?usp=sharing)

## Acknowledgments

A special expression of gratitude to HPCC Systems for providing the platform and datasets pivotal to the success of this challenge.
