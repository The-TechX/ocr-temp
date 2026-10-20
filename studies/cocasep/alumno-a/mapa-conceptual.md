# Mapa conceptual propuesto — jerarquía y relaciones transversales

> **Borrador de apoyo.** Debe ser revisado y reelaborado personalmente antes de cualquier entrega, por la restricción de IA indicada en la rúbrica.

## Reglas de diseño para la versión final
1. **Concepto central arriba**; cuatro ejes en el segundo nivel; conceptos específicos debajo.
2. **Lectura descendente**: del comité a sus funciones, instrumentos y resultados.
3. **Palabras de enlace en todas las relaciones**, incluyendo las transversales.
4. **Líneas continuas y flechas legibles**, sin cruces que oculten texto ni enlaces desconectados.
5. **Nodos breves**: términos, no párrafos. Ejemplos de NAV, BACVC e IVU-SAD en una sola rama.
6. **Jerarquía visible** con tamaños y colores sobrios; tipografía de alto contraste, márgenes y alineación constantes.
7. **Bibliografía y citas verificadas** en un pie o apartado separado, sin ocupar el espacio de las proposiciones.
8. **Formato de impresión** A3 horizontal como propuesta técnica; confirmar requisitos de entrega del docente.

## Diagrama de referencia (Mermaid)

```mermaid
flowchart TB
  C["COCASEP / CICASEP"]
  O["Organización institucional"]
  P["Prevención y estandarización"]
  I["Gestión de incidentes"]
  M["Mejora continua"]
  O1["Equipo interdisciplinario"]
  O2["Presidencia · Secretaría · Vocalías"]
  P1["GPC · Protocolos · NOM"]
  P2["Barreras de seguridad"]
  P3["Doble verificación · Bundles"]
  I1["Cultura no punitiva"]
  I2["Reporte de incidentes"]
  I3["Cuasifalla · Adverso · Centinela"]
  I4["SIRE"]
  A["Análisis de causa raíz"]
  M1["PMCCS"]
  M2["Ciclo PHVA"]
  S["Seguridad del paciente"]
  Q["Calidad asistencial"]

  C -->|"se organiza mediante"| O
  C -->|"estandariza mediante"| P
  C -->|"gestiona"| I
  C -->|"impulsa"| M
  O -->|"se integra por"| O1
  O1 -->|"comprende"| O2
  P -->|"se fundamenta en"| P1
  P1 -->|"orientan"| P2
  P2 -->|"incluyen"| P3
  I -->|"fomenta"| I1
  I1 -->|"favorece"| I2
  I2 -->|"distingue"| I3
  I2 -->|"puede usar"| I4
  I2 -.->|"se analiza mediante"| A
  A -.->|"orienta"| M1
  M -->|"desarrolla"| M1
  M1 -->|"se verifica mediante"| M2
  P2 -.->|"contribuyen a"| S
  M2 -.->|"fortalece"| Q
  C -->|"promueve"| S
  C -->|"impulsa"| Q
```

## Verificación de enlaces
Las flechas continuas describen **jerarquías**. Las punteadas muestran **relaciones transversales** entre ramas. Cada flecha incluye una expresión verbal que permite leer una proposición completa. El diseño gráfico final debe mantener esa diferencia visual.

## Referencias
Consultar `conceptos-unificados.md` para referencias de las diapositivas, limitaciones y validaciones pendientes.
