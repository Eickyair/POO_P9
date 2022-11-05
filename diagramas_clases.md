@startuml
!define DARKBLUE
!includeurl https://raw.githubusercontent.com/Drakemor/RedDress-PlantUML/master/style.puml

class Animal{
    -nombre:String
    -lugarOrigen:String
    -color:String
    --
    +sonar(sonido:String):void
    +comer():void
}

class AnimalAcuatico{
    -numeroAletas: int
    --
    +nadar():void
    +comer():void
}
class AnimalTerrestre{
    -numeroPatas:int
    --
    +correr():void
    +comer():void
}
class AnimalAereo{
    -numeroAletas:int
    --
    +volar():void
    +comer():void
}
class Ballena{
    -largo:int
    --
    +pelearConPinocho():void
}
class Perro{
    -colorCollar:String
    --
    +hacerTrucos():void
}
class Pajaro{
    -tipoPico:String
    --
    +recolectarRamas():void
}
@enduml