# Admin boundaries

This is a collection of administrative boundaries compiled from various sources including: [GADM](https://gadm.org), [GeoBoundaries](https://www.geoboundaries.org/), and [UN sources](https://data.humdata.org/).<sup>1</sup> Our purpose is to make this data readily available to use in web applications.

 Administrative boundaries are organized by: 
 * Country (ISO 3166 Alpha 3)
 * Levels of granularity (i.e ADM 0-4)
 * Data formats (.geojson, .shp, .csv)

> <sup>1</sup> The main source of data is from Runfola, D., Seitz, L., Hobbs, L., Panginaban, J., Oberman, R. et al. geoBoundaries Global Administrative Database. http://www.geoboundaries.org.

# How the data is organized

The collection uses the following folder structure:

- [3-LETTER-ISO-CODE]
    - [ADM-LEVEL]
        - [FILE-FORMAT]

In order for Hikaya applications to locate the file and render it within its applications, the following file format must be used:
```
[3-LETTER-ISO-CODE]-[ADM-LEVEL].geojson

Example: AFG-ADM0.geojson
```

## Example:

- [AFG]
    - [ADM0]
        - `.geojson`
        - `.shp`
        - `.csv`
        - `.txt`
    - [ADM1]
    - [ADM2]
    - [ADM3]

## Roadmap

In the future, we plan to add the following:
* Add support for UN P-Code (placecode)
* Integration with original source to refresh with any updates
* Provide a map preview when exploring administrative boundaries