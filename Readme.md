# Extracción de Información de Recibos y Facturas

## Descripción General

Este proyecto implementa un sistema de extracción automática de información contenida en recibos y facturas a partir de imágenes subidas al entorno.

Mediante técnicas de Procesamiento Digital de Imágenes y Reconocimiento Óptico de Caracteres (OCR), el sistema transforma información no estructurada en datos organizados que pueden utilizarse para almacenamiento, consulta y automatización de procesos administrativos.

El código desarrollado realiza el preprocesamiento de la imagen, mejora su calidad, identifica las regiones de interés, ejecuta el reconocimiento de texto y finalmente extrae los campos más relevantes del comprobante.

---

## Problema

La digitalización manual de recibos y facturas es una tarea repetitiva, lenta y propensa a errores humanos.

En empresas e instituciones, el registro manual de comprobantes incrementa el tiempo de procesamiento y dificulta la automatización de los procesos documentales.

---

## Solución Propuesta

El proyecto propone un sistema basado en Visión por Computadora y OCR que automatiza la extracción de información desde imágenes de comprobantes.

El proceso completo comprende las siguientes etapas:

- Carga de la imagen.
- Preprocesamiento y mejora de calidad.
- Detección de bordes.
- Corrección de perspectiva.
- Segmentación de regiones de interés.
- Normalización de la imagen.
- Reconocimiento óptico de caracteres mediante Tesseract.
- Extracción automática de:
  - RUC.
  - DNI.
  - Fecha.
  - Importe total.

---

## Objetivos

### Objetivo General

Desarrollar un sistema capaz de extraer automáticamente información relevante de recibos y facturas mediante técnicas de procesamiento digital de imágenes y OCR.

### Objetivos Específicos

- Mejorar la calidad de las imágenes mediante técnicas de preprocesamiento.
- Detectar automáticamente la región correspondiente al comprobante.
- Aplicar OCR para convertir el contenido de la imagen en texto.
- Identificar automáticamente los principales datos del documento.
- Reducir la intervención manual durante el proceso de digitalización.

---

## Características del Proyecto

El sistema implementa las siguientes funcionalidades:

- Preprocesamiento de imágenes.
- Conversión a escala de grises.
- Filtrado y reducción de ruido.
- Detección de bordes.
- Corrección de perspectiva.
- Segmentación de regiones de interés.
- Normalización de la imagen.
- Reconocimiento óptico de caracteres (OCR).
- Extracción automática de información estructurada.

---

## Limitaciones

La precisión del sistema depende principalmente de la calidad de la imagen de entrada.

Entre los factores que pueden afectar el reconocimiento se encuentran:

- Baja resolución.
- Iluminación deficiente.
- Sombras pronunciadas.
- Comprobantes arrugados o deteriorados.
- Texto borroso.
- Fuentes tipográficas poco legibles.
- Diseños de comprobantes poco convencionales.

Actualmente, el sistema ha sido desarrollado para el procesamiento de recibos y facturas redactados en idioma español.

---

## Procedimiento de Uso

El proyecto puede ejecutarse en **Visual Studio Code** utilizando **Jupyter Notebook**, o de manera alternativa en **Google Colab**.

Para utilizar el sistema:

1. Clonar este repositorio.
2. Instalar las dependencias del proyecto.
3. Abrir el archivo `00_Pipeline_Completo.ipynb`.
4. Ejecutar las celdas de instalación e importación de librerías.
5. Cargar la imagen del comprobante.
6. Ejecutar las celdas del notebook en el orden establecido.
7. Visualizar los resultados obtenidos en cada etapa.
8. Obtener el texto reconocido y la información extraída automáticamente.

---

## Tecnologías Utilizadas

- Python
- OpenCV
- NumPy
- Matplotlib
- Pytesseract
- Jupyter Notebook

---

## Entorno de Desarrollo

**Lenguaje:** Python 3.12.1

**OpenCV:** 4.9.0

**NumPy:** 1.26.4

**Matplotlib:** 3.5.2

**Pytesseract:** 0.3.13

**Motor OCR:** Tesseract OCR

**Sistema Operativo:** Windows 11

**Entorno de desarrollo:** Visual Studio Code + Jupyter Notebook

**Entorno alternativo de ejecución:** Google Colab

---

## Integrantes

- Alarcón Crisanto Leonardo David
- Aldana Pasache Jhon Brayan
- Calderón Guerrero Schneider
- Calderón Rufino José Daniel
- More Crisanto Luis Brayan
- Neyra Tocto César Josué
- Ordinola Huacchillo Fernando Noé
