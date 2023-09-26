# python-gui

Khinsa F Zahirah
GUI trial using Python

After running the code, there will be a GUI window with dropdown menus
1. Covid-19 Data (choose this if you want to see covid-19 charts)
	1.a. Area Type (nation / region / local authorities; 
	     choose the area type you want to see for the chart)
	1.a.a. England (if you chose nation, the only option will be England. 
             choose this if you want to see England's chart)
	1.a.b. London, South East, South West, etc. (if you chose region, 
             there will be different regions shown as an option. 
             choose any of the region you would like to see the chart of)
	1.a.b.c. York, Derby, Leicester, etc. (if you chose local authorities, 
               there will be different local authorities shown as an option. 
               choose any of the local authority you would like to see the chart of)
2. Stop and Search Data (choose this if you want to see stop and search charts)
	2.a. Age range (10-17, 17-24, 25-34, over 34; 
           choose the age range you want to see for the chart)
	2.b. Gender (Man, Woman, Other; 
           choose the gender you want to see for the chart)
3 and 4. Date range (choose the starting and ending date). 
         For covid data, the date range is from 30/01/2020 to 01/11/2020. 
         For stop and search data, the date range is from 01/01/2021 to 31/12/2021.
         However, you can choose any date range. If the date range is not covered 
         in the data, the charts produced will be blank.
After choosing the options, make sure to click the submit button,
then close the GUI window to see the charts.

Types of charts produced:
Covid-19 Chart 1: An area chart of daily new cases (daily new cases by date) 
			of the appropriate (user’s chosen) area and date
Covid-19 Chart 2: An area chart of new cases rolling sum (new cases rolling sum 
			by date) of the appropriate (user’s chosen) area and date
Covid-19 Chart 3: A bar chart of daily percent change (daily percent change 
			by date) of the appropriate (user’s chosen) area and date
Covid-19 Chart 4: A bar chart of rolling percent change (rolling percent change 
			by date) of the appropriate (user’s chosen) area and date
Stop and Search Chart 1: A histogram of daily stop and search done of the 
				 appropriate (user’s chosen) age range and gender
Stop and Search Chart 2: A histogram of stop and search’s street name of the 
				 appropriate (user’s chosen) age range and gender
Stop and Search Chart 3: A histogram of stop and search’s outcome of the 
				 appropriate (user’s chosen) age range and gender
Stop and Search Chart 4: A histogram of stop and search’s object of search of 
				 the appropriate (user’s chosen) age range and gender
