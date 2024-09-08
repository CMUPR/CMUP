The file of "Code" provides the code and necessary case study data to run the coastal marine use planning model.
The spatial planning model for the coastal zone is written in R language, and the main code is in "Model.R"
The files of "Template_for_marine_use_planning.shp", "Template_for_onshore_industries.shp" and "Pre_calculated_distance_matrix.RData" are the basic template data provided for the coastal marine use planning.
Node:
You can open the project file directly, or open the R language file, and modify the internal file paths.
Some additional R language packages need to be installed in advance, includes the:

#install.packages("raster")
#install.packages("sf")
#install.packages("gdalUtilities")
#install.packages("dggridR")
#install.packages("spdep")

The file of "Data" provides the raw data for the marine spatial resource assessment, and the specific calculation methods and data sources are described in the document "Suitability assessment method.docx". In addition, The file of "hexagonal space calculation grid" provide the benchmark for spatial calculation, and the file of "Suitability assessment results for different marine use types" provide the Suitability assessment results, and the file of "Onshore industries" provides the spatial distribution of onshore industries in Jiangsu Province, China.
