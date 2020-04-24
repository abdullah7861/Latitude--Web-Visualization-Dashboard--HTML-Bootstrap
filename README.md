# Web Visualization Dashboard
Live Link: https://abdullahsher1.github.io/abdullahsher1/Latitude--Web-Visualization-Dashboard/
## Background
Create a Visualization Dashboard Website of Weather in 500+ World Cities Relative to the Equator at Different Latitudes Using HTML5, CSS3 and Bootstrap 4
### Objectives 
In building this dashboard, create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements
#### The website contains 7 pages total, including:
- A Landing Page containing
- An explanation of the project
- Links to each visualizations page

![Alt Tag](https://github.com/abdullahsher1/Latitude--Web-Visualization-Dashboard/blob/master/Images/landing_page.png?raw=true)

#### Four Visualization Pages, each with:
- A descriptive title and heading tag
- The plot/visualization itself for the selected comparison
- A paragraph describing the plot and its significance

![Alt Tag](https://github.com/abdullahsher1/Latitude--Web-Visualization-Dashboard/blob/master/Images/visualizations_page.png?raw=true)

#### A Comparisons Page that:
- Contains all of the visualizations on the same page so that it can be easily visually compared
- Uses a Bootstrap grid for the visualizations
- The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page
- Contains a dropdown on the right of the navbar named Plots which provides links to each individual visualization page
- Provides two more links on the right: Comparisons which links to the comparisons page, and Data which links to the data page
- Is responsive (using Media Queries). The nav's background color must change
![Alt Tag](https://github.com/PetraLee2019/Web-Visualization-Dashboard-Latitude-/blob/master/Images/comparisons_page.png?raw=true)

#### A Data Page that:
- Displays a responsive table containing the data used in the visualizations
- The table must be a Bootstrap table component
- The data must come from exporting the .csv file as HTML, or converting it to HTML
![Alt Tag](https://github.com/abdullahsher1/Latitude--Web-Visualization-Dashboard/blob/master/Images/data_page.png?raw=true)

#### Observations
- From the weather data for 538 cities collectd today(11/07/2018), we conclude that temperature is peaked around 80 Fahrenheit near the equator from -20 to 30 degrees of Latitude. It continually drops to 30 Fahrenheit(even lower for several cities) in the region of 40 to 80 degree of latitude.
- There is no obvious dependence of cloudiness on latitude. Yet somehow there are several cloudiness values, 0, 20, 40, 78,97, are most crowded with citis all over the world, much more than other values.
- The humidity percentage has only weak dependence on the latitude. It takes smallest value around -20(Southern Hemisphere) and 20 latitude(Northern Hemisphere).
- There is no obvious dependence of wind speed on latitude. The wind speed in general is from 0 mph to 15 mph.
