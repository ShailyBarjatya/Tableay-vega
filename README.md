# Tableau-vega
Created an interactive visualization system to explore the cause of loss indemnities dataset for 2015 available at http://www.rma.usda.gov/data/cause.html. Create an interactive multiform visualization system in Tableau and separate single forms in Vega.

The visualization system contain two views: (1) a choropleth map on the left that shows state boundaries and uses a sequential segmented colormap to encode the total amount of losses, and (2) a bar chart on the right that expresses the amount of loss with aligned horizontal position and separates the damage type with vertical position. The marks are ordered by the loss amount attribute that encodes the size of the bar. When no interaction is available the entire data set is used to generate the two views. Namely the colormap encodes the sum aggregated losses of all types of damage and the bar chart encodes the sum aggregated losses for all the states, see below.

Interaction and linked views: 
(1) When the user hovers over a state on the left view then the bar chart will show only the data related to that state. Aggregation of losses is no longer over the entire US, rather it is only over the highlighted state.

(2) When the user hovers over a bar corresponding to a specific type of damage then the map encodes only the data related to that damage. Aggregation of losses is no longer over all damage types, rather it is only over the highlighted damage.

TABLEAU LINK: https://public.tableau.com/profile/shaily4423#!/vizhome/AgriculturalLosses2015_2/Dashboard1?publish=yes
