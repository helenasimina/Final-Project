Target User Profile (Persona)
Name & Position: Alicia Brooks, Public Health Analyst

Background Description: Alicia is a public health analyst for Planned Parenthood in Illinois. She knows that since the fall of Roe v. Wade in 2022, state policies have severely limited access to abortion care across the US. She also knows that access has changed differently within states based on the distance to an abortion facility that someone lives, their transportation options, the amount of money they have for travel, and the number of abortion providers who live in their state or the state nearest to them. These issues of access are complex, and Alicia is looking for a way to compare access within states so that she can identify areas where PP can allocate more resources to support gynecological patients. She is also interested in finding a visual that she can use to communicate the complex and emotional toll of access to abortion care.

User Case Scenarios
Scenario #1: When they arrive at the interactive map, the user sees a map of the US (census tracts) with an overlay of some contextual information about the contents of the web interactive. There is a prompt to either continue to look at the US as a whole, or to jump to a state or a zip code/specific location. The user decides they first want to look at the US as a whole to compare access between states. They see the US states with a choropleth map that shows ranked abortion access for each census tract. This ranking shows a combination of data (distance to clinic, number of OB/GYNs, average cost of abortion, gestational limits). The user has the option to slide between maps of 2018 data to 20224 data. To identify areas that lost access to care after the Dobbs decision, they use this slider to compare the years. They also have the option to simplify the map (using clickable layers) to just see state-level data like the number of OB/GYNs. This would allow them to identify any trends in the movement of OB/GYNs after the Dobbs decision, or to look at state policy changes. If they click on a state, the map zooms to the state and displays a data visualization showing people’s views on abortion next to the map. They could use this to compare public opinion to the state legislature.  

Scenario #2: When they land on the interactive map, the user chooses the option of looking up their hometown in the search query. The choropleth map zooms to their hometown and its census tracts. They can move their mouse around the map and see distance to nearest clinic pop up in the bottom info panel (calculating depending on their location). In an information box at the bottom of the page, they see the average cost of travel to abortion in that location (calculated by state cost + estimated travel cost). They can also slide between maps showing 2018 vs. 2022 data for temporal/situational comparisons. There is a search query next to this information that allows the user to type in other US locations and to retrieve information about their average distance to clinic/cost of abortion/number of physicians in state. This information could be compared easily next to the numbers for their hometown location. 




Representation
1
Basemap
US census tracts 

https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2020&layergroup=Census+Tracts


2
Abortion Facilities
ANSIRH - https://www.ansirh.org/abortion-facility-database

Depicted as distance to nearest clinic (location of clinic not identifiable) (similar to other visuals on distance to clinic - line showing distance could change color if it crosses state lines) (alternatively could create a scale of abortion access that incorporates distance to clinic, then depict overall access via choropleth
3
OB-GYNs in state 
https://www.americashealthrankings.org/explore/measures/OBGYN
Depicted as a number and also could incorporate into overall abortion access scoring scale


4
Public Opinion Chart
https://www.prri.org/research/abortion-attitudes-in-a-post-roe-world-findings-from-the-50-state-2022-american-values-atlas / (2018: attitudes on abortion by state)
https://www.covidstates.org/reports/state-by-state-views-on-abortion-in-america
(2022: attitudes on abortion by state, post Dobbs)

Depicted by a visualization that shows proportion pro vs. against legal abortion (I want a 


5
Cost Table
https://www.kff.org/other/state-indicator/median-self-pay-charges-for-abortions-by-type-of-abortion/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D


6
State Policies
https://states.guttmacher.org/policies/?gad_source=1&gclid=Cj0KCQjw2uiwBhCXARIsACMvIU1DfA7ne5E_-CPdH6ZBwbFUDuXrILOwvAYRemn85cG_92rmzP5oP8oaAj2REALw_wcB - Part of overall access scoring, but also available to be visible on its own as a layer with qualitative colors showing different types of policies (ie 6 week ban vs. full ban)
Interaction
1
Slider to show difference from 2018 to 2024
Sequence: Objects. Move the slider over map to transition map from 2018 data to 2024 abortion access data. 
2
Primary Query Panel
Filter: location. Search by location and zoom to that location for more information there.
3
Cost Table
Retrieve: cost data/distance data. Shows cost by location (state average + travel estimation) Allows costs of over locations to be displayed. 
4
Distance to clinic
Retrieve/Calculate: distance to nearest abortion facility. User hovers to retrieve/calculate this info.
5
Hub toggle
Overlay: Objects. Turn off/on layers about state policies
6
State select
Overlay: Objects. On selecting state, display visualization of public opinion data.


