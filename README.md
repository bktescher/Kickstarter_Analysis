# Kickstarter_Analysis

## Overview

This is analysis of Kickstarter campaigns.  From the data, we have made observations regarding the success Theater campaigns relative to their launch month.  We also analyzed the success of crowdfunded plays relative to initial goals set for the campaign.
##
## Theater Campaign Success rates
From our comparisons, we've found the highest success rates for campaigns in the spring months with a steady decline through the years' end.

![Outcomes Based on Launch Date](https://github.com/bktescher/Kickstarter_Analysis/blob/main/Resources/Outcomes%20based%20on%20Launch%20Date.png)

May and June held the highest success rates with 111 and 100 respectively.  Failures also spike in May (52) and June (49).  This correlates as these months feature the most total entries at 166 and 153 respectively.  Failed campaigns have a fairly tight range, highest 52 and lowest 31.  

Further analysis could be useful to evaluate correlation between success downtrends and sustained failures in summer months.  There is difficulty evaluating the causation of cancelled projected d/t a relatively small sample size and data missing for the month of October.  

## Goal Amount vs Success/Failure
Success and Failure rates depend entirely upon the Goal amount:

Higher goals = higher chances of failure.  
Lower goals = higher chance of success.  

![Outcomes vs_Goals.png](https://github.com/bktescher/Kickstarter_Analysis/blob/main/Resources/Outcomes%20based%20on%20Goals.png)

In this set of info, we parsed the goal amount in 12 increments ranging from less than $1,000 to Greater than $50,000.  As is turns out, the campaigns with goals set at $20,000 or less were at least 50% successful.  In direct corelation, the failure rates steadily increased with increased goal amounts.  

This set of data was relatively more difficult to obtain than the first set d/t increased factors analyzed in a single snapshot.  Further analysis filtering the data via Country could be useful in discerning local market conditions and favorability.  
