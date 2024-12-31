# Boosting-RecSys-Insurance
Data analysis and development of recommendation models for auto insurance policies.

# Objectives
- Leverage customer data (demographics, behavioral, attitudinal) to understand customer needs and preferences.
- Develop a recommendation system that suggests relevant insurance products.
- Optimize product development and pricing by analyzing the popularity of diverse insurance products.

# Data Cookbook
The dataset used in this project originates from an automobile insurance company. The customer or insurance agent enters the data on the company website while registering to buy automobile insurance. Personal or Identifying Information is removed from the dataset. It contains valuable information about customer demographics, vehicle characteristics, and the specific insurance policies they hold. This comprehensive data provides a rich landscape for exploring and predicting the insurance policy preferences of prospective customers.

# Column and Data Description

1. id - The unique customer id.
2. Gender - The gender of the customer. Either Male or Female.
3. Age - The age of the customer
4. Region_Code - The region code is the Census Bureau of the United States of America–designated regions and divisions of the customer's residential address. It has four possible values:
  - North-East abbreviated as NE
  - Mid-West abbreviated as MW
  - South abbreviated as S
  - West abbreviated as W
5. Location_Type - States whether the customer's residential address is in an urban, suburban, or rural locality.
6. Education - The Education qualification of the customer. It has five possible values:-
  - High School or Below
  - College
  - Bachelors
  - Masters
  - Doctor
7. Annual_Income - The annual income of customer in dollars.
8. Vehicle_Type - The type of vehicle the customer has insured. Vehicle Type has been categorized as follow:-
  - Normal Car
  - SUV
  - Luxury Car
  - Luxury SUV
9. Previously_Insured - 1 if the vehicle has been insured previously with our company or else 0. We will change this in the code to make 0 as No and 1 as Yes
10. Veh icle_Age - States whether the vehicle is less than 10 years old, 10-20 years old, or greater than 20 years old.
11. Vehicle_Damage - Yes if the vehicle has suffered damage in the past or else No.
12. Policy - The Automobile Insurance Policy that the customer holds. The company sells seven different kinds of policies:-
  - Platinium Tier I
  - Platinium Tier II
  - Gold Tier I
  - Gold Tier II
  - Silver Tier I
  - Silver Tier II
  - Basic
