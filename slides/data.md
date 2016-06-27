## data

![data](css/img/data.png)

```bash
$ curl -XPOST -d 'shp=@data/parks.shp' -d 'shx=@data/parks.shx' \
-d 'dbf=@data/parks.dbf' -d 'prj=@data/parks.prj' \
-F 'class_store=parks&target_store=virtuoso&...' \
http://localhost:8000/shape2triple
```
