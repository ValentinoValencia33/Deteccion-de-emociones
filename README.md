# Deteccion-de-emociones
# El sitio web se titula "Detección de Emociones en Tiempo Real" y esta diseñado para capturar video en vivo desde la cámara del usuario, analizar la emoción detectada y mostrar la confianza del modelo en la detección.
# El notebook de deteccion de emociones esta enfocado en entrenar y utilizar un modelo de detección de emociones basado en Machine Learning. 
# Funcionalidades Principales
#🔹 Carga de datos desde Kaggle (FER2013, un dataset de emociones faciales).
#🔹 Procesamiento de imágenes (detección y recorte de rostros con dlib y opencv).
#🔹 Uso de modelos de deep learning (YOLO, EfficientNet y PyTorch).
#🔹 Entrenamiento y prueba de un modelo de detección de emociones.

# El sitio web captura imágenes desde la cámara usando canvas.toBlob(), lo que sugiere que las imágenes son enviadas a un backend.
# El notebook entrena un modelo de detección de emociones, que probablemente es el que usa el backend del sitio web.
# El backend en Python (detectado por la carpeta .venv) podría estar usando este modelo para procesar imágenes enviadas desde la interfaz web.
