# Quality_and_Health
Compose of multiple datasets to predict the risk of diabetes, effects on income, and vaccination.
First dataset:
Found in Kaggle under the name of “Early-Stage Diabetes Risk Prediction Dataset”. 
Attribute information: Age 1.20-65, Sex (Male, Female), the symptoms are answer by yes and no: Polyuria, Polydipsia, sudden weight loss, weakness, Polyphagia, Genital thrush, visual blurring, Itching, Irritability, delayed healing, partial paresis, muscle stiffness, Alopecia, Obesity. The target attribute Class (Positive, Negative).
https://www.kaggle.com/ishandutta/early-stage-diabetes-risk-prediction-dataset 
Second dataset:
Found in Kaggle under the name of “Life Expectancy (WHO)”.
It is divided by Countries, years (2000-2015), status, life expectancy, adult mortality, infant deaths, alcohol, percentage expenditure, hepatitis B, measles, BMI, under-five deaths, polio, total expenditure, diphtheria, HIV/AIDS, GDP, population, Thinness 1-19 years, thinness 5-9 years, income composition of resource, schooling.
However, for this project we will be using data from 201-2015, countries that belong to Asia, and delete some of the columns. 
This dataset will be connected to with the first dataset representing the income of those countries and provide answer to the income being an attribute to have a better health. 
https://www.kaggle.com/kumarajarshi/life-expectancy-who 
Third dataset:
Found in UNICEF under the name of “Cross-sector indicators”. However, as a user your modify the information you want and download the csv. 
The attributes give a percentage of the populations newborns and infants receiving certain vaccinations. This percentage are only for the countries in Asia. Below are some examples:
Percentage of live births who received bacilli Calmette-Guerin (vaccine against tuberculosis); Percentage of surviving infants who received the first dose of DTP-containing vaccine, Percentage of surviving infants who received the third dose of DTP-containing vaccine, Percentage of surviving infants who received the third dose of hep B-containing vaccine.
https://data.unicef.org/resources/data_explorer/unicef_f/?ag=UNICEF&df=GLOBAL_DATAFLOW&ver=1.0&dq=AFG+ARM+AZE+BGD+BHR+BTN+BRN+KHM+CHN+CYP+GEO+IND+IDN+IRN+IRQ+ISR+JPN+JOR+KGZ+LBN+MYS+MDV+MNG+MMR+NPL+OMN+PAK+PHL+QAT+TLS+SAU+LKA+SYR+SGP+PSE+TUR+THA+TKM+TJK+ARE+UZB+VNM+YEM+LAO+KWT+KAZ.IM_BCG+IMMUNISATION+IM_DTP1+IM_DTP3+IM_HEPB3+IM_HEPBB+IM_HIB3+IM_IPV1+IM_MCV1+IM_MCV2+IM_PCV3+IM_POL3+IM_RCV1+IM_ROTAC+IM_YFV+IM_PAB+IM_HPV..&startPeriod=2010&endPeriod=2020&lastnobservations=1 
Note: this dataset has not yet been connected to the other two, other the geographical relationship.
