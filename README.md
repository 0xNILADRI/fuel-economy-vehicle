# Fuel Economy


## Data on Cars used for Testing Fuel Economy¶


The test data used to determine fuel economy estimates is derived from vehicle testing done at EPA's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, and by vehicle manufacturers who submit their own test data to EPA.

Each year, EPA provides fuel economy data to the Department of Energy (DOE), the Department of Transportation (DOT) and the Internal Revenue Service (IRS) so that they can administer their fuel economy-related programs.

## Overview


In this scenario we will analyse how the fuel economy has made impact on vehicles after a decade. Therfor we will use the dataset for 2010 and 2020 respectively and analyse how much impact has been done. One of the major concern of recent times is pollution which contributes to environmental degradatation and vehicles adds the most of it. With the steep increase in vehicle buying we need to analyse the economy of vehicles, as the more fuel is burnt the more residue is emmisioned into the atmosphere plus the rapid decrease in non-renuable sources would put a devastation scenario to our future generations.

### Python libraries used

      1.Numpy
      2.Panadas
      3.Matplotlib.pyplot
      4.Seaborn


### Data Sets

      1.all_alpha_10.xls
      2.all_alpha_20.xlsx
      3.data_2010_v1.csv
      4.data_2020_v1.csv
      5.data_2010_v2.csv
      6.data_2020_v2.csv
      7.data_combined.csv
      8.data_combined_onehot.csv


## About the Dataset


Fuel economy data are the result of vehicle testing done at the Environmental Protection Agency's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, and by vehicle manufacturers with oversight by EPA.


Source : <a href="https://www.fueleconomy.gov/feg/download.shtml"></a>


### Attribute Information

The data set comprises of the following features of vehicles and the respective vehicles data points :

* Model – vehicle make and model
* Displ – engine displacement in liters
* Cyl – number of engine cylinders
* Trans – transmission type plus number of gears
    1. Auto - Automatic
    2. Man - Manual
    3. SemiAuto - Semi-Automatic
    4. SCV - Selectable Continuously Variable (e.g. CVT with paddles)
    5. AutoMan - Automated Manual
    6. AMS - Automated Manual-Selectable (e.g. Automated Manual with paddles)
    7. Other - Other
    8. CVT - Continuously Variable
    9. CM3 - Creeper/Manual 3-Speed
    10. CM4 - Creeper/Manual 4-Speed
    11. C4 - Creeper/Manual 4-Speed
    12. C5 - Creeper/Manual 5-Speed
    13. Auto-S2 - Semi-Automatic 2-Speed
    14. Auto-S3 - Semi-Automatic 3-Speed
    15. Auto-S4 - Semi-Automatic 4-Speed
    16. Auto-S5 - Semi-Automatic 5-Speed
    17. Auto-S6 - Semi-Automatic 6-Speed
    18. Auto-S7 - Semi-Automatic 7-Speed
* Drive – 2-wheel Drive, 4-wheel drive/all-wheel drive
* Fuel – fuel(s)
* Veh Class – EPA vehicle class. 
* Air Pollution Score (Smog Rating) 
* City MPG – city fuel economy in miles per gallon
* Hwy MPG – highway fuel economy in miles per gallon
* Cmb MPG – combined city/highway fuel economy in miles per gallon
* Greenhouse Gas Score (Greenhouse Gas Rating) 
* SmartWay – Yes, No, or Elite. 
* Comb CO 2 – combined city/highway CO 2 tailpipe emissions in grams per mile