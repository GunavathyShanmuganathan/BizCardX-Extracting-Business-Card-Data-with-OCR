# BizCardX-Extracting-Business-Card-Data-with-OCR

**Introduction**
    This Streamlit application that allows users toupload an image of a business card and extract relevant information from it using
easyOCR. The extracted information which include the company name, card holdername, designation, mobile number, email address, website URL, area, city, state,and pin code.In addition, this application should allow users to save the extracted information intoa database along with the uploaded business card image. The database able to store multiple entries.

**Approach:**

**1. Install the required packages:**
     You will need to install Python, Streamlit,easyOCR, and a database management system like SQLite or MySQL.
     
**2. Design the user interface:**
    The user interface  is designed by using Streamlit that guides users through the process of uploading the business card image and extracting its information.
    
**3. Implement the image processing and OCR:**
    Used easyOCR to extract the relevant information from the uploaded business card image. 
     
**4. Display the extracted information: **
    Once the information has been extracted,it will be displayed in a clean and organized manner in the Streamlit GUI.
     
**5. Implement database integration:**
     MySQL is used to store the extracted information along with the uploaded business card image and SQL queries are used to create tables, insert data,
and retrieve data from the database, Update the data and Allow the user to delete the data through the streamlit UI

**6. Test the application: **
    Test the application thoroughly to ensure that it works as expected. You can run the application on your local machine by running the command streamlit run app.py in the terminal, where app.py is the name of your Streamlit application file.
    
**Libraries Used:**
 
   import easyocr as ocr  
   
   import streamlit as st
   
   from PIL import Image
   
   import numpy as np 
   
   import re
   
   import mysql.connector as sql
   
   import io
 
** Result:**
      https://gunavathyshanmuganathan-bizcardx-extracting-bus-bizcardx-oj1d3y.streamlit.app/
