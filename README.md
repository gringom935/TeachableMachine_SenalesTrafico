# TeachableMachine_SeñalesTrafico

### Comenzando :rocket:

Lo primero que debes hacer es clonarte el repositorio y abrirlo con el editor que prefieras.

Partiendo de que el proyecto es de python, debemos tener instalado python en el editor web o local que vayamos a usar.

### Pre-requisitos :memo:

Instalar keras, tensorflow, pillow:

	$ pip install keras
	$ pip install tensorflow
	$ pip install pillow

### Pruebas :building_construction:

En el archivo SenalesTrafico.py, vamos a la línea de código número 13, debemos sustituir el texto "tu-imagen.jpg" por una imagen real de extensión .jpg de una señal de tráfico que queramos identificar.

Además, debemos añadir la imagen a la carpeta donde esté nuestro proyecto para que se pueda identificar.

Después guardaremos el archivo .py y ejecutaremos el siguiente comando:

	$ python SenalesTrafico.py

Nos debe devolver como respuesta el resultado de la predicción con el tipo de señal que estamos intoduciendo.

Nota: Podemos modificar el proyecto a nuestro gusto para que recorra un conjunto de imágenes o crear un servicio web desde el cuál importar imágenes.

### Construido con :construction_worker:

- Teachable Machine
- Python
- Tensorflow
- Keras
- Pillow

