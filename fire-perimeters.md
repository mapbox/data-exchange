
## Tileset Name

Historic US Wildfires

## Tileset ID(s)

[enf.fire-perimeters](https://studio.mapbox.com/tilesets/enf.fire-perimeters/#3.68/39.56/-98.27)

## About the data

Historic fire perimeters in the US from 2010-2019

## Organization Name

National Interagency Fire Center _processed by Mapbox_

## Organization Description

The [National Interagency Fire Center](https://www.nifc.gov/) (NIFC) has initiated this project to better share maps and data related to wildland fire activities across the country with all agencies and persons interested in such data.

## What's included in the tileset (brief description)


| Property | Description | Type |
| --- | --- | ----
| fireyear | year of fire | number |
| gisacres | acres within perimeter | number |

![](https://github.com/mapbox/data-exchange/blob/main/res/img/wildfire-tilesets.png?raw=true)

## Recipe File

<pre>
{
    "version": 1,
    "layers": {
        "perimeters_2019": {
            "minzoom": 0,
            "maxzoom": 11,
            "source": "mapbox://tileset-source/enf/2019_perimeters",
            "features": {
                "attributes": {
                    "set": {
                        "irwinid": null,
                        "st_area_sh": null,
                        "st_length_": null,
                        "shape_Leng": null,
                        "shape_Area": null
                    }
                }
            },
            "tiles": {
                "id": null
            }
        }
}
</pre>

_add additional layers for each year, replaceing the tileset name and tileset source with associated year from 2010-2019_

## Link to original data 

https://data-nifc.opendata.arcgis.com/search

## Images

![](https://github.com/mapbox/data-exchange/blob/main/res/img/wildfire-latimtes.png?raw=true)
