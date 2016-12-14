# chicago-lead

## requirements

* postgres ([instructions](http://exponential.io/blog/2015/02/21/install-postgresql-on-mac-os-x-via-brew/))
* ogr2ogr (`brew install gdal`) 
* csvkit (`pip install csvkit`)
* pandas (`pip install pandas`)

## to reproduce

clone this repo and from a terminal window, run:

`make setupdb`
`make all`

the files should land in `output/`.