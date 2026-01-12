# OCR – Proyecto Final de Inteligencia Artificial
## 📁 Material del proyecto

| Recurso | Descripción | Enlace |
|-------|------------|--------|
| 🎥 Vídeo de resolución | Grabación del funcionamiento del sistema OCR, mostrando las pruebas realizadas y los resultados obtenidos durante el examen | [Ver vídeo en Google Drive](https://drive.google.com/drive/folders/1700S_NUAnzKa2Q-uFHbkE_vKFUQcRyFk?usp=drive_link) |


Este proyecto consiste en el desarrollo de un sistema de Reconocimiento Óptico de Caracteres (OCR) implementado desde cero, como trabajo final de la asignatura **Inteligencia Artificial** del Grado en Ingeniería Informática.

El objetivo principal del proyecto ha sido transformar texto contenido en imágenes en texto digital, sin utilizar librerías externas que ya resuelvan directamente el problema (como Tesseract OCR), afrontando manualmente todas las etapas del proceso.

## Características principales

- Reconocimiento de **texto impreso**, con buenos resultados en imágenes de alta calidad.
- Reconocimiento de **caracteres manuscritos aislados** mediante comparación con plantillas.
- Preprocesado de imágenes que incluye:
  - Conversión a escala de grises
  - Mejora de contraste
  - Reducción de ruido
  - Binarización automática
- Segmentación de caracteres basada en contornos.
- Normalización de cada carácter antes del reconocimiento.
- Cálculo de una **medida de confianza** asociada al texto reconocido.

## Limitaciones

- Dificultad para distinguir caracteres morfológicamente similares (por ejemplo: `l`, `I`, `i`, `1`, `7`).
- Reconocimiento manuscrito limitado a **caracteres aislados**.
- Escritura manuscrita continua o cursiva fuera del alcance del sistema.
- Sensibilidad a la calidad de la imagen y al tipo de tipografía.

Estas limitaciones son inherentes al enfoque basado en plantillas utilizado y han sido analizadas y justificadas en la memoria del proyecto.

## Conclusión

El proyecto permite comprender en profundidad el funcionamiento y las limitaciones reales de los sistemas OCR clásicos. Más allá de los resultados obtenidos, el mayor valor del trabajo ha sido el proceso de análisis, prueba y ajuste continuo, así como la justificación técnica de las decisiones adoptadas.

