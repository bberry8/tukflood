# tukflood

An interactive bathtub-flood prediction map for the community of Tuktoyaktuk, NT, Canada.

These simple flooding models predict the submerged land area by assuming that all areas connected to the ocean with a lower altitude than the storm surge height will be affected. 

The menu allows users to select:
- Storm frequency: expressed as a probability of occurrence. For example, a 1-in-2 year storm has a 50% chance of occurring in a given year, while a 1-in-100-year storm has a 1% chance.
- Year: view 2020 storm conditions, or the predicted conditions in 2050 and 2100 under RCP 8.5 climate change scenario by Baird (2019).

These maps were created using the qgis2web plugin: https://github.com/tomchadwin/qgis2web

## References
Baird (2019). Tuktoyaktuk Coastal Erosion Study. Report for the Government of the Northwest Territories, Municipal and Community Affairs.
