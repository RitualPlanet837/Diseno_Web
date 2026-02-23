mermaid
flowchart TD
    Start([User accesses application]) --> Auth{Authenticated?}
    Auth -->|No| Public[Public area]
    Auth -->|Yes| Dashboard[Administrative Dashboard]
