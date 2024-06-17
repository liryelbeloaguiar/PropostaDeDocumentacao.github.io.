# Diagrama de Casos de Uso

```plantuml
@startuml
actor Bibliotecario
actor Usuario

Bibliotecario --> (Gerenciar Livros)
Bibliotecario --> (Emprestar Livros)
Bibliotecario --> (Registrar Usuario)
Usuario --> (Solicitar Emprestimo)
Usuario --> (Devolver Livro)
@enduml

