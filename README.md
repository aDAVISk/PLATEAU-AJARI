# PLATEAU-AJARI
This work is done at PLATEAU hackathon at Kyoto 2023.

https://protopedia.net/prototype/4950

### Included Data
- KyotoBunkazai.csv : from https://kunishitei.bunka.go.jp/bsys/searchlist
- kyotocity_buildings_edo.csv : from https://www.city.kyoto.lg.jp/bunshi/page/0000005493.html, mannually geocoded.

### ConnectBuildingCSV.ipynb
ConnectBuildingCSV.ipynb parses CityGML of Kyoto-city from PLATEAU and build a structured cache of building footprints. The footprints of buildings are used for collision test with given (lon, lat) of heritages saved at CSV files. The results are compiled into style.json for Cesium which allows to show buildings only specified as heritages.