# Rent Control 21 - Proposition 21

## Objective
This project was prepared for the CA Election Data Challenge, organized by UC Davis DataLab, and was submitted on October 2020.

This project explores Proposition 21 - Rental Affordability Act, and in particular, intended to answer the following research questions:
* What and where are the current local rent control laws in California?
* What are the socio-demographic attributes related to rent increasing rate?
* Do local rent control laws have significant effect on the rent increasing rate?

## Data Sources

* <b> Proposition 21: </b> https://ballotpedia.org/California_Proposition_21,_Local_Rent_Control_Initiative_(2020)
* <b> AB 1482: </b> https://sfrb.org/article/summary-ab-1482-california-tenant-protection-act-2019
* <b> Prop. 21 VS AB 1482: </b> https://noonprop21.vote/wp-content/uploads/2020/07/HousingFreeze_FactSheets_4-Comparison_v5.pdf
* <b> Local Rent Control Law: </b> https://www.tenantstogether.org/resources/list-rent-control-ordinances-city and https://www.tenantstogether.org/resources/list-rent-control-ordinances-city
* <b> American Community Survey: </b> http://www.dof.ca.gov/Reports/Demographic_Reports/American_Community_Survey/
* <b> Home ownership rate: </b> https://www.ocregister.com/2019/02/28/californias-homeownership-rate-hits-8-year-high/
* <b> Inflation Rate: </b> https://www.usinflationcalculator.com/inflation/current-inflation-rates/

## Directory
1. [raw data](https://github.com/FengYinan/Prop21-Team/tree/master/raw%20data) - Raw data as downloaded from the American Community Survey. Please see txt files in folder for further details.
2. [clean data](https://github.com/FengYinan/Prop21-Team/tree/master/clean%20data) - Clean data.
3. [code](https://github.com/FengYinan/Prop21-Team/tree/master/code) - All code files, both for visualizing and modeling.
4. [image](https://github.com/FengYinan/Prop21-Team/tree/master/image) - Output image files.
5. [docs](https://github.com/FengYinan/Prop21-Team/tree/master/docs) - Output web files.

## Data Visualization
### Current rent control law status
We found that 25 Municipalities in California have Rent Control and/or Just Cause laws.

More details can be found in our [Rent Control Map](https://fengyinan.github.io/Prop21-Team/Rent_Control_Map.html).

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/map%20rent%20control.PNG' width = 500>

### Socio-demographic attributes and other data snapshots
There are four levels of rent control. From the pie chart, we can see that most cites are under level 4, meaning that most cities do not have rent control.

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/Pie%20Chart%20of%20Rent%20Control.png' width = 400>

From plotting 10 counties with the highest median family income, we can see that Marin county has the highest average median family income. However, it does not have the highest rent. In fact, the county with the highest rent is San Mateo County.

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/income_rent_bar.png' width = 500>

Here we see that Marin county is mostly occupied by White population. San Mateo, Santa Clara, and Orange Counties, counties with highest rent, are mostly occupied by White and Asian populations.

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/race_bar.png' width = 500>


## Modeling

Rent has a high linear relation with income, based on correlation coefficient, and most Rent control policies are by cities with large population.

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/scatter%20plot.png' width = 500> 

Rent control laws do not have significant effect on the rent increasing rate. 
Income increasing rate, time, and inflation rate have significant effect on rent increasing rate.

<img src='https://github.com/FengYinan/Prop21-Team/blob/master/image/Model%20results.png' width = 400>


## Conclusions
<b> Data  </b>
* Most cities have no rent control laws.
* Marin County has the highest average family income and does not have the highest rent.
* Counties with high rent are mostly occupied by White and Asian populations.
* Rent has high linear relation with income.
* Most Rent control policies are by cities with large population.

<b> Modeling </b>

Rent control laws do not have significant effect on the rent increasing rate.
Income, time, and inflation rate have significant effect on rent increasing rate.

<b> Limitation </b>

Median income and rent cannot reflect the situation of low-income people.

<b> Further work </b>

To analyze different model types, and check model accuracy.


## Contributors
Yunan Hou, Master's Student, Biostatistics, UC Davis, ynhou@ucdavis.edu

Yinan Fang, Master's Student, Computer Science , The University of Virginia, yf7da@virginia.edu

Stella Dong, PhD Candidate, Applied Mathematics, scdong@ucdavis.edu

Koral Buch, PhD Student, Transportation Technology and Policy, kbuch@ucdavis.edu
