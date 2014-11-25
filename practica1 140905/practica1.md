## PRACTICA 1

**LO UNICO QUE NO PUEDEN HACER EN ESTA PRACTICA ES PASARSE INFORMACION ENTRE COMPANIEROS NI SOLICITAR AL MAESTRO/AYUDANTE INFORMACION ALGUNA RELACIONADA CON LAS ACTIVIDADES NI CON R.**

Crea un script con el nombre practica1.Nombre1.Apellido1. Ahi pon tanto las preguntas como las respuestas en cada actividad. Recuerda que todo esto debe ir como #comentarios. En el script solo puede haber instrucciones de R y #comentarios.

Baja los archivos datos0.xls y datos1.xls del github en la carpeta _practica1_ y ponlos en el Escritorio. Abre los archivos y comparalos. 

datos1.xls muestra el monto que reciben por anio los beneficiarios de un programa agrario en municipios de diferentes estados del pais.

_ACTIVIDAD1:_

1. ¿Que correcciones se le tuvieron que hacer a datos0.xls para que no tuviera problemas R en leerlas? (valor: 0.5)
2. ¿Que columna agregarias? (valor: 0.5)

Convierte el archivo datos1.xls a formato .csv.
En R, cambia de directorio de trabajo al Escritorio, lee el archivo *datos1.csv* (con header = TRUE) y almacalo con el nombre _datos_.

_ACTIVIDAD2:_

1. En el registro 22 se tiene que los beneficiarios ocupan una superficie de 0 ha. Este es un error. La superficie correcta es 4521.83 ha. Corrijan este dato. (valor: 1.0)

_ACTIVIDAD3:_

Usa las funciones **str()** y **summary()** para decirme:

1. ¿Que clase es cada variable de la base de datos? (valor: 0.5)
2. ¿Cual es el intervalo de valores que toma la variable _datos$No.Beneficiarios_? (valor: 0.5)
3. En promedio, ¿cuanto reciben, por municipio y por anio, los beneficiarios del programa? (valor: 0.5)

_ACTIVIDAD4:_

La moda se puede calcular usando la instruccion: ```as.numeric(names(sort(-table(x)))[1])```. Esta instruccion se puede desglosar en los siguientes pasos:

table(x) -> -table(x) -> sort(-table(x)) -> names(sort(-table(x))) -> names(sort(-table(x)))[1] -> as.numeric(names(sort(-table(x)))[1])

1. Describe que esta pasando en cada uno de los pasos. (valor: 2.0)
2. Obten la moda de _datos$No.Beneficiarios_. (valor: 0.5)

_ACTIVIDAD5:_

En la carpeta _practica1_ ve el archivo _pay.pdf_.

1. ¿Cual es el codigo que permitiria generar esta grafica? Reconstruye el codigo que lo genera y en lugar del titulo pon tu nombre (Nombre1.Apellido1) y enviale a Leticia la grafica como parte de la practica. (valor: 1.0)
2. ¿Que patron puedes ver en este grafico con respecto a la cantidad de municipios beneficiados? (valor: 0.5)

_ACTIVIDAD6:_

Ahora ve el archivo _cajaybigotes.pdf_.

1. ¿Cual es el codigo que permitiria generar esta grafica? Reconstruye el codigo que lo genera, en el titulo pon tu nombre (Nombre1.Apellido1) y en el eje Y pon el nombre y unidades de la variable graficada. Enviale a Leticia la grafica como parte de la practica. (valor: 1.0)
2. ¿Que entidad federativa presenta la mayor dispersion en el numero de beneficiarios? ¿Y que estado la menor dispersion? (valor: 0.5)
3. ¿En que estado es mas probable tener, en un municipio y anio particulares, la mayor cantidad de beneficiarios del programa? (valor: 1.0)

_RETO: Observa las graficas reto1.pdf y reto2.pdf. La primera muestra la grafica de dispersion de la relacion entre datos$Superficie.ha y datos$Monto.pesos. La segunda muestra la misma relacion. ¿En que difieren las dos graficas? ¿Como obtendrias la segunda grafica? Mandame el codigo que genera la segunda grafica explicando que funcion usaste para lograrlo. HINT: transformaciones. (valor: 2.0)_

 