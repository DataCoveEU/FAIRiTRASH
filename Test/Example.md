# FAIRiTRASH
Sandbox for internal FAIRiCUBE work

```mermaid
classDiagram
   class earthAtmosphere{
    }
    note for earthAtmosphere "sosa:FeatureOfInterest"
    class earthAtmosphere_StE{
    }
    note for earthAtmosphere_StE "sosa:Sample"
    class atmosphericPressure{
    }
    note for atmosphericPressure "sosa:ObservableProperty"
    class iphone7-35-207306-844818-0{
    }
    note for iphone7-35-207306-844818-0 "sosa:Platform"
    class sensor-35-207306-844818-0-BMP282{
    }
    note for sensor-35-207306-844818-0-BMP282 "sosa:Sensor"
    class Observation-346344{
      hasSimpleResult "1021.45 hPa"^^cdt:ucum
    }
    note for Observation-346344 "sosa:Observation"
    Observation-346344 --> atmosphericPressure: observedProperty
    Observation-346344 --> earthAtmosphere_StE: hasFeatureOfInterest
    Observation-346344 --> sensor-35-207306-844818-0-BMP282: madeBySensor



```
