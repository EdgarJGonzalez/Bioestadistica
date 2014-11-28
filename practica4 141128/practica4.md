## PRÁCTICA 3

**LO ÚNICO QUE NO PUEDEN HACER EN ESTA PRÁCTICA ES PASARSE INFORMACIÓN ENTRE COMPAÑEROS NI SOLICITAR AL MAESTRO/AYUDANTE INFORMACIÓN ALGUNA RELACIONADA CON LAS ACTIVIDADES NI CON R.**

Crea un script con el nombre practica4.Nombre1.Apellido1. Ahí pon tanto las preguntas como las respuestas a cada actividad. Recuerda que todo esto debe ir como #comentarios. En el script solo puede haber instrucciones de R y #comentarios. Una vez que termines la práctica envíala al correo de Leticia: leticia.0705@hotmail.com.

Para cada prueba de hipótesis usen un _alfa_ = 0.05 y reporten:

1. Hipótesis nula y alternativa.
2. El valor del estadístico de prueba.
3. El valor de p.
4. Su conclusion: ¿se rechaza o no se rechaza la hipótesis nula?

**ACTIVIDAD1** (valor 3 puntos):

Tenemos muestras de la longitud (cm) de los individuos de cuatro poblaciones de una especie de ratón silvestre ubicadas a cuatro diferentes latitudes (Población 1: 35.1453ºN, Pob2: 39.9321ºN, Pob3: 41.3234ºN y Pob4: 48.3412ºN):

Pob1: 9.916 8.252 10.777 11.479 9.994 11.167 9.711 10.069 9.746 9.481 10.832 9.272 11.575 9.816 6.064 11.158 13.746 10.021

Pob2: 12.725 12.399 12.951 10.009  9.880 10.903 13.543 11.130 10.358 12.338  9.471 13.040 11.669 13.446 13.829 12.931 14.228 12.313

Pob3: 15.077 17.017 16.105 15.546 14.886 15.715 16.988 16.970 15.427 14.823 16.243 14.213 14.380 16.901 15.140 15.924 14.208 16.203

Pob4: 17.343 15.020 17.926 17.008 15.376 16.698 15.271 17.738 15.781 17.041 15.251 12.845 16.489 16.015 15.077 13.843 16.137 16.949

¿Cambia el tamaño de los individuos con respecto a la latitud a la que están las poblaciones?

**ACTIVIDAD2** (valor 3 puntos):

En un estudio se busca saber si existe una correlación significativa entre el número de especies de vertebrados en una isla y el área (km<sup>2</sup>) de la misma. Los datos que se tienen son los siguientes:

<TABLE>
<TR><TD># Especies</TD><TD>45</TD><TD>81</TD><TD>101</TD><TD>97</TD><TD>106</TD><TD>119</TD><TD>112</TD><TD>108</TD><TD>72</TD><TD>88</TD><TD>108</TD><TD>104</TD><TD>89</TD><TD>98</TD><TD>109</TD></TR>  
<TR><TD>Área</TD><TD>758674.2 554219.2</TD><TD>606520.4</TD><TD>424985.2</TD><TD>579379.1</TD><TD>425023.8</TD><TD>530630.3</TD><TD>631837.0</TD><TD>473345.9</TD><TD>526580.6</TD><TD>613983.9</TD><TD>401345.5</TD><TD>432633.3</TD><TD>309525.6</TD><TD>428207.8</TD></TR>  
</TABLE>

**ACTIVIDAD3** (valor 3 puntos):

Nos interesa saber si diferentes especies de coral se especializan en habitar a diferentes profundidades. Se registró la profundidad (m) a la que se encontraban individuos de cuatro especies de coral. Los datos son los siguientes:

Lophelia pertusa: 643.15 498.07 462.59 470.79 604.26 577.02 569.22 606.47 475.55 661.47 495.50 557.25 566.11 588.89

Oculina varicosa: 87.20  84.28 102.82  56.28  88.83  68.40  92.20  63.72  72.65  64.12  78.03 90.23  62.75  81.99  84.01  52.79  77.80  60.75  92.21  97.25  78.68

Acropora cervicornis: 39.10 16.43 46.93 28.57 23.80 31.70 16.13 28.46 28.84 14.67 30.57 18.13 6.96 22.19 28.77 27.18 17.71 22.14 37.44 33.78 11.64 23.55

Diploria labrynthiformis: 11.73  5.82 10.40  8.06 10.29  7.40 10.44 14.22 12.95  9.03  7.32  9.01  7.89 8.36  3.73 10.42 13.04

**ACTIVIDAD4** (valor 2 puntos):

Si en la actividad anterior mostraron que diferentes especies se especializan en habitar a diferentes profundidades, utilicen la prueba de Tukey para mostrar qué especies se encuentran significativamente a diferente profundidad de qué especies. La prueba de Tukey no reporta el estadístico de prueba, así que no es necesario que lo reporten. Calculen la media de profundidad a la que se encuentra cada especie y, de acuerdo a lo concluido en cada prueba, muestren el orden en que se observarían las especies a medida que se desciende en profundidad.