# Diagrama de Classes

```plantuml
@startuml
class Livro {
- titulo: String
- autor: String
- ISBN: String
+ emprestar(): void
+ devolver(): void
  }

class Usuario {
- nome: String
- ID: int
- telefone: String
+ registrar(): void
+ remover(): void
  }

class Bibliotecario {
- nome: String
- ID: int
+ gerenciarLivros(): void
+ gerenciarUsuarios(): void
  }
  @enduml
