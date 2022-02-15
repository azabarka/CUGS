# CUGS
The Calgary Urban Green Space (CUGS) application provides a directory of all documented green spaces and outdoor recreation spaces within the City of Calgary boundary. The application was designed with a human-centered approach. The goal was to make getting outside as easy and fun as possible! Additionally, this app has implications in the the future of GIS driven city planning. Urban planners can use the census data provided within the app to pinpoint locations with a lack of green space or recreation facilities in order to make outdoor recreation safe and accessibile for all. 
## Team
- Awani Khatu
- Caroline Fleming 
- Marjan Nikoukar
- Alex Zabarka 
## Mission Statement 
According to SDG 11, the goal of this app is to ensure that the city and its residents have access to safe, inclusive, and accessible green and public spaces. The application aims to bring inhabitants closer to their local green spaces through locating and providing information on green space and outdoor facilities. These tools in turn can provide users with comprehensible data that can be used to assess their community's long-term sustainability.

The app displays the location of outdoor recreation areas such as parks, basketball courts, playgrounds, picnic areas, and other commonly sought after activities. The map then displays nearby activities that are relevant to them and will provide a more comprehensive and in-depth breakdown of outdoor recreational opportunities in the surrounding area than Google Maps does. Long term benefits of the app include opportunities to show CUGS to city planning officials in order to determine which neighborhoods lack green space and require additional investment in outdoor recreation. Census data allows users to identify where the most vulnerable populations are located and whether these populations have adequate access to green space and outdoor recreation. CUGS is focused on the entities of users for the equal usage and enjoyment of a safe and welcoming public green space that is within easy walking distance of all users in order to achieve a happy, healthy life.

Moreover, this app provides a platform for parents to identify walking distances and safe and responsible access to green spaces based on the various recreational facilities available for their children. Green spaces benefit children's mental, physical, and social development, promoting their growth as environmentally conscious and responsible citizens.
Overall, this app is a step toward providing a safe, accessible green space, as well as a means of removing physical, environmental, and societal barriers to a better life in a sustainable city.
## App Link 
https://ucalgary.maps.arcgis.com/apps/webappviewer/index.html?id=3d3290cd2b5f4f3fb3f819db101e55c7
## Data Sources 
### ArcGIS Online: 
- City of Calgary Parks Turf 
https://services2.arcgis.com/XSv3KNGfmrd1txPN/arcgis/rest/services/Census_Data_and_Green_Spaces/FeatureServer
- Calgary City Boundary 
https://data.calgary.ca/Base-Maps/City-Boundary/erra-cqp9 
- Calgary City Parks 
https://services1.arcgis.com/AVP60cs0Q9PEA8rH/arcgis/rest/services/City_Park/FeatureServer 
- City of Calgary Parks Wayfinder Picnic and Benches 
https://services1.arcgis.com/AVP60cs0Q9PEA8rH/arcgis/rest/services/Parks_Wayfinder_Picnic_and_Benchs/FeatureServer 
- Calgary City Parks (Turf and Natural Area) “Location of Turf and Natural Area Parks in Calgary.” 
https://services1.arcgis.com/AVP60cs0Q9PEA8rH/arcgis/rest/services/PARKS/FeatureServer
- City of Calgary Parks Wayfinder Shelter and Platform 
https://services1.arcgis.com/AVP60cs0Q9PEA8rH/arcgis/rest/services/Parks_Wayfinder_Shelter_and_Platform/FeatureServer 
### City of Calgary Open Data Portal:
- Calgary Bikeways 
https://data.calgary.ca/Base-Maps/Community-District-Boundaries/surr-xmvs
- Census by Community 2019 
https://data.calgary.ca/Base-Maps/Community-District-Boundaries/surr-xmvs
- Community District Boundaries 
https://data.calgary.ca/Base-Maps/Community-District-Boundaries/surr-xmvs
- Off Leash Dog Area 
https://data.calgary.ca/Recreation-and-Culture/Off-Leash-Dog-Area/enr4-crt
- Parks Sport Surfaces
https://data.calgary.ca/Recreation-and-Culture/Parks-Sport-Surfaces/vr9r-mchr 
- Parks Wayfinder Garbage and Recycle 
https://data.calgary.ca/Recreation-and-Culture/Parks-Wayfinder-Garbage-and-Recycle/fwyk-8pth
- Playground equipment map 
https://data.calgary.ca/Recreation-and-Culture/Playground-Equipment/bdu9-amk8 
- Public Art 
https://data.calgary.ca/Recreation-and-Culture/Public-Art/2kp2-hsy7 
## Furthur Description and Use 

### Start 
When users first start the app they will see a splash screen displaying the app logo and some information. After pressing ok the user is taken to the main screen. Additional information is shown on the left hand corner. Also on the left hand side is the panel displaying all the different layers available in the app. The space to the right is taken up by the map itself, along with the layers, directions, search, swipe and legend widgets. 
### Layers 
Users can turn different layers on and off within the layers panel. Layers are divided into six categories: Kids Play Areas, Picnicking Spots, Biking, Off-Leash Dog Parks, Outdoor Sports and Census Data. This ensures users can quickly and easily find what they are looking for or explore Calgary to find new outdoor activities. Once a user has located their desired place they can use the directions widget to get there from their neighbourhood. The directions widget includes options for driving, walking and biking time. By clicking the symbols on the map the user can see detailed information about each feature in a layer. 
### Census and Community Data 
In order to analyse Calgary's urban green spaces ArcGIS's Summarize Within geoprocessing tool was used. This tool summarizes all the areas where an input layer overlaps with a boundary layer. When the user clicks on any community on the map, pop-up text displays the number of green spaces maintained by the City of Calgary within each community. Additionally, the pop-up tells the user the name of the community and the community class. Demographic data is displayed in a bar chart below the pop-up text. Percentages of the population who are female, 14 years of age and under and 65 years of age and older are shown. Chloropleth layers allow the user to visualize the demographic distribution and compare layers using the swipe tool. 

## References
1. The City of Calgary. (n.d.). City of Calgary’s Open Data Portal. Data.Calgary.Ca. Retrieved January 28, 2022, from https://data.calgary.ca/
2. ArcGIS online. (n.d.). Map Viewer. Arcgis.Com. Retrieved January 28, 2022, from https://www.arcgis.com/apps/mapviewer/index.html 
3. The Global Goals. (n.d.). Goal 11: Sustainable Cities and Communities. Retrieved January 28, 2022, from https://www.globalgoals.org/11-sustainable-cities-and-communities
4. SDSN. (n.d.). 70. Area of public and green space as a proportion of total city space – Indicators and a Monitoring Framework. Indicators.Report. Retrieved February 4, 2022, from https://indicators.report/indicators/i-70/
