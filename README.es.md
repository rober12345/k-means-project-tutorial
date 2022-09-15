<!-- hide -->
# K-means Project Tutorial
<!-- endhide -->

- En este pequeño proyecto, utilizarás el algoritmo k-means para segmentar casas según sus coordenadas y su ingreso medio.

## 🌱  Cómo iniciar este proyecto

Esta vez no se hará Fork, tómate un tiempo para leer estas instrucciones:

1. Crear un nuevo repositorio basado en el [proyecto de Machine Learing](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) [haciendo clic aquí](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Abre el repositorio creado recientemente en Gitpod usando la [extensión del botón de Gitpod](https://www.gitpod.io/docs/browser-extension/).
3. Una vez que Gitpod VSCode haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

## 🚛 Cómo entregar este proyecto

Una vez que hayas terminado de resolver los ejercicios, asegúrate de confirmar tus cambios, hazle "push" a el fork de tu repositorio y ve a 4Geeks.com para subir el enlace del repositorio.

## 📝 Instrucciones

**Agrupación de casas**

Crearemos 6 grupos de viviendas basados ​​únicamente en su columna de 'latitud', 'longitud' y 'ingreso medio'.

Enlaces de conjuntos de datos:

https://raw.githubusercontent.com/4GeeksAcademy/k-means-project-tutorial/main/housing.csv

**Paso 1:**

Instala e importa las bibliotecas necesarias: pandas, sklearn y seaborn.

**Paso 2:**

Carga el conjunto de datos de vivienda y echa un vistazo a las primeras filas. Luego crea un nuevo marco de datos con solo la columna 'latitud', 'longitud' e 'ingreso medio' para crear nuestros grupos.

**Step 3:**

Crea una instancia del algoritmo kmeans. Luego, crea una nueva característica de 'cluster' en tu conjunto de datos y predice el clúster ajustando las 3 columnas que tiene. Puede ver la documentación de k-means para implementarlo: https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html.

**Paso 4:**

Convierte tu nueva columna de 'cluster' al tipo de 'categoría'.

**Paso 5:**

Utiliza el gráfico de Seaborn para visualizar tus nuevos grupos.

**Paso 6:**

Como siempre, usa tu notebook para experimentar y asegúrate de obtener los resultados que deseas.

Usa tu archivo app.py para guardar tus pasos definidos, pipelines o funciones en el orden correcto.

En tu archivo README escribe un breve resumen.

Guía de soluciones: 

https://github.com/4GeeksAcademy/k-means-project-tutorial/blob/main/solution_guide.ipynb

