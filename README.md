# Vision Transformer (ViT) desde cero + ViT preentrenado con timm

Este repositorio contiene una implementación **desde cero** de un Vision Transformer (ViT) usando PyTorch, junto con un segundo modelo basado en la implementación oficial de `timm`.  
Todo el entrenamiento se realiza sobre el dataset **MNIST**, cargado desde `fetch_openml`.

El código muestra:

- Cómo cargar MNIST manualmente desde OpenML.
- Cómo crear un `LightningDataModule`.
- Cómo preparar las imágenes correctamente para modelos de visión (formato **(B, 1, 28, 28)**).
- Implementación propia de:
  - Patch Embedding con convoluciones.
  - Multi-Head Self Attention.
  - Transformer Encoder Blocks.
  - Clasificador basado en el token `[CLS]`.
- Cómo entrenar un modelo con PyTorch Lightning.
- Comparación con el VisionTransformer de `timm`.
- Visualización y predicción sobre imágenes reales.

---

🧩 Requisitos

Antes de ejecutar el script, instala las dependencias:

pip install -r requirements.txt

🧑‍💻 Autor

Desarrollado por Gus como parte de su aprendizaje en Python e IA.
