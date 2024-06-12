# Extraction_Methods_OpenCV

Este repositorio contiene la implementación de un proyecto en C++ utilizando OpenCV para la detección de objetos en imágenes. El proyecto emplea diferentes métodos de extracción de características para localizar y reconocer objetos específicos dentro de imágenes más amplias.

## Contenido

1. [Abstract](#abstract)
2. [Tecnologías Utilizadas](#Tecnologías_Utilizadas)
3. [Implementación](#Implementación)
4. [Referencias](#Referencias)

## Abstract
La detección de objetos en imágenes es una tarea fundamental en el campo de la visión por computadora. Este proyecto utiliza OpenCV en C++ para aplicar diversos métodos de extracción de características, como SIFT, SURF, ORB, entre otros, para detectar objetos específicos dentro de imágenes más amplias. La implementación se centra en la identificación precisa y robusta de objetos mediante el análisis de sus características distintivas, facilitando aplicaciones en áreas como la robótica, la vigilancia y la realidad aumentada.

## Tecnologías_Utilizadas
* C++: Lenguaje de programación principal para la implementación del proyecto.
* OpenCV: Biblioteca de procesamiento de imágenes y visión por computadora utilizada para la detección y reconocimiento de objetos.
* CMake: Herramienta de gestión de compilación utilizada para compilar el proyecto.

## Implementación
La implementación del proyecto se divide en varias etapas:
* Carga de Imágenes: Importación de la imagen objetivo y la imagen más amplia en la que se desea detectar el objeto.
* Preprocesamiento de Imagen: Aplicación de técnicas de procesamiento de imágenes para mejorar la calidad y facilitar la detección.
* Extracción de Características: Uso de diferentes métodos de extracción de características como SIFT, SURF y ORB para identificar puntos clave y descriptores en la imagen objetivo.
* Coincidencia de Características: Comparación de los descriptores extraídos entre la imagen objetivo y la imagen más amplia para encontrar coincidencias.
* Detección del Objeto: Identificación y localización del objeto en la imagen más amplia basado en las coincidencias de características.
* Visualización de Resultados: Mostrar los resultados de la detección, incluyendo los puntos clave y los límites del objeto detectado en la imagen más amplia.

## Referencias
OpenCV Documentation: https://docs.opencv.org/
CMake Documentation: https://cmake.org/documentation/
