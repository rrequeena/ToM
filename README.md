# Proyecto ToM: Tomatoes Monitor
<img src="https://github.com/rrequeena/ToM/blob/main/ToM-logo2.jpg?raw=true"
     alt="Markdown Monster icon"
     style="width: 1000px !important;" />
     
Un proyecto que nace en la comunidad de Saturdays.AI Quito como parte del evento realizado en el año 2021. El cual consiste en crear un monitor de la etápa de madurez en los tomates utilizando visión artificial y transfer learning. 

Se utilizó la API de object detection de Tensorflow, haciendo uso de esta se dió información a un modelo preentrenado para que pueda reconocer los tomates en sus distintas etapas, el objetivo del proyecto es ayudar en la etapa de producción de los tomates a reducir los desperdicios utilizando inteligencia artificial para el reconocimiento de los tomates y así los productores puedan sacar sus productos a tiempo para su venta y que no se pase de la etapa óptima para su transporte y venta.
## Datos utilizados
Para desarrollar el proyecto se utilizó una base de datos libre en mendeley la cual contiene más de 1000 imágenes en alta resolución sobre tomates en su etápa de flor, verde y en su etapa de madurez más alta que es cuando se tornan a su color rojizo característico. La base de datos se puede encontrar en el siguiente [link](https://data.mendeley.com/datasets/9zyvdgp83m/1)

## Video Demostración
El video a continuación muestra el resultado del modelo ya entrenada, y la aplicación está disponible para hacer las pruebas en el siguiente URL: https://share.streamlit.io/rrequeena/tom-base-app/app.py

https://user-images.githubusercontent.com/64110737/141595508-73fe9d9f-d17b-420f-b4ed-16f545d3ccbe.mp4

## Archivos en el repositorio
En este repositorio se encuentran varios archivos que fueron utilizados para el desarrollo y el demoDay realizado al final del evento de Saturdays.AI Quito.
### Image Labelling.ipynb
Es el notebook donde se encuentra el código para realizar el etiquetado de las imágenes y obtener su metadata en archivos .xml y así pasarlos al modelo.
### Proyecto_ToM.ipynb
En este notebook se encuentra el código utilizado para el entramiento del modelo con las imágenes recopiladas de la base de datos redactada anteriormente.
### Adicionales
Adicionalmente también se encuentra el archivo utilizado para la presentación del DemoDay.

### Nota:
Hoy en día se pueden entrenar modelos con tensorflow y utilizarlos en [microcontroladores](https://microcontroladoress.com) de bajo consumo, con lo cual se puede crear proyectos cómo el del repositorio e implementarlos en estos dispositivos.

