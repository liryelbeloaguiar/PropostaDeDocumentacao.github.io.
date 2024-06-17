# Diagrama de Sequencia 

```plantuml
@startuml
actor Usuario
actor Bibliotecario
participant Sistema

Usuario -> Bibliotecario: Solicitar Emprestimo
Bibliotecario -> Sistema: Verificar Livro Disponível
Sistema --> Bibliotecario: Livro Disponível
Bibliotecario --> Usuario: Emprestimo Confirmado
@enduml
