# webapi-component-geospatial

## Geospatial support

Geospatial is an optional component that provides to build analyses utilizing locations and areas.
To build WebAPI with geospatial include the following profile `webapi-gis`.
For example in the following way:

```
mvn -Pwebapi-postgresql,webapi-gis clean package
```
**Note:** follow the instructions in the [Atlas project](https://github.com/OHDSI/Atlas) to include Geospatial UI part.
