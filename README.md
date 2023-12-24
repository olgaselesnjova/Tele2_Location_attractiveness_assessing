# Tele2
## Location attractiveness assessing
### Task
Building a model for assessing the attractiveness of a location for opening a retail outlet.
### Data
1. Hexagonal grid for the territory of St. Petersburg, containing the following information:
- Number of residents (by gender, age, income level)
- Number of visitors per day
2. Data on points of interest (POI) in the city (OpenStreetMap)
3. Transport network data (OpenStreetMap)

### An algorithm for solving the problem
1. Determine a set of characteristics/factors that can describe a territory and that can influence the success of running a certain type of business.
2. Determine what additional open data sources may be useful in developing the case. Collect this data.
3. Perform the calculation of features on a hexagonal grid (one hexagon - a section of the city territory is described by a set of factors/signs).
4. Select the type of business being analyzed (you can take a certain category of POI from OSM, you can divide it into data from one company against the rest as data on competitors).
5. Conduct a statistical analysis of the data - what factors influence the placement of retail outlets of this type.
6. Build an ML model that will allow you to evaluate other attractive locations for opening retail outlets and evaluate the influence of factors (feature importance)
7. Prepare a presentation, including hypotheses for improving the solution (what other approaches could be tried, what factors and data are needed to improve the solution, a description of the architecture of the analytical solution, how the results are validated)
   
An alternative option: take a similar task, but not from a business point of view, but from the point of view of social infrastructure - to evaluate the effectiveness of placing a network of clinics, schools or kindergartens.

