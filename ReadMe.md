# Radius Valley File Explanations

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
