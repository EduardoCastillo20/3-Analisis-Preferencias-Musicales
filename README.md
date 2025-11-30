# Análisis de Preferencias Musicales entre Springfield y Shelbyville

## Introducción
Este proyecto analiza el comportamiento de los usuarios de dos ciudades —Springfield y Shelbyville— utilizando datos de reproducción musical.  
El objetivo es evaluar si existe una diferencia significativa en la actividad de escucha según el día de la semana y según la ciudad.  
Para ello se realiza un proceso de exploración, limpieza, estandarización y análisis descriptivo que garantiza la calidad del dataset antes de formular conclusiones.

## Funcionalidades

### 1. Exploración inicial del dataset
- Revisión del archivo `music_project_en.csv`.
- Identificación de tipos de datos.
- Detección de encabezados inconsistentes, valores faltantes y duplicados.

### 2. Limpieza y preprocesamiento
- Estandarización de nombres de columnas.
- Corrección de variaciones en texto, especialmente en el campo de género musical.
- Reemplazo de valores nulos en columnas como artista, canción y género.
- Eliminación de duplicados explícitos e implícitos.

### 3. Análisis descriptivo
- Conteo de reproducciones por ciudad.
- Comparación de actividad por día (lunes, miércoles y viernes).
- Agrupación por ciudad y día para detectar patrones de comportamiento.
- Implementación de funciones personalizadas para obtener métricas por ciudad y fecha.

### 4. Prueba de hipótesis
Se evalúa la hipótesis:
"La actividad de los usuarios difiere según el día de la semana y según la ciudad."

Se utilizan comparaciones directas y segmentación de los datos para confirmar o rechazar la hipótesis.

## Herramientas
- Python 3
- Jupyter Notebook
- Librerías:
  - pandas (manipulación de datos)
  - numpy (operaciones numéricas básicas)
  - matplotlib / seaborn (gráficas cuando aplican)

## Conclusión
El análisis confirma que:
- Sí existen diferencias claras entre las ciudades: Springfield tiene mayor actividad que Shelbyville.
- Las diferencias entre días de la semana no son suficientemente significativas para afirmar una variación marcada.
- La hipótesis se confirma parcialmente: hay diferencias por ciudad, pero no fuertes diferencias por día.

Este proyecto sienta una base sólida para estudios posteriores, como análisis de tendencias musicales, segmentación de usuarios o modelos de recomendación.
