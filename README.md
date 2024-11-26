# Proyecto de Comparación de Algoritmos de Reemplazo de Páginas: FIFO, LRU y Modelo Predictivo

Este proyecto tiene como objetivo comparar el rendimiento de los algoritmos de reemplazo de páginas **FIFO (First-In-First-Out)**, **LRU (Least Recently Used)** y un **modelo predictivo** basado en **Random Forest** para predecir los fallos de página en sistemas de gestión de memoria.

El proyecto genera un conjunto de datos simulado de accesos a páginas de memoria y luego compara cómo cada algoritmo maneja estos accesos en función de distintos tamaños de marcos de memoria.

## Algoritmos Implementados

1. **FIFO (First-In-First-Out)**: Este algoritmo reemplaza la página más antigua en memoria.
2. **LRU (Least Recently Used)**: Este algoritmo reemplaza la página menos recientemente usada.
3. **Modelo Predictivo**: Un modelo de clasificación basado en **Random Forest** que predice qué página será reemplazada en base a características como la frecuencia de acceso y el tiempo desde el último acceso.

## Requisitos

Asegúrate de tener instalados los siguientes paquetes para ejecutar el proyecto:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
