```
mermaid
flowchart TD
    Start([Usuario accede]) --> Auth{¿Autenticado?}
    Auth -->|No| Public[Área pública]
    Auth -->|Sí| Dashboard[Panel administrativo]
```
