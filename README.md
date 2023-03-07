# webapi-component-geospatial

## Geospatial support

Geospatial is an optional component that provides to build analyses utilizing locations and areas.
To build WebAPI with geospatial include the following profile `webapi-gis`.
For example in the following way:

```
mvn -Pwebapi-postgresql,webapi-gis clean package
```

[ExecutionEngine](https://github.com/OHDSI/ArachneExecutionEngine) installed and running is required to use this component.
 
**Note:** follow the instructions in the [Atlas Geospatial project](https://github.com/OHDSI/atlas-component-geospatial) to include Geospatial UI part.
