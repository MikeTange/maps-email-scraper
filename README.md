# maps-email-scraper
Scraping emails from websites found through Google Maps' Places API. The script returns an Excel file containing the names of the places, the places' websites as listen by Google, and the email(s) scraped from the website.

As input the script requires a .txt file titled "Search task details.txt". This file should contain three lines in the following order, with the following keywords:
1. Central point: city, country || address, city, country
2. Radius: radius_in_meters
3. Keywords: keyword_1, keyword_2, keyword_3, ...

Additionally, a .txt file titled "APIkey.txt" is required. This file should contain nothing but the Google Cloud Developer API key. 
