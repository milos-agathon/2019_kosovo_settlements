# 2019_kosovo_settlements

This repo includes a replica of Kosovo's official settlement boundaries from the [Kosovo Cadastral Agency - KGP](http://geoportal.rks-gov.net/en/search) in shapefile format. I took several steps to reproduce this shapefile:

1. I printed high-resolution images for every part of Kosovo interactive map from the KGP site in 1:30,000 scale with coordinate lines in WSG84 format
2. Then I manually merged these images in paint.net to create a single image the size of several GBs
3. Finally, I georeferenced the image in QGIS.

# Codebook

| feature | description                                                                    |
|---------|--------------------------------------------------------------------------------|
| opstina | municipality                                                                   |
| naselje | settlement                                                                     |
| ID_1    | official settlement identifier                                                 |
| lat     | geographic latitude of the settlement in EPSG:4326 geodetic coordinate system  |
| long    | geographic longitude of the settlement in EPSG:4326 geodetic coordinate system |
|         |                                                                                |
