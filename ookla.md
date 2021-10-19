## Tileset Name

Speedtest by Ookla Global Fixed and Mobile Network Performance Map Tiles

## Tileset IDs

Each of the available quarters includes one tileset of fixed broadband and one tileset of mobile networks.

### Q3 2021
* [ookla-ofg.mobile_20210701_20211001](https://studio.mapbox.com/tilesets/ookla-ofg.mobile_20210701_20211001/)
* [ookla-ofg.fixed_20210701_20211001](https://studio.mapbox.com/tilesets/ookla-ofg.fixed_20210701_20211001/)

### Q2 2021
* [ookla-ofg.mobile_20210401_20210701](https://studio.mapbox.com/tilesets/ookla-ofg.mobile_20210401_20210701/)
* [ookla-ofg.fixed_20210401_20210701](https://studio.mapbox.com/tilesets/ookla-ofg.fixed_20210401_20210701/)

### Q1 2021
* [ookla-ofg.mobile_20210101_20210401](https://studio.mapbox.com/tilesets/ookla-ofg.mobile_20210101_20210401/)
* [ookla-ofg.fixed_20210101_20210401](https://studio.mapbox.com/tilesets/ookla-ofg.fixed_20210101_20210401/)

### Q1 2019
* [ookla-ofg.mobile_20190101_20190401](https://studio.mapbox.com/tilesets/ookla-ofg.mobile_20190101_20190401/)
* [ookla-ofg.fixed_20190101_20190401](https://studio.mapbox.com/tilesets/ookla-ofg.fixed_20190101_20190401/)

## About the data

This [dataset](https://registry.opendata.aws/speedtest-global-performance/) provides global fixed broadband and mobile (cellular) network performance metrics in web mercator tiles (up to zoom level 16 detail). Download speed, upload speed, and latency are collected via the Speedtest by Ookla applications for Android and iOS and averaged for each tile. Measurements are filtered to results containing GPS-quality location accuracy.

Data is licensed [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

More information: https://github.com/teamookla/ookla-open-data

## Organization Name

Ookla

## Organization Description

[Ookla®](https://www.ookla.com/) is the global leader in mobile and broadband network intelligence, testing applications and technology. [Speedtest®](https://www.speedtest.net/), the company's flagship product, is the most accurate way to measure internet performance and network diagnostics.

## What's included in the tileset (brief description)

| Field Name | Type | Description |
| --- | --- | --- |
| avg_d_kbps | Integer | The average download speed of all tests performed in the tile, represented in kilobits per second. |
| avg_u_kbps | Integer | The average upload speed of all tests performed in the tile, represented in kilobits per second. |
| avg_lat_ms | Integer | The average latency of all tests performed in the tile, represented in milliseconds |
| tests | Integer | The number of tests taken in the tile. |
| devices | Integer | The number of unique devices contributing tests in the tile. |
| quadkey | Text | The quadkey representing the tile.  |

## Recipe File

## Link to original data 

https://registry.opendata.aws/speedtest-global-performance/

## Images

## Tips for working with this data

Python: https://github.com/teamookla/ookla-open-data/blob/master/tutorials/aggregate_by_county_py.ipynb
R: https://github.com/teamookla/ookla-open-data/blob/master/tutorials/aggregate_by_county.md, https://www.speedtest.net/insights/blog/best-ookla-open-data-projects-2021/
