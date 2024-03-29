# Shark_Project

![aviso-ataque-tirubon-california](https://github.com/19972024/Shark_Project/assets/156945446/c02248bf-c10a-4d3d-ae21-6fa0cd5aebe3)

INTRODUCCION:

Gracias a los datos obtenidos del conjunto de datos attacks.csv, obtuvimos información valiosa sobre distintos temas. Tras comprender y depurar este conjunto de datos, estas son mis hipótesis:

HIPOTESIS 1: Es la actividad con mas casos la mas fatal?

Para responder a esto se tuvo en cuenta diferentes analisis comparando si la actividad con mas casos de ataque era la mas fatal
![Cantidad de casos fatales y no fatales por actividad](https://github.com/19972024/Shark_Project/assets/156945446/c120c1e0-dc3f-42ef-ac85-aeaf8259c236)

Aqui vemos en este plot como la actividad Surfing es la que tuvo mas casos, en comparacion con las otras actividades se ve claramente como es la que menos casos fatales tuvo. Esto nos llevo a descubrir que la actividad mas fatal es la de Swimming, no solo eso sino que por sorpresa la seguna actividad mas fatal es la de Fishing, lo extraño de esto es que en esta actividad las personas no se encuentran en contacto directo con el agua.

![Swarmplot Cantidad de casos fatales y no fatales por actividad](https://github.com/19972024/Shark_Project/assets/156945446/6cd5830f-39dc-4631-9292-cf432ee27ca0)

Siguiendo lo descrito, en este grafico (Swarmplot) se llega a ver como la diferencia de colores hace notar que la actividad con mas victimas fatales es la de Swimming y como la que menos victimas fatales tiene es la de Surfing.

![Captura de pantalla 2024-02-17 145143](https://github.com/19972024/Shark_Project/assets/156945446/b0e3209f-6e2d-4727-8a75-96b545057e64)



La caja del boxplot representa el 50% de los datos que hay en la columna nombrada. La línea dentro de la caja representa la mediana de los datos, es decir, en este caso la mediana de mas victimas fatales estuvo entre aproximadamente el año 1920 y el año 1990. En Los bigotes se extienden los casos entre el 1820 y el 2018. Los puntos fuera de los bigotes se consideran valores atípicos o extremos. Es curioso que hay datos atipicos de una victima fatal con registro entre el año 1400 y 1550 aproximadamente.

EN CONCLUSION: podemos decir que hay varias cosas que nos sorprendieron, la dicha antes que la actividad Fishing sea la segunda con mas casos mortales, que la actividad Swimming tenga el doble de victimas fatales que la actividad Diving, siendo casi lo mismo, esto querra decir que uno es mas susceptible a morir por un ataque de tiburon si esta nadando en la superficie o cerca de la costa, que nadando en las profundidades directamente con ellos. Y para finalizar ver como desde el año 2000 en adelante han bajado significativamente los casos, esto porque?, Medidas de prevencion?, Pesca descontrolada?, Influye el calentamiento global y los tiburones cambian de area? en fin muchas preguntas, pocas respuestas.

HIPOTESIS 2: En base a la cantidad de victimas fatales es el pais con mas casos el que mas victimas fatales tiene?

Para responder a esto se tuvo en cuenta diferentes analisis comparando los diferentes paises y sus victimas fatales.

![Top 10 Cantidad de casos fatales y no fatales por actividad](https://github.com/19972024/Shark_Project/assets/156945446/b0cb0462-5986-47ce-892f-665076fafa17)

Aqui vemos un plot donde grafica los 10 paises con mas casos registrados, la pregunta es, es USA en proporcion el pais con mas victimas fatales?, Lo descubriremos...

![Cantidad de casos fatales y no fatales por pais](https://github.com/19972024/Shark_Project/assets/156945446/88fa4fa9-5bd9-421c-98e3-e4b20b3cc30a)

En esta serie de graficos de torta podemos ver como son los porcentajes de victimas fatales y no fatales en los diferentes paises, sorprendentemente arrojo resultados muy particulares, ya que se ve en algunos paises como Papua Nueva Guinea si uno es atacado por un tiburon tiene casi el 50% de posibilidades de morir, mas si a uno le sucede esto en Mexico, es verdad que la cantidad de casos es mucho menor a la de otros paises, pero en Usa por ejemplo la cantidad de victimas fatales es infima en comparacion de las victimas no fatales.

EN CONCLUSION: Analizando los diferentes graficos podemos ver que aqui tambien se desmiente esta posibilidad como en la hipotesis 1 ya que USA que es el pais con mas casos podemos decir que en comparacion a los demas paises es el que menos victimas fatales tiene. Entre otras cosas podemos decir tambien que casi la mitad de personas son atacadas en Brazil, Mexico y Papua mueren. Tambien como Estados Unidos y Bahamas son los unicos paises que sus victimas fatales no superan el 10%. Sorprenden algunos casos como Italia ya que en el Mediterraneo la existencia de tiburones es muy escasa o de especies nada agresivas ni de gran tamaño.

![istockphoto-1267653808-1024x1024](https://github.com/19972024/Shark_Project/assets/156945446/51eb9d3f-1fbe-4fed-a258-fa1597461b6d)

HIPOTESIS 3: Siguiendo con las actividades en los diferentes paises, hay alguna actividad que sea en comparacion mas fatal que no letal?

Proporción de casos fatales y no fatales en USA
![Actividad_fatal_no_fatal_por_paisUSA](https://github.com/19972024/Shark_Project/assets/156945446/12db84a5-d7a7-4b56-bdde-e25b71abe58e)

Proporción de casos fatales y no fatales en AUSTRALIA
![Actividad_fatal_no_fatal_por_paisAUSTRALIA](https://github.com/19972024/Shark_Project/assets/156945446/964b7954-c944-4a67-8011-afede07b27a3)

Proporción de casos fatales y no fatales en SUDAFRICA
![Actividad_fatal_no_fatal_por_paisSOUTH AFRICA](https://github.com/19972024/Shark_Project/assets/156945446/fda1ffaf-ff5c-461f-9b02-0746a7007b23)

Proporción de casos fatales y no fatales en BRAZIL
![Actividad_fatal_no_fatal_por_paisBRAZIL](https://github.com/19972024/Shark_Project/assets/156945446/5c6d0a3f-396a-46a4-b312-3d5ec2b7dfef)

Proporción de casos fatales y no fatales en PAPUA NUEVA GUINEA
![Actividad_fatal_no_fatal_por_paisPAPUA NEW GUINEA](https://github.com/19972024/Shark_Project/assets/156945446/47ea8388-eac2-4a2c-8188-c2698d84a3e9)

Proporción de casos fatales y no fatales en NUEVA ZELANDA
![Actividad_fatal_no_fatal_por_paisNEW ZEALAND](https://github.com/19972024/Shark_Project/assets/156945446/77de2f5f-4005-48a4-aec5-890ad314eccc)

Proporción de casos fatales y no fatales en BAHAMAS
![Actividad_fatal_no_fatal_por_paisBAHAMAS](https://github.com/19972024/Shark_Project/assets/156945446/ee06d63e-38c8-48a9-aaae-949fa58bb62b)

Proporción de casos fatales y no fatales en MEXICO
![Actividad_fatal_no_fatal_por_paisMEXICO](https://github.com/19972024/Shark_Project/assets/156945446/140dabc1-6ca1-4014-b682-7b5885cd1c5e)

Proporción de casos fatales y no fatales en ITALIA
![Actividad_fatal_no_fatal_por_paisITALY](https://github.com/19972024/Shark_Project/assets/156945446/5a42d8c7-6fad-49b9-b3a7-545ce6b7d45a)

Proporción de casos fatales y no fatales en FIJI
![Actividad_fatal_no_fatal_por_paisFIJI](https://github.com/19972024/Shark_Project/assets/156945446/416cfd56-e7ef-46f8-a4ea-3593b724e004)

Proporción de casos fatales y no fatales en NUEVA CALEDONIA
![Actividad_fatal_no_fatal_por_paisNEW CALEDONIA](https://github.com/19972024/Shark_Project/assets/156945446/db1cf21d-176a-41a3-b5c2-0a1eb10044e3)

Proporción de casos fatales y no fatales en REUNION
![Actividad_fatal_no_fatal_por_paisREUNION](https://github.com/19972024/Shark_Project/assets/156945446/265b177b-4b2a-4733-940d-bc6cd46f3feb)


Despues de varios analisis podemos ver diferentes cosas muy interesantes que dividiremos por pais:

En Usa podemos ver que las victimas fatales son muy pocas y la unica variable que se nota un poquito es la de Swimming, sorprende tambien la cantidad de casos en la actividad Surfing y las pocas vicitmas fatales que hay.

En Australia sorprende que casi la mitad de los ataques a nadadores es fatal, aqui la variable mas alta de no fatal es la de fishing.

En Sudafrica pasa lo mismo que en Australia.

En Brazil pasa lo mismo que los anteriores lo que empieza a demostrar en las hipotesis anteriores que la actividad mas susceptible a tener victimas fatales es la de Swimming.

En Papua al contrario se lleva muchas victimas fatales la actividad fishing y 0 victimas la actividad Surfing.

En Nueva Zelanda vemos lo mismo que en Australia, Sud Africa.

En Bahamas vemos que es muy dificil morir si se es atacado por un tiburon es el primer pais que no tiene victimas por surfing y sorprende que no tenga victimas por la actividad con mas muertes que es Swimming.

En Mexico la cosa es bastante interesante ya que casi todas las variables estan al 50% entre victimas fatales y no. Sorprende tambien que es el unico pais que tiene una variable mas mortal que no mortal y esa es la de Diving.

En Italia parecido a Australia solo que aqui tambien es el unico pais que tiene una variable mas mortal que no mortal y esa es la de Swimming.

En Fiji la variable Diving se lleva la atencion ya que tiene casi el 40% de victimas fatales, como sorprende tambien las 0 en surfing.

En Nueva Caledonia no hay sorpresas pero en Reunion si ya que en este archipielago Frances si Eres atacado por un tiburon mientras nada las probabilidades de morir son del 100%.

FINAL:
Tengo que decir que para ser mi primer proyecto quede con mas preguntas que certezas ya que las hipotesis planteadas me dejaron con muchas mas preguntas de las que empeze.., En fin espero este analisis haya sido interesante.
Saludos!!!
