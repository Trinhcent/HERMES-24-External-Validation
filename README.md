# HERMES-24 External Validation 

## R markdown file with example scripts and code for Trinh et al. (2026)

The HERMES-24 score is a stroke prognostication tool published by Tanaka et al. in 2024
to prognosticate patient outcome following endovascular treatment of Large Vessel Occlusion
stroke. 

It was derived utilising the HERMES (Highly Effective Reperfusion Evaluated in Multiple
Endovascular Stroke Trials) collaboration dataset (n=1764) and externally validated using cohorts
from the ESCAPE-NA1 (Efficacy and Safety of Nerintide for the Treatment of ACute
Ischaemic Stroke; n=1066) and INTERRSeCT ( (Identifying New Approaches to Optimize Thrombus 
Characterization for Predicting Early Recanalization and Reperfusion With IV Alteplase and 
Other Treatments Using Serial CT Angiography; n=614) trials. 
The score was also further validated for patients presenting in the late time window.

The included file contains code to perform the following in R: 
* Calculate discriminative performance and calibration metrics for binary outcomes
* Evaluate ordinal performance for 3 month modified Rankin Score
* Subgroup analysis of binary and ordinal outcomes
* Temporal analysis of discriminative performance and time-cut off sensitivity analyses