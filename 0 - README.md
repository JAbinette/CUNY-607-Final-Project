# CUNY-607-Final-Project

**File Naming Convention:** 
Files starting with 0 are the datasets imported into R for analysis 
Files starting with 1 includes supplemental information related to source and content of datasets (e.g.,data dictionaries, criteria, etc.)
Files starting with 2 are FINAL versions of R Analysis and Project Presentation

**Background:** 
In 2019, the U.S. ranked eighth out of 64 high-income countries & territories for homicides by firearm with Puerto Rico and the US Virgin Islands, two US territories, ranking first and third. (https://www.healthdata.org/acting-data/gun-violence-united-states-outlier)

**Research Question:** 
Are there aspects of gun policy in the U.S. that predict firearm mortality rate?

**Dataset Sources used in analysis include:**
1) Underlying Cause of Death by Single Race data retrieved from wonder.cdc.gov grouped by State, Year & Cause of Death.  Statistics for firearm as cause of death exclude Terrorism, Legal Intervention and Operations of War

2) Firearm Laws by State data retrieved from https://www.statefirearmlaws.org/resources
Database containing detailed annual information on firearm-related laws in place in each of the 50 US states from 1991 to 2016 indicating the presence or absence of each of 133 provisions of firearm laws covering 14 aspects of state policies, including regulation of the process by which firearm transfers take place, ammunition, firearm possession, firearm storage, firearm trafficking, and liability of firearm manufacturers.
    For Data Dictionary see file titled '1 - Data Dictionary for statefirearmlaws.org - codebook_0'
    Michael Siegel, Molly Pahn, Ziming Xuan, Craig S. Ross, Sandro Galea, Bindu Kalesan, Eric Fleegler, and Kristin A. Goss, 
      2017:Firearm-Related Laws in All 50 US States, 1991–2016 American Journal of Public Health 107, 1122_1129, https://doi.org/10.2105/AJPH.2017.303701

Analysis in R Studio:
RPubs: https://rpubs.com/JAbinette/CUNY607_Final_Presentation
    
Conclusion:
The total number of firearm laws is a significant predictor and accounts for 49% of the variability in Firearm Deaths as a Proportion of the State Population. In breaking down the firearm laws by category, a multiple regression analysis determined that the number of Stand Your Ground, Child Access Prevention, and Preemption firearm laws can explain 55% of the variability.
