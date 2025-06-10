# Modelos
Modelo Hate Speech:
1. Una vez descargado el dataset HASOC 2019, debe ser almacenado en la carpeta ModeloHS\Preprocesamiento.
2. Se debe ejecutar el código preprocesamiento.py.
3. Se generará un archivo del dataset HASOC 2019 limpio.
4. En la carpeta ModeloHS\EmbeddingsHS se debe ejecutar el código embeddingsHS.py.
5. Se generará un archivo .h5 en la misma carpeta
6. En la carpeta ModeloHS, ejecutar entrenarHS.
7. Se generará el modelo.
Nota: En el código entrenarHS se obtienen los 8 experimentos del modelo.


Modelo Rumor Detection:
1. En la carpeta ModeloRD\PreprocesamientoRD\Dataset original se debe dejar el dataset PHEME.
2. En la carpeta ModeloRD\PreprocesamientoRD se debe ejecutar preprocesamientoRD.py.
3. Se generarán los archivos preprocesados del conjunto de datos en ModeloRD\PreprocesamientoRD\Archivos preprocesados.
4. En la carpeta ModeloRD\EmbeddingsRD se debe ejecutar el archivo embeddingsRD.py
5. Se generará un archivo .h5 para el embedding.
6. En la carpeta ModeloRD se debe ejecutar entrenamientoRD2.py
7. Se generará el modelo de Rumor Detection.
Nota: Si se quiere ejecutar un experimento en específico, se debe comentar los  que no se quieran generar.

![image](https://github.com/user-attachments/assets/1b0c1e78-fb9c-4c1b-a182-97fe6ff91fc6)

Hate Speech + Rumor Detection:
1. En  la carpeta ModeloRDHS se debe ejecutar el código modeloRDHS4.py.
2. Se generará el o los modelos correspondientes.
