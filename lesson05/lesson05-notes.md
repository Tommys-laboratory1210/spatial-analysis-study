# Lesson 05 — Local Moran's I(LISA)

## 1. Global Moran's I vs. Local Moran's I
With Global Moran's I, we summarize spatial pattern of entire data.

But if spatial autocorrelation is high, we don't know where the clusters are formed.

## 2. LISA
- Spatial Cluster
HH : High-High (Hot Spot)
LL : Low-Low (Cold Spot)
- Spatial Outlier
HL : High-Low (one point has high values, but near points are not)
LH : Low-High

## 3. Spatial Lag
x = 15

neighbor = [10, 12, 14, 16]

mean(neighbor) = 13 -> Spatial Lag

In LISA, we use not x but deviation.
