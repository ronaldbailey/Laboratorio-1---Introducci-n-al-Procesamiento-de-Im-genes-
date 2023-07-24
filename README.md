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

#### Solucion4: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Problema4.ipynb

**Problema 5:**

Investigue brevemente en qué consiste el espacio de color HSV y cómo se mapean colores a dicho espacio. Para entregar este ejercicio, puede hacerlo con un archivo PDF.

#### Solucion5: https://github.com/ronaldbailey/Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-/blob/main/Problema5.ipynb

https://dreampuf.github.io/GraphvizOnline/#digraph%20HSV%20%7B%0D%0A%20%20%20%20node%20%5Bshape%3Dbox%2C%20style%3Dfilled%2C%20color%3Dlightblue%5D%3B%0D%0A%20%20%20%20HSV%20%5Blabel%3D%22Espacio%20de%20Color%20HSV%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20Matiz%20%5Blabel%3D%22Matiz%20(Hue)%22%5D%0D%0A%20%20%20%20MatizDetalles%20%5Blabel%3D%22-%20Representa%20el%20color%5Cn-%20Rango%3A%200%20a%20360%20grados%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20Saturacion%20%5Blabel%3D%22Saturaci%C3%B3n%20(Saturation)%22%5D%0D%0A%20%20%20%20SaturacionDetalles%20%5Blabel%3D%22-%20Representa%20la%20dominancia%20del%20matiz%5Cn-%20Rango%3A%200%20a%20100%25%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20Valor%20%5Blabel%3D%22Valor%20(Value)%22%5D%0D%0A%20%20%20%20ValorDetalles%20%5Blabel%3D%22-%20Representa%20el%20brillo%20del%20color%5Cn-%20Rango%3A%200%20a%20100%25%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20Mapeo%20%5Blabel%3D%22Mapeo%20de%20Colores%22%5D%0D%0A%20%20%20%20MapeoDetalles%20%5Blabel%3D%22-%20El%20matiz%20se%20mapea%20a%20un%20punto%20en%20el%20c%C3%ADrculo%20crom%C3%A1tico%5Cn-%20La%20saturaci%C3%B3n%20es%20la%20distancia%20desde%20el%20centro%20del%20c%C3%ADrculo%5Cn-%20El%20valor%20es%20la%20luminosidad%20del%20color%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20Ventajas%20%5Blabel%3D%22Ventajas%20del%20HSV%22%5D%0D%0A%20%20%20%20VentajasDetalles%20%5Blabel%3D%22-%20M%C3%A1s%20intuitivo%20para%20los%20humanos%20que%20el%20RGB%5Cn-%20Separaci%C3%B3n%20clara%20entre%20la%20informaci%C3%B3n%20de%20color%20(Hue)%20y%20la%20informaci%C3%B3n%20de%20luminosidad%20(Value)%5Cn-%20%C3%9Atil%20para%20aplicaciones%20de%20procesamiento%20de%20im%C3%A1genes%2C%20como%20la%20detecci%C3%B3n%20de%20colores%20y%20la%20segmentaci%C3%B3n%20de%20im%C3%A1genes%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20CirculoCromatico%20%5Blabel%3D%22C%C3%ADrculo%20Crom%C3%A1tico%22%5D%0D%0A%20%20%20%20CirculoCromaticoDetalles%20%5Blabel%3D%22-%20Representaci%C3%B3n%20circular%20de%20los%20colores%5Cn-%20Los%20colores%20primarios%20y%20secundarios%20est%C3%A1n%20distribuidos%20alrededor%20del%20c%C3%ADrculo%5Cn-%20Los%20colores%20opuestos%20en%20el%20c%C3%ADrculo%20son%20complementarios%5Cn-%20Utilizado%20en%20el%20mapeo%20del%20matiz%20en%20HSV%22%5D%0D%0A%20%20%20%20%0D%0A%20%20%20%20HSV%20-%3E%20Matiz%0D%0A%20%20%20%20Matiz%20-%3E%20MatizDetalles%0D%0A%20%20%20%20HSV%20-%3E%20Saturacion%0D%0A%20%20%20%20Saturacion%20-%3E%20SaturacionDetalles%0D%0A%20%20%20%20HSV%20-%3E%20Valor%0D%0A%20%20%20%20Valor%20-%3E%20ValorDetalles%0D%0A%20%20%20%20HSV%20-%3E%20Mapeo%0D%0A%20%20%20%20Mapeo%20-%3E%20MapeoDetalles%0D%0A%20%20%20%20HSV%20-%3E%20Ventajas%0D%0A%20%20%20%20Ventajas%20-%3E%20VentajasDetalles%0D%0A%20%20%20%20HSV%20-%3E%20CirculoCromatico%0D%0A%20%20%20%20CirculoCromatico%20-%3E%20CirculoCromaticoDetalles%0D%0A%7D%0D%0A

---
**Nota:** Recuerde que este es solo el enunciado del laboratorio. Debe completar cada ejercicio y presentar los resultados en un Notebook y un repositorio de GitHub.
