# GrasshopperSparrowDispersalFood
This repository contains data and code for the manuscript titled "Food availability cannot explain dispersal and settlement decisions of a grassland bird"

Emily J. Williams, Theo K. Michaels, and W. Alice Boyle


All data for this study was analyzed using R software using code included in analysis files. Code is executable using WilliamsEtAl_04Dec2025.Rmd and the html version includes all code and output of analyses. 

Associated data files in .CSV format: 
	# "EdibleMassData2014_raw.csv"
	# "GRSP_Food_Manuscript_Final_Dec2025.csv"
	# "GRSP_DispersalData_withBFE_April2025.csv"

Throughout, "GRSP" is the code for the species, Grasshopper Sparrow. 

Variable descriptions found in .csv file "EdibleMassData2014_raw.csv":
This data is used for prediction i. 
Watershed: Unique name of pasture.
TransectID: Unique identification number of the transect within each pasture; 150m2 per transect (80 m x 1.88 m sweep width).
EdibleMass: Mass of potential prey collected within the 150m2 transect (g/150m2).
SweepNumb: Two sweeps, 1 or 2, within each TransectID.
DateSampled: Date that sweeps were conducted. 
TimePeriod: GRSP breeding season designated as Early, Mid, or Late. 
BurnTreatment: Frequency of the prescribe fire regime every 1, 2, or 3 years. 
GrazingTreatment: Grazing by Bison, Cattle, or no grazing (None).
YearSinceBurn: Number of years since the prescribed burn relative to the year sampled, either 0,1,2.

Variable descriptions found in .csv file "GRSP_Food_Manuscript_Final_Dec2025.csv":
This data is used for predictions ii-iv. 
CaptureDate: Date GRSP individual was captured.
PlotName: Unique Name of pasture, referred to as "Watershed" above.
CaptureTime: Time of capture. 
Recap: If the GRSP individual was captured before (TRUE) or not (FALSE) over the corse of the study.
BandPrefixNumber: Leg band number that identifies a shared batch of bands associated with the location where captured. 
BandSuffixNumber: Unique leg band number associated with the individual.
ColorBands: Unique set of colored leg bands associated with the individual.
Age: Age of the individual, designated by a three letter code. 
Sex: Sex of the individual, either male (M), female (F), or unknown (U). 
FatScore: A categorical designation of the amount of fat on the individual.
ConcTRIG: The measure of Triglycerides (TRIG), blood plasma lipid metabolites that provide measures of energy dynamics (mmol/l).
TRIG.issues: A designation of issues with sampling, blood analysis, etc., either True (issues)or False (no issues).
BurnTreatment: Frequency of the prescribe fire regime every 1, 2, or 3 years. 
GrazingTreatment: Grazing by Bison, Cattle, or no grazing (None).
timeperiod: GRSP breeding season designated as Early, Mid, or Late. 
CaptureYear: Year individual was captured. 
YearSinceBurn: Number of years since the prescribed burn relative to the year sampled, either 0,1,2.
MeanDensity: The period specific density of GRSP of a 10-ha designated plot within the PlotName,(territorial males/10-ha).
MeanEdiableMass: The mean of the edible biomass within each PlotName (g/150m2). Note that data is for 2014 only, the year edible biomass was collected. 

Variable descriptions found in .csv file "GRSP_DispersalData_withBFE_April2025.csv":
This data is used for prediction v. 
ColorBands: Unique set of colored leg bands associated with the individual.
Year: Year individual was captured. 
DispersalStatus: Males that were identified and recaptured, designation of dispersal status, either dispersed (disperser) or site-faithful (non-disperser). 
Diff_ConcTRIG: The difference in TRIG determined by subtracting the value associated with the first capture from the second capture(mmol/l). 
Diff_ResidTRIG: The difference in Residual TRIG determined by subtracting the Residual TRIG value associated with the first capture from the second capture(mmol/l). 

