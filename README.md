# Code-Challenge

PROGRAMA PASANTÍAS GLOBANT

Desafío Técnico: ETL y Consultas SQL en Google Colab y BigQuery Este documento proporciona una descripción detallada del proceso ETL (Extracción, Transformación y Carga) que se ha desarrollado, junto con las consultas SQL realizadas sobre un conjunto de datos alojado en un archivo CSV.

Procedimiento: Carga de Datos en Google Colab: Se inició cargando el archivo CSV en Google Colab, utilizando las bibliotecas estándar de Python y pandas. Para futuras referencias, es esencial mencionar que, al trabajar con Google Colab, el archivo CSV debe estar alojado previamente en Google Drive o ser accesible a través de una API.

Proceso ETL: Se empleó la biblioteca pandas para realizar operaciones de limpieza y transformación de datos. Esto aseguró que los registros estuvieran uniformes y listos para su análisis. Se eliminaron valores nulos, se gestionaron duplicados y se transformaron campos para mejorar la calidad de los datos.

Exportación a Google Sheets: Utilizando gspread, se exportó el DataFrame transformado a una hoja de cálculo específica, preparándolo para la integración con BigQuery.

Carga en BigQuery: Con los datos ya en Google Sheets, se utilizó la interfaz de BigQuery para cargar estos datos en una tabla específica, permitiendo realizar consultas SQL avanzadas sobre ellos. La integración entre Google Sheets y BigQuery proporcionó un flujo eficiente para el traspaso de datos.

Consultas SQL: Una vez en BigQuery, se llevaron a cabo diversas consultas SQL para analizar y extraer insights de los datos. Estas consultas incluyeron selecciones, filtrados, agrupaciones y ordenamientos.
Durante el proceso, se instaló Git en el entorno de Google Colab. Una vez instalado, intentamos registrar nuestras modificaciones a través de un commit. Sin embargo, enfrentamos desafíos técnicos que impidieron la conclusión exitosa del commit.
