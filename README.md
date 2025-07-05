# Python-Weather-Report-System

Currently only support Tuen Mun(Yes, my home town) and its surrounding area's last hour rainfall data.
Very likely, I might add a csv to allow user to key in their current location, and show them weather at their own location.

It took me a heck of a time to understand what data.gov.hk is trying to show.

## Edge cases handled
  - When 1-3 nearest automatic weather station is not working/ under maintance.
    - I kindly believe that this is more than enough to solve maintanence issue. It will still be able to show the 4th nearest automatic weather station. A short notice will notify user that those 2 nearest station is not available. 
  - http request error, any sort of API request error

## Knowledge used
  - API request (ofc)
  - JSON and python dictionary handling
  - datetime handling
  - Maybe, in the near future. I will make a class for each cat of the data.

## Dependicies
  - Google Colab (My Primary working platform)
  - Python 3
  
