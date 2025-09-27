 Análisis Exploratorio de Netflix 

 Introducción
Este proyecto es un análisis exploratorio de datos (EDA) utilizando el dataset de títulos de Netflix.  
El objetivo es practicar herramientas de análisis de datos con Python, Pandas, Matplotlib y Seaborn, y obtener insights sobre el catálogo de Netflix.

Objetivos
- Conocer la distribución de títulos por tipo (películas y series).
- Analizar las duraciones de películas y temporadas de series.
- Identificar los géneros y países más frecuentes.
- Observar la evolución de estrenos a lo largo del tiempo.

Dataset
- Fuente: [Netflix Titles - Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- Formato: CSV
- Columnas principales:
  - type: Película o Serie
  - title: Título del contenido
  - director,cast: Equipo involucrado
  - country: País de producción
  - release_year: Año de estreno
  - duration: Duración (minutos o temporadas)
  - listed_in: Géneros

Herramientas utilizadas
- Python 
- Pandas
- Matplotlib y Seaborn
- Jupyter Notebook

Resultados principales
- La mayoría del catálogo corresponde a películas.
- Las películas tienen una duración típica de 90 a 120 minutos.
- Las series suelen tener entre 1 y 3 temporadas.
- Géneros más frecuentes: Dramas internacionales, Comedias y Documentales.
- Estados Unidos e India son los países con mayor aporte de títulos.

Ejemplo de gráficos generados:
![Distribución de películas y series](images/type_distribution.png)
![Top países productores](images/top_countries.png)

Conclusiones
- Netflix mantiene un catálogo variado pero dominado por películas.
- Existe una concentración fuerte en unos pocos países productores.
- La plataforma ha incrementado su producción en los últimos años, reflejando su estrategia de expansión global.

Próximos pasos
- Aplicar análisis de texto para etiquetas de géneros.
- Comparar catálogo de Netflix con otras plataformas.
- Construir dashboards interactivos en Power BI o Tableau.

Autor: Nis Steingart Fatima  
LinkedIn: (https://www.linkedin.com/in/fatima-candela-nis-44a3a6302) | GitHub:(https://github.com/SteingartFatima)
