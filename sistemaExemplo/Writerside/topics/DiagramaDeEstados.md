# Diagrama de Estados

```plantuml
@startuml
[*] --> Disponível
Disponível --> Emprestado : Emprestar
Emprestado --> Disponível : Devolver
@enduml
