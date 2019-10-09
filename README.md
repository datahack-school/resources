# resources
Some resources used for the lessons
* **California Housing Dataset**: The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices, it does provide an accessible introductory dataset for teaching people about the basics of machine learning. A short description of its features.<br><br>
        - `longitude`: A measure of how far west a house is; a higher value is farther west.<br>
        - `latitude`: A measure of how far north a house is; a higher value is farther north.<br>
        - `housingMedianAge`: A measure of how far north a house is; a higher value is farther north.<br>
        - `totalRooms`: A measure of how far north a house is; a higher value is farther north.<br>
        - `totalBedrooms`: A measure of how far north a house is; a higher value is farther north.<br>
        - `population`: A measure of how far north a house is; a higher value is farther north.<br>
        - `households`: A measure of how far north a house is; a higher value is farther north.<br>
        - `medianIncome`: A measure of how far north a house is; a higher value is farther north.<br>
        - `medianHouseValue`: A measure of how far north a house is; a higher value is farther north.<br>
        
**Reference**

Pace, R. Kelley, and Ronald Barry, "Sparse Spatial Autoregressions," Statistics and Probability Letters, Volume 33, Number 3, May 5 1997, p. 291-297.

The following is the data methodology described in the paper:

    We collected information on the variables using all the block groups in California from the 1990 Census. In this sample a block group on average includes 1425.5 individuals living in a geographically compact area. Naturally, the geographical area included varies inversely with the population density. We computed distances among the centroids of each block group as measured in latitude and longitude. We excluded all the block groups reporting zero entries for the independent and dependent variables. The final data contained 20,640 observations on 9 characteristics.
