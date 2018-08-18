# gunData
This is a collection of data that may be useful pertaining to gun violence.



## Gun_Violence_Archive 
In this folder you will find raw data from https://www.gunviolencearchive.org/

###### From their website:
>Gun Violence Archive (GVA) is a not for profit corporation formed in 2013 to provide free online public access to accurate information about gun-related violence in the United States.

Included within these data are date, state, city, address, # killed and # injured.

These data need a lot of work, but I will be working on creating reproducible methods to use as more data are produced. This includes-but is not limited to-figuring out an efficient and reproducible way to parse addresses and geocode them. I would also like to simplify the process so these data can be more easily used for mapping.

## Shot_Spotter
In this folder you will find raw data from http://justicetechlab.org/shotspotter-data/

###### Justice Tech Lab
>FINDING EFFECTIVE, SCALABLE SOLUTIONS TO CRIMINAL JUSTICE PROBLEMS

These are geographic point data of the traingulation of gunshots by a company called shotspotter. https://www.shotspotter.com

These data will need to be cleaned before they can be used effectively. I will be working on methods to accomplish this. These data are limited, but I believe that is the nature of Shot Spotter data.

From TIME http://time.com/4951192/shots-fired-shotspotter/
> "Any potential study is complicated by ShotSpotter’s refusal to release its data. Every shot registered by its sensors is owned by the company. Anyone wanting to fully analyze gunfire patterns must pay ShotSpotter for the information–a decision Clark defends on the grounds that the data is too valuable to give away."

## Other resources 

CompstatR package
https://github.com/slu-openGIS/compstatr
R package for working with St. Louis Metropolitan Police Department crime data
