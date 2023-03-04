# Political Polarization in US Congress

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F466e70c347974ab1f64280395bb45974%2Fpolitical%20polarization%20flag.png?generation=1677875491440013&alt=media)

# 52,540 DAYS (March 4th, 1879 to January 7th, 2023)
This is a dataset that tracks **political polarization** in US Congress (46th to 117th) through proportions from 1879 to 2023. 

All data are official figures from Voteview that have been compiled and structured by myself. **Ideological positions** are calculated using the **DW-NOMINATE** (Dynamic Weighted NOMINAl Three-step Estimation). This procedure was developed by Keith T. Poole and Howard Rosenthal in the 1980s and is a "scaling procedure", representing legislators on a spatial map. In this sense, a spatial map is much like a road map--the closeness of two legislators on the map shows how similar their voting records are. Using this measure of distance, DW-NOMINATE is able to recover the "dimensions" that **inform congressional voting behavior**.

Why did I create this dataset? In my personal opinion, **political polarization** is the **greatest threat to democracy** today, particularly in America. Polarization not only creates an "US VS THEM" situation, but also renders legislative bodies **less effective** at passing meaningful legislation. By uploading time-series data regarding American polarization over the past two centuries, I hope that the community will use my dataset to determine insightful statistical trends. Achieving a **quantitative yet objective viewpoint** of **political polarization** is crucial to understanding both its underlying causes and its everlasting effects.

###### IMPORTANT:
The **first dimension** picks up **differences in ideolology**, which is represented through the **"liberal" vs. "conservative"** (also referred to as "left" vs. "right") proportions throughout American history. 
The **second dimension** picks up **differences within the major political parties** over slavery, currency, nativism, civil rights, and lifestyle issues during periods of American history.

# Data Sources
##### The primary data source used was Voteview's official website, which publishes ideological data pertaining to America. Considering the meticulous documentation of congressional activities by such an accredited organization, no other organization is more equipped to provide insight on US polarization.

1. [Voteview's Realtime NOMINATE Ideology and Related Data](https://voteview.com/data) - Voteview's download links for NOMINATE scores, tutorials for generating ancillary data, and other publicly available databases are stored here. 
2. [Voteview's "Polarization in Congress" Data Analysis](https://voteview.com/articles/party_polarization) - Jeff Lewis, the project lead of Voteview, published a data analysis of the available polarization data. The detailed work gave insight into the true analytical potential of the dataset, and inspired many elements of my accompanying notebook.
3. [Voteview's "The Polarization of the Congressional Parties"](https://legacy.voteview.com/political_polarization_2015.htm) - Voteview released a detailed overview of their polarization data, the methodology behind their data, and the proper definitions and terminologies for the variables tracked. The guide mainly provided essential contextual knowledge needed to create a meaningful dataset.

# Statistics Being Tracked
- Chamber (House or Senate)
- Congress (Number)
- Year (First Year of Congress)
- Party.mean.diff.d1 (Difference in Party Means - First Dimension)
- Prop.moderate.d1 (Proportion Moderates)
- Prop.moderate.dem.d1 (Proportion of Moderate Democrats (-0.25 to +0.25))
- Prop.moderate.rep.d1 (Proportion of Moderate Republicans (-0.25 to +0.25))
- Overlap
- Chamber.mean.d1 (Chamber Mean - First Dimension)
- Chamber.mean.d2 (Chamber Mean - Second Dimension)
- Dem.mean.d1 (Democratic Party Mean - First Dimension)
- Dem.mean.d2 (Democratic Party Mean - Second Dimension)
- Rep.mean.d1 (Republican Party Mean - First Dimension)
- Rep.mean.d2 (Republican Party Mean - Second Dimension)
- North.rep.mean.d1 (Northern Republican Mean - First Dimension)
- North.rep.mean.d2 (Northern Republican Mean - Second Dimension)
- South.rep.mean.d1 (Southern Republican Mean - First Dimension)
- South.rep.mean.d2 (Southern Republican Mean - Second Dimension)
- North.dem.mean.d1 (Northern Democrat Mean - First Dimension)
- North.dem.mean.d2 (Northern Democrat Mean - Second Dimension)
- South.dem.mean.d1 (Southern Democrat Mean - First Dimension)
- South.dem.mean.d2 (Southern Democrat Mean - Second Dimension)

# Dataset History
2023-03-03 - Dataset is created (52,595 days after temporal coverage start date).

[Kaggle Dataset](https://www.kaggle.com/datasets/justin2028/political-polarization-in-us-congress?select=Political+Polarization+in+US+Congress+%28Assorted%29.csv) - The same data but on Kaggle.

# Polarization Plots Notebook
[Link to Notebook](https://www.kaggle.com/code/justin2028/political-polarization-us-congress-data-analysis/notebook)

# Example Graph Possible With Data
###### Credit to Jeff Lewis, Professor of Political Science at UCLA
![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F8ab2780a783aaab37e5f5446d7566d9e%2Fvoteview_party_mean_diff.png?generation=1677880338861536&alt=media)
