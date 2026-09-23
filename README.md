# Sistemas Inteligentes 1

Repositorio correspondiente a la actividad de la asignatura sistemas inteligentes 1.

## Integrantes

- Michel Dahiana Arenas Lopez
- Danna Alexandra Madrid Roa

## Descripción

Se implementan algoritmos de búsqueda no informada, búsqueda informada y búsqueda adversarial.

El trabajo analiza el funcionamiento, complejidad, comportamiento experimental
y diferencias entre los algoritmos estudiados.

## Notebooks incluidos

### 01. Búsqueda no informada: BFS y DFS

Implementación y comparación de Breadth-First Search y Depth-First Search
sobre problemas representados mediante grafos.

### 02. Búsqueda informada

Implementación de algoritmos de búsqueda informada, incluyendo A* y una
comparación basada en el uso de heurísticas.

### 03. Búsqueda adversarial: Minimax

Implementación del algoritmo Minimax para seleccionar acciones en un juego
entre dos agentes racionales.

### 04. Búsqueda adversarial: poda Alfa-Beta

Implementación de la poda Alfa-Beta y comparación con Minimax en términos de
estados evaluados y tiempo de ejecución.

## Requisitos

- Python 3.10 o superior.
- Jupyter Notebook o JupyterLab.
- matplotlib.

Las demás librerías utilizadas pertenecen a la biblioteca estándar de Python.

## Instalación

Clonar el repositorio:

```bash
git clone
cd Inteligencia_Artificial_1
```

Crear y activar el entorno virtual
```bash
python -m venv .venv
```
Instalar las dependencias
```bash
pip install -r requirements.txt
```
## Ejecución 
Iniciar Jupyter:
```bash
jupyter notebook
```

Abrir la carpeta notebooks/ y ejecutar los archivos en orden.

Se recomienda utilizar la opción Restart Kernel and Run All para comprobar
que cada notebook funciona desde cero y que los resultados son reproducibles.

## Organización del repositorio
- notebooks/: notebooks de la actividad.
- resultados/: gráficas o tablas exportadas.
- requirements.txt: dependencias del proyecto