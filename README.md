# MicrosoftBuildingsToFeatureclass

The toolbox and associated script in the zipped folder will convert the geoJSON building 
footprints from Microsofts USBuildingFootprints project to ESRI Polygon features

Download the zipped folder and unzip it.

Either add the toolbox to ArcCatalog or ArcMap.

Execute the tool.

The parameters that you must enter are:
raw json file from microsoft
Desired spatial refernece for the output featureclass
Filepath to an existing GDB where featureclass will be created
Name for output featureclass

THE FEATURECLASS WILL BE DELETED IF IT ALREADY EXISTS WHEN SCRIPT IS EXECUTED.
