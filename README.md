# Luzu TV — 5 años de evolución (Análisis con YouTube API)

Este proyecto analiza **la evolución de Luzu TV durante los últimos 5 años** utilizando datos extraídos directamente desde la **YouTube Data API**.  
El objetivo principal es comprender el crecimiento del canal en términos de **producción, audiencia, engagement** e impacto dentro del ecosistema digital argentino.

---

## Fuente de datos

Los datos se obtuvieron mediante consultas a la **YouTube Data API v3**, utilizando Python para extraer, procesar y analizar toda la información directamente desde los endpoints de YouTube.

> *Este repositorio no incluye archivos de datos locales ya que todo se descarga automáticamente desde la API.*

---

## Objetivos del análisis

- Analizar la evolución del canal a lo largo de 5 años.
- Estudiar cambios en duración, volumen de publicaciones y frecuencia.
- Medir el crecimiento en visualizaciones y engagement.
- Identificar patrones, picos y transformaciones relevantes.
- Comprender cómo creció la comunidad y cómo respondió a la mayor oferta de contenidos.

---

## Tecnologías utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **WordCloud**
- **TQDM**
- **YouTube Data API**
- **Google Colab**

---

## Estructura del repositorio
- /notebooks → Notebook completo del análisis (.ipynb)
- /presentation → Presentación del informe (PDF)
- /requirements.txt → Librerías necesarias para reproducir el proyecto

---

## Principales hallazgos

- **Luzu TV multiplicó su producción de contenidos** de forma sostenida a lo largo de los cinco años analizados, mostrando una estrategia clara de expansión en su oferta digital.

- **La audiencia creció en paralelo** al incremento de producción, lo que demuestra que la comunidad respondió positivamente a la mayor presencia y frecuencia de contenidos.

- **El engagement se mantuvo alto**, incluso en períodos de mayor volumen de publicaciones, indicando una **audiencia fiel y activa**.

- Se observa una **evolución notable en la duración promedio de los videos**, adaptándose a nuevas dinámicas de consumo sin perder retención.

- Las **interacciones (likes, comentarios y visualizaciones)** reflejan una comunidad altamente involucrada, con picos asociados a contenidos clave.

- Los patrones analizados muestran que Luzu TV **entiende a su audiencia y crece junto a ella**, fortaleciendo su identidad y presencia dentro del ecosistema digital argentino.

---

## Cómo reproducir el análisis

1. Clonar o descargar este repositorio.
2. Instalar dependencias:

```bash
pip install -r requirements.txt

3. Ejecutar el notebook:
/notebooks/Luzu_5years_evolution.ipynb
