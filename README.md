# TP1: Predicción de Ingresos

## Descripción
Este proyecto aborda la **predicción de ingresos** utilizando modelos de regresión lineal y técnicas avanzadas como validación cruzada y análisis de errores. Los datos provienen del informe de 2018 "Medición de Pobreza Monetaria y Desigualdad" para Bogotá, basado en la GEIH.

El notebook incluye:
- Limpieza y preprocesamiento de datos.
- Creación y evaluación de modelos predictivos.
- Comparación de métricas de desempeño como **MSE** y **LOOCV-MSE**.
- Exploración del compromiso sesgo-varianza.

---

## Contenido del Notebook
1. **Scraping de Datos**:
   - Extracción de datos desde un sitio web público.
   - Conversión a un formato estructurado para análisis.

2. **Limpieza y Transformación**:
   - Filtrado de observaciones relevantes (edad ≥ 18 y empleados).
   - Eliminación de columnas irrelevantes o con datos faltantes significativos.
   - Selección de predictores clave como edad, nivel educativo, horas trabajadas y tipo de ocupación.

3. **Modelos Predictivos**:
   - Construcción de modelos desde especificaciones simples hasta complejas.
   - Evaluación de modelos con **MSE fuera de muestra** y validación cruzada (**LOOCV**).
   - Discusión del compromiso sesgo-varianza.

4. **Resultados y Discusión**:
   - Identificación del modelo óptimo basado en el error fuera de muestra.
   - Análisis de observaciones con errores significativos.

---

## Requisitos
- **Python 3.8+**
- Bibliotecas:
  - `numpy`
  - `pandas`
  - `sklearn`
  - `matplotlib`
  - `fpdf` (opcional, para generación de reportes)

---

## Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/dipla70/ML-TP1.git
