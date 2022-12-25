# Election_Analysis_challenge
## Overview of Election Audit
Election data have been recieved from a election team and they asked for data analysis based on it. the data provides candidates name, candidate county and ballot IDs. The main purpose of this analysis is finding the election winner with the percentage of their votes, county with the largest number of votes and other candidates and counties detailed results. Python has been used to perform this study and the data is written in a file and command line for the user.

##Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
The written python code goes through each line of data to count total number of votes, fined each candidate number of votes and each county turnout. The following results is extarcted from the code.
  - The total number of votes were 369,711.
  - The brakdown of the number of votes for each county and their percentage is as follow : 
      Jefferson: 10.5% (38,855)
      Denver: 82.8% (306,055)
      Arapahoe: 6.7% (24,801)
  - Denver county received 82.8% of the total votes with the total of 306,055 votes that has the largest number of votes.
  
  - The brakdown of the number of votes for each candidate and their percentage is as follow : 
      Charles Casper Stockham: 23.0% (85,213)
      Diana DeGette: 73.8% (272,892)
      Raymon Anthony Doane: 3.1% (11,606)
   - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes won the election.

![Code Results](Resources/text_file_pic.png)

##Election-Audit Summary: 

Python has been choosed over excell because there is a lot of data to process when analysing election data. with using python basics codes we are able to have a reliable results. The script can be modified depending on the column that is holding the data. This codes goes through the data line by line and extact the necessary data. This script can be used—with some modifications—for any election data for example:
  - If national election data is provided, this code can find out each state turn-out and candidates votes as long as the data is provided in a similar way.
  - This code can provide detail analysis for any electronic voteing and survays. Therfore it can be used for pre-election survays to know which candidate has more supporter. 
