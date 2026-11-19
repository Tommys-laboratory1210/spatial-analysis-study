# Lesson 04 — Spatial Autocorrelation

## 1. What is Spatial Autocorrelation?

Spatial autocorrelation describes the degree to which observations at nearby locations are correlated with each other.
Unlike ordinary statistical analysis, spatial analysis considers not only the values of observations but also their geographic relationships.
For example, nearby regions may have similar earthquake frequencies because they share geological structures or tectonic environments.

## 2. Types of Spatial Autocorrelation

### Positive Spatial Autocorrelation
Similar values tend to cluster together.

Examples:
- High values are surrounded by high values.
- Low values are surrounded by low values.

### Negative Spatial Autocorrelation
Dissimilar values tend to be adjacent to each other.

Examples:
- High values are surrounded by low values.
- Low values are surrounded by high values.

### No Spatial Autocorrelation
There is no systematic spatial pattern in the distribution of values.

## 3. Global Moran's I

Global Moran's I is a statistical measure used to quantify spatial autocorrelation.

It evaluates whether spatially neighboring observations tend to have similar or dissimilar values.

General interpretation:

- Positive Moran's I → Positive spatial autocorrelation
- Negative Moran's I → Negative spatial autocorrelation
- Moran's I near its expected value under spatial randomness → Weak evidence of spatial autocorrelation

The value alone does not establish statistical significance. Significance should also be evaluated.


## 4. Spatial Weights Matrix

A spatial weights matrix represents the spatial relationships between observations.

For example:

- 1 indicates that two regions are neighbors.
- 0 indicates that they are not neighbors.
- Diagonal values are generally set to 0, because a region is not considered its own neighbor.

Common approaches for defining spatial neighbors:

- Queen contiguity
- Rook contiguity
- K-nearest neighbors (KNN)
- Distance-based neighbors


## 5. Why Spatial Autocorrelation Matters

Spatial autocorrelation matters because spatial observations may not be independent.

Ignoring spatial dependence may affect:
- Statistical inference
- Standard errors
- Model interpretation
- The validity of conclusions
