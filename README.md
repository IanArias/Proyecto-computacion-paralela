Entrega 2 - Implementación inicial y validación parcial
Resumen
Comparativa inicial entre Polars y pandas para el dataset product_10000000.csv (10M filas).

Cómo ejecutar
Colocar product_10000000.csv en la ruta indicada en el notebook/archivo.
Ajustar POLARS_MAX_THREADS según CPUs asignadas (ver sección de configuración en el notebook).
Ejecutar el notebook entrega2_benchmark.ipynb en el entorno Jupyter de Kabre.
Resultados y CSVs se guardarán en la carpeta ./results_entrega2.
Requisitos
Python 3.8+
polars
pandas
psutil
matplotlib
(opcional) memory_profiler
Notas de implementación
Se compara Polars (lazy & eager) con pandas (streaming por chunks).
Se exportan resultados parciales y tablas agregadas para análisis y para el informe.
