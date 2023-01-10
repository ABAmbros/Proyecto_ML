![](https://github.com/ABAmbros/Proyecto_ML/blob/main/header.jpg)
# PROYECTO-ML-Spaceship Titanic
## **Competición de Kaggle: Spaceship Titanic**

## **DESCRIPCIÓN**

Bienvenido al año 2912, donde se necesitan tus habilidades de ciencia de datos para resolver un misterio cósmico. Hemos recibido una transmisión desde cuatro años luz de distancia y las cosas no pintan bien.

La nave espacial Titanic fue un transatlántico interestelar de pasajeros lanzado hace un mes. Con casi 13.000 pasajeros a bordo, la nave emprendió su viaje inaugural transportando emigrantes de nuestro sistema solar a tres exoplanetas recientemente habitables que orbitan estrellas cercanas.

Mientras rodeaba Alpha Centauri en ruta hacia su primer destino, el tórrido 55 Cancri E, la desprevenida nave espacial Titanic chocó con una anomalía del espacio-tiempo escondida dentro de una nube de polvo. Lamentablemente, tuvo un destino similar al de su homónimo de 1000 años antes. Aunque la nave permaneció intacta, ¡casi la mitad de los pasajeros fueron transportados a una dimensión alternativa

En esta competición, tu tarea es predecir si un pasajero fue transportado a una dimensión alternativa durante la colisión de la nave espacial Titanic con la anomalía del espacio-tiempo. Para ayudarlo a hacer estas predicciones, se le proporciona un conjunto de registros personales recuperados del sistema informático dañado de la nave.

___
## **Objetivo:**

El objetivo de este proyecto será predecir qué pasajeros de la nave interestelar Titanic fueron transportado a una dimensión alternativa cuando esta colisionó. Con lo único que contamos para hacer estas predicciones, es un conjunto de registros personales recuperados del sistema informático dañado del la nave. Estos están incompletos...dañados. Pues partiendo de estos datos que se nos proporcionan, debemos de ser capaces de hacer una predióccique pueda ayudar a las naves de rescate.

Aquí podrás encontrar diferentes modelos de machine learning y diferentes predicciones, se pueden consultar en el directorio "notebooks". Después de muchas pruebas nos quedaremos con el modelo que mejores resultados predictivos nos haya arrojado, para finalmente entregarle el modelo que mostraba las mejores métricas, a las tripulaciones de rescate. 

Este Repositorio cuenta con varios directorios. En el directorio "modelos" podrás encontrar los diferentes modelos de machine learning utilizados. En "notebooks" encontrarás el analisis exploratorio de los datos con los que contamos, como el procesamiento de estos. También podemos encontrar los diferentes gráficos generados del EDA en el directorio "img", como las diferentes submissions generadas en formato .csv en el directorio "SUBMISSIONS",  que a su vez se encuentra dentro del directorio "data".

## **Resumen de las Variables del dataset**

**PassengerId**: Se trata de una identificación única para cada pasajero. Cada Id toma la forma gggg_pp donde gggg indica el grupo con el que viaja el pasajero, y pp es su número dentro del grupo. Las personas en un grupo a menudo son miembros de la familia, pero no siempre.

**HomePlanet**: El planeta del que partió el pasajero, normalmente su planeta de residencia permanente.

**CryoSleep**: Indica si el pasajero eligió que se le ponga en 'animación suspendida' durante la duración del viaje. Los pasajeros en criosueño están confinados en sus cabinas.

**Cabin**: El número de cabina donde se hospeda el pasajero. Toma la forma deck/num/side, donde el lado puede ser 'P' para babor, o 'S' para estribor.

**Destination**: El planeta en el que desembarcará el pasajero.

**Age**: La edad del pasajero.

**VIP**: Si el pasajero ha pagado por un servicio VIP durante el viaje.

**RoomService, FoodCourt, ShoppingMall, Spa, VRDeck**: La cantidad que el pasajero ha facturado en cada uno de los muchos servicios de lujo del Spaceship Titanic.

**Name**: El nombre y apellido del pasajero.

**Transported**: Si el pasajero fue transportado a otra dimensión. Este es el target, la columna que trataremos de predecir.

## **Fuente**

https://www.kaggle.com/competitions/spaceship-titanic/overview
