# Intro to Visualization
## A short workshop to get acquainted with data visualization

### Learning objectives
By the end of this class you will be able to:
* Describe where visualization is used in the Analytics workflow
* Create a visualization using Tableau
* Create a dashboard from several visualizations

### Agenda
* **Introductions** -  6:30
* **Visualization overview**  -  6:45
* **Code-along with the Pronto Bike Share data**  -  7:00
  * Get acquainted  with the Tableau worksheet functions
  * Connect to a file in Tableau
  * Create a simple chart
* **Exercise: Develop your first graph Seattle Pet Licenses data**  -  7:30
* **Code along**  -  7:45
  * Create simple calculated fields
  * Work with multiple measures
* **Exercise with Elliot Bay Trail data**  -  8:00 
  * Use calculated fields to feed look at pedestrians vs. bikes
* **Code along - Create Dashboards**  -  8:20
* **Exercise: Create dashboards with Pronto Bike share data**  -  8:30
* **Closure**  -  8:50
 
## Content

##### Visualization overview  -  6:45
* [A few slides](https://docs.google.com/presentation/d/1fRl4N4mOWAYA5mRbtbnBE5lQMnku0eSJa6vqJq9oUgI/edit?usp=sharing)
 
#### Code-along  -  7:00
* Download the Pronto Bike Share dataset
  * [In our class repository](/Pronto_bike_share_visualization/cycle-share-dataset/trip.csv)
  * [Web Location](https://www.kaggle.com/pronto/cycle-share-dataset)
    * Note this data set on Kaggle has some data quality issues that are eliminated in the class repository version
* Get acquainted with the Tableau worksheet editing areas and functions
* Connect to a file in Tableau
* Create a simple chart
 
#### Exercise: Create your first chart using the Seattle Pet License data  -  7:30
* The Seattle Pet License dataset
    * [In our class repository](/Seattle_pet_license_data/Seattle_Pet_Licenses_2016_to_2018.csv)
    * [Web link](https://data.seattle.gov/Community/Seattle-Pet-Licenses/jguv-t9rb)
* Create a line chart with License Day on the x axis (horizontal axis) and count of License Numbers on the y axis (vertical access)
* Duplicate worksheet and modify to be a line chart with Month on the x axis
* Modify to be a bar chart
  
#### Code along: Work with multiple measures  -  7:45
* Freemont bridge data
  * [In our class repository](/Freemont_bridge_data/Freemont_bridge_bike_traffic-daily.json)
  * [Web link](https://data.seattle.gov/Transportation/Fremont-Bridge-Daily-Bicycle-Counts/eytj-7qg9/data)
* Create simple calculated fields
* Work with multiple measures
* Add filters

#### Exercise with Elliot Bay Trail data  -  8:00
* Elliot Bay Trail data
  * [In our class repository](/Elliot_bay_trail_data/Elliott_Bay_Trail_in_Myrtle_Edwards_Park.csv)
  * [Web link](https://data.seattle.gov/Transportation/Elliott-Bay-Trail-in-Myrtle-Edwards-Park/4qej-qvrz)

* Use a calculated fields to create a line chart of total pedestrians by month
* Use a calculated fields to create a line chart of bikes by month
* Create a new chart using the "Measure Names" and filters to create a chart comparing total pedestrians and bikes over time
* Bonus: Create a new chart that compares all four bike and pedestrian counts over time
  
#### Code along - Create Dashboards  -  8:20
* Create a dashboard from worksheet vizualizations
* Add text and blank areas for clarity and pleasant appearence

#### Exercise: Create dashboards with Pronto Bike share data
* Together let's create a chart with a count of Trips by day of the week (code along)
  * Add a color of Month of Starttime
  * Add a filter of Month of Starttime and select just December 2014 and July or 2015
* Create another chart (new worksheet) with the average trip duration vs day of the week
  * Add a color of Month of Starttime
  * Add a filter of Month of Starttime and select just December 2014 and July or 2015
* Combine these into a dashboard
* Bonus: Find something interesting in the data with a vizualization
  
