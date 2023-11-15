# CHOKE1.0

Data and code accompany Stellpflug, S., Dalrymple, K.A., Dummer, M. F., Schindler, B.R., Ashton, S.V., Bachman, D., & LeFevere, R. (under review). Cognitive assessment in grappling athletes following choke versus non-choke submissions.

CHOKE 1.0.rmd was programed in 2023.06.0 Build 421 (RStudio Team, 2020), by Kirsten A. Dalrymple, PhD, CCRC.

***NOTE: Code runs best chunk by chunk. Do not Run All.

CHOKE folder contains: 
 /CHOKE 1.0.rmd
 /Data_In
 /Data_Out
 /Figures
 /Stats


FILE AND FOLDER DESCRIPTIONS

/CHOKE 1.0.rmd code to be run in R Studio.


/Data_In:

File name (.csv)	and variables included

CHOKE_1_Data_Clean	

 Internal Id: random ID.

First name: Anonymized first name.

•	Last name: Anonymized last name.

•	Age: participant age in years.

•	Belt: highest Jiu Jitsu belt achieved

•	Experience: Number of years of experience in grappling sport

•	Baseline (sec): Best time from all tests, in seconds.

•	Teams: Participants were assigned to Choke or Non-Choke depending on the outcome of their spar, and Male or Female.

•	HitHead: 0 = did not hit head during spar, 1 = did hit head during spar.

•	1. Test Type: Baseline or “Post-Injury”. Post-Injury is the test after sparring.  

•	1. Duration (sec): Time it took participant to complete Test 1, in seconds.

•	1. Errors: Number of errors in Test 1.

•	1. Number of Cards: Number of cards completed in Test 1 (out of 3).


•	1. Card 1 Duration (sec): Time to complete Card 1 from Test 1, in seconds.

•	1. Card 2 Duration (sec): Time to complete Card 2 from Test 1, in seconds.

•	1. Card 3 Duration (sec): Time to complete Card 3 from Test 1, in seconds.

•	2. Test Type: Baseline or Post-Injury. “Post-Injury” is the test after sparring.  

•	2. Duration (sec): Time it took participant to complete Test 2, in seconds.


•	2. Errors: Number of errors in Test 2.

•	2. Number of Cards: Number of cards completed in Test 2 (out of 3).

•	2. Card 1 Duration (sec): Time to complete Card 1 from Test 2, in seconds.

•	2. Card 2 Duration (sec): Time to complete Card 2 from Test 2, in seconds.

•	2. Card 3 Duration (sec): Time to complete Card 3 from Test 2, in seconds.

•	3. Test Type: Baseline or Post-Injury.  

•	3. Duration (sec): Time it took participant to complete Test 3, in seconds.

•	3. Errors: Number of errors in Test 3.

•	3. Baseline when run (sec): Best baseline time out of all baseline tests for that participant, in seconds. 

•	3. Card 1 Duration (sec): Time to complete Card 1 from Test 3, in seconds.

•	3. Card 2 Duration (sec): Time to complete Card 2 from Test 3, in seconds.

•	3. Card 3 Duration (sec): Time to complete Card 3 from Test 3, in seconds.

•	4. Test Type: Baseline or Post-Injury. 

•	4. Duration (sec): Time it took participant to complete Test 4, in seconds.

•	4. Errors: Number of errors in Test 4.

•	4. Baseline when run (sec): Post-test 2 baseline time, in seconds.

•	4. Card 1 Duration (sec): Time to complete Card 1 from Test 4, in seconds.

•	4. Card 2 Duration (sec): Time to complete Card 2 from Test 4, in seconds.

•	4. Card 3 Duration (sec): Time to complete Card 3 from Test 4, in seconds.



/Data_Out: Summary files produced by R code are saved here.



/Figures: Figures produced by R code are saved here.



/Stats: Chi square tests run by R code are saved here.



REFERENCES

RStudio Team (2020). RStudio: Integrated Development for R. RStudio, PBC, Boston, MA URL http://www.rstudio.com/
