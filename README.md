# Global-Temperature-Analysis-and-Prediction-
# Introduction

Glaciers are melting, sea levels are rising, cloud forests are dying, and wildlife is scrambling to keep pace. It has become clear that humans have caused most of the past century's warming by releasing heat-trapping gases as we power our modern lives. Called greenhouse gases, their levels are higher now than at any time in the last 800,000 years.

We often call the result global warming, but it is causing a set of changes to the Earth's climate, or long-term weather patterns, that varies from place to place. While many people think of global warming and climate change as synonyms, scientists use “climate change” when describing the complex shifts now affecting our planet’s weather and climate systems—in part because some areas actually get cooler in the short term.

Climate change encompasses not only rising average temperatures but also extreme weather events, shifting wildlife populations and habitats, rising seas, and a range of other impacts. All of those changes are emerging as humans continue to add heat-trapping greenhouse gases to the atmosphere, changing the rhythms of climate that all living things have come to rely on.
# Data Sources
I have downloaded the dataset from [Kaggle](https://kaggle.com)
# Purpose
I will be analysing the changes that have been taking place with respect to temperature all around the world. 
My attempt is to understand the trends and patterns behind the rise in temperature and to eventually build a predictive model which can predict the temperature.

# NOTE
I have taken attributes like Monthly Average Temperatures on the basis of countries and cities. I have made these attributes out of data till year 2018 and have copied the same in the attributes of test dataset which includes data after 2018, hence it will not depend on the test dataset target variable.

### Packages used
**sklearn, numpy, pandas, matplotlib, seaborn**
# Exploratory Data Analysis
Performed some analysis to better undertsand the data.

<img src="https://github.com/Vaibhavnaudiyal92/Global-Temperature-Analysis-and-Prediction-/blob/master/download%20(5).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
<img src="https://github.com/Vaibhavnaudiyal92/Global-Temperature-Analysis-and-Prediction-/blob/master/download%20(7).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

<img src="https://github.com/Vaibhavnaudiyal92/Global-Temperature-Analysis-and-Prediction-/blob/master/download%20(4).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
<img src="https://github.com/Vaibhavnaudiyal92/Global-Temperature-Analysis-and-Prediction-/blob/master/download%20(6).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
<img src="https://github.com/Vaibhavnaudiyal92/Global-Temperature-Analysis-and-Prediction-/blob/master/download%20(3).png?raw=true"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />

     

# Conclusion
Right now, I have used just one model without using GridSearchCV and other parameter tuning. I have used Root Mean Squared Error technique for meterics evaluation. With using and comparing more models, I am sure we can get a better functioning model than the current one.
We can also focus our work to analyse the average temperatures of some particular city or country. These points are left for future work.
