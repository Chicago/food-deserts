food-deserts
============
This repository contains the necessary information to estimate the food deserts in Chicago. Food deserts are defined as areas in Chicago which are more than 0.5 or 1 mile from a grocery store, depending on the grocery store size. Further refinements are applied to grocery stores to ensure they provide adequate food.

Methodology
-----------
Retail Food Establishment business license data (a license to sell food), from Department of Business Affairs and Consumer Protection, was obtained and geocoded.   A half-mile and one-mile buffer was applied to all grocery stores 2,500 square feet and larger and 10,000 square feet or larger, respectively. 

The areas within the half-mile and one-mile buffer associated with grocery locations represent areas of Chicago that are considered served by a grocery store.  Areas that are located outside of the ½ mile and one-mile buffers are considered unserved.  Unserved areas were further analyzed by identifying community areas which have an average median income below the City of Chicago median income.   

Areas that are non‐residential in nature were removed from the analysis.  The ten Community Areas with the highest median income levels were also removed from the calculation.   

2010 U.S. Census block population data was then used to estimate the population of the unserved areas and low income unserved areas.
