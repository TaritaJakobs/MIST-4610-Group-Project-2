# MIST 4610 Group Project 2

## Team Name:

Team 6

## Team Members:
1. Nico Espinel [@nicoespinel](https://github.com/gne74937/MIST4610GroupProject2)
2. Evan Mahathirath [@evanmahathirath](https://github.com/emahathirath/MIST-4610-Group-Project-2) 
3. Tarita Jakobs [@taritajakobs](https://github.com/TaritaJakobs/MIST-4610-Group-Project-2)
4. Mia Townsend [@miatownsend](https://github.com/MiaGTownsend/MIST4610-GroupProject2-Storms) 
5. Krysta Schwab [@krystaschwab](https://github.com/krystaschwab/MIST4610-KrystaSchwab-GroupProject2-Storms)

## Dataset
The dataset is from https://data.gov/, an open resource for data about the United States. It contains information about storms and severe weather in the United States in 2023. It has 53977 rows and 51 columns. The data types of each column range from strings to numerical values, as well as date-time data types. Some columns are event type(hurricane, tornado, etc.), state, month, number of fatalities, and property damage.


## Question 1 and Significance
What is the cost of property damage caused by tornadoes in Tornado Alley(Texas, Oklahoma, Kansas, Nebraska, Missouri, North Dakota, South Dakota, and Iowa)?

The question is significant because it would be important for insurance companies to allocate the right rates and offer unique plans in this region to cover tornado damage specifically for emergency services, like FEMA, it would be important to know which states are the most significantly affected by tornadoes and provide relief to those areas. This information would be important for the states within tornado alley to ensure that future infrastructure is more secure and resistant to getting damaged in a tornado, especially in Mississippi, Arkansas, and Tennessee.

## Question 1 Results and Analysis

![image](https://github.com/user-attachments/assets/9db77086-fd23-4805-bc59-558952e80ee6) 

This map shows the sum of damage in each state in tornado alley, showing that there is significant damage in this region, and the three states with the most significant damage with Mississippi having 1.5 billion dollars, Arkansas having 700,000, and Tennessee having 414,000 which is significantly higher than the other states. Furthermore, Tornado Alley has been shifting eastward in the past couple of decades to states such as Mississippi, Tennessee and Alabama, which all showed significant damage, while states that were in the historic tornado alley like North Dakota and South Dakota had no damage. This reinforces the idea of the shift of Tornado Alley. 


## Question 2 and Significance
Is there a correlation between fatalities and the amount of property damage a storm causes in the United States?

The significance of this question would be for the use of updating compliance codes in buildings, ensuring proper insurance coverage, and preventing storm-related casualties. It would be important for people to be aware of the correlation between property damage and casualties because it would reinforce the importance of staying up to date with compliance codes for buildings, furthermore, people would know to make sure they take out the right insurance if they live in an area prone to storms. Additionally, if buildings are up to code and safer, then people are less likely to be seriously harmed and killed in a natural disaster, which would be very significant. 

## Question 2 Results and Analysis

![D4A8E24A-255F-45B2-B186-3A680F8F977E_1_201_a](https://github.com/user-attachments/assets/ebef30c7-701f-4750-993a-34659c5de630)  


The graph shows property damage on the x-axis and property damage on the y-axis. Each dot is a storm. After drawing a line of regression, we got an R-square of .29 and a p-value of <.0001, showing the significance of the date and proving a correlation between property damage and number of fatalities. Therefore, we can prove that there is a positive relationship between deaths and property damage, showing that an increase in property damage can lead to an increase in fatalities during natural disasters.

## Data Manipulations
Our dataset consists of two tables: storm details and storm fatalities. We joined them together to acquire more data and show the severity of the natural disasters. The storm fatality consists of data about fatalities of the storm while storm details contain general information about the storms, like the type and location. Additionally, we created a calculated field to change the column "Property damage" from a string to a numeric data type so we can use it to conduct our analysis.

## Tableau Packaged Workbook
[Tableau Workbook](https://github.com/TaritaJakobs/MIST-4610-Group-Project-2/blob/main/MIST4610_Group6.twbx)
## Slide Presentation
[Presentation](https://docs.google.com/presentation/d/1B46KUGu4pRxniZi-3Z1cxYYDa6x0bsMjXq1WEiI80h0/edit?usp=sharing)

## Tarita’s Honors Option
[Link to Google Doc](https://docs.google.com/document/d/1LCuGXBnOrmYiUFvPo0kyIFfiAr1rGX5Xj8dHGfC10vE/edit?usp=sharing)
[Tableau Workbook With Honors Option](https://github.com/TaritaJakobs/MIST-4610-Group-Project-2/blob/main/MIST4610_Group6%20(1).twbx)

## Honors Option Question and Significance
What is the total cost of damaged crops in 2023 in the top 5 farming states in the United States (California, Illinois, Iowa, Texas, Nebraska) caused by natural disasters?

This question is significant especially for farmers, so that they know to take proper precautions for their crops during natural disasters. Perhaps the farmers in Texas, Iowa, and Nebraska can look to what practices the farmers in California and Illinois are implementing, and see if they can use the same methods to protect their crops. Additionally, farmers could take out insurance in appropriate amounts to protect their farms since it is their livelihood. 


## Honors Option Results and Analysis

<img width="1023" alt="5E2E3CE8-3F2E-4034-BF68-383D85DFE415" src="https://github.com/user-attachments/assets/95b500ed-1a11-443d-865d-96a5d75cc261">

I found that although California produces the most crops in the United States, they had the second lowest amount of crop damage, at $51,000. Furthermore, I noticed that states like Texas and Nebraska featured crop damage of over $100,000. 

To analyze this question, I had to convert Damage Crops from a String value into a numerical value, using a calculated field and naming it Damage Crops Numerical:

<img width="692" alt="E598EDCD-C197-4B63-A195-A09CD011C6FB" src="https://github.com/user-attachments/assets/6897b193-e13e-4563-ba4f-c459e1936a3b">


I also used a filter on the states to ensure that only the top 5 crop producing states are showing. 

