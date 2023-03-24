# Cold Climate Adaptation in Potatoes - Analysis Project

This project analyzes data from an experiment on how plants adapt to cold climates, specifically focusing on the effect of different experimental factors on ion leakage as a response variable.

## Data

The data used for this project is available in `potato.txt`, which can be found in the [RawData](https://github.com/30-na/plants_adapt_cold_climate/tree/main/RawData) folder.

This dataset is from an experiment on how plants adapt to cold climates. The investigators
decided to study this problem after observing that plants that have been conditioned to cold
previously appear to suffer less damage from the cold.
Two species of potato were studied (species 1 and 2). Each plant was exposed to one of
two acclimatization regimes (1= plant was kept in cold room; 0= plant was kept at room
temperature) for several days. Later, plants were subjected to one of two cold temperatures (-4
degrees C is coded as 1; -8 degrees C is coded as 2). Two responses were measured: damage
score for photosynthesis (photo), and damage score for ion leakage (leak). Some of the 80 plants
originally assigned to the treatment combinations were lost during the experimen

## Research Question

What is the effect of species, acclimatization regime, and temperature on ion leakage in potatoes?

## Methods

??
We did perform a statistical analysis of the data using R. This will include exploratory data analysis, such as creating profile plots to visualize the relationship between the response variable and the different experimental factors.

We did also fit a three-way ANOVA model to the data, using the `aov()` function in R. We did check the model assumptions such as constant variance, independence, normality, and check for outliers.


## Results

???


## Notes:
* Unequal sample sizes in the different cells

