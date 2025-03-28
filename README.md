# Aviation risk data analysis

## Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

## objective

determining which aircraft are the lowest risk for the company for commercial and private enterprises.
translating findings into actionable insights


## Data
 
 ### data source
the dataset is from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

 ### important fields in the data
- Event date - the date of the occurence of the accident or incident
- location - place of the occurence
- country - country where the occurence took place
- injury serverity - extent of the injury, whether fatal or not
- Aircraft damage - the extent of the damage of the aircraft involved
- Make - the make of the aircraft
- Number of engines - the number of engines of the aircraft involved
- Engine type - the type of engine of the aircraft involved
- Purpose of flight
- Total fatal injuries - the total fatal injuries caused by the occurence
- Total serious injuries - the total minor injuries caused by the occurence
- Total minor injuries - the total minor injuries caused by the occurence
- Weather - the weather condition when the occurence took place
- Broad phase of flight


## Tools Used

Programming language: Python,Jupyter notebook


## visuals
1. bar graph of the engine type of the aircrafts by the total number of accidents
 ![image alt](https://github.com/kibngetich/aviation-data-analysis/blob/6f32b88609c8285f484e48ad92427eedc37818e4/Screenshot%202025-03-27%20122336.png)

    The aircrafts with reciprocating type of engine had the most number of accidents
    The aircrafts with lr type of engine had the least number of accidents


2. bar graph of the number of engines of the aircrafts by the total number of accidents
 ![image alt](https://github.com/kibngetich/aviation-data-analysis/blob/150d4b0f7b98a2f9ea70b1bb2785fef3b459c5d0/Screenshot%202025-03-27%20122559.png)

    The aircrafts with 1 engine had the most number of accidents.Those with 2 engines also had relatively high number of accidents
    The aircrafts with 8 engines had the least number of accidents

 
3. bar graph of the make of the aircrafts by the total number of accidents
  ![image alt](https://github.com/kibngetich/aviation-data-analysis/blob/861371cada9e6a947682ad2b22022b2b6916de7c/Screenshot%202025-03-27%20122828.png)

    cessna and piper recorded very high number of accidents with beech also having relatively high numbers
    hiller had the least number of accidents


## Recommendation

- ### Engine Type
  reciprocating type of engine are most likely to fail hence the aircrafts with this type of engine are not advisable to purchase.
- ### Aircraft Make
   cessna, piper and beech are likely to cause accidents hence it is advisable to avoid them
- ### Number of engines
 The aircrafts with 1 or 2 engines are most likely to fail 
 Aircrafts with many number of engines are more suitable


 ## Tableau link
 https://public.tableau.com/views/aviationriskanalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


  



