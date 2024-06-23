# Ruby-travelmanager

This is ruby - a Saas application that helps you find out the latest events and celebrations that happen around you or any place around the world. This is a Django application that has all the basic features of any modern application. I am working more on improving and implementing features to this application

## Features

- Custom user registration and login using passwords
- Create and views Events in specific locations
- Uses Django's Postgis extension to find distance between points 
- User can select date and distance to location of event to filter events displayed
- Users can add events including pictures , date-time and location
- Uses Google's Maps API to sent your selected location info and recieve nearest places
- Users can View all nearby attractions and locations and filter based on category 


## How to initialise your local Repository

The following commands helps you to set up this project on your local machine
Make sure to install [postgis](https://postgis.net/) and pgadmin(optional) 
Note:  GDAL and postgis installation can vary accouring to your device. red docuumentation to know more..!
```sh
python venv rubyvenv
rubyenv/Scripts/activate 
pip install -r requirements.txt
pip install gdal
```

#Images
<img src="https://github.com/ArjunKVarma/ruby-travelmanager/blob/main/images/home.png" alt="Home image" width="500" height="270"/>
<img src="drawing.jpg" alt="drawing" width="200" height=""/>
<img src="drawing.jpg" alt="drawing" width="200" height=""/>
<img src="drawing.jpg" alt="drawing" width="200" height=""/>
<img src="drawing.jpg" alt="drawing" width="200" height=""/>
