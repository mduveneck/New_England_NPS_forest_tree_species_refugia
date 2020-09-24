# New_England_NPS_forest_tree_species_refugia
Species maps within National Park units in New England
Matthew Duveneck
August 2020
These biomass maps simulated current conditions (2010) and simulated conditions at year 2050, and 2080 under climate change.  Specifically, I used the Hadley Global Circulation Model coupled to the RCP 8.5 emission scenario.   I added a buffer around each NPS park unit based on a 20% increase in the maximum distance across the park.  Therefore, the buffer area varied based on the size (and shape) of the park.  The refugia maps for each species and NPS unit are made for the area assuming: sustained sites= sites where species-specific simulated biomass was present in 2010 AND species-specific simulated biomass was present in 2080.  New sites = sites where species-specific simulated biomass was not present in 2010 but did occur in 2080. Lost sites = sites where species-specific simulated biomass was present in 2010 but did not occur in 2080.  

Percentages listed on the maps refer to the percent of cells in each group among the cells in the park unit (and NOT the buffer area shown around the park unit). That is, the percentages refer to all the cells in the Park unit only of new, sustained, and lost sites.  Likewise, average biomass values shown in each map represents the mean species biomass within the NPS boundary only.  

Species maps were created when a particular species was present somewhere on the landscape in 2010 (in at least one cell).  Therefore, some park units may show high percentages but in reality, do not have a lot of that species to begin with (e.g. Lowell National Historical Park with sugar maple).
Important notes: These simulations do not include land-use.  That is, they represent an unrealistic hypothetical absence of any human-disturbance. The raster resolution of the species communities is 250m, however climate is represented is a much coarser scale.  Simulated species biomass for these figures are aboveground biomass only (Mg/ha).  I did not include species maps in National Park units where none of that species was present in 2010 (some park units have no forest at all).  

These results represent a simulated representation of a scenario zoomed-in for each National Park unit.  This model was initially intended to study large landscape patterns (i.e., all of New England).  These simulation results for individual parks (especially considering the limits to the analysis) should not be interpreted as predictions.   

For the map legends, NF=non forest or no-data available.  
The csv file (New_england_species_parks_refugia.csv) show the same information as the maps in a summary table.  Table fields are as follows:
	P= Park Unit Name (Appalachian Trail sub-sections are denoted with “AT_” and then the 	subsection name.
	SPP_name = Tree Species Name
	Mean_2010 = Species specific mean aboveground biomass Mg/ha across all cells in map in the 	year 2010.
	Mean_2050 = Species specific mean aboveground biomass Mg/ha across all cells in map in the 	year 2050.
	Mean_2080 = Species specific mean aboveground biomass Mg/ha across all cells in map in the 	year 2080.
refugia_count_cells = number of cells categorized as refugia (using definition described above) 	within the map.
transition_count_cells = number of cells categorized as transition (using definition described 	above) 	within the map.
lost_count_cells = number of cells categorized as lost (using definition described above) 	within 	the map.
	refugia_percent = Percent of cells in map categorized as refugia.

	transition_percent = Percent of cells in map categorized as transition.

	lost_percent = Percent of cells in map categorized as lost.

More details about the methods including the forest succession model, climate scenarios, and soils can be found in the following publication.  
Duveneck, M. J., & Thompson, J. R. (2017). Climate change imposes phenological trade‐offs on forest net primary productivity. Journal of Geophysical Research: Biogeosciences, 122(9), 2298-2313.
