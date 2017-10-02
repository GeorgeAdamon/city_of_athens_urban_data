# city_of_athens_urban_data
Processed GIS dataset of City Blocks and Backyards of the Municipality of Athens, Greece

Author : Georgios Adamopoulos
Original Raw Data:  NTUA School of Architecture, Laboratory of Geographical Information Systems in Urban and Regional Planning

This dataset was originally produced as part of the NTUA School of Architecture Thesis Project **"KEMP: A Digital Platform for Participatory Design"** *(Adamopoulos, G., Pappas, P. and Aronidis, E. (2016). KEMP: A Digital Platform for Participatory Design. Master Thesis. National Technical University of Athens, School of Architecture.)* and proved to be a valuable tool for the analysis, filtering and classification of Athens' city blocks.

We open this dataset to any researcher interested in analysing the city of Athens, welcoming additions, corrections and forks.

The numerical data contained in this dataset are original and were computed by the author within the Grasshopper3D plug-in of the Rhinoceros package. They were exported in .shp format via a custom python script, utilizing the pyshp library.

Part of the geometric data ("shapes" or "polygons") contained in this dataset are a derivative of the original data obtained thrpugh the standard procedure from  the Laboratory of Geographical Information Systems in Urban and Regional Planning, in the NTUA School of Architecture. These data unfortunately correspond to the 2001 census. A significant amount of geometric computation and clean-up has been performed on the raw data in order to extract the shapes of the CityBlock Backyards, which were originally produced by the author. 

The Geographic Projection System is **GGRS87/Greek Grid (EPSG:2100)** . The corresponding .prj files are included.

## Explanation of CityBlock Properties

| Property | Meaning |
|:--------:|:-------|
Area        | Total Area of the City Block
AtriumCount | Number of joined backyards or "Akaliptoi"
AtriumToBui | The ratio of the area covered by Backyards to the are covered by Buildings
AtriumToTot | The ratio of the area covered by Backyards to the total CityBlock area
BlockID     | The ID of the CityBlock
BuildingCou | The number of buildings contained in the City Block
BuildingDen | The number of buildings per 1000 square meters (property density) contained in the City Block
BuiltToTotal| The ratio of the area covered by Buildings to the total CityBlock area
Deviation45 | The angle between the CityBlock's longitudinal axis and the North vector, remapped to a 0-45 degree range
Deviation90 | The angle between the CityBlock's longitudinal axis and the North vector, remapped to a 0-90 degree range
Deviation18 | The angle between the CityBlock's longitudinal axis and the North vector, remapped to a 0-180 degree range
Ratio       | The ratio of the longest side of the CityBlock to its shortest side.
Perimeter   | The Perimeter of the City Block
TotalBuiltA | Total Area covered by Buildings
TotalAtrium | Total Area covered by Backyards

