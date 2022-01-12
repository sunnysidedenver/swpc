# swpc
Snippets of code written to streamline forecast operations

##GOAL

Improve forecast operations by phasing out the IDL "image" program to resize and print image files for the synoptic drawing.

##SUMMARY

This code auto-pulls image files from NASA's SDO website (https://sdo.gsfc.nasa.gov/) into a local directory then renames the files according the file convention required to be used by the "image tool" in the forecast office. Forecasters use these images to produce twice-daily synoptic drawings of the Sun. 

The code eliminates the need for forecasts to search through an ftp directory for the latest files. 

##FUTURE EFFOTS

This code currently compliments the IDL "image" program. Future iterations of code will bypass this program entirely and allow auto-resize (ephemeris-dependent) and print the code with just a few clicks. 
