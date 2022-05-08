This project is a collaboration between Shreya Sriram, Sun Hao Ting, Neaton Ang Jia Jun, Charlene Chan Mun Yee, Adam Tan Etai, Zoe Yee Zong Yee. Based on given datasets, our group proposed and wireframe an application to help Malaysians select grocery plans to meet their needs, in terms of health needs, monetary needs, family needs, media habits, etc.

** IMPORTANT: SOME FILES OMITTED DUE TO FILE SIZE. CODE REQUIRES THESE FILES TO WORK, PLEASE CONTACT ME FOR ACCESS TO THESE FILES. **

This folder contains:

-README.txt

-Affordability of food items.ipynb
	to do data exploration on food items that low income families purchase the most

-Consistent Monthly Items Bought.ipynb
	to determine whether we are justified in only using data from January 2021 to do our Market Basket Analysis.

-cosine-sim.ipynb
	to use test cosine similarity and identify items for Siti's Plan

-Data Simulation.ipynb
	to use panelist demographics to simulate data for our analysis, and some basic data exploration

-EDA Daily Purchases and Demographics.ipynb
	to do data exploration on daily purchases over time and demographics

-EDA Media Habit Survey.ipynb
	to do data exploration on the media habit survey to identify trends within age groups

-mba-plans.ipynb
	to use MBA to create different Meal Plans with Add-Ons

-plotsforpart4.ipynb
	to create plots for part 4 of the report


-dailyconsumption.csv
	output of EDA Daily Purchases and Demographics.ipynb,
	contains panelist demographic information joined with their daily calorie consumption

-transcations_joined.csv (omitted due to file size)
	output of EDA Daily Purchases and Demographics.ipynb
	contains DACC_Hackathon_TransactionData.csv joined with additional information on calories

-dates_min_max.csv
	output of EDA Daily Purchases and Demographics.ipynb
	contains the total calories bought, earliest and latest purchase date of each panelist

-siti-test.csv
	as seen in cosine-sim.ipynb,
	cosine similarity of Siti's daily consumption to the Asian and Western plan

-panelists_demog_with_simulations.csv
	output of Data Simulation.ipynb
	contains simulated panelist demographic information



-data
--DACC_Hackathon_Categories_Information_V2.csv
--DACC_Hackathon_Categories_Information.xlsx
--DACC_Hackathon_Media_Habit_Survey.xlsx
--DACC_Hackathon_Panelists_Demogs.xlsx
--DACC_Hackathon_TransactionData.csv	(omitted due to file size)


Requirements:

matplotlib
mlxtend
numpy
pandas
plotly
scipy
seaborn
sklearn
statsmodels
