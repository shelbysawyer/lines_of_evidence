My project will be developing transform functions for "lines of evidence" for use in a spatial data tool. The output of the tool is a likelihood raster that shows likelihood of valley bottom. The lines of evidence that I will be using are: slope, HAND (height-above-nearest drainage), and DA (drainage area).

Data type and sourcing: The data for this project will be in the form of a .csv file of point data. This data will be derived from a point shapefile that will be used to pull values from the same locations on the three raster layers (slope, HAND, DA) in ArcMap. I'll plot these points in excel to produce figures.

gitignore: I chose to ignore the figures folder, as well as any files with the .docx or .tiff extentions. I don't need Git to track changes to any .docx files or figure images, and I also don't want it to track .tiff files (if I choose to store them in this repository) because of their size.

