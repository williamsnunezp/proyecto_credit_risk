# proyecto_credit_risk
  
  




---

# Estructura del proyecto

```
proyecto_credit_risk_elt/
├── notebooks/              # Scripts de flujo de trabajo
│   ├── bronze/             # Notebooks para la ingesta inicial (E/L)
│   ├── silver/             # Notebooks para limpieza y estandarización (T)
│   └── gold/               # Notebooks para agregaciones finales y dashboard (T)
├── data/                   # Ubicación de los datos en el DBFS/Unity Catalog
│   ├── raw/                # (Bronze layer) Datos brutos de Kaggle
│   ├── clean/              # (Silver layer) Datos limpios y estructurados
│   └── aggregated/         # (Gold layer) Tablas listas para consumo/BI
├── resources/              # Archivos adicionales (configuraciones, scripts SQL DDL)
└── README.md               # Documentación del proyecto
```