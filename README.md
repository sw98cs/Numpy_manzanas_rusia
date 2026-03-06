# Numpy_manzanas_rusia

## Descripción
Este proyecto es una implementación de análisis numérico de precios de manzanas utilizando NumPy en Python. Carga datos de un archivo CSV, maneja valores faltantes, realiza comparaciones entre series de tiempo y ajusta un modelo de regresión lineal simple. Finalmente, exporta los resultados de las normas y pendientes calculadas.

## Instalación
Para ejecutar este proyecto, necesitarás tener Python instalado junto con las siguientes librerías:

*   `numpy`
*   `matplotlib`

Puedes instalarlas usando pip:

```bash
pip install numpy matplotlib
```

## Uso
1.  Clona este repositorio o descarga los archivos del proyecto.
2.  Abre el notebook de Colab (o un entorno de Jupyter).
3.  Ejecuta todas las celdas en secuencia.

El notebook realizará las siguientes operaciones:
*   Cargará los datos de precios de manzanas desde un URL remoto.
*   Realizará una transposición de los datos para facilitar el análisis.
*   Manejará los valores `NaN` en la serie de precios de Kaliningrado imputándolos con el promedio de los valores adyacentes.
*   Graficará los precios de Moscú y Kaliningrado.
*   Calculará y graficará una regresión lineal para los precios de Moscú.
*   Generará valores aleatorios de pendientes y calculará la norma de la diferencia entre los precios de Moscú y la línea de regresión generada.
*   Exportará un archivo CSV con las normas y las pendientes aleatorias.

## Estructura del Notebook
*   **Carga de datos:** Se carga el archivo `manzanas.csv` y se prepara el array de NumPy.
*   **Visualización y Selección:** Se extraen las fechas y los precios, y se visualizan los datos.
*   **Tratamiento de NAN:** Se identifica y se trata un valor `NaN` en los datos de Kaliningrado.
*   **Comparación entre arrays:** Se analizan las diferencias entre los arrays de precios y una línea de regresión.
*   **Valores Aleatorios:** Se generan valores aleatorios y se utilizan para calcular normas.
*   **Exportando el archivo generado:** Se guarda un archivo CSV con las normas y pendientes generadas.
