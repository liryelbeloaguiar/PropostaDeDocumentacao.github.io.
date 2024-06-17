# Diagrama De Implantação

```plantuml
@startuml
node "Servidor Web" {
  component "Sistema de Biblioteca"
}
node "Servidor de BD" {
  component "Banco de Dados"
}
@enduml
