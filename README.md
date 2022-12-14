# Kickstarting with Excel

## Overview of Project
Our main character, Louise, did a great job raising funds for her play, Fever. Even though her efforts came close to meeting her goals, it made Louise wonder if campaign outcomes have any correlation to launch dates and funding goals. This factor may have played a key role on her recent campaign outcomes, so Louise decided to find out by utilizing the same Kickstarter dataset.

### Purpose
To determine if any correlation exists between campaign outcomes based on their launch dates and their funding goals, a written report and two data visualizations must be created from the same Kickstarter dataset.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes by Launch Date](https://github.com/lramirez1619/module-1-kickstarter-analysis/blob/fe3c58bc7b30099494ce59b23dfe4457d4a64cc0/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![Outcomes Based on Goals](https://github.com/lramirez1619/module-1-kickstarter-analysis/blob/fe3c58bc7b30099494ce59b23dfe4457d4a64cc0/Resources/Outcomes%20Based%20on%20Goals.png)

### Challenges and Difficulties Encountered
A few challenges and difficulties encountered includes correctly utilizing countifs formula (with greater than, less than, and equal signs) and not factoring plays as a sub-category in addition to dollar goals and outcomes. It was also a challenge that when the pivot chart was created, the amount goals was not in the same order as illustrated. All were challenging but the Learning Assistant team stupendously explained and helped identify errors.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	- The month of May is the most successful month for a launch while December is the worst in comparison. 
	- Even though a steady decline of success was experienced, the months of May to September is the best timeframe to launch.

- What can you conclude about the Outcomes based on Goals?
	- There is an inverse correlation between successful and failed outcomes based on amount goals. There is a chance of 50% success and 50% failure for the amount goal 15000 to 19999.

- What are some limitations of this dataset?
	- The Theater Outcomes by Launch Date only has data for the last three years (2014, 2015, 2016). Considering that the economy has shifted since 2016, this data may no longer depict the current population. 
	- The data was also pulled from 19 different countries, with no specific identifier what part of each country. 

- What are some other possible tables and/or graphs that we could create?
	- For Theater Outcomes by Launch Date, a cluster column and sorted by descending of success.  This will illustrate that in addition to May to September, February and April are also strong months to launch. However, I would still like to see additional years of data. 
	- For Outcomes Based on Goals, a cluster column and sorted by descending of percent of success. This will illustrate those goals of < 1000, 1000 to 4999, 40000 to 44999, and 35000 to 39999 have a 67% or higher success rate with only 33% or lower failed rate
