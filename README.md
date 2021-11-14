## ElectionAnalysis

### Overview of the Election Audit
  Find the key statistical summary for the election commision. Analysis will focus on voter turnout for each county, percentage of votes from each county out of the total count and county with the highest turnout
    
###  Election-Audit Results
  <img width="1037" alt="ElectionStats" src="https://user-images.githubusercontent.com/93223274/141693801-eda8a253-d54d-49ac-b02f-2a9e502804ce.png">

  - Total Votes: 369,711
  - County Votes:
      - Jefferson: 10.51%
      - Denver: 82.78%
      - Arapahoe: 6.71%

  - Largest County Turnout: Denver

  - Breakdown of the number of votes and the percentage of the total votes each candidate received
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

  - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%

### Summary
  Currently script uses the csv module within the python. Script iterate thorugh the all the rows and stores the necessary values in the hash dictonary which is later called to export the necessary values. To improve readiblity of the script some of the modules like pandas and collection can be used. 
