# Some Stuff about the Service Layer

Description here. Diagram below:

## Diagram

```plantuml
@startuml

class Car

Driver - Car : drives >
Car *- Wheel : have 4 >
Car -- Person [[$./helper/demo-service-helper.md]] : < owns

@enduml
```
