## GeoLinkeData

- It's a [Django Application](https://www.djangoproject.com/) based on a custom [GeoNode project](https://github.com/GeoNode/geonode-project) which allows to publish interlinked geodata (currently limited to *Shapefiles*) as **triple stores** and load them into a **SPARQL** [Virtuoso](https://github.com/openlink/virtuoso-opensource) back-end
- Publish REST APIs with the power of [Django Rest Framework](http://www.django-rest-framework.org/)
- It's a Web Browsable APIs with a lean and clean approach to try your integration for converting shapefiles
- Support several different security protocols to protect the APIs (*OAuth2*, *JSON Web Token*, etc) and it is integrated Out-of-The-Box with the GeoNode authentication system
- Triple store formats supported are: **XML/RDF** - **N3** - **N-TRIPLES** - **TURTLE**
