# Radius Valley File Explanations

# Kepler Survey
## [Full_Data_Kepler_Survey_RECENT.csv](/Full_Data_Kepler_Survey_RECENT.csv)
This is the original data table downloaded and reformatted into a compatible CSV file from the [NASA exoplanet archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative) for the Kepler Survey.
The criteria for this data set includes:
- Exoplanet archive disposition= CONFIRMED
- Disposition score=1
- Planetary Radius Cuts: between 1.5 and 2 Earth radii

## [Kepler_Reduced_AllSystems.csv](/Kepler_Reduced_AllSystems.csv)
This contains all of the following cuts to the original data table downloaded from the NASA exoplanet archive (as described above):
- All planets in the system have an orbital eccentricity<0.1
- None of the planets have any Transit Timing Variations (TTVs)
- None of the planets have host binary star systems
- None of the planets have circumbinary orbits

## [Kepler_Reduced_MultiPlanet.csv](/Kepler_Reduced_MultiPlanet.csv)
This contains all of the reduced data for only the higher multiplicity (more than one planet in system) planetary systems

## [multiplanet_kepler_candidates_reduced.txt](/multiplanet_kepler_candidates_reduced.txt)
This text file contains our complete list of finalized candidates made compatible with UW Hyak.

## [Kep_all_data_3rad.csv](/kep_all_data_3rad.csv)
- This is the original data table downloaded and reformatted into a compatible CSV file from the [NASA exoplanet archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative) for the Kepler Survey.
The criteria for this data set includes:
- Exoplanet archive disposition= CONFIRMED
- Disposition score=1
- Planetary Radius Cuts: between 0 to 3 Earth radii
- Contains 1114 planets and 551 multiplanet systems

# TESS Survey
## [TESSsurvey.ipynb](/TESSsurvey.ipynb)
Notebook to reduce TESS data & create survey plot.

## [Full_Data_TESS_Survey.csv](/Full_Data_TESS_Survey.csv)
Data for all of the planetary systems downloaded from the [NASA exoplanet archive](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=cumulative) for the TESS Survey.

## [TESS_Reduced_AllSystems.csv](/TESS_Reduced_AllSystems.csv)
Contains all of the following cuts to the [Full_Data_TESS_Survey.csv](/Full_Data_TESS_Survey.csv) table:
- ttv_flag=0 (no TTV in the system)
- number of stars=1 (only one host star per planetary system)
- eccentric?=False (cut out all planets with an eccentric planet in the system)
