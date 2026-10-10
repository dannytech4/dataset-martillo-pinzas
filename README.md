# dataset-martillo-pinzas

Dataset de detección de objetos con dos clases: `martillo` (0) y `pinzas` (1). Tiene 38 imágenes y 47 cajas anotadas en CVAT.

## Contenido

- `images/`: las 38 imágenes (`img_001.jpg` … `img_038.jpg`).
- `anotaciones_v3/`: export de CVAT en formato YOLO 1.1, con un `.txt` de etiquetas por imagen en `obj_train_data/`.
- `fuentes.csv`: origen y licencia de cada imagen (Pexels, Pixabay y Unsplash).
- `_revision/`: imágenes con las cajas dibujadas.