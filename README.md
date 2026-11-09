# Color Perception: Hues and Cues

Proyecto final de *Introducción a Python para Ciencia de Datos e IA*: análisis perceptual y limpieza de datos con las respuestas humanas del juego **Hues and Cues** (Alabau-Bosque et al., IPL – Universitat de València).

## Contenido

| Archivo | Descripción |
|---|---|
| `Ejercicio_Hues_and_Cues_Alumnos.ipynb` | Notebook con el análisis completo |
| `HC.csv` | 3.899 respuestas de 324 participantes |
| `board_color_categories.txt` | Mapeo de las 480 casillas del tablero a 8 categorías de color |

## Análisis

1. Ingesta y normalización de categorías con diccionarios (`.replace()`, `.map()`).
2. Perfil demográfico y filtrado de participantes con daltonismo (CVD).
3. Comparación de la percepción entre tricrómatas y daltónicos.
4. Anclas culturales (*TRACTOR*, *ESPERANZA*) y consenso semántico por categoría.
5. Visualización con Matplotlib y Seaborn, incluido un mapa del tablero con las casillas elegidas por los participantes.

## Ejecución

Crear un entorno virtual e instalar las dependencias de `requirements.txt`:

```bash
python -m venv .venv

# Activar el entorno
source .venv/bin/activate        # Linux / macOS
.venv\Scripts\Activate.ps1        # Windows (PowerShell)
source .venv/Scripts/activate    # Windows (Git Bash)

pip install -r requirements.txt
```

Abrir el notebook:

```bash
jupyter notebook Ejercicio_Hues_and_Cues_Alumnos.ipynb
```
