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
## Evidencias

Extracción
<img width="609" height="216" alt="image" src="https://github.com/user-attachments/assets/9c71b8e2-49f7-4b98-b459-92b4fc999ce7" />

Transformacion
<img width="710" height="206" alt="image" src="https://github.com/user-attachments/assets/69dba639-78ec-410d-ac5a-cbb77029578a" />

Carga
<img width="527" height="191" alt="image" src="https://github.com/user-attachments/assets/fc855eb0-a142-4c0d-83d4-60467ccd06fc" />


