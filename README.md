# AP_sliceAnalysis
This macro was developed for analysis of organotypic slice culture 

IHC Data should be: nested folders of non-RGB z-stack MAX projection compressed two channel images 

Asks for adjustment of rolling ball radius for the two channels,
max/min puncta size, adjustment of circularity, but these shouldn’t need to change so they can be left as is 

Outputs three folders per channel: 
binary, data, puncta masks: 
Binary – masks of the image separated by channel 
Data – contains the .zip file with ROI data and an .xls file with the individual puncta areas per image 
Puncta masks – contains a tracing of the puncta analyzed in each image 

Also outputs a “Summary.xls” file: Contains the total area of each image, the total area occupied by puncta, 
the ratio of puncta area/total area, avg area of individual puncta, total # puncta, #puncta/100um^2, 
mean grey value per puncta, and descriptors of the pixel size
