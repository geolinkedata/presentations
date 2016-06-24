## Orchestrator

- [Express](http://expressjs.com/) Node.js router for the data workflow management with asynchronous communications to the back-end servers:
    - **Load** geodata and metadata into GeoNode
    - **Transform** geodata to triples with the [TripleGeo](https://web.imis.athena-innovation.gr/redmine/projects/geoknow_public/wiki/TripleGeo) web services which actually does the conversion
    - Store triples into **Virtuoso**, a semantic database for RDF resources
- Optionally can create a basic viewer with a web mapping template for remote clients
