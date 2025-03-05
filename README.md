# Deteccion-de-emociones
El sitio web se titula "Detección de Emociones en Tiempo Real" y esta diseñado para capturar video en vivo desde la cámara del usuario, analizar la emoción detectada y mostrar la confianza del modelo en la detección.
El notebook de deteccion de emociones esta enfocado en entrenar y utilizar un modelo de detección de emociones basado en Machine Learning. 
Funcionalidades Principales
- Carga de datos desde Kaggle (FER2013, un dataset de emociones faciales).
- Procesamiento de imágenes (detección y recorte de rostros con dlib y opencv).
- Uso de modelos de deep learning (YOLO, EfficientNet y PyTorch).
- Entrenamiento y prueba de un modelo de detección de emociones.

El sitio web captura imágenes desde la cámara usando canvas.toBlob(), esto es enviado al backend
El backend en Python (detectado por la carpeta .venv) usa este modelo para procesar imágenes enviadas desde la interfaz web.

Nota: Para ejecutar el sitio web se debe instalar el entorno virtual (.venv) en el bakckend y ejecutar lo siguiente en la terminal 
PS C:\---\---\---\Sitio Web> .\.venv\Scripts\activate.bat
                 \Sitio Web> Set-ExecutionPolicy Unrestricted -Scope Process
                 \Sitio Web> cd backend
                 \Sitio Web> uvicorn backend:app --host 127.0.0.1 --port 8000 --reload
Finalmente ejecutar index.html 
