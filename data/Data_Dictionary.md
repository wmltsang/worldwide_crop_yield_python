This month's dataset contains crop yields (in tonnes per hectare) by country or region for 11 key crops for the years 1961 through 2018. This dataset comes from [Our World In Data](https://ourworldindata.org/crop-yields).

Also included is geo-countries.geojson which can be joined to to key_crop_yields.csv using the ISO_A3 and Code columns, respectively.

The file key_crop_yields.csv contains the following variables:

|variable                         |class     |description |
|:--------------------------------|:---------|:-----------|
|Entity                           |character | Country or Region Name |
|Code                             |character | Country Code (note is NA for regions/continents) |
|Year                             |double    | Year |
|Wheat (tonnes per hectare)       |double    | Wheat yield |
|Rice (tonnes per hectare)        |double    | Rice Yield |
|Maize (tonnes per hectare)       |double    | Maize yield |
|Soybeans (tonnes per hectare)    |double    | Soybeans yield |
|Potatoes (tonnes per hectare)    |double    | Potato yield |
|Beans (tonnes per hectare)       |double    | Beans yield|
|Peas (tonnes per hectare)        |double    | Peas yield |
|Cassava (tonnes per hectare)     |double    | Cassava (yuca) yield|
|Barley (tonnes per hectare)      |double    | Barley|
|Cocoa beans (tonnes per hectare) |double    | Cocoa |
|Bananas (tonnes per hectare)     |double    | Bananas |