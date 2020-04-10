# Admin boundaries

This is a collection of administrative boundaries compiled from various sources including: [GADM](https://gadm.org), [GeoBoundaries](https://www.geoboundaries.org/), and [UN sources](https://data.humdata.org/).

We collection houses administrative boundaries at different levels (i.e admin 0-4) and formats (.geojson, .shp, .csv) for easy use in web applications.

# How to navigate

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
- Add support for UN P-Code (placecode)
- Integration with original source to refresh with any updates
- Provide a map preview when exploring administrative boundaries