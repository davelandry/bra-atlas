Brazil Atlas TopoJSON
=========

ogr2ogr -f GeoJSON munic.json 31MUE250GC_SIR.shp 

topojson -s 3e-9 --id-property CD_GEOCODM -p NM_MUNICIP=name -p name -o topojson.json munic.json

retained 66187 / 688948 points (10%)

PATH=$PATH:/usr/local/share/npm/bin

export PATH
