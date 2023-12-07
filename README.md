# MIST4610GroupProject2

MIST 4610 9:35-10:50 Group 9 

# TEAM MEMBERS

1. John Hulsey | @J-Hulsey
   
   REPO: https://github.com/purwplhaze/mist4610_project1
   
3. Jack Mathison | @JackMathison
   
   REPO: https://github.com/JackMathison/tissue
   
5. Carson Whitt | @whittcarson

   REPO: https://github.com/whittcarson/MIST4610GroupProject1
   
7. Justin Sullivan | @Justin7ime
   
   REPO: https://github.com/Justn7ime/effective-parakeet
   
9. Hayes Herzog | @purpwlhaze
    
   REPO: https://github.com/purwplhaze/mist4610_project1

# DESCRIPTION OF DATASET
This dataset represents Battery Electric Vehicles (BEV) and Plug-in Hybrid Electric Vehicles (PHEV) that are currently registered through the Washington Department of Licensing. We obtained the dataset from the website provided: (https://catalog.data.gov/dataset/electric-vehicle-population-data). The varying data types include the make and model of the car, VIN number, and electric vehicle type; these data types are strings. Numeric measurements such as the electric vehicle range and base MSRP are of datatype number(whole), with the date of the model of the car being of datatype date & time. This dataset helps us depict the reality of electric vehicles within the state of Washington within the period of 1997 to the present day and draw conclusions for consumers based upon this dataset.

# QUESTION 1

### QUESTION: 
Is there a correlation between newer PHEV and BEV car models and longer electric car ranges? And if so, how significant is that correlation?

### SIGNIFICANCE: 
The general significance of this question lies with the consumer in the electric vehicle market, especially in areas similar to the state of Washington. The answer to this question provides potential consumers with information regarding the relationship between newer car models and electric car ranges among Plug-in Hybrid Electric Vehicles (PHEV) and Battery Electric Vehicles (BEV). Depending on which car model the consumer prefers, this information would help them consider if purchasing a newer car model will generally lead to improved range on their vehicle.
### GRAPH 1
![image](https://github.com/Justn7ime/MIST-Project-2/assets/148248332/294b61f2-c10e-4840-9624-2d8c6b391168)

After analyzing the average electric range of cars from this dataset by manufacturing year and type, we can infer that there is a significant increase in the electric range of Battery Electric Vehicle (BEV) models created from 2000 to 2010 of over 240 miles on average. Post 2010 there was actually a sharp decline in average electric range temporarily, with a steady recovery to the rate we saw in 2010 models. We can also see that by 2020, the average electric range of new BEVs surpassed that of any year in Washington. Also included and labeled in orange are Plug-in Hybrid Electric Vehicles (PHEV). Although we want to focus on the fully electric cars labeled in blue, it is interesting to note that the average electric range of hybrids also declined for models after 2010 yet did not experience the same recovery in the 2020 model in the state.

### GRAPH 2
<img width="624" alt="AvgRangeBy Year" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/e523276f-b4bf-4d67-8a8a-17866cbaeadd">


After viewing the results of the first diagram, we filtered the data to include only the top 20 makes of cars with model year 2008 or later. This change aided in eliminating outliers and void space on the visual from the years 1996-2007. Our results show a similar trend to the initial graph for each vehicle type. BEVs have a large uptick in their average range starting in 2008 and peaking at 245 average miles in 2010. Then 2011 still showed a steep decline in efficiency, followed by a positive trend until peaking again in 2020 at approximately 278 miles average for Battery Electric Vehicles. The Plug-In Hybrid Electric Vehicles are not nearly as efficient in terms of average range, but, notably, their data mirrors the spike in 2010 with a following drop. Also, as in the first visual, the data shows that PHEVs never received the attention in development to exceed that previous peak as the BEV trend shows. A separate detail on the tail end of the diagram after 2020. PHEVS’ continue their slight up-and-down trend, but there is very little or zero data for BEVs. This is mainly due to a lack of owners buying newer vehicles around this time.


# QUESTION 2

### QUESTION: 
"Which make of car has the highest rate of purchase for each type of electric vehicle in Washington?"

### SIGNIFICANCE: 
This question and the relevant data are significant as they allow one to understand who the market leaders are for both PHEVs and BEVs. By understanding who the market leaders are in the electric car market, consumers can make more informed decisions on what kind of electric vehicle to purchase. In the mind of many consumers, BEVs, and PHEVs, with more market share may be better options than BEVs and PHEVs with less market share as there must be a reason that more of one kind of car is bought over others. 

### PHEV's:

<img width="625" alt="PHEV Heat" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/8e05031c-e25e-4782-ade9-9079f7c62fe4">

<img width="622" alt="PHEV Pie" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/4ed587df-8491-447f-a16e-983c7dbee0e2">


### BEV's:

<img width="623" alt="BEV Pie" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/76780a04-01aa-4f3e-afdf-5b222d79e996">

<img width="625" alt="BEV Heat" src="https://github.com/whittcarson/MIST4610GroupProject2/assets/131502055/748ac9a2-1c8f-40ba-84a8-b823729e8006">

# MANIPULATIONS
We did not manipulate any raw data, but we did filter out irrelevant data and apply measurable functions to certain columns. In Q1, we filtered data to only include the top 20 makes of EVs with model year 2008 or later. We also applied the average function to "Electric Range" in order to set a standard for comparing the electric range of electric vehicle types year after year. For Q2, we applied the count function to "Electric Vehicle Type" in order to compare the amount of EV types manufactured for each make. All filters/marks applied to the data are solely intended to show the viewer quantifiable information related to the questions. In regards to integrity, our data has no inaccuracies, irrelevancies, or 3rd party imports.

# TABLEAU PACKAGED WORKBOOK
The Tableau Packaged Workbook featuring these graphs and the dataset is attached to the repository.
