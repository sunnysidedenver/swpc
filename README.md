## <p align="center"> INCREASING AUTOMATION FOR SYNOPTIC DRAWING & EVENTUALLY PHASING OUT THE IDL IMAGE TOOL FOR RE-SIZING AND PRINTING IMAGES </p>

![Example Synoptic Drawing](https://raw.githubusercontent.com/sunnysidedenver/swpc/main/synoptic-map.jpg)

# GOAL

Improve forecast operations by phasing out the IDL "image" program to resize and print image files for the synoptic drawing.

# SUMMARY

This code auto-pulls image files from NASA's SDO website (https://sdo.gsfc.nasa.gov/) into a local directory then renames the files according to the file convention required to be used by the IDL "image tool" in the forecast office. Forecasters use these images to produce twice-daily synoptic drawings of the Sun. 

The code eliminates the need for forecasts to search through an enormous ftp directory for the latest files. It should be compatible with GIMP, software used by some forecasters to do the synoptic drawing digitally. 

# TESTING

This code is in beta mode and testing is ongoing in the forecast office. There is no expected completion date.

# FUTURE EFFORTS

This code currently compliments the IDL "image" program. Future iterations of code will bypass this program entirely. The code will auto-resize (ephemeris-dependent) and print the images with just a few clicks. 

The code does not pull H-alpha GONG imagery yet given that human/forecaster has to determine which image is best for analysis (i.e., which is sharpest). I will be experimenting with image analysis/machine learning techniques to train a model to auto-select the "best" image.



