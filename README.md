# EII7446
Intento Resolución y aplicación del Rijksmuseum Challenge 2014
Se presenta una aproximación a la resolución del Rijksmuseum Challenge 2014 (https://figshare.com/articles/dataset/Rijksmuseum_Challenge_2014/5660617?file=9878152) (https://jvgemert.github.io/pub/mensinkICMR14rijksmuseum.pdf) (https://github.com/tmensink/rijkschallenge) en R. 
Como el desafío está codificado en MatLab, se toman los archivos XML de la BD original y se extructuran en una base de datos en Excel, formato xlsx.
El obejtivo no es la lectura de las imágenes, si no que a través de la BD obtenida de los archivos XML, aplicar árboles de clasificación de forma tal de poder clasificar según tipo de obra, autor, año, material. En esta oportunidad se presenta el modelo de clasificación para obra de arte pintura, según dimensiones de las distintas obras de arte, material y técnica.
El archivo .mat es el código utilizado para agrupar todos los archivos xml (112.000) correspondientes a las obras de arte en una base estructurada en excel.
Las macros presentadas se utilizaron para ordenar la base de datos en excel.
La carpeta de archivos XML se puede bajar del gittub del challenge
Finalmente en el archivo R se adjunta el código del modelo de clasificación usando árboles de decisión
