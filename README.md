# Data-Visualization-Website
This is the operation guide for the project.


# Project introduction
The project can crawl Chinese national data and automatically process it into MySQL. Flask framework is used to build web pages to realize data visualization.

# Environmental dependence
Python 3.0
MySQL 8.0

# Directory structure description

│  list.txt
│  README.txt
│  
├─back
│  ├─  最终代码.py   //Back-end crawler startup file
│  │  
│  ├─.idea   //IDEA configuration file
│  │  │  
│  │  └─.......
│  │          
│  ├─Lib  //Static library file
│  │  └─.......
│  │              
│  └─Scripts   //Script file
│   	└─.......
│          
├─database
│ 	├─house.sql  //Project database
│      
└─front
    │  app.py  //Front-end project startup file
    │  
    ├─.idea   //IDEA configuration file
    │  └─.......
    │          
    ├─data  //excel table of data for each province
    │      
    ├─static //Static file
    │  └─assets
    │      ├─css   //Web page cascading style Sheets
    │      	  └─.......
    │      ├─font  //Font file required for web page
    │          └─.......
    │      ├─img   //Page involving pictures
    │          └─.......
    │      └─js    //Web javascript
    │          └─.......            
    ├─templates   //Web page
    │
    └─__pycache__

# Instructions
    1.Data crawled by the back end will be imported directly into the "house" library, so make sure you have created "house" in the target database.
    2.Ensure that the data has been saved to the local database. Otherwise, an error of 500 will be reported

           
# Version content is updated
