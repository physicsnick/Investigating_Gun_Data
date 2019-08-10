# Investigating_Gun_Data

**Key Notes:** "The data used in this notebook comes from the FBI's National Instant Criminal Background Check System. The NICS is used to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase. The data has been supplemented with state level data from census.gov.

The **NICS** data is found on sheet1 of the excel file (.xlsx) gun_data.

* The FBI Gun data inclues different background check types, such as; 'permit', 'permit_recheck', 'handgun', 'long_gun', etc... Data is collected at a month, state level for each variable in the dataset. For this analysis we will be using the total count of all background check types (all variables) at the month, state level.

The **U.S. census data** is found in a .csv file.

* It contains several variables at the state level. Most variables just have one data point per state (2016), but a few have data for more than one year."

## Questions to explore:
In this analysis we will be exploring purchasing trends in the united states. The main questions we want to answer are;

1. Does Firearm shopping have a seasonal pattern?
2. What is the avg background checks completed by month? And what is the month with the greatest avg?
3. Which states had the highest growth in gun registrations?
