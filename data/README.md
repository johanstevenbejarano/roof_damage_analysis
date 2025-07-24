# 📁 Carpeta `data/`

Esta carpeta contiene referencias y descripciones sobre el dataset utilizado en el proyecto.

---

## 📦 Dataset principal

- Nombre: **troof-4**
- Fuente: [Roboflow](https://roboflow.com/)
- Contenido: imágenes aéreas anotadas con defectos en techos.

---

## 📥 Descarga

Los datos de entrenamiento y validación no se almacenan aquí directamente por peso y licencia. En su lugar, se descargan dinámicamente desde:

- Hugging Face: [jobejaranom/yolo-roof-damage](https://huggingface.co/JGuevara-12/yolo-roof-damage)
- Subcarpeta relevante: `train_inference/`

La descarga es gestionada mediante `snapshot_download()` desde los notebooks.

---

## 📌 Nota

Se recomienda no subir datasets completos al repositorio. Usa enlaces externos o descarga programática para mantener el repositorio ligero y escalable.

