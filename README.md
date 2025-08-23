# Python Weather Report System

**MAUNAL IMPORT IS REQUIRED DURING THE EARLY ACCESS STAGE.**

Support all locations for most of the information.

Yet, the experimental feature is only available in some selective locations/districts (Tuen Mun, Tin Shui Wai, Yuen Long, Sai Kung does not support the launch of nearest weather station so,), due to the complexity of other districts.

Very likely, I might add a CSV file to automate the selection. 
Currently, we allow users to key in their district and select the nearby weather station instead.

## The Report Covers
The Report covers a small amount of data provided by HKO, including:
- Lightning
- Humidity
- Temperature
- Hourly Rainfall
- Tropical Cyclone Position
- UV index
- Warning Message
- Special Weather Tips (Never seen them appeared but, ok)

## Edge cases handled
  - When the 1-3 nearest automatic weather stations are not working/ under maintenance.
    - I kindly believe that this is more than enough to solve the daily maintenance (or more than daily, etc., large-scaled electricity outage). It will still be able to show the 4th nearest automatic weather station (Somewhere around Yuen Long). A short notice will notify the user that the stations located in Tuen Mun are not available. 
  - HTTP request error, any sort of API request error
  - Full maintenance of HKO's system. Won't break the whole program at least
  - Minor Input Error in Grammar
## Knowledge used
  - API request (ofc)
  - JSON
  - CSV
  - Python dictionary Handling
  - Datetime handling
  - OOP


## Dependicies
  - Google Colab (My Primary working platform)
  - Python 3 or higher
  
## How to use
  1. Download ***Weather_Station_for_temp.csv***
  2. Click [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/WMFong0/Python-Weather-Report-System/blob/Third-Version-Early-Access/Python_Weather_App.ipynb)
  3. Click the folder icon from the left-hand sidebar
  4. Click the upload icon (located directly below the header "**Files**")
  5. Upload ***Weather_Station_for_temp.csv***
  6. Click **Run all** for first time.
  7. Run **the last module only** for the second time or after (You can still click run all, it just takes a split second longer)

# Example output
<img width="910" height="765" alt="image" src="https://github.com/user-attachments/assets/c2976fc9-ecb1-46bf-86e5-8cfdcb630273" />

