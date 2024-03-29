# Dominican Republic

Below is my final project on the Dominican Republic. My original country was Chad, but the enormous size of the country meant that the process of extracting data took up too much time and space, so I chose the smaller Dominican Republic as a replacement.

## Political Subdivisions

### Administrative Subdivisions
![](dr.png)
This map shows the regions and provinces of the Dominican Republic as a whole. The country is located on the island of Hispaniola and is bordered on the west by Haiti, with the Atlantic Ocean to the north and east and the Caribbean Sea to the south. The Dominican Republic is divided into ten regions and 31 provinces.

![](combined.png)
Pictured are the boundaries and districts of La Romana and Villa Hermosa provinces, which I decided to focus on. These two provinces have a combined population of 143,074. There are very few districts present in the region, making the entire province of Villa Hermosa appear as part of a city. The region is located along the southern coast, and an island is present at the bottom of the map. Almost all of the population is concentrated in the city of La Romana, with only one other small urban area located in the region. Off the coast of the region lies Santa Catalina Island, famously visited during the voyage of Christopher Columbus.

## Population

### Population of the Dominican Republic's Regions
![](dom_pop19_1.png)
![](domrepublic.png)
These maps illustrate the population of each region of the Dominican Republic. Yellow colors indicate low population, while red colors indicate high population. Outside of the Santo Domingo region, which contains approximately 3/8 of the country's population, people are concentrated in tourist regions along the coast. One thing to note is the low population in the western provinces bordering Haiti; this is likely a result of poverty and reduced infrastructure.

### Population Log of the Dominican Republic's Provinces
![](dom_logpop19b.png)
![](dr.mp4.png)
These plots show the population logarithm of the provinces of the Dominican Republic from a 2d and 3d perspective. Blue colors indicate a low logpop, while red colors indicate a high logpop. Population has very large concentration in and around Santo Domingo; nowhere else in the country does the population log even come close to that of the capital city.

### Density Histogram
![](domhistogram.png)
The apparent negative correlation between population and density in this histogram reveals that density is very high in Santo Domingo and quite low everywhere else, even in other urban areas.

### Correlation
![](domr2one.png)
This plot reveals a heavy correlation between population and nighttime lights within the Dominican Republic as a whole. One explanation for the result is the country's large urban population, as more people in cities will produce a greater positive correlation with lighting.

![](domr2two.png)
This plot illustrates the fitted values of each available variable against the residual data of the regression model. The high r-squared value suggests strong correlation between population and the variables.

### Differences
#### Sums Differences
![](diffsums.png)
![](diffsums3d.png)
These two plots suggest that the largest differences between the predicted output and population sums occur in the cities. Negative values exist in the largest urban areas because population models tend to overestimate the populations of cities. My population sums model was the most accurate of the three, having the smallest margin of error.

#### Means Differences
![](diffmeans.png)
![](diffmeans3d.png)
These two plots appear similar to the sums differences plots above, as means are also overestimated in the cities. In fact, the gap between Santo Domingo and the rest of the country is even more exaggerated here than for sums differences.

#### Logpop Differences
![](difflogpop.png)
![](difflogpop3d.png)
The logpop differences are similar to the aforementioned differences because the inner cities have the largest overestimations. However, for the population log, the suburbs of urban areas are much more positive than in the other difference plots, suggesting that the logarithm tends to underestimate these areas.

## Roads and Health Care
### Transportation in La Romana & Villa Hermosa
![](dom_roads.png)
The roadways in the two provinces are largely focused on the major city of La Romana, with a moderate correlation between number of roads and population density. There appears to be one road that bypasses the city and connects to the second largest city in the region, while it continues to traverse the southern coast of the island. Another road branches off from the main city and travels north further into the country. Overall, most major roads are built with the purpose of connecting settlements and traveling between cities.

**Total Roads: 3042**  
**Total Roads on Map: 261**  
**Primary Roads: 46**  
**Secondary Roads: 65**  
**Tertiary Roads: 112**  
**Motorways: 38**  

### Healthcare in La Romana & Villa Hermosa
![](dom_health.png)
Healthcare facilities proved to be few and far between in La Romana and Villa Hermosa. Only 11 health centers were present in the region; all of them were classified as hospitals and all of them were located within the limits of the largest city. Therefore, access to health care may be unreliable for people living in the second largest city and other, more rural areas of these two provinces. However, the presence of hospitals as the only method of healthcare suggests that whatever facilities do exist may be adequate for treatment. The map reveals that the local and state governments are not investing enough money into healthcare in these two provinces.

**Total Healthcare Facilities: 11**  
**Hospitals: 11**

### Combined with Topography
![](render.png)
Based on the topographic map, there is little correlation between topography and population. Since the region is coastal, very few mountains are present. Furthermore, the few hills and valleys that do exist have virtually no roads passing through and no access to healthcare, which is completely limited to cities.
