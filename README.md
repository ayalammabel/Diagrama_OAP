```mermaid
flowchart TD
    A[SIMISIONAL] --> B[Analista]
    A --> C[DBA]
    A --> D[Frontend]
    A --> E[Backend]

    %% Al hacer clic se abre la ficha del rol (en /docs/)
    click B "docs/analista.md" "Ver responsable"
    click C "docs/dba.md" "Ver responsable"
    click D "docs/frontend.md" "Ver responsable"
    click E "docs/backend.md" "Ver responsable"

    %% (Opcional) Estilos suaves
    style A fill:#f5f5f5,stroke:#444,rx:6,ry:6
    style B fill:#ffffff,stroke:#777,rx:6,ry:6
    style C fill:#ffffff,stroke:#777,rx:6,ry:6
    style D fill:#ffffff,stroke:#777,rx:6,ry:6
    style E fill:#ffffff,stroke:#777,rx:6,ry:6
