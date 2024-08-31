# Tanzanian-Water-Wells-Project
![numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)  ![pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)   ![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)    ![scikitlearn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)    

![my-image jpg](![alt text](image.png))

### Project Overview

This project aims to develop a machine learning classifier to predict the condition of water wells. The classifier will categorize wells into three conditions: functional, functional-but-needs-repair, and non-functional. The prediction will be based on various features, including the type of pump, installation date, installer information, region, and other relevant data.
---

### Business Understanding
Tanzania is a country in east africa. The country is known for its vast wilderness areas. They include the plains of Serengeti National Park, a safari mecca populated by the “big five” game (elephant, lion, leopard, buffalo, rhino), and Kilimanjaro National Park, home to Africa’s highest mountain Mount kilimanjaro. Offshore lie the tropical islands of Zanzibar, with Arabic influences, and Mafia, with a marine park home to whale sharks and coral reefs.

The World Bank estimates its population at 65.5 million as of 2022 and its land size is about 947,303 km2 (365,756 sq mi).

However, like many other sub-Saharan African countries, Tanzania is a developing country struggling to provide adequate clean water for its population that is growing at 3% per annum.

Extreme poverty measured at the international poverty line of $2.15 per day rate was 44% in 2022 as the population continued to grow at 3% per year. This means an increasing population is not affording the basic quality of life.



### GROUND WATER SITUATION IN TANZANIA
According to [this website](https://www.suaire.sua.ac.tz/items/cf57c442-9327-46f5-8616-359bdc5fb86c) the hydrogeology of Tanzania has not been thoroughly studied and ground water development has concentrated mainly on shallow wells for domestic purposes over a wide part of the country. The results of this study further showed that up to 90% of pumps and other equipment used for water extraction fail due to a lack of repair and maintenance.

Various actors, such as the national and regional governments, religious organizations, and foreign cooperation agencies have established many water points around the country but they are hardly enough. What is worse is that a significant number of the water points are in need of repair while others have failed altogether.

### Business Problem

With the ongoing global climate change, water scarcity has become an increasing problem in Tanzania, as some regions experience either intense and destructive rainfall or long dry spells.

According to the World Bank, only 61% of households in Tanzania currently have access to a basic water-supply, 32% have access to basic sanitation, and 48% have access to basic hygiene. About 31,000 deaths each year emanate from lack of or poor quality water and sanitation, which is costly to the economy.

The average water project in Tanzania about USD 6,000 to USD 8,000 for a hand pump water point, impacting 600-700 lives per well. For mechanized systems, the cost is atleast USD 12,000.

The above cost is too high for a developing country, and given that up to 90% of pumps and other water extraction equipment in Tanzania fail due to lack of repair and maintenance, the country can only provide water to more millions of its people by following effective installation methods and proper maintenance of existing water projects.

Partnering with the government could significantly impact the clean and safe water crisis in Tanzania.

### BUSINESS OBJECTIVE

My main objectives in this project will be:

1.To build a Machine Learning classifier that will predict the condition of a water well (functional, functional-but-needs-repair, and non-functional), using data such as the kind of pump, when it was installed, the installer, the region, and so on.

2.To help the Government of Tanzania find patterns in functional and non-functional wells, to help influence how new wells are built.

3.To find the most important factors that influence whether a pump is functional, functional-but-needs-repair, or non-functional. This can guide the management of new and existing water wells.

4.To find out the geographical distribution of the three classes of water pumps, to help inform which regions need more attention in terms of repair, maintenance, and replacement.

- ## Modelling: 
These predictions can help in decision-making for maintenance, resource allocation, and improving access to safe water supplies and will save the goverment and other stakeholders wastage of resourses.
For this project I choose f1-score as the best performance metric.This project, since it can only be high when both precision and recall are high, I will build several models using different classifiers and then compare the performance metrics to choose the best classifier. These will be:
1.Logistic Regression
2.Decision Tree Classifier
3.K-Nearest Neighbour
4.Cross-validation modelling
5.Resampling of imbalanced target classes
6.GridSearchCV() class for combined hyperparameter tuning
7.Random Forest Classifier
8.eXtreme Gradient Boosting (XGBoost)


The best performing model was Random Forest Metrics for Functional class:
  Precision: 0.8293
  Recall: 0.8320
  F1 Score: 0.8307
Metrics for Functional Needs Repair class:
  Precision: 0.3924
  Recall: 0.4860
  F1 Score: 0.4342
Metrics for Non Functional class:
  Precision: 0.8234
  Recall: 0.7852
  F1 Score: 0.8038
Overall Accuracy: 0.7909

## Recommendation
I recommend that the Government of Tanzania implement my final model to predict the condition of well pumps across the country. This model is capable of accurately assessing the condition of each pump with at least an 80% success rate.

I recommend the government should prioritize the Northern regions of Bukoba and Arusha, where there is a high concentration of pumps that are functional but in need of repair. Additionally, increased focus is needed in the regions of Dodoma and Mtwara, where the density of non-functional pumps is the highest.

I recommend the government need to find out more about why there are more non-functional pumps among the pumps recorded as having zero static head and in areas recorded as having zero population.

I recommend the government need to implement and operationalize a payment scheme for the water points, having observed that the sites where people never pay for water had the highest frequency of non-functional pumps.



 

