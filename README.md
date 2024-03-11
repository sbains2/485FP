# Project Title: Comparing Transportation Expenses by Income with Hospital locations/Healthcare professional shortages

**SmartDashboard Link: https://sbains2.github.io/485FP/index.html**

## Team Members:

<ul>
  <li><b>Elaine Azul</b></li>
  <li><b>Sahil Bains</b></li>
  <li><b>Badria Kadir</b></li>
  <li><b>NQ Nguyen</b></li>
  <li><b>Edward Park</b></li>
</ul>

## Project Description:

Our project aims to create an interactive dashboard application that will analyze the spatial relationship between transportation availability, income level, and corresponding healthcare accessibility. Through the dashboard, we will be able to visualize the disparities between transportation and healthcare in the mode of transportation accessibility and costs. An article highlighting the need for greater investment in public transportation highlights how “our road conditions are consistently ranked among the worst in the nation. Traffic jams abound. Major bridges are either out of commission or face deferred maintenance.” (Kidde, 2021). The need to improve transportation infrastructure fundamentally affects how people who rely on public transit are able to commute to important areas, such as hospitals. While transportation investments are crucial, we plan on taking a multifaceted approach which looks at other systematic issues relating to healthcare accessibility, such as the income spent on transportation and corresponding transit stops and hospital locations.

## Screenshot Examples:

![Image 1 for dashboard](/img/Map_1.png)

![Image 2 for dashboard](/img/Map_2.png)

## Project Goal:

Our project has the emphasis on empowering low-income individuals and vulnerable populations by providing them with access to data that allows advocacy for improved transportation to healthcare services. Through designing this web map, we aim to build the capacity for data driven advocacy as well as raise awareness to policy makers and local authorities to address transportation challenges in low-income areas and promote health equity through highlighting disparities in healthcare access among all income brackets. By focusing on empowerment and community impact, our project strives to ensure equal opportunities for transportation and healthcare services for all, regardless of the income level.

# Utilized libraries

## Mapbox GL JS Library
- Creates interactive maps with various layers.
- Allows adding transit stops, hospital clusters, and income expense data

## Mapbox functions
- `mapboxgl.Map`: Creates a new Mapbox map object.
- `map.on('load', function() {...})`: Event listener for map loading.
- `map.addSource()`: Adds data source to the map for layers.
- `map.addLayer()`: Adds new layers to the map.
- `map.setLayoutProperty()`: Modifies layout properties of layers.

## C3 & D3
- **D3**: Powerful library for interactive data visualizations
- **C3**: Builds on D3 for simplified chart creation 


## Data Sources:

**Income by Census Tract in 2022 (Census Bureau):**
<ul>
 <li>U.S. Census Bureau. (2022). Income by Census Tract in 2022. Retrieved from https://data.census.gov/table/ACSST5Y2022.S1901?g=040XX00US53$1400000</li>
</ul>

**Hospitals in Washington (WGODP):**
<ul>
 <li>Washington State Department of Health. (n.d.). Hospitals in Washington. Retrieved from https://geo.wa.gov/datasets/WADOH::hospitals/explore?location=47.170174%2C-120.675488%2C7.66</li>
</ul>

**Social Vulnerability Index Layer for 2010 Census Tracts (WGODP):**
<ul>
 <li>Washington State Department of Health. (n.d.). Social Vulnerability Index Layer for 2010 Census Tracts. Retrieved from https://geo.wa.gov/datasets/cfbc9657d7b84fa3bd1b6a378314019f_0/explore</li>
</ul>

**Transit Stops (WGODP):**
<ul>
 <li>Washington State Department of Transportation. (n.d.). Transit Stops. Retrieved from https://geo.wa.gov/datasets/WSDOT::wsdot-transit-stops/explore?location=47.179925%2C-120.753984%2C7.62</li>
</ul>

**Transportation Expense (WGODP):**
<ul>
 <li>Washington State Department of Health. (n.d.). Transportation Expense. Retrieved from https://geo.wa.gov/datasets/WADOH::transportation-expense-current-version/explore</li>
</ul>
