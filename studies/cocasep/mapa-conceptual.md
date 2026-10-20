# Mapa conceptual — Calidad y seguridad del paciente

El diagrama organiza las relaciones explícitas e implícitas del material. Las etiquetas de los enlaces explican el vínculo entre conceptos.

```mermaid
flowchart TD
    C["COCASEP / CICASEP"] -->|"es"| O["Comité multidisciplinario"]
    O -->|"se integra por"| I["Presidencia · Secretaría técnica · Vocalías"]
    C -->|"persigue"| S["Seguridad del paciente"]
    C -->|"promueve"| Q["Calidad asistencial"]
    C -->|"opera mediante"| P["Mejora continua PHVA"]
    C -->|"estandariza con"| G["GPC · Protocolos · NOM"]
    C -->|"promueve"| N["Cultura no punitiva"]
    N -->|"facilita"| R["Reporte de incidentes"]
    R -->|"puede usar"| SIRE["SIRE: registro de eventos"]
    R -->|"clasifica"| T["Tipos de incidentes"]
    T --> F["Cuasifalla"]
    T --> A["Evento adverso"]
    T --> E["Evento centinela"]
    R -->|"se investiga con"| ACR["Análisis de causa raíz"]
    ACR -->|"orienta"| PM["Plan de mejora PMCCS"]
    PM -->|"se sigue mediante"| P
    G -->|"sustenta"| B["Barreras de seguridad"]
    B --> D["Doble verificación independiente"]
    D --> M["Medicamentos de alto riesgo"]
    B --> U["Bundles en áreas críticas"]
    U --> NAV["Prevención NAV"]
    U --> BAC["Prevención BACVC"]
    U --> IVU["Prevención IVU-SAD"]
    P -->|"reduce"| V["Variabilidad y riesgos"]
    B -->|"reduce"| V
    V -->|"favorece"| S
    S -->|"contribuye a"| Q
```

## Lectura del mapa
El comité articula la prevención (guías y barreras) con la respuesta a incidentes (reporte, clasificación, análisis de causa raíz y plan de mejora). El ciclo PHVA conecta las medidas correctivas con su verificación y estandarización.