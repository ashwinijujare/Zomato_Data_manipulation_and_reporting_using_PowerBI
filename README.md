# Zomato Data manipulation and reporting using Power BI
 Constructing a consolidated and interactive PowerBI report that will allow Zomato to quickly assess the required data.

# Steps performed: 
### Data transformation steps:
1.	Imported data from all the available Excel files (mentioned below) into Power BI.
   a. Africa
   b.	Asia
   c.	Europe
   d.	NAM
   e.	SAM
   f.	Oceania
   g.	Fact Table
   h.	Country-Code 
2.	Appended the Continent wise data files into a single file (i.e. from 'a' through 'f' from above list).
3.	Split the column Restaurant Name, Address to have 2 separate columns respectively.
4.	Replaces all the City names to have correct values.
5.	Removed unwanted columns like Locality, Locality Verbose, etc.
6.	For Country-Code data removed null or duplicates.
7.	Created Measures for – Restaurant Count, Average Rating, Average cost, Cuisine count.

### Created following visuals for the report:
World Wide Analysis Page:
1.	Created Cards for: 
a.	Restaurant Count
b.	Average Rating
c.	Average Cost
2.	Map using the Continent -> Country -> City hierarchy, with bubble size indicating the restaurant count.
3.	Infographic designer -> custom column chart with martini image as custom columns indicating the average rating for restaurant name.
4.	Interaction between Map & Infographic designer charts to view data for selected region.

#### Restaurant Analysis Page:
1.	Slicers created for 
   a.	Rating color – which follows below logic for assigning colors:
      Aggregate rating                 Rating color
  	   Above 4.5                             Dark Green
      4 to 4.4                                 Green
      3.5 to 3.9                              Yellow
      2.5 to 3.4                              Orange
      1.8 to 2.4                              Red
      0 to 1.7                                 White
   b.	Country
   c.	City
   d.	Has Online delivery
   e.	Has Table Booking
3.	Tree Map – Shows the Restaurant Names & Cuisine Count.
4.	Gauge – Created 2 gauge as follows:
   a.	Average Cost for 2
   b.	Average Rating
5.	Cards – Created 2 cards
   a.	Shows the Restaurant Address for selected Restaurant.
   b.	Shows the available cuisines for the selected Restaurant.
6.	Interactions are enabled across the page using slicers & between tree map & other visuals.

# Report:
![WorldWideAnalysis](https://github.com/ashwinijujare/Zomato_Data_maipulation_and_reporting_using_PowerBI/assets/117963460/a2538dd7-a3da-4aee-8384-33239e84e108)

![RestaurantAnalysis](https://github.com/ashwinijujare/Zomato_Data_maipulation_and_reporting_using_PowerBI/assets/117963460/69e48392-a7a8-4de5-8790-a426d0abbc26)

# Link to Report published on Power BI Service:
https://app.powerbi.com/view?r=eyJrIjoiY2ZjNTNjZGUtNmQ1My00MDZkLWFmZDYtNTU5ZGE5OWM4ODQ1IiwidCI6IjQ0NjQ1YjhiLWRhYzctNDM1OS05MmNjLTdmM2JjZWE1YzVlNiJ9


