# Tableau-Project
## Spotlighting Water stress level in MENA region

### Project Objective
MENA is the most water stressed region in the world. The consumption is augmenting whereas the supply and internal freshwater availability is declining. The main objective of this project is to analyze "How the region is getting scarce and what measures has to be taken to prevent the region from getting worse".

**Key Intent**:
1. Total Available Freshwater
2. Availability of freswater per capita
3. Water Withdrawal and usage in major sectors
4. Identifying the Stress Level for MENA region
5. Dependency Percentage i.e., How much the country is depending on external resources
6. Best Strategies to opt out

### Data Collection
Collected the below mentioned data for the year range 2009 to 2019 from resources like Worldbank.com, fao.org, Our world in Data.
1. Total Renewable water resource in Billion Cubic meter 
2. Total Renewable water resource per capita 
3. Total Internal and External Water resouces in BCM
4. Water withdrawals in major sectors - Agri, Industrial, Domestic
5. Level of water stress accross the globe

### Data Cleaning
Cleaned the data in Excel and R Programming. Used Pivot functions like Pivot_longer and Pivot_wider to structure and organize the data. 

![image](https://user-images.githubusercontent.com/125816681/220259226-7d75ba70-c141-48a7-a265-afaa55e6ce09.png)

Calculated the dependency percentage using the formula, Dep % = Total External Renewable resource/(Total External renewable resouce + Total Internal renewable resource)

![image](https://user-images.githubusercontent.com/125816681/220260321-cad12079-ad29-4598-80a6-cdd9597efa38.png)

### Data analysis and Visualization
* By Plotting graphs for Available freswater resources and consumption, it is noted that Available freswater decreases year by year while the consumption on the other hand rises yearly. This leads to **Higher stress level** in the region apart from arid climate and climatic changes.

* Iran stands out for highest consumption in **Agricultural sector**. In 2019, the total available freshwater resource is **1652 CM/inhab**, whereas the consumption is **92.5 BCM/inhab**.

* The average per capita renewable water resource availability is ten times less than worldwide range.

* Kuwait is the most stressed region. It depends completely on other countries since there is no internal resource.

* The stress trend from the year 2009 to 2019 shows a rising curve which is an alarming signal for the region. If the situation pesists in the uplcoming years, the region has greatest expected economic losses from climate related water scarcity estimated at 6-14% GDP.

* Best strategies like DESALINATION and RECYCLING should be identified and opted out to scale down the scarcity in MENA region. 

### Tableau Dashboard:

![Project1](https://user-images.githubusercontent.com/125816681/220265131-69932931-0217-47a9-8663-fd0bb0eb38a4.png)

### Technologies Used
* Advance Excel
* Tableau
* R Programming
* Bigquery

### Project References:

| S.No  | Reference  👨‍💻   | Link 🔗|
| ----- |:-------------:|:-----:|
| 1     | Tableau Project Dashboard : Spotlighting Water stress level in MENA region | https://public.tableau.com/app/profile/kashiba.m/viz/Project1_16732724207260/Dashboard1   |
| 2     | Tableau Profile                                                            | https://public.tableau.com/app/profile/kashiba.m/viz/MyResume_16674001460840/FinalResume  |
| 3     | Tableau Chart References                                                   | https://help.tableau.com/current/pro/desktop/en-us/what_chart_example.htm|
