CORNER STORE INDEX 

by Michael Valentino Ochoa


*** WORKING PAPER ***

# WELCOME

* Chicago has a long history with its corner stores.  Often they are reflection of a neighborhood's social, economic and environmental health. This field research aims to quantify the costs of losing a corner store by estimating the effect its closures have on neighborhood purchasing power. 
* The objective is to construct a more reliable purchasing power index and better consider how neighborhood amenities affect prices at the corner store.  My goal is to showcase how purchasing power varies termendously across the city. This research was motivated how by I witnessed the value of my dollar vaporize traveling across  six blocks.

# WHY AM I DOING THIS?  WORRIES OF MINE?

* Chicago may be a single market, but its products do not have single prices. Some price differences are inevitable.  Goods downtown cost more than neighborhoods tucked miles away from the city center. My question is: how much do prices vary across the city? And is the corner store index a good guide for understanding neighborhood purchasing power?  The timeliness and quality of the Corner Store Index could be a helpful supplement to official city figures.  Understanding this data is a local affair, decided neighborhood by neighborhood. 
* Unfortunately this index will not capture everything. The quality of the field data collection and number crunching will vary.  The indirect effects of long-term neighborhood construction projects are also tough to analyze, yet other methods for measuring neighborhood purchasing power are at present worringly subjective. I believe the corner store index could have some anchoring power over the historical economic long run.  

# DATA COLLECTION

* My field work has me gathering price data from corner stores, census reports and land records to compare the value of ones dollar across the city.  This corner store index is a simple illustation of purchasing-power-parity across Chicago, which shows whether goods are cheaper or more expensive than you would expect given covariates such as:  age of buildings, building desnity, proximity to parks, etc.

* Data collection of prices of select goods occurs in-person by yours truly during 14 day intervals across neighborhood corner stores.

# DATA PREP

* STEP 1 RawData >> unformatted spreadsheet with hand collected prices 
* STEP 2 TidyDataSet >> script takes raw data as input and produces tidy data as output
* STEP 3 Description >> describe each variable and values in tidy data set
* STEP 4 ReproducibilityRecipe >> set up calculations in a way that is easy for reproducibility

# METHODS (WORKING)

* I estimate what the probability is of overpaying for a select goods in neighborhood corner stores along Chicago's North Avenue.  Using a bit of rearrangement and the GLM function in R(programming language) I estimate the regression coefficients with the maximum likelihood function to identify the strength and direction of significant risk factors for overpayment. 
* I also compute a 95% confidence intervals for the slopes / odds ratios. 
*TLDR: I'm 95% sure that the odds a location is overpaying versus the city average are between ___ and ___ greater than the odds for other locations are overpaying

# DATA STORYTELLING / UX

* Hand-drawn data illustrations will be dropped into a flowing dynamic web-application.

# DISCUSSION

# REFERENCES

* An Introduction to Statistical Learning with Applications in R by Gareth James et la. 
* R Programming for Data Science by Roger D. Peng
* Business Location Decisions Class Notes from Geoffrey J.D. Hewings, University of Illinois (Fall 2014)
* Statisical Analysis Class Notes from Ellen Fireman, University of Illinois (Fall 2015)
