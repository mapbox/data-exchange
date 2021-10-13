Probable Futures tilesets
=========================

This document includes three tilesets

1.  Freezing days
2.  10 hottest wet-bulb days
3.  Days above 32°C (90°F)

## Organization Name

[Probable Futures](https://probablefutures.org/)

## Organization Description

Probable Futures is an initiative that aims to increase the chances that our future is good. We offer useful tools to visualize climate change along with stories and insights to help people understand what those changes mean. We also partner with courageous leaders and influential organizations — without cost or compensation — to show how this perspective and these tools can be applied towards practical approaches to the problems posed by climate change. 

## Tips for working with this data 

-   Background. To understand more about how these data are created, how they can be applied, and their uses and limitations, we highly recommend reading the [science section on the Probable Futures website](https://probablefutures.org/science/?tab=climate-models). 

-   Tileset performance. These tilesets are very large. For applications that do not require viewing the whole world, you may find the tilesets load faster if they are loaded (at least initially) at a more zoomed-in zoom level. 

-   Colors and binning. Selecting colors and bins is challenging. In the [Probable Futures application that uses these tilesets](https://probablefutures.org/heat/maps-of-heat/), we put considerable time and thought into the colors and bins we use. 

-   The colors we selected are intended to discourage snap judgments about "good" and "bad" outcomes in particular places. For example, when we used a color palette with reds and oranges, people who saw the map immediately thought of the darker red areas as having a particularly bad climate outcome. Absolute temperatures, unless they are very high, are not inherently "bad". But change can negatively impact infrastructure, industry, and community culture in different ways. We tried to use colors that encourage viewers of the maps to look closely, notice change, and imagine for themselves what the potential consequences of those changes might be.

-   The colors we selected are distinguishable for many types of vision impairment such as common forms of color blindness. [ColorBrewer](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) is a helpful tool for selecting accessible color palettes.

-   "Binning", or the "stops" when one color stops and another begins, also make a big difference for how people perceive information within maps. We selected bins that are generally intuitive -- such as divisions at known intervals like roughly weeks and months, and stops at significant thresholds like freezing and temperatures above which it becomes uncomfortable or challenging for the human body to cool itself through perspiration.

### What's included in the tilesets

These are definitions of terms within used within property names

Term in Property | Description  |
--- | --- |
baseline | This data point shows the baseline value for the location. Probable Futures uses the CORDEX-CORE regional climate modeling framework. 1971-2000 is the earliest time period for which results are available from this system of models. The average surface temperature during these years was approximately 0.5°C above that of 1850-1900.  |
1c | This data point shows the value for the location at 1°C of global heating. In 2017 the average surface temperature passed 1.0°C above the 1850-1900 average. Humans have only experienced higher temperatures during a brief period 120,000 years ago. Major biotic changes, including release of greenhouse gases from thawing permafrost, forest fires, and collapse of Arctic sea ice, have begun contributing to further warming.|
1_5c | This data point shows the value for the location at 1.5°C of global heating. Reaching 1.5°C is likely by 2030, and the probability of stopping warming below 1.5°C is approaching zero. Standards and expectations based on the past are rapidly becoming outdated. Heat, drought, deluge, and other stresses will increase, and large-scale biotic feedbacks are likely to intensify. |
2c | This data point shows the value for the location at 2°C of global heating. The probability of staying below 2.0°C of warming is falling quickly. On the current path of emissions, 2.0°C will likely be passed in the 2040s. However, rapid, dramatic action to get to zero emissions can substantially lengthen the time before reaching 2.0°C, giving society and nature more time to adapt, prepare, and innovate. |
2_5c | This data point shows the value for the location at 2.5°C of global heating. Rapid, dramatic action to get to zero emissions can substantially reduce the probability of reaching 2.5°C. On the current path, 2.5°C will likely be passed in the 2050s. The earth was last this warm nearly 3 million years ago, when there were no land-based ice sheets other than on Antarctica and Greenland. Stabilizing temperatures at 2.5°C would likely require humans to perpetually offset biotic sources of warming. |
3c | This data point shows the value for the location at 3°C of global heating. If we act rapidly to get to zero emissions and find ways to increase carbon stores, we can make reaching 3.0°C a low probability. On the current path of emissions, 3.0°C will likely be passed in the 2060s. At 3.0°C, most regions of the Earth would have entered a different climate, causing severe biological disruptions. The climate is extremely unlikely to be stable at this temperature. |

**Property listing**

Property name | Type |
---|---|
data_baseline_mean | integer |
data_baseline_pctl10 |integer|
data_baseline_pctl90 | integer |
data_1c_mean | integer |
data_1c_pctl10 | integer |
data_1c_pctl90 | integer |
data_1_5c_mean | integer |
data_1_5c_pctl10 | integer |
data_1_5c_pctl90 | integer |
data_2c_mean | integer |
data_2c_pctl10 | integer |
data_2c_pctl90 | integer |
data_2_5c_mean | integer |
data_2_5c_pctl10 | integer |
data_2_5c_pctl90 | integer |
data_3c_mean | integer |
data_3c_pctl10 |integer|
data_3c_pctl90 | integer |

**Layers**

|Layers in east tilesets | Layers in west tilesets |
| --- | --- |
region_as_oc_1 | region_na_sa_1 |
region_as_oc_2 | region_na_sa_2 |
region_as_oc_3 | region_na_sa_3 |
region_as_oc_4 | region_na_sa_4 |
region_as_oc_5 | region_na_sa_5 |
region_as_oc_6 | region_na_sa_6 |
region_as_oc_7 | region_na_sa_7 |
region_as_oc_8 | |
region_eu_af_1 | |
region_eu_af_2 | |
region_eu_af_3 | |
region_eu_af_4 | |
region_eu_af_5 | |
region_eu_af_6 | |
region_eu_af_7 | |
region_eu_af_8 | |
region_eu_af_9 | |

## Tilesets

### Freezing days

#### Tileset IDs

-   [probablefutures.40205-east-draft](https://studio.mapbox.com/tilesets/probablefutures.40205-east-draft/)

-   [probablefutures.40205-west-draft](https://studio.mapbox.com/tilesets/probablefutures.40205-west-draft/)

#### About the data

[Example of the tileset displayed on the public Probable Futures platform](https://probablefutures.org/heat/maps-of-heat/?selected_map=cksstcyx00eru17mjadv04qjk#2.2/0/0).

"Freezing days" measures the number of days per year that remain below freezing all day, or have a maximum temperature below freezing (0°C or 32°F).  "Freezing days" are a proxy of the length and consistency of the cold season, particularly at mid and high latitudes. As mean global temperatures rise, local climates will experience fewer freezing days.  For each warming scenario, the number of days below 0°C are identified from daily maximum temperature projected by climate models. The displayed values are from a range of simulated years from multiple models. Actual outcomes may prove to be higher or lower than the displayed values.

#### Tileset specific term descriptions

Term in Property | Description  |
--- | --- |
mean | This is the average number of days per year that reach freezing at this location in the warming scenario specified in the property name. |
pctl10 | This is the 10th percentile of the number of days per year that reach freezing for this location. There is approximately a one in ten chance that this location will experience this number of freezing days per year or fewer.  |
pctl90 | This is the 90th percentile of the number of days per year that reach freezing for this location. There is approximately a one in ten chance that this location will experience this number of freezing days per year or more |

#### Recipe Files

-   [probablefutures.40205-east-draft](https://gist.github.com/petercroce/b2febc80e869ab61f19ef7f9ce387a20)

-   [probablefutures.40205-west-draft](https://gist.github.com/petercroce/5d83079ad08659298a395fdeb7a42ac0)


#### Images

![](https://lh4.googleusercontent.com/6qaH4spdCak5pl4ZZpp6H9lCKlmyDBm4Tr7AXIewyz3Dg_rfdu2nrSPScjtAmA_9C0v4oXE5X4s-QyRwZH868UoZZuNO_geODmLJAVkyvP9Qc86-n6lGT1Ixb7BVVRH0DTxg5dzJ=s0)

![](https://lh5.googleusercontent.com/3J1JXSE7kd_YAUJU_IQRLjfZESFqSDFG3n3njIY2j559SNUdzaD_qQR_RN2X6Kos56aVnEQn85wMvazJ9bkaQZ8ChoMthhfEZwffJyX6y3nHrN6gTcV5WTsc5iluhIHgbLGFpYhP=s0)

### 10 hottest wet-bulb days

#### Tileset IDs 

-   [probablefutures.40305-east-draft](https://studio.mapbox.com/tilesets/probablefutures.40305-east-draft)
-   [probablefutures.40305-west-draft](https://studio.mapbox.com/tilesets/probablefutures.40305-west-draft)

### About the data

[Example of the tileset displayed on the public Probable Futures platform](https://probablefutures.org/heat/maps-of-heat/?selected_map=ckssu64dk3fbv17pi8ha51h47#2.2/0/0).

Wet-bulb temperature is calculated using temperature and humidity. High wet-bulb temperatures can impair the human body's ability to self-cool through sweating. For each warming scenario, the mean temperature of the 10 hottest wet-bulb days per year is identified from daily maximum wet-bulb temperatures computed using daily maximum temperature and daily minimum relative humidity, variables that are projected by climate models. The displayed values are from a range of simulated years from multiple models. Actual outcomes may prove to be higher or lower than the displayed values.

#### Tileset specific term descriptions

Term in Property | Description  |
--- | --- |
mean | This is the average temperature (in Celsius) of the 10 hottest wet-bulb days per year at this location in the warming scenario specified in the property name.  |
pctl10 | This is the 10th percentile of the temperature (in Celsius) of the 10 hottest wet-bulb days per year   for this location. There is approximately a one in ten chance that this location will experience this temperature or a lower one for the 10 hottest wet-bulb days per year.  |
pctl90 | This is the 90th percentile of the temperature (in Celsius) of the 10 hottest wet-bulb days per year at this location. There is approximately a one in ten chance that this location will experience this temperature or a higher one for the 10 hottest wet-bulb days per year.  |

#### Recipe Files

-   [probablefutures.40305-east-draft](https://gist.github.com/petercroce/1cfddabeecbaac9dd9710950cdf3c2b0)
-   [probablefutures.40305-west-draft](https://gist.github.com/petercroce/833dbf777d8d0bd4a97a16b6c63909c0)

#### Images

![](https://lh5.googleusercontent.com/1at6Yw1etd3eXz9T5EL5xn29KtpVFYgh_gxfbMcfcA5CADJJBB1UcW8fjYKTzwcvmOFQrWAUdVbyXWEOdhXgAmMKyUkJI9GpecxJtPyIz0lSNBvOGVW88NeR3a1NtwlliomPXC6d=s0)

![](https://lh5.googleusercontent.com/93i4lVzSJCmWyE7prLYlsC9YJCYW4OIs66O-Azk7dNkCNV2mneBbg7_ZqzOVibkAa46XKoes2vw34eY_aHv5x-CIyBPzbnXdWelsdYTRPvvbBbNpj0AugTapVRwLZEfcTDGLDQtB=s0)


### Days above 32°C (90°F)

#### Tileset IDs

-   [probablefutures.40104-east-draft](https://studio.mapbox.com/tilesets/probablefutures.40104-east-draft/)
-   [probablefutures.40104-west-draft](https://studio.mapbox.com/tilesets/probablefutures.40104-east-draft/)

#### About the data
[Example of the tileset displayed on the public Probable Futures platform](https://probablefutures.org/heat/maps-of-heat/?selected_map=cksssg07h3itq17nkf2zav4sw#2.2/0/0).

As mean global temperatures rise, local climates will experience extreme temperatures more frequently. For each warming scenario, the number of days exceeding 32°C are identified from daily maximum temperature projected by climate models. The displayed values are from a range of simulated years from multiple models. Actual outcomes may prove to be higher or lower than the displayed values.

#### Tileset specific term descriptions

| Term in Property | Description  |
| --- | --- |
| mean | This is the average number of days per year that reach 32°C at this location in the warming scenario specified in the property name. |
| pctl10 | This is the 10th percentile of the number of days per year that reach 32°C for this location. There is approximately a one in ten chance that this location will experience this number of freezing days per year or fewer.  |
| pctl90 | This is the 90th percentile of the number of days per year that reach 32°C for this location. There is approximately a one in ten chance that this location will experience this number of freezing days per year or more |

#### Recipe Files

-   [probablefutures.40104-east-draft](https://gist.github.com/petercroce/cd35947412c943686b5ef1b1dbba27a9)
-   [probablefutures.40104-west-draft](https://gist.github.com/petercroce/a6952e15c831b880da9ef39aa223411e)

#### Images

![](https://lh4.googleusercontent.com/1ib4wLzg9b2TrpIDB1hnAOnr24ckNdR_DMx-cyGZzETEuyl-ZLgod6cvvgBNDW6fbluctUpgZjJCeANy0Vx0NJXI-zzgF2-YYV5jkzlckxD_DdvU32hDkopyj3FeVHqzjcyWPNmy=s0)

![](https://lh3.googleusercontent.com/myrSM81EaN2L6PzEQByasJyiLnrNKwMotkzv1B5KingXCHeCH3kME7-YCIhqDJ1ZhtEVzQch7p2crt04KZl1gIk63A-QO-ZQ6eqLZYxSpKAPHqQHp-kcQMr8rfv7MUucZCXvoC11=s0)
