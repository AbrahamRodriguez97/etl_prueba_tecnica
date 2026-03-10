# ETL Pipeline: Procesamiento de Ventas con PySpark 

Este repositorio contiene un proyecto para la prueba tecnica de un flujo de datos **ETL (Extract, Transform, Load)** desarrollado en PySpark. El proyecto simula el procesamiento de transacciones de ventas, realizando limpieza de datos y cálculos de negocio antes de almacenar los resultados. 

---

## Stack 
* **Lenguaje:** Python 
* **Motor de Procesamiento:** Apache Spark (PySpark)
* **Entorno de Desarrollo:** Google Colab / Jupyter Notebooks
* **Formato de Almacenamiento:** CSV (Nota: Se recomienda Parquet para entornos de producción por eficiencia columnar, pero por eficiencia de ver resultados lo hice en csv).

## Estructura del Proyecto
```text
mi-primer-etl-spark/
├── data/
│   └── ventas.csv             # Dataset original (input)
├── notebooks/
│   └── etl_ejemplo.ipynb   # Lógica del ETL en PySpark
├── outputs/
│   └── ventas_transformado.csv/  # Resultado del proceso (formato carpeta Spark/archivo csv)
└── README.md
```