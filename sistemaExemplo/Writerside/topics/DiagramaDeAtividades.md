# Diagrama de Atividades

```plantuml
@startuml
|Usuario|
start
:Solicitar Emprestimo;
|Bibliotecario|
:Verificar Disponibilidade;
if (Disponível) then (yes)
:Atualizar Registro;
else (no)
:Informar Indisponibilidade;
endif
stop
@enduml
