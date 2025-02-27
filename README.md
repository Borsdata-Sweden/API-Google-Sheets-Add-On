# Google Sheets Add-On

Börsdata Google Sheets Add-on is a plugin you install to your Google Sheets account.  
When the Add-on is installed you get access to several new functions to directly call the Börsdata API.  

You have access to all data from Börsdata API like Stockprices, reportdata and Kpis.  
To use the Google Sheets Add-on you need to be a PRO Börsdata member and having an API Key.  

Börsdata Google Sheets Add-on  are an extension to Börsdata API.  
In the background the Add-on is calling the API to get data and formats the data to fit into Google Sheets.  

It has the same limitations, like number of requests, as the normal API, so if you have many functions it can take some time to load all data.  
We are happy for all feedback on how to improve the API and the Google Sheets Addon.  

[Also read the Wiki for more details](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki)


## V12 Global data
- Added Global instruments. Stockprices, reports and Kpis.   

## Installation
[Read more](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki/Get-Started)


## Sharing Sheet is not allowed
Because the APIKEY is personal and you agreed not to share the API data with others - we check that the Sheet is not Shared.  
[Read more](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki/Sharing-Sheet-with-other-users)


## API Key
If you dont have an API KEY you need to Apply for it on Börsdata MyPage.  
[Go to Api Info](https://borsdata.se/en/info/api/api_page)


## Functions
[Go to Function page](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki)

## Settings menu
[Go to button page](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki/settings)

## Instruments (InstId)
An Instrument at Börsdata is normaly a company or index.   
Anything that has a price or report data is an Instrument.  
All Instrument has a uniqe ID called Instrument ID (InstID).  
To get the Instrument ID (InstID) you need to call the BD_INSTRUMENTS() function and check the returning table.

## Stockprice data
All stockprice data is EndDay.  
We do not offer intraday data in API or Google Sheets Addon.  

## Info about Report data
https://github.com/Borsdata-Sweden/API/wiki/Reports

## Info about Kpi data
https://github.com/Borsdata-Sweden/API/wiki/KPI  
https://github.com/Borsdata-Sweden/API/wiki/KPI-Screener  

## Language support
You can select if you like English or Swedish translation.  
You find checkbox in [Settings panel](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki/Settings).

# Known issues
[Go to page](https://github.com/Borsdata-Sweden/API-Google-Sheets-Add-On/wiki/Known-Issues)

## Issues Tracking
We use GitHub's Issues tracker for our project. Feel free to create bug reports and features requests.   
Make sure to read the documentation before asking questions - this will avoid repeated questions, leaving us more time for developing the library.

## Version

### 2021-01-10 V1  
- Release

### 2022-09-13 V12  
- Add Global Data

### 2023-09-06
- Instrument description 
- Report calendar 
- Dividend calendar 
- Holdings Insider 
- Holdings Shorts 
- Holdings Buyback

### 2024-02-14 (v10)
- Added two new values to BD_Instruments()
1. StockPriceCurrency
2. ReportCurrency

3. Added Original flag to report calls.
  This return reportdata in original currency.   
- BD_REPORT_YEAR
- BD_REPORT_R12
- BD_REPORT_QUARTER
- BD_KPI_SUMMARY

## Disclaimer
Börsdata and the information contained herein is not intended to be a source of advice or credit analysis with respect to the material presented, and the information and/or documents contained in this website do not constitute investment advice.  
The user is responsible for the risk and should therefore acquire information about the terms that apply to trade with such instruments, and about the qualities of the instruments. Placements or other positions in financial instruments such as stock is done at your own risk.  
Börsdata cannot in any way be held responsible for any investment decisions that result from the financial information on the website.
Always do your own Research.  



