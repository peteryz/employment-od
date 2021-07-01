# Commuting Distances and Times under Different Transportation Modes for U.S. Households

## Summary

Efficient and fair transportation planning creates opportunities and equity for jobs, health care, and education.
Therefore, data consolidation for transportation systems provides basis for evidence based policies. In this work, we construct a dataset that documents home-to-job commuting time and distance information for the 100 most populated U.S. urban areas. Our dataset builds on the U.S. Census Bureau's Longitudinal Employer-Household Dynamics Dataset, which provides origin (home) and destination (job) location information for households. For these origin-destination (OD) pairs, we derive commuting time and distance information under different travel modes, each a combination of walking, public transit, and ridesourcing. We construct data under different modes so policymakers and researchers have information about alternatives and can perform what-if analysis. Towards the end of this data sheet, we document a sample use case to illustrate this goal. 

## Data Description

Each instance in our dataset contains commuting time and distance information for one OD pair. We randomly sampled 100,000 OD pairs from the U.S. Census Longitudinal Employer-Household Dynamics Dataset (1,000 data points each for the 100 most populated urban areas, the list or urban areas with the corresponding indices can be found under `Urban_Area_ID.csv`.
In particular, each instance contains travel time and distance information for five different travel modes, as documented in Table 1. 
![image](https://user-images.githubusercontent.com/14277518/124179047-3da7ac80-da80-11eb-864c-876ea8c7768e.png)

The definition of columns of the dataset is provided in Table 2, with sample instances of the dataset shown in Table 3. The data files are organized as follows: `data/Duration_M1M5_{Urban_Area_Index=i}.csv` and `data/Distance_M1M5_{Urban_Area_Index=i}.csv` each contains the travel time and travel duration information of $1,000$ OD pairs within the $i$th urban area.
![image](https://user-images.githubusercontent.com/14277518/124179197-79db0d00-da80-11eb-9cd4-486a2eb9ae22.png)
![image](https://user-images.githubusercontent.com/14277518/124179218-82334800-da80-11eb-8997-427a04ffe4a2.png)


## Data Construction

Please refer to the data sheet PDF.

## Summary Statistics

The summary statistics of travel duration/distance across the five travel modes are shownin Tables 4 and 5. The summary statistics for the percentage of OD-pairs with access to public transit within each of the 100 urban areas is documented in Table 6.

![image](https://user-images.githubusercontent.com/14277518/124179379-ca526a80-da80-11eb-9365-6e17e27104bb.png)

Figure 2 shows the histograms of OD travel duration and distance under five different travel modes.
![image](https://user-images.githubusercontent.com/14277518/124179520-f837af00-da80-11eb-8411-1f1e823e6f75.png)
