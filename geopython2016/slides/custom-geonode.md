## Custom GeoNode application

- Create a new project based on the current **stable** branch version of GeoNode and install the API as a dependency:

```bash
(geolinkedata)$ django-admin.py startproject geonode-lod --template=https://github.com/GeoNode/geonode-project/archive/2.4.zip -epy,rst
```
```bash
(geolinkedata)$ mkdir cache && cd cache && git clone https://github.com/geolinkedata/geolod-api
(geolinkedata)$ pip install -e geolod-api
```

- Append required apps to ``INSTALLED_APPS`` var in your **settings.py**:

```python
    INSTALLED_APPS = (
        ...
        ...
        ...
        'rest_framework',
        'rest_framework_swagger',
        'provider',
        'oauth2_provider',
        'api',
    )
```
