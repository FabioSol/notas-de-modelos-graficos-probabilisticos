---
title: "Introducción al curso"
date: 2026-01-19
draft: false
type: "document"
description: "Introducción al curso de Modelos Gráficos Probabilísticos"
showDescription: false
weight: 3
---

## ¿Qué son los Modelos Gráficos Probabilísticos?

Los **Modelos Gráficos Probabilísticos (MGP)** combinan tres componentes fundamentales:

- **Modelos**: Representación declarativa de nuestro entendimiento del mundo. El modelo captura variables y sus interacciones de forma independiente del algoritmo usado.

- **Probabilísticos**: Marco formal para manejar incertidumbre mediante teoría de la probabilidad, permitiendo razonar con nueva información, tomar decisiones bajo incertidumbre y aprender desde datos.

- **Gráficos**: Estructuras que manejan complejidad mediante grafos (nodos = variables aleatorias, aristas = dependencias probabilísticas), permitiendo representar sistemas complejos de forma modular y visual.

Como señala Michael I. Jordan (1998), los MGP son "un matrimonio entre teoría de probabilidad y teoría de grafos", proporcionando herramientas para manejar incertidumbre y complejidad mediante modularidad.

## ¿Por qué aprender MGP?

Los MGP abordan problemas que no son fáciles de resolver con modelos tradicionales de machine learning porque **separan el modelo del algoritmo**, permitiendo:

### Formular distintas preguntas sobre el mismo modelo:
- Diagnóstico: $P(\text{Enfermedad} | \text{Síntomas})$
- Predicción: $P(\text{Síntomas} | \text{Enfermedad})$
- Completado de datos faltantes: $P(X_i|X_{-i})$
- Detección de anomalías

### Elegir distintos algoritmos según necesidad:
- Inferencia exacta o aproximada
- Algoritmos rápidos vs. precisos

### Diseñar modelos interpretables y modulares

Esta separación convierte a los MGP en un **marco de razonamiento general bajo incertidumbre**, no solo una herramienta específica.

## Tres pilares de los MGP

Según Daphne Koller y Nir Friedman:

### I. Representación
Usar estructura gráfica para capturar dependencias entre variables. El grafo es declarativo, transparente, inspeccionable e independiente del algoritmo.

### II. Inferencia
Aplicar algoritmos sobre el modelo para responder preguntas usando la estructura gráfica eficientemente. Pueden ser exactos (eliminación de variables, propagación de creencias) o aproximados (muestreo, variacional).

### III. Aprendizaje
Construir el modelo automáticamente desde datos: estimar parámetros, aprender estructura del grafo. Combina conocimiento experto con información empírica.

## Objetivos del curso

### Objetivo general
Comprender los modelos gráficos probabilísticos y sus aplicaciones en análisis de datos, inferencia estadística y toma de decisiones bajo incertidumbre mediante la construcción, análisis y aplicación de modelos como redes bayesianas y redes de Markov.

### Objetivos particulares
- Modelar situaciones reales mediante grafos probabilísticos
- Responder preguntas prácticas usando algoritmos de inferencia
- Estimar parámetros y/o estructura de modelos usando técnicas de optimización

## Prerrequisitos
- Probabilidad y Estadística 
- Programación en Python 
- Optimización Convexa 
- Análisis Estadístico Multivariado 

## Referencias
- Koller, D., & Friedman, N. (2009). *Probabilistic Graphical Models: Principles and Techniques*. MIT Press.
- Jordan, M. I. (1998). *Learning in Graphical Models*. NATO Science Series D: Behavioural and Social Sciences vol. 89. Springer.

