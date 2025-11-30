# 🎵 Análisis de Preferencias Musicales entre Springfield y Shelbyville

## 📘 Introducción
Este proyecto analiza el comportamiento musical de los usuarios de dos ciudades —**Springfield** y **Shelbyville**— utilizando sus historiales de reproducción.  
El objetivo principal es determinar si **la actividad de escucha cambia según el día de la semana y según la ciudad**, apoyándose en procesos de limpieza, estandarización y análisis descriptivo del dataset.

---

## ✨ Funcionalidades

### ✔️ 1. Exploración inicial del dataset
- Revisión del archivo `music_project_en.csv`.
- Identificación de estructura, tipos de datos y calidad inicial.
- Detección de encabezados inconsistentes, valores nulos y duplicados.

### ✔️ 2. Limpieza y preprocesamiento
- Estandarización de nombres de columnas.
- Corrección y normalización de valores textuales (por ejemplo, géneros mal escritos).
- Sustitución de valores faltantes en campos como artista, canción y género.
- Eliminación de duplicados explícitos e implícitos.

### ✔️ 3. Análisis descriptivo
- Conteo de reproducciones por ciudad.
- Comparación de actividad entre lunes, miércoles y viernes.
- Agrupaciones por ciudad + día para identificar patrones de comportamiento.
- Funciones personalizadas para obtener estadísticas específicas por ciudad y fecha.

### ✔️ 4. Prueba de hipótesis
Hipótesis analizada:
> **La actividad de los usuarios difiere según el día de la semana y según la ciudad.**

Se realizan comparaciones directas de conteos y segmentación del dataset para confirmarla o rechazarla.

---

## 🛠️ Herramientas utilizadas
- **Python 3**
- **Jupyter Notebook**
- Librerías:
  - 🐍 **pandas** (limpieza y manipulación de datos)
  - 🔢 **numpy** (operaciones numéricas)
  - 📊 **matplotlib / seaborn** (visualización cuando aplica)

---

## ✅ Conclusión
Los resultados obtenidos muestran que:

- ✔️ **Sí hay diferencias claras entre ciudades**: Springfield tiene mayor actividad que Shelbyville.  
- ⚠️ **Las diferencias entre días de la semana no son suficientemente significativas**, pues lunes y viernes presentan niveles similares, y miércoles solo muestra un ligero descenso.  
- 📌 **La hipótesis se confirma parcialmente**:  
  - Hay diferencias por ciudad.  
  - No hay diferencias fuertes por día.

Este análisis establece una base sólida para estudios más avanzados, como patrones de comportamiento musical, segmentación o futuros modelos de recomendación.
