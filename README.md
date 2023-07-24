# Laboratorio-1---Introducci-n-al-Procesamiento-de-Im-genes-
Laboratorio #1 - (Introducción al Procesamiento de Imágenes)


Postgrado en An´alisis y Predicci´on de Datos
Tercer Trimestre, 2023
FISICC
Text Mining & Image Recognition
Laboratorio # 1
Instrucciones: A continuaci´on ver´a una lista de ejercicios que debe completar para poder entregar
el laboratorio #1. Para desarrollar su soluci´on deber´a utilizar un Notebook el cual contenga todos
los ejercicios indicando cada uno de ellos expl´ıcitamente con sus resultados. Para la entrega deber´a
subir un link al repositorio de github el cual contiene su soluci´on.
Problema 1:
Desarrolle una funci´on la cual reciba dos par´ametros, una imagen y un entero llamado color, la
funci´on debe devolver una imagen la cual tenga activos los canales de color segu´n los siguientes
puntos:
Si el par´ametro color vale 1, la imagen debe mostrar activos u´nicamente el color azul.
Si el par´ametro color vale 2, la imagen debe mostrar activos u´nicamente el color verde.
Si el par´ametro color vale 3, la imagen debe mostrar activos u´nicamente el color rojo.
Si el par´ametro color vale 10, la imagen debe mostrar activos u´nicamente los colores rojo y
verde.
Si el par´ametro color vale 20, la imagen debe mostrar activos u´nicamente los colores verde y
azul.
Si el par´ametro color vale 30, la imagen debe mostrar activos u´nicamente los colores azul y
rojo.
Problema 2:
En el .zip del laboratorio se le comparti´o un conjunto de im´agenes en escala de grises, estas im´agenes
fueron creadas utilizando una escala de grises en 3D, cree una funci´on que dadas las 3 im´agenes se
construya la imagen original a color.
Problema 3:
Cree una funci´on que dada una imagen cree una escala de grises en tres dimensiones, tome en
cuenta que su funci´on debe crear 3 im´agenes como salida. Para entregar este ejercicio debe incluir
una las im´agenes que haya utilizado como prueba y el resultado de las misma, no puede utilizar la
imagen del Problema #2.
Problema 4:
Cree una funci´on que dada una imagen, muestre el histograma de cada canal de color y el de
escala de grises (utilice un promedio aritm´etico para su escala de grises, no puede usar funciones
de opencv), sus histogramas deben incluir una l´ınea vertical la cual muestre el valor de la media
de la distribuci´on.
Problema 5:
Investigue brevemente en que consiste el espacio de color HSV y como se mapean colores a dicho
especio, para entregar este ejercicio puede hacer con un archivo PDF.
1