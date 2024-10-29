

#Terrorism Analysis Project

Objective:

The primary goal of this project was to analyze global terrorism data to understand trends, patterns, and regional differences in terrorist activities. Through this analysis, we aimed to answer several key questions:

How has the number of terrorist incidents changed over time?
Are certain regions or time periods associated with higher or lower terrorism rates?
What are the most common methods of attack, and do they vary by region or change over time?
How are the number of incidents and casualties correlated, and are there any noticeable outliers?
Where do most attacks take place, and what patterns of locations can be visualized?

Business Needs:

With an increasing global focus on security and law enforcement, there is a pressing need for insights into the dynamics of terrorist activities:

Predictive Insights: The project provides historical insights that can be leveraged for predictive models, helping anticipate and mitigate future incidents.
Resource Allocation: Understanding the trends and regional variations can help organizations allocate resources to regions more prone to higher incidents.
Policy Development: By identifying common methods and changes over time, government agencies and NGOs can tailor their policies to address current patterns of terrorist activity.

Data Description:

The provided compressed file globalterrorismdb_0718dist.tar.bz2 is an extract from the Global Terrorism Database (GTD) - an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.

Since the number of variables and instances is very large, for this project, feel free to select a subset of columns or a specific timeframe.

Explanation of selected columns:

success - Success of a terrorist strike
suicide - 1 = "Yes" The incident was a suicide attack. 0 = "No" There is no indication that the incident was a suicide
attacktype1 - The general method of attack
attacktype1_txt - The general method of attack and broad class of tactics used.
targtype1_txt - The general type of target/victim
targsubtype1_txt - The more specific target category
target1 - The specific person, building, installation that was targeted and/or victimized
natlty1_txt - The nationality of the target that was attacked
gname - The name of the group that carried out the attack
gsubname - Additional details about group that carried out the attack like fractions
nperps - The total number of terrorists participating in the incident
weaptype1_txt - General type of weapon used in the incident
weapsubtype1_txt - More specific value for most of the Weapon Types
nkill - The number of total confirmed fatalities for the incident
nkillus - The number of U.S. citizens who died as a result of the incident
Hint The provided .tar.bz2 file is a compressed CSV file.

Data Collection and Preprocessing:

The dataset used for this analysis contained records of terrorist attacks around the world, with columns for various attributes, including dates, regions, attack methods, and casualties.

Steps in Data Preprocessing:

Loading and Inspecting the Data: The dataset was loaded and inspected for any inconsistencies.
Handling Missing Values: Key columns such as year, region, attack type, and casualties were checked for missing values. We handled missing data by filtering or imputing where necessary.
Data Filtering: We filtered the data to include only relevant rows, for instance, focusing on incidents that occurred after a certain year or by specific regions.
Creating New Columns: Calculated fields were added to support analysis, such as grouping by year, regions, and attack type to better understand trends.

Methodology:

The methodology consisted of the following analytical steps:

Yearly Trend Analysis: We calculated the number of terrorist incidents per year to understand trends over time. Using line graphs, we visualized the global trend and compared it with regional variations.

Regional Analysis: We grouped data by region to determine which areas had the highest frequency of incidents and casualties. This allowed us to visualize variations across regions.

Attack Type Analysis: By grouping incidents based on the type of attack, we identified the most common methods and explored whether they differed by region or changed over time.
Casualties vs. Incidents Correlation: We explored the relationship between the number of incidents and casualties, identifying potential outliers where casualties were disproportionately high or low.
Geographical Visualization: Using mapping techniques, we plotted attack locations to identify regional hotspots and spatial patterns of terrorist activities.

Insights and Findings:

Increasing Global Trend: A marked increase in terrorist incidents was observed from the early 2000s, peaking around 2014, followed by a slight decrease in recent years.

Regional Variations: Certain regions, such as the Middle East and South Asia, consistently recorded higher numbers of incidents compared to regions like Western Europe or North America.

Most Common Attack Methods: Bombing/explosions and armed assaults emerged as the most common methods of attacks. The preferences for attack methods varied slightly by region, influenced by regional resources and tactics.

Casualties Correlation: The correlation between the number of incidents and casualties was positive, though some years, such as 2014, stood out with disproportionately high casualty counts. These years represented outliers that were further analyzed to understand their context.

Geographical Spread: Mapping revealed high concentrations of incidents in conflict-ridden areas, especially in the Middle East and parts of Africa, indicating geopolitical factors at play.

Conclusion:

The analysis provided valuable insights into the complex dynamics of global terrorism. Key takeaways included the identification of high-risk regions, understanding the preferred methods of attacks over time, and observing trends in casualties.

These findings can aid policymakers and law enforcement agencies in crafting strategies tailored to specific regions, allocating resources to high-risk areas, and understanding the evolution of terrorist tactics. Furthermore, the project sets the foundation for predictive modeling, potentially enabling a proactive approach to tackling future terrorist threats.

Future Work:

Predictive Modeling: Build models that leverage historical data to predict future terrorist activities.
Real-Time Dashboards: Develop interactive dashboards for stakeholders, showing real-time trends in global terrorism.
Deep Dive into Specific Regions: Explore factors contributing to high terrorism rates in specific regions for targeted interventions.
This project demonstrates a thorough analysis of historical terrorism data, from initial exploration to actionable insights, making it a valuable addition to your portfolio. Feel free to expand on any of the points above to highlight specific skills or tools you used in each step.
