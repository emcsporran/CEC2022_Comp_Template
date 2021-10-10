# CEC2022_TestingRepo


If you are working with MATLAB and plan on using GitHub to push/pull and share work with other 
team members then it is strongly advised that you have
[GitHub Desktop](https://desktop.github.com/) downloaded. 


## Participant Signature

Name - Date (DD/MM/YY)


ex. Eleanor McSporran - 10/11/21


## Data Files
Name the code files below with a small description of what the data units are/imply. 
As well as dpecifiying whether a file is a key file or a metrc file.


* No Unit (NU)
* Number of whole units (#)

 
| Filename               | File Information                                           | Units        | Key/Metric |
|------------------------|------------------------------------------------------------|--------------|------------|
| fire_station_locations | Location of fire stations                                  | NU           | Key        |
| key_site_locations     | Location of the key locations that need to be protected    | NU           | Key        |
| average_forest_fire    | Average occurance of froest fires from the last 10 years   | %            | Metric     |
| water_distance         | Distance to the nearest body of water                      | km           | Metric     |
| firework_sales         | Number of fireworks sold in the region                     | #            | Metric     |
| foliage_density        | Amount of foliage in the area                              | foliage/km^2 | Metric     |
| population_density     | Amount of people in the area                               | people/km^2  | Metric     |
| camping_traffic        | Amount of people purchasing national/provincial passes     | #            | Metric     |
| convicted_arsonists    | Amount of people from speciofic regions convicted of arson | #            | Metric     |


## Key Locations
All these locations are seen in the data file labelled "key_site_locations.csv"
Highlighting the key locations throughout the prcince 

* All locations that are normal land are labelled with the key of 1
* All locations that shouldn't be considered are labelled with a key of 0
 
| Filename               | Type         | Key        |
|------------------------|--------------|------------|
| Mactaquac              | Park         | 2          |
| Mount Carelton         | Park         | 2          |
| Parlee Beach           | Park         | 2          |
| Kouchibouguac          | Park         | 2          |
| Fundy                  | Park         | 2          |
| Gagetown               | Military     | 3          |
| Fredericton            | City         | 4          |
| Saint John             | City         | 4          |
| Moncton                | City         | 4          |
| Mirimichi              | City         | 4          |
| Bathurst               | City         | 4          |