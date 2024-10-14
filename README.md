# Data-Visualization-Website

This document provides an operation guide for the project.

**Notice: This project has been discontinued and is no longer actively maintained.**

## Project Introduction

This project crawls Chinese national data and automatically processes it into MySQL. The Flask framework is used to build web pages for data visualization.

## Environment Dependencies

- Python 3.x
- MySQL 8.0

## Directory Structure Description

```
scss复制代码│  list.txt  
│  README.txt  
│  
├─ back  
│  ├─ final_code.py   // Back-end crawler startup file  
│  │  
│  ├─ .idea   // IDEA configuration files  
│  │  └─ ...  
│  │          
│  ├─ Lib  // Static library files  
│  │  └─ ...  
│  │              
│  └─ Scripts   // Script files  
│      └─ ...  
│          
├─ database  
│  └─ house.sql  // Project database  
│      
└─ front  
    │  app.py  // Front-end project startup file  
    │  
    ├─ .idea   // IDEA configuration files  
    │  └─ ...  
    │          
    ├─ data  // Excel files containing data for each province  
    │  
    ├─ static // Static files  
    │  └─ assets  
    │      ├─ css   // Web page stylesheets  
    │      │  └─ ...  
    │      ├─ font  // Web page fonts  
    │      │  └─ ...  
    │      ├─ img   // Web page images  
    │      │  └─ ...  
    │      └─ js    // Web page JavaScript files  
    │          └─ ...            
    ├─ templates   // Web page templates  
    └─ __pycache__
```

## Instructions

1. The data crawled by the back-end will be imported directly into the `house` database. Ensure that the "house" library is created in the target database before running the project.
2. Confirm that the data is saved to the local database, otherwise, a 500 error will occur.

## Version Updates

Updates to the project will be listed here.