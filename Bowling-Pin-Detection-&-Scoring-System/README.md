# 🎳 Bowling Pin Detection & Scoring System

# 📌 Versión en Español

Desarrollé un sistema de visión computacional para la detección y conteo automático de pinos de boliche a partir de imágenes con perspectiva cenital, simulando un sistema de puntuación en tiempo real.

El sistema aplica técnicas de procesamiento de imagen para aislar las regiones relevantes, identificar contornos circulares correspondientes a las cabezas de los pinos y calcular el puntaje por ronda. Además, permite simular partidas de múltiples rondas, generar un marcador para dos jugadores y determinar posiciones finales.

Características principales

Detección y conteo automático de pinos

Análisis de contornos para reconocimiento de objetos circulares

Sistema de puntuación por rondas

Seguimiento de puntajes para múltiples jugadores

Determinación de ganador y perdedor

Flujo de trabajo

Carga aleatoria de imágenes

Conversión a escala de grises y reducción de ruido

Segmentación por color mediante umbralización

Extracción de contornos con OpenCV

Conteo de pinos y cálculo de puntajes

Simulación de partidas multironda

Tecnologías

Python

OpenCV

NumPy

Matplotlib

Notas

Este proyecto es una simulación basada en imágenes estáticas. El rendimiento depende de factores como iluminación y calidad de imagen.

# 📌 English Version

Developed a computer vision system for automatic detection and counting of bowling pins from top-down images, simulating a real-time scoring system.

The solution applies image processing techniques to isolate relevant regions, detect circular contours corresponding to pin heads, and compute round-based scores. It also supports multi-round simulations, generates a two-player scoreboard, and determines final rankings.

Key Features

Automatic bowling pin detection and counting

Circular contour analysis for object recognition

Round-based scoring system

Multi-player score tracking

Winner and loser determination

Workflow

Random image loading

Grayscale conversion and noise reduction

Color-based threshold segmentation

Contour extraction using OpenCV

Pin counting and score computation

Multi-round game simulation

Technologies

Python

OpenCV

NumPy

Matplotlib

Notes

This project is a simulation based on static images. Performance may vary depending on lighting conditions and image quality.
