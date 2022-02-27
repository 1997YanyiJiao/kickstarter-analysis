# kickstarter-analysis
## Overview of Project
A girl name Louise, she had wrote a play called "Fever", it came close to its fundraising goal very soon and she wants to find the correlation between different campaigns and their launch dates and their funding goals, therefore she has me helping her analyzing the statistics with all the data we pulled.  
### Purpose
The purpose of this project is to make data more readable by making graphs eventually help Louise find what she wants.
## Analysis and Challenges
The Analysis was created based on "Theater Outcomes by Launch Date" and "Outcomes Based on Goals", multiple charts were made during the project. 
### Analysis of Outcomes Based on Launch Date
First, I convert the timestamp from the original Kickstarter spreadsheet into the better readable day-month-year format. Then I use the data extracted made a pivot table on a new sheet, named it "Outcomes Based on Launch Date". BY apply filter on category and years, we eventually made a line chart that enabled much better visualize of relation between datas such as months and the successful rate of plays.
### Analysis of Outcomes Based on Goals
The Analysis of Outcomes based on Goals was a little different from the Analysis of Outcomes Based on Launch Data, I made a line chart disply the Percentage of successful or Failed plays and their Goal was. They varioused from less than 1000 to over 50000. 
### Challenges and Difficulties Encountered
I feel one of the major different I have encountered was when I was working "Outcomes Based on Goals" chart, the code work (such as "=COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"=successful",Kickstarter!$R:$R,"=plays")") took me very long time to figured out, because I'm ranther unfamiliar with the formula, and in Excel the formulas we use, they have to be very precise, and one simply mistake of missing one comma may hold I up for long times before I'd try enough times to finally got it right. 
## Results 
## Two conclusions you can draw about the Outcomes based on Launch Date
- the amount of successfully funned plays peaked in May 
- The amout successfully plays has been continuous decreasing since May other than the month of October.
## Two conclusions you can draw about the Outcomes based on Goals
when the goal number is in between 15000$ to 19999$,the percentage of success rate and failed rate are 50/50.
When the goal amount are less than 1000$, success rate is the highest.
## the limitations of this dataset
no dataset is perfect, more details such as what demographic of the audience would be helpful in some ways. 
