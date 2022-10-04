# Amazon Vine Analysis

## Overview

### Background
Amazon receives reviews written by members of a paid Amazon Vine program as well as nonmembers. The vine program allows companies to pay to have their products reviewed.

### Purpose
The purpose of this analysis is to determine if there is any bias toward favorable reviews from vine members compared to non-vine members.

## Results
Vine Program Reviews Dataframe
![vine_program](Resources/vine_program_df.PNG)

Not Vine Program Reviews Dataframe
![not_vine_program](Resources/not_vine_program_df.PNG)
- In the dataset there were 94 total reviews from the vine program, and 40,471 total reviews not from the vine program
![total_reviews](Resources/total_reviews.PNG)
- There were a total of 48 5-star reviews from vine members and 15,663 5-star reviews from non-vine members.
![total_5star](Resources/total_5star.PNG)
- For vine members, the total percentage of 5-star reviews was 51.06%, and for non-vine members it was 38.7%.
![percemtage_5star](Resources/percentage_5star.PNG)

Final Output for All Results
![final_results](Resources/final_results.PNG)
## Summary
Based on the analysis there does appear to be some positivity bias for reviews in the vine program. 51.06% 5-star reviews from the vine program vs 38.7% from outside the vine program is a significant difference. The total number of reviews from the vine program is far lower, which could cause some skewing of the data due to a low sample size. Another test, including 4-star reviews would be good to see if the bias tracks to all positive reviews, not just 5-star. 
