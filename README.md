# secDataFetch

This program was made to run in PythonAnywhere.com and what it does it gets from a personal Google Drive a .csv file full with codes named CIKs, then we download from the sec.gov's web the .xml file that we need, check if there's match between the CIKs that i have and the ones that are found in the .xml, get the info, write it in an output.csv and move on to the next .xml until we cover two years worth of .xml files (each .xml represents a quarter of a year). When the program is done it generates two outputs: the .csv with all the info that i need wich is uploaded to Google Drive and the program logs
