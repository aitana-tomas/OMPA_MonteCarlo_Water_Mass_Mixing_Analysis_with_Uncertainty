# Análisis OMPA con Simulaciones de Monte Carlo

### Trabajo de Fin de Grado - Aitana Tomás San Martín
#### Tutor: Leopoldo Pena
#### Ciéncias del Mar UB

Este repositorio contiene una herramienta computacional en Python que implementa el método de análisis multiparamétrico óptimo (OMPA) con simulaciones de Monte Carlo. Esta herramienta tiene como objetivo mejorar la estimación de mezclas de masas de agua y cuantificar la incertidumbre asociada a estas estimaciones.

El enfoque se ha aplicado a los datos de la campaña oceanográfica TRANSMOW, centrada en el margen ibérico atlántico. La implementación del Análisis Multiparimétrico Óptimo (OMPA) utilizada en este trabajo se basa en los principios y metodologías detalladas en el libro "Modeling Methods for Marine Science" de Glover, D. M., Jenkins, W. J., & Doney, S. C. (2011), Cambridge University Press (https://doi.org/10.1017/CBO9780511975721). 

## Contenido

* `OMPA_MonteCarlo.ipynb`: Cuaderno Jupyter con el código Python para el análisis OMPA y las simulaciones de Monte Carlo.
* `MEMORIA.pdf`: Memoria del Trabajo de Fin de Grado que describe el proyecto en detalle. 
* `data/`:  Carpeta para almacenar los datos utilizados en el análisis.
* Power Point ilustrativo: https://www.canva.com/design/DAGYI79KAsY/5am5WE9DPbopCobngIPd3A/view?utm_content=DAGYI79KAsY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h9b73eb83ff 

## Resumen del proceso

1.  Configuración del entorno
2.  Importación y preparación de datos
3.  Generación aleatoria de endmembers y vectores de error
4.  Estandarización y ponderación
5.  Resolución del sistema OMPA
6.  Simulación Monte Carlo
7.  Análisis estadístico y visualización de resultados

## Requisitos

Para ejecutar el código en este repositorio, necesitarás tener instalado Python 3 y las siguientes librerías:

* NumPy
* Pandas
* Matplotlib
* SciPy
* Seaborn
* Scikit-learn
* mpl_toolkits.mplot3d (Axes3D)
* sklearn (datasets, preprocessing)

Puedes instalar estas librerías utilizando `pip`:

```bash
pip install ...

