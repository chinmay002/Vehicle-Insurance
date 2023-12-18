## Vehicle-Insurance

# Objective 
* Construct a model designed to aid insurance companies in identifying and engaging potential customers interested in purchasing vehicle insurance.

# About Data


# Python Packages Used
In this section, I include all the necessary dependencies needed to reproduce the project, so that the reader can install them before replicating the project. I categorize the long list of packages used as -

* **General Purpose**: General purpose packages like urllib, os, request, and many more.
* **Data Manipulation** : Packages used for handling and importing dataset such as pandas, numpy and others.
* **Data Visualization** : Include packages which were used to plot graphs in the analysis or for understanding the ML modelling such as seaborn, matplotlib.
* **Machine Learning** : This includes packages that were used to generate the ML model such as scikit, Smote, XGB etc

# Hypothesis
* Customers may be inclined to buy insurance for new or recently purchased vehicles.
* The cost of insurance is a significant consideration for customers.
* Having a driving license can be a motivating factor for purchasing vehicle insurance.
   * In terms of targeting customers for insurance sales:
* Target owners of older vehicles due to the increased risk of malfunctions.
* Focus on individuals who are currently without insurance as they represent a new market.
* Investigate and utilize effective strategies for customer outreach.

# Exploratory Data Analysis EDA.
* Our data is heavily imbalanced  with 87.74% of data have Response of 0 and just over 12% with Response 1 (People who are interested in buying Insurance)
   ![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/5c3e4954-0a5c-48ba-8e1d-b0b8cf3451a0)

* The data suggests that while the majority of the population is relatively young, with most individuals aged between 20 to 27 years, those who are interested in purchasing insurance tend to be older, with an average age of 45 years. Conversely, the average age of individuals who are not interested in insurance is 37 years, indicating that interest in insurance increases with age.
  ![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/0cfe51d0-e0e1-41be-818a-205eedffa1e2)

* ![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/e1b5e8c7-f933-412f-801a-c3e2e8e1a488)
 ![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/5eb60d85-6854-4ff0-bec1-0d88f85f2083)

* Individuals without a driving license (Driving_License = 0) mostly decline insurance. A very small percentage of those without a driving license accept insurance.
Individuals with a driving license (Driving_License = 1) are more inclined to accept insurance. Despite having a driving license, there is still a notable portion that declines insurance.
**Possession of a driving license seems to correlate with a higher likelihood of accepting insurance**
![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/4c3d6478-85de-4a4a-8306-daeb3ca8c0a4)

* Individuals not previously insured (Previously_Insured = 0) show a higher likelihood of declining insurance (Response 0). A smaller proportion of those not previously insured are willing to accept insurance (Response 1).
* Individuals who were previously insured (Previously_Insured = 1) exhibit an overwhelmingly high acceptance rate for insurance (Response 1). The response of previously insured individuals to decline insurance (Response 0) is minimal.
![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/88992a47-413d-4703-a1a6-f7b3e247b655)

* For vehicles aged 1-2 years, a majority did not accept insurance (Response 0), with a smaller percentage accepting (Response 1). Vehicles less than 1 year old show a high insurance acceptance rate (Response 1) and a lower non-acceptance rate (Response 0).
* Vehicles older than 2 years have a balanced distribution, with a notable percentage declining insurance (Response 0) and a significant proportion accepting it (Response 1)


![image](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/59c7d50d-1ae7-4b9f-adf1-de538bce24b3)



![aws_architecture](https://github.com/chinmay002/Vehicle-Insurance/assets/60249099/d93f7ca9-41c3-4ddf-a49a-54f7d9fd70f8)
