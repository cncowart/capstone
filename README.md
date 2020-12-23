# The Remote Work Model, Here to Stay

## Motivation
The motivation behind this analysis is to look into how the economy has been effected by Covid-19 and how a remote work model is both viewed by employees and how it could help to save money for companies that are able to institute some form of a remote model. With the current health climate of the world this information could be very useful for seeing how companies were able to adjust to a massive shift in how work is able to be done. Remote work is something that a lot of companies are trying to institute and has even more benefits now than it did a year ago. Looking at the status of remote work, along with financial data, could produce insights into the importance of remote work for companies in the future.
## Data
* Financial Reports - polygon.io - https://polygon.io/
* Stock Data - Nasdaq - https://www.nasdaq.com/
* GDP Data - https://fred.stlouisfed.org/series/GDP
* Unemployment Data - https://www.bls.gov/opub/ted/2020/unemployment-rate-falls-to-6-point-9-percent-in-october-2020.htm#tab-2
* Survey Data - Buffer x AngelList - https://lp.buffer.com/state-of-remote-work-2020
* Developer Survey Data - StackOverflow - https://insights.stackoverflow.com/survey/

The data used in this project is all very different and was obtained in many different ways. The GDP and unemployment data contain information to help set the scene with how Covid-19 has effected the economy. The financial and stock data contain valuable earnings reports information and insights into daily stock trends. Finally both surveys give a good picture for how remote work is viewed by the employees that work for companies that have some sort of remote work structure.
## Analytical Approach
### Known Issues and Challenges:
* The first major challenge with regard to this analysis was obtaining the necessary data to create a clear picture for what the economy looks like at this juncture.  
* The second and largest challenge, was to find remote work data that could accurately represent how remote workers feel about their remote work situation but was also readily available to be used for analysis
* Finally the third challenge was that 2020 remote work data is not readily available yet and could have really helped to complete the entire picture of what remote work is like in this current day and age

The approach used was to use Python to clean and prepare the data and in some cases, obtain the data as well. Then Tableau was used to prepare visuals to help set the economic scene, show the value of remote work tools, present findings from the survey data and finally to visually show some of the possible benefits of remote work.

## Work
The first step in this analysis was to obtain the many sources of data needed for use in this analysis. Using an API connection, polygon.io provided the financial data needed to help show Net Income, Property Plant and Equipment Nets along with other relevant financial data for helping to show some possible financial benefits of remote work. The unemployment data was obtained via webscraping to help retrieve a table allowing for the making of the line graph that shows the spike in unemployment that occured this year. The other files were flat files found on their respective websites or in the case of the Buffer x AngelList Survey, reaching out to Buffer to obtain the data behind their report going into 2020.
## Overall Summary
## Tools Used
* Python/Pandas - obtain some of the data sources then to clean and explore the data
* Tableau - visualize the data along with being used as a presentation tool
* Git - version control
* Atom - editing ReadMe
