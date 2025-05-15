# Weekly/Bi-Weekly Log

## Prompts
Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:

### Date: 
Week number, today's date, etc. 


### Number of hours: 
A quantity of hours, maybe towards specific tasks. 

### Rose:
The highlight from the previous weekly/bi-weekly working period, such as something you found particularly rewarding. This could also be something you're excited to implement now.

### Bud: 
Something that you are looking forward to digging into deeper. This could also be ideas on how to apply concepts to your research in the future. 

### Thorn: 
Something that was challenging that could be worked on, such as anything that wasn't 100% clear and could be elaborated on. Any sticking points should be addressed here. 

## Additional thought
Write anything that you think would be important for YOU later on.

---
##Log 1: Jan 29 – Feb 11
Tasks: Team Formation, Project Familiarization & Goal Definition
Hours: ~8 hrs

#Rose:
We successfully formed our team and had several productive discussions to define the project's goals and understand expectations. Assigning roles early helped streamline responsibilities moving forward.

#Bud:
Looking forward to diving into the literature to understand NEE, modeling, and sensor data characteristics more thoroughly.

#Thorn:
Initial ambiguity in defining everyone's roles led to overlapping efforts, but we resolved it through a clear planning session.

##Log 2: Feb 12 – Feb 27
Tasks: Literature Exploration, Dataset Acquisition
Hours: ~8 hrs

#Rose:
Gained insights into NEE modeling, data imputation, and the importance of tower placement. We also acquired our initial raw datasets, which was a key milestone.

#Bud:
Excited to start cleaning and analyzing the datasets to identify meaningful patterns and features.

#Thorn:
The volume and diversity of literature made it overwhelming to filter relevant material. It took extra time to organize findings effectively.

##Log 3: Feb 28 – Mar 02
Tasks: Zone & Variable Selection, Null & Missing Value Checks
Hours: ~5 hrs

#Rose:
Identified key zones (NE and CO) and confirmed the completeness of high-resolution (15-min) sensor data. Selected essential variables for analysis.

#Bud:
Planning to begin missing value interpolation techniques and assess how they influence downstream analysis.

#Thorn:
Some variables had unexpected null patterns due to sensor downtime, which required revisiting our selection criteria.

##Log 4: Mar 03 – Mar 07
Tasks: Interpolation of Missing Data, Outlier Detection
Hours: ~5 hrs

#Rose:
Implemented interpolation effectively. Outlier detection was conducted using IQR and KNN-based approaches with solid success.

#Bud:
Looking forward to visualizing these detections to validate accuracy and prepare for aggregation.

#Thorn:
IQR method found to be a bit less accurate than KNN. Felt like invested too much for us not to use it anymore.

##Log 5: Mar 08 – Mar 11
Tasks: Outlier Visualization, Tower Selection
Hours: ~6 hrs

#Rose:
Plotted outlier distributions and validated. Finalized the selection of NE and Mountain towers for focused analysis.

#Bud:
Ready to calibrate data from these towers, which will enhance confidence in subsequent NEE estimates.

#Thorn:
Some tower metadata was incomplete, which complicated the validation of sensor placement and readings.

##Log 6: Mar 12 – Mar 20
Tasks: Humidity Data Cleaning, Tower Calibration, Radiation, Temp, RH Calibration
Hours: ~7 hrs

#Rose:
Cleaned humidity data using robust bounds and calibrated sensors based on height. Applied corrections to radiation and temperature using reference measurements.

#Bud:
Now preparing datasets for standardization and aggregation across time and zones.

#Thorn:
Conflicting calibration equations in prior documentation led to rechecking our calibration methods with reference data.

##Log 7: Mar 21 – Mar 26
Tasks: Data Cleaning & Standardization, Zone-Wise Daily Averaging
Hours: ~7 hrs

#Rose:
Successfully standardized datasets (units, timestamps) and averaged variables (temp, RH) by zone and day.

#Bud:
Planning CO₂ mole calculations next, which will be key for NEE.

#Thorn:
Inconsistent timestamp formats across towers made merging datasets tedious and time-consuming.

##Log 8: Mar 27 – Mar 31
Tasks: CO₂ Moles Calculation, Buffer/QA Period
Hours: ~6 hrs

#Rose:
Calculated moles of CO₂ per sample using cleaned sensor data and ideal gas law. Quick QA buffer helped us catch minor inconsistencies early.

#Bud:
Next step involves computing the final NEE estimates, which ties everything together.

#Thorn:
Unit conversion mistakes in early iterations required rechecking all formula implementations.

##Log 9: Apr 01 – Apr 08
Tasks: NEE Calculation for 2020, Extended Analysis (2024–2025), Signed Proposal
Hours: ~8 hrs

#Rose:
Estimated years NEE successfully using flux-based methods and daily averages. Also submitted a signed proposal.

#Bud:
Eager to apply fill in missing values and finally feeling like not so lost.

#Thorn:
Running seasonal aggregations over long time spans required large memory and introduced delays in script execution.

##Log 10: Apr 09 – Apr 16
Tasks: Pattern Recognition for Imputation, Missing Value Filling
Hours: ~7 hrs

#Rose:
Making progress no fillimg out missing values and getting an ides on how to continue the next analysis

#Bud:
Now that data is imputed, we can begin cross-tower aggregation and prepare visuals for final presentation.

#Thorn:
Had to customize standard algorithms to account for region-specific trends, which wasn’t straightforward.

##Log 11: Apr 17 – Apr 30
Tasks: Cross-Tower Zone Aggregation, Poster & Showcase Preparation
Hours: ~10 hrs

#Rose:
Successfully aggregated cross-tower data, ensuring spatial consistency. Began drafting the poster and finalized ishowcase content.

#Bud:
Excited to formally present the findings and share outcomes with peers and faculty.

#Thorn:
It was difficult to visulaize all the analytical work with visual clarity in the poster design.

##Log 12: May 01 – May 04
Tasks: Final Presentation, Final Documentation Submission
Hours: ~8 hrs

#Rose:
Completed the final presentation and documentation. Successfully delivered the talk and submitted the final cleaned datasets, methodology, and results.

#Bud:
Looking forward to incorporating feedback and possibly publishing parts of this work.

#Thorn:
Forget to add 2019 codes to the data preprocessing files and to haev to chaneg variables name sto maintain consistency.







