The spatial planning model for the coastal zone is written in R language, and the main code is in "Model.R"
The files of "Template_for_marine_use_planning.shp", "Template_for_onshore_industries.shp" and "Pre_calculated_distance_matrix.RData" are the basic template data provided for the coastal marine use spatial planning.
Node:
You can open the project file directly, or open the R language file, and modify the internal file paths.
Some additional R language packages need to be installed in advance, includes the:

#install.packages("raster")
#install.packages("sf")
#install.packages("gdalUtilities")
#install.packages("dggridR")
#install.packages("spdep")