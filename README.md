# ML_Project_FCRD
Database used to predict the FCRD prices in Sweden by means of unsupervised learning, consisting of:
- FCRD (2011-04-01 00:00 - 2022-10-16 23:00, nonzero values starting at 2011-11-01 00:00), obtained from: Mimer (https://mimer.svk.se/PrimaryRegulation/PrimaryRegulationIndex)
- Day-ahead Prices by years (01.01.2015 00:00 - 18.10.2022 23:00), obtained from ENTSOe: https://transparency.entsoe.eu/transmission-domain/r2/dayAheadPrices/show?name=&defaultValue=false&viewType=GRAPH&areaType=BZN&atch=false&dateTime.dateTime=13.10.2022+00:00|CET|DAY&biddingZone.values=CTY|10YSE-1--------K!BZN|10Y1001A1001A47J&resolution.values=PT15M&resolution.values=PT30M&resolution.values=PT60M&dateTime.timezone=CET_CEST&dateTime.timezone_input=CET+(UTC+1)+/+CEST+(UTC+2)  
- Demand (): Total Load Day Ahead Prediction (), obtained from ENTSOe: https://transparency.entsoe.eu/generation/r2/dayAheadAggregatedGeneration/show
- Temperature values in Stockholm (), obtained from NASA's Data Access Viewer: https://power.larc.nasa.gov/data-access-viewer/
