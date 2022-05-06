# A MultiPle Environment and MultiPle Network Parameter Path Loss Dataset


The uploaded dataset is intended for use in developing path loss models that canbe used at various environments, with various values of network parameters. It consists of three files as follows:
 
1) A file newdata.csv contains path loss measurements with other variables, including GPS coordinate of positions at which measurements were taken. 
2) A file with name extract_images.ipynb is used for downloading satellite images of GPS coordinates in newdata.csv from mapbox. 
3) A file, tiling images.ipynb is for combining the images at various distances between the transmitter and receiver into a single image.
