# 🎰 Proyecto de Análisis de Números de Lotería de Navidad

Este proyecto fue realizado como **parte de mi formación en un curso de machine learning y data science**, con el objetivo de **afianzar mis conocimientos prácticos en Python, Pandas, visualización y análisis estadístico**.

El proyecto está desarrollado en **Anaconda** utilizando **Jupyter Notebook**, y contiene herramientas para **obtener, procesar y analizar números de lotería histórica**, así como una **calculadora interactiva de probabilidades**.

---

## 📂 Archivos principales

1. **`Loteria_DataScience.ipynb`**  
   - Notebook donde se **extraen los datos de un PDF**, se **normalizan** y se **limpia el dataset**.  
   - Se preparan columnas adicionales como centena, decena, unidad y tipo de premio.  
   - Contiene análisis exploratorio y visualizaciones preliminares de los números de lotería.  
   - Es la **base para generar el DataFrame procesado** usado en los otros archivos.

2. **`loteria_datos.pkl`**  
   - DataFrame procesado con todos los números premiados desde 2013.  
   - Incluye información adicional: centena, decena, reintegro y tipo de premio (`normal` o `especial`).  
   - Sirve como **fuente de datos para consultas y análisis históricos**.

3. **`Consulta_numeros_loteria.ipynb`**  
   - Script interactivo que permite **ingresar un número de 5 dígitos** y obtener estadísticas detalladas:
     - Veces que ha salido el número exacto.  
     - Probabilidad teórica y probabilidad histórica.  
     - Probabilidades de aproximaciones: centena, decena y reintegro.  
     - Factor de frecuencia comparado con la media de todos los números.  
   - Permite analizar varios números consecutivamente y muestra alertas sobre su frecuencia relativa.



