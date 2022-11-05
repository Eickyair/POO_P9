@startuml
!define DARKBLUE
!includeurl https://raw.githubusercontent.com/Drakemor/RedDress-PlantUML/master/style.puml

Animal <|-- AnimalAcuatico
Animal <|-- AnimalTerrestre
Animal <|-- AnimalAereo
AnimalAcuatico <|-- Ballena
AnimalTerrestre <|-- Perro
AnimalAereo <|-- Pajaro
@enduml