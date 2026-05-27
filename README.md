# Predicting-NBA-Success
Using only collegiate stats and draft position, can we predict future NBA success?

This repository will help create an NBA success prediction model using the CBBD API. 

Files:

**Data Collection + Merging:**

This file contains all the api calls for the CBBD API as well as all the data cleaning and merging necessary to create an adequate dataset. 

**NBA Draft Model:**



**college_data_26 - draft_picks:**

This csv is needed for the overall_pick variable. Our model uses overall_pick to take into account unseen factors that scouts and managers pick up on about prospects. Until the draft occurs, the order for picks changes often, I found that having an excel sheet that I can easily update for new mocks works best and I use this csv file to easily update the values. This is then used at the end of the **Data Collection + Merging:** file.
