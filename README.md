# Exploring-Sentinel5p
Exploratory Data Analysis on Sentinel 5p data

## Introduction
We will start our exploration using the excellent blogpost 
[http://www.acgeospatial.co.uk/sentinel-5p-and-python/](http://www.acgeospatial.co.uk/sentinel-5p-and-python/) as a 
basis.

'bash
source dhusget.sh -d https://s5phub.copernicus.eu/dhus/#/home -u sp5guest -p sp5guest -m Sentinel-5 -i TROPOMI -S 2018-08-01T00:00:00.000Z -c 50.659,-0.534:50.972,0.323 -T NO2 -o manifest -O ./`