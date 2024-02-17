# Shark_Project
Shark Attack CSV para mi primer proyecto en Python.
![aviso-ataque-tirubon-california](https://github.com/19972024/Shark_Project/assets/156945446/c02248bf-c10a-4d3d-ae21-6fa0cd5aebe3)

INTRODUCCION:

Gracias a los datos obtenidos del conjunto de datos attacks.csv, obtuvimos información valiosa sobre distintos temas. Tras comprender y depurar este conjunto de datos, estas son mis hipótesis relacionadas con este tema:
HIPOTESIS 1: Es la actividad con mas casos la mas fatal?

Para responder a esto se tuvo en cuenta diferentes analisis comparando si la actividad con mas casos de ataque era la mas fatal
![Cantidad de casos fatales y no fatales por actividad](https://github.com/19972024/Shark_Project/assets/156945446/c120c1e0-dc3f-42ef-ac85-aeaf8259c236)

Aqui vemos en este plot como la actividad Surfing es la que tuvo mas casos, pero en comparacion con las otras actividades se ve claramente como es la que menos casos fatales tuvo. Esto nos llevo a descubrir que la actividad mas fatal es la de Swimming, no solo eso sino que por sorpresa la seguna actividad mas fatal es la de Fishing, lo extraño de esto es que en esta actividad las personas no se encuentran en contacto directo con el agua.

![Swarmplot Cantidad de casos fatales y no fatales por actividad](https://github.com/19972024/Shark_Project/assets/156945446/6cd5830f-39dc-4631-9292-cf432ee27ca0)

Siguiendo lo descrito, en este grafico (Swarmplot) se llega a ver como la diferencia de colores hace notar que la actividad con mas victimas fatales es la de Swimming y como la que menos victimas fatales tiene es la de Surfing.

![boxplot](https://github.com/19972024/Shark_Project/assets/156945446/d2dce60d-b3cb-4f4b-b7a0-ada98c70c63d)


La caja del boxplot representa el 50% de los datos que hay en la columna nombrada. La línea dentro de la caja representa la mediana de los datos, es decir, en este caso la mediana de mas victimas fatales estuvo entre aproximadamente el año 1920 y el año 1990. En Los bigotes se extienden los casos entre el 1820 y el 2018. Los puntos fuera de los bigotes se consideran valores atípicos o extremos. Es curioso que hay datos atipicos de una victima fatal con registro entre el año 1400 y 1550 aproximadamente.

En conclusion, podemos decir que hay varias cosas que nos sorprendieron, la dicha antes que la actividad Fishing sea la segunda con mas casos mortales, que la actividad Swimming tenga el doble de victimas fatales que la actividad Diving, siendo casi lo mismo, esto querra decir que uno es mas susceptible a morir por un ataque de tiburon si esta nadando en la superficie o cerca de la costa, que nadando en las profundidades directamente con ellos. Y para finalizar ver como desde el año 2000 en adelante han bajado significativamente los casos, esto porque?, Medidad de prevencion?, Pesca descontrolada?, Influye el calentamiento global y los tiburones cambian de area? en fin muchas preguntas, pocas respuestas.

HIPOTESIS 2: Es el pais con mas casos el que mas victimas fatales tiene?

Para responder a esto se tuvo en cuenta diferentes analisis comparando los diferentes paises y sus victimas fatales.

![Cantidad de casos fatales y no fatales por pais](https://github.com/19972024/Shark_Project/assets/156945446/88fa4fa9-5bd9-421c-98e3-e4b20b3cc30a)



