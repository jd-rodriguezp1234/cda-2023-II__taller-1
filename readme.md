# Taller 1
## Autor
Johan David Rodríguez Portela

## Ciudad elegida
La ciudad seleccionada es Chicago, la capital de Illinois, Estados Unidos y su ciudad más poblada. Esta ciudad es de interés debido a que es una metrópolis que se encuentra cerca a un lago y este lago tiene una playa que visualmente se parece al mar.

El dataset se puede descargar en el siguiente [enlace.](http://data.insideairbnb.com/united-states/il/chicago/2023-06-18/data/listings.csv.gz)


## Notebooks
Hay 2 notebooks que deben ejecutarse secuencialmente. Estos notebooks fueron ejecutados en colab, por lo que no se necesito instalar alguna librería especial.

### 1_EDA_inicial.ipynb
Es el notebook que presenta el entendimiento inicial de datos, yendo desde la eliminación de columnas no pertinentes, análisis de tipos, corrección de estos y llegando a análisis univariado. En la sección de constantes hay dos valores para leer el archivo de listings original y guardar el limpio preliminar las cuales son LISTINGS_FILE y SAVING_LISTINGS_FILE respectivamente.

### 2_Busqueda_de_insights.ipynb
Es el notebook que utiliza preprocesamiento y análisis multivariado para llegar a insights de negocio. En este notebook se comienza con eliminación de variables redundantes por correlación y significado, se sigue con la geneneración de la variable revenue y amenities en un formato más manejable; se hace el análisis bivariado de variables categóricas contra revenue y se eligen las categorías top; se sigue con el análisis bivariado de variables cuantitativas contra revenue y también se tienen comparación de variables del mismo tipo contra ellas mismas, con la comparación de categóricas contra categóricas respecto al revenue promedio de las categorías top y correlación entre variables cuantitativas.

## Reporte
Se genera un reporte que incluye toda la documentación pedida en el enunciado:

- Página 1: Selección de la ciudad
- Páginas 2 a 6: Entendimiento de datos e insights preliminares más relevantes de las 5 características consideradas más importantes. Como incluye una gráfica por variable relevante se ve más extenso de lo que realmente es.
- Página 7: Descripción de la estrategia de análisis.
- Páginas 8 a 12: Generación de resultados o reporte ejecutivo donde se justifican las características de las propiedades más deseables para rentabilidad, partiendo del análisis gráfico y no gráfico multivariado contra revenue y entre variables. Al igual que el entendimiento de datos, tiene una o más gráficas por criterio de elegibilidad, lo que lo hace ver más extenso de lo que es.