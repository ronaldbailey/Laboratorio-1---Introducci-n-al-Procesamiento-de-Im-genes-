# Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-
Laboratorio #1 - (Introducción al Procesamiento de Imágenes)

# Postgrado en Análisis y Predicción de Datos
## Tercer Trimestre, 2023
### FISICC
#### Text Mining & Image Recognition
### Laboratorio #1

**Instrucciones:** A continuación, verá una lista de ejercicios que debe completar para poder entregar el laboratorio #1. Para desarrollar su solución deberá utilizar un Notebook que contenga todos los ejercicios indicando cada uno de ellos explícitamente con sus resultados. Para la entrega, deberá subir un enlace al repositorio de GitHub que contenga su solución.

**Problema 1:**

Desarrolle una función que reciba dos parámetros, una imagen y un entero llamado color. La función debe devolver una imagen que tenga activos los canales de color según los siguientes puntos:

- Si el parámetro color vale 1, la imagen debe mostrar activos únicamente el color azul.
- Si el parámetro color vale 2, la imagen debe mostrar activos únicamente el color verde.
- Si el parámetro color vale 3, la imagen debe mostrar activos únicamente el color rojo.
- Si el parámetro color vale 10, la imagen debe mostrar activos únicamente los colores rojo y verde.
- Si el parámetro color vale 20, la imagen debe mostrar activos únicamente los colores verde y azul.
- Si el parámetro color vale 30, la imagen debe mostrar activos únicamente los colores azul y rojo.


#### Solucion 1: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Problema1.ipynb
**Problema 2:**

En el .zip del laboratorio se le compartió un conjunto de imágenes en escala de grises. Estas imágenes fueron creadas utilizando una escala de grises en 3D. Cree una función que, dadas las 3 imágenes, construya la imagen original a color.

#### Solucion2: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Problema%202.ipynb

**Problema 3:**

Cree una función que, dada una imagen, cree una escala de grises en tres dimensiones. Tome en cuenta que su función debe crear 3 imágenes como salida. Para entregar este ejercicio, debe incluir una de las imágenes que haya utilizado como prueba y el resultado de las mismas. No puede utilizar la imagen del Problema #2.

#### Solucion3: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Prolbema3.ipynb

**Problema 4:**

Cree una función que, dada una imagen, muestre el histograma de cada canal de color y el de escala de grises (utilice un promedio aritmético para su escala de grises, no puede usar funciones de OpenCV). Sus histogramas deben incluir una línea vertical que muestre el valor de la media de la distribución.

#### Solucion3: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Problema4.ipynb

**Problema 5:**

Investigue brevemente en qué consiste el espacio de color HSV y cómo se mapean colores a dicho espacio. Para entregar este ejercicio, puede hacerlo con un archivo PDF.

---
**Nota:** Recuerde que este es solo el enunciado del laboratorio. Debe completar cada ejercicio y presentar los resultados en un Notebook y un repositorio de GitHub.
