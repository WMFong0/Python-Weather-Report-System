# Python-Weather-Report-System

Currently only supports Tuen Mun(Yes, my hometown) and its surrounding areas' last hour rainfall data.
Very likely, I might add a CSV file to allow user to key in their current location, and show them the weather at their own location.

It took me a hell of a time to understand what data.gov.hk is trying to show.

## Edge cases handled
  - When the 1-3 nearest automatic weather stations are not working/ under maintenance.
    - I kindly believe that this is more than enough to solve the daily maintenance (or more than daily, etc., large-scale area electricity outage). It will still be able to show the 4th nearest automatic weather station (Somewhere around Yuen Long). A short notice will notify the user that the 2 nearest stations are not available. 
  - HTTP request error, any sort of API request error
  - Full maintenance of HKO's system. Won't break the whole program.

## Knowledge used
  - API request (ofc)
  - JSON and Python dictionary handling
  - datetime handling
  - Maybe, in the near future. I will make a class for each category of the data.

## Dependicies
  - Google Colab (My Primary working platform)
  - Python 3
  
