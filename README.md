# sprint7-final-project
Repositorio donde se documenta el proyecto final del Sprint 7 del Bootcamp de Analisis de datos en Tripleten

## Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de uso de los clientes de ConnectaTel, limpiar y preparar los datos, identificar patrones de consumo y segmentar a los usuarios para obtener conclusiones útiles para el negocio.

## Datasets utilizados

Se utilizaron tres tablas principales:

- **`users`**: información de los clientes, como edad, ciudad, plan, fecha de registro y fecha de cancelación.
- **`usage`**: registros de uso por usuario, incluyendo llamadas, mensajes y duración.
- **`plans`**: información básica de los planes disponibles.

## Etapas del análisis

1. **Carga e inspección inicial de datos**
   - Revisión de dimensiones, tipos de datos y valores nulos.

2. **Limpieza de datos**
   - Corrección de valores sentinela.
   - Tratamiento de fechas fuera de rango.
   - Revisión de valores nulos e inválidos.

3. **Resumen del uso por usuario**
   - Agrupación de la tabla `usage` por `user_id`.
   - Cálculo de mensajes, llamadas y minutos totales.

4. **Análisis exploratorio**
   - Estadísticas descriptivas.
   - Distribución de variables numéricas y categóricas.
   - Detección de outliers.

5. **Segmentación de clientes**
   - Segmentación por nivel de uso.
   - Segmentación por edad.

6. **Análisis ejecutivo**
   - Interpretación de hallazgos.
   - Recomendaciones de negocio.

## Cómo ejecutar el notebook

Puedes abrir y ejecutar el notebook en:

- **Google Colab**
- **Jupyter Notebook**
- **JupyterLab**

### En Google Colab
1. Sube el archivo `.ipynb` a tu cuenta de Google Drive o GitHub.
2. Ábrelo con Google Colab.
3. Ejecuta las celdas en orden de arriba hacia abajo.

### En Jupyter
1. Descarga el repositorio o clónalo en tu equipo.
2. Abre una terminal en la carpeta del proyecto.
3. Ejecuta:

```bash
jupyter notebook
