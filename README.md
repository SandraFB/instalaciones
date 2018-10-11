# Verificación de instalación

## Probablemente te preguntes ¿Cómo puedes comprobar que tu instalación es correcta? 

1. Vamos a generar otro entorno virtual para OpenCV2 (el cual ocuparemos para la práctica de calibración durante el curso). 

Desde Anaconda, escribe las siguientes líneas de código:


conda create -n py27 python=2.7 anaconda

activate py27

conda install -c https://conda.anaconda.org/conda-forge opencv

jupyter notebook


![Jupyter](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen5.jpg)



2. Ahora, desde Jupyter Notebook, crearemos un nuevo documento:


![Nuevo](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen3.jpg)


![Nuevo Notebook](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen6.jpg)


3. Importamos librerías escribiendo el siguiente código en el Notebook creado y ejecutamos:

import numpy as np

import cv2

import glob

import matplotlib.pyplot as plt

import pickle

%matplotlib inline

%matplotlib qt

Nota: Estas líneas de código importan las librerías mencionadas. Si no te marca error, has instalado correctamente las librerías.

cv2.__version__ 

Nota: Esta línea de código imprime la versión de OpenCV instalada. Si no te marca error, has instalado correctamente OpenCV.


![Notebook](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen7.jpg)


![Código](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen8.jpg)


4. Prácticas en Python

A forma de taller introductorio para Python, puedes ejecutar las prácticas 1, 2 y 3 en Jupyter Notebook.

Primero selecciona la práctica a realizar y abre el enlace.


![Selección](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen9.jpg)


Después, ejecuta el código línea por línea y observa el resultado.


![Ejecución](https://github.com/SandraFB/CursoPDI-CICATA2018/blob/master/PruebaInstalacion/imagen10.jpg)



## Referencias

1. Python 3.6 documentation.
