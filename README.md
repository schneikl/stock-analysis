# Election Audit Analysis 

## Project Overview
The purpose of this project is to create a python script that reads election votes by candidate for each county, and then outputs a python script and text file summarizing the results. Ultimately, I evaluated the total number of votes that were cast, the total votes and percentage by county, while then highlighting the county with the most votes. Additionally, to then determine the election winner I calculated the votes and vote percentage by candidate, and declared the winner, highlighting their votes and percentage.

## Results of Election
Evaluating election results, we found the following results:

*Winner: Diana DeGette
    *Winning Vote Count: 272,892
    *Winning Percentage: 73.8%
    
*Largest County Voter Turnout: Denver
    *Voter Turnout: 306,055
    
*Total Election Voter Turnout: 369,711

![Election_Analysis](election_analysis.PNG) 

---

## Summary of Audit
This python analysis can be used for any election, with a couple considerations to be made. First, we are reading results from a 3 column csv file, so similar elections by county could use this same python file, however if you wanted to include other geographical or political attributes we would need to edit the code to include those variables, for example adding state and political party we'd need to add those to be accounted for in the code and perhaps determine votes by party by state or county.

Additionally, if we wanted to dig deeper and see how each candidate performed in each county, we could adjust the code to see that level of granularity and better understand where a candidate has the most/least support.

```bash
Kyle Schneider, 9/20/2020
```
