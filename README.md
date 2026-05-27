# IR System - Embeddings Comparison

Sistema de recuperación de información que compara dos modelos de embeddings semánticos en un corpus de 5000 reseñas de películas (Rotten Tomatoes).

## Características

- **Modelo 1**: `all-MiniLM-L6-v2` (384 dim, rápido)
- **Modelo 2**: `all-mpnet-base-v2` (768 dim, preciso)
- Búsqueda por similitud coseno
- Visualización PCA de embeddings
- 8 consultas benchmark sobre géneros y atributos cinematográficos
