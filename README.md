# Clasificación de Plantas Usando TF.
Proyecto de clasificación de imágenes para identificar 22 clases de hojas de plantas (sanas y enfermas de 12 especies) utilizando *Transfer Learning* con *MobileNetV2*.
Entrenado en clúster de supercómputo y desplegado como aplicación web con TensorFlow.js y Github Pages.

- [Artículo en Medium](https://medium.com/@dawedqueen/clasificaci%C3%B3n-de-enfermedades-en-hojas-de-plantas-usando-redes-neuronales-convolucionales-y-668fa462bbbe)

## Cómo ejecutar el entrenamiento
``
pip install -r requirements.txt
python main.py
``
El script guarda el modelo entrenado y genera en ``resultados/`` las gráficas de entrenamiento, muestras de prueba y la matriz de confusión.
## Probar la aplicación web localmente
``
python3 -m http.server 8000
``
Abre ``http://localhost:8000/index.html`` en tu navegador para acceder.
