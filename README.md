*** WORKING PAPER ***

# ABSTRACT

* Chicago has a long history with its corner stores.  When neighborhoods decline, many corner stores are unplugged from the community.  These neighborhoods find new costs in the form of social, environmental and economic debts.  This field research quantifies these costs by estimating the effect of corner store closures on local purchasing power. My goal is to show how purchasing power varies termendously across the city.

# INTRODUCTION

* Chicago may be a single market, but its products do not have single prices. Some price differences are inevitable.  Goods downtown will cost more than ones in neighborhoods on the city's edge. My question is: how much do prices vary across the city? And is the corner store index a good guide for understanding city purchasing power?

# WHAT IS IT?

* I gather price data from corner stores, census reports and land records to find compare the value of ones dollar across the city.  My calculations show how social and environmental factors relate to neighborhood purchasing power. The corner store index is a simple illustation of purchasing-power-parity across Chicago, which shows whether goods are cheaper or steeper than you would expect given a neighborhood's level of income per person, etc.

# WHY AM I DOING THIS? SHORTCOMINGS?

* The timeliness and quality of the Corner Store Index could be a helpful supplement to official city figures.  Understanding this data is local affair, decided neighborhood by neighborhood. However, this analysis does not capture everything. The quality of the data and number crunching varies.  The indirect effects of long-term neighborhood projects are also tough to analyze, but other methods for measuring neighborhood purchasing power are worringly subjective. I believe the corner store index could have some anchoring power over the long run.

# WEB APP

* A color gradient map with a searchable tile-based interface of price data sorted by luminance, from least to most bright (to represent the value of a dollar across the city) 

# DATA COLLECTION

* All price data is collected in-person during 10 to 14 day intervals from approximately 150+ neighborhood corner stores.

# DATA PREP

* STEP 1 RawData >> unformatted spreadsheet with hand collected prices 
* STEP 2 TidyDataSet >> script takes raw data as input and produces tidy data as output
* STEP 3 Description >> describe each variable and values in tidy data set
* STEP 4 ReproducibilityRecipe >> set up calculations in a way that is easy for reproducibility

# CALCULATIONS

* I estimate what the probability is of overpaying for a select goods in neighborhood corner stores on Chicago's West and North sides.  Using a bit of rearrangement and the GLM function in R(programming language) I estimate the regression coefficients with the maximum likelihood function to identify the strength and direction of significant risk factors for overpayment. 
* I also compute a 95% confidence intervals for the slopes / odds ratios. TLDR: I'm 95% sure that the odds a location is overpaying versus the city average are between ___ and ___ greater than the odds for other locations are overpaying

# DATA EVALUATIONS

# DISCUSSION

# REFERENCES

* An Introduction to Statistical Learning with Applications in R by Gareth James et la. 
* R Programming for Data Science by Roger D. Peng
* Business Location Decisions Class Notes from Geoffrey J.D. Hewings, University of Illinois (Fall 2014)
* Statisical Analysis Class Notes from Ellen Fireman, University of Illinois (Fall 2015)
* The Web Developer Bootcamp by Colt Steele 
