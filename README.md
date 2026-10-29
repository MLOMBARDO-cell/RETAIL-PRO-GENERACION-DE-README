# RETAIL-PRO-GENERACION-DE-README

## Arquitectura y flujo de trabajo

El proyecto RetailPro se desarrolla en cuatro etapas principales, desde la creación de la base de datos hasta el análisis de indicadores comerciales en Power BI.

```mermaid
flowchart TD
    A["1. Base de datos SQL<br/>Creación de tablas y carga de datos"]
    B["2. Consultas de negocio<br/>JOIN, agregaciones y análisis comercial"]
    C["3. Pipeline ETL<br/>Limpieza y transformación de datos"]
    D["4. Power BI<br/>Modelo de datos, medidas DAX y KPIs"]

    A --> B
    B --> C
    C --> D

    classDef etapa fill:#303030,color:#ffffff,stroke:#555555,stroke-width:1px
    class A,B,C,D etapa
```
