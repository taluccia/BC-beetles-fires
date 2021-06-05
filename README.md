# BC-beetles-fires

## Overview


## Process

1. Raster to Polygon (R)
2. GRTS Sampling (R)
3. Terrain Variables (GEE)
4. Weather variables (R + GEE)
5. Vegetation Indices (GEE)
6. BRTs Analysis (R)



# Preprocess 2021-06-05
1. R---select perimeters from historical perimeter database
2. AcrGIS---Subset  VRI  from  gdb  for each  perimeter
3. R--clip perimeters to only treed areas (removes water, rock, meadows)
4.

# New Process 2021-06-05
1. GEE---Export Rdnbr Raster with Landsat projection
2. R---Convert raster to point
3. R---Randomly sample 5% of points in each fire
4. GEE---Extract data from GEE


## References

### Spatial Data

British Columbia [Fire Perimeters-Historical](https://catalogue.data.gov.bc.ca/dataset/fire-perimeters-historical) 