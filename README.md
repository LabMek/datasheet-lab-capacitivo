# Plantilla en LaTeX para Datasheets de Sensores y Actuadores
---
Andrés M. Morales Martínez (amoralesma@unal.edu.co) 





Este repositorio contiene una **clase de documento para LaTeX** diseñada para crear hojas de datos (datasheets) de componentes electrónicos y sensores.  
La plantilla busca dar un formato claro, estandarizado y profesional a la documentación técnica de los dispositivos usados en el curso de **Sensores y Actuadores**.

## Contenido del repositorio

- `datasheet.cls`: Clase principal de LaTeX para generar el formato del datasheet.  
- `example.tex`: Documento de ejemplo mostrando cómo usar la clase.  
- `example.pdf`: Ejemplo compilado del resultado final.

## Objetivo

El propósito de esta plantilla es facilitar la creación de un **datasheet académico** donde se reporten las **características estáticas** de un sensor o actuador, acompañadas de explicaciones, gráficas y justificaciones.  
Debe permitir que una persona que no conozca el sensor pueda entenderlo, sus principios de funcionamiento y su aplicación.

## Requisitos del datasheet

Cada entrega debe incluir, como mínimo, la descripción de las siguientes características del sensor:

- Precisión  
- Exactitud  
- Linealidad  
- Sensibilidad  
- Rango de entrada y salida  
- FSO (*Full Scale Output*)  

Además, el documento debe contener:  

- Explicación clara del **principio de funcionamiento**.  
- Gráficas, tablas o figuras necesarias para sustentar la información.  
- Justificación de **cómo podría modificarse cada característica** en el sensor.  
- Texto claro y organizado.  

📄 **Extensión máxima:** 6 páginas.  

## Uso en Overleaf

Para usar la plantilla en [Overleaf](https://overleaf.com):  

1. Descarga este repositorio como archivo `.zip`.  
2. En Overleaf, crea un nuevo proyecto → **Upload Project**.  
3. Sube el `.zip` completo (incluyendo `datasheet.cls`).  
4. Abre el archivo `example.tex` (o crea tu propio `.tex`).  
5. En la primera línea, asegúrate de llamar la clase con:  

   ```latex
   \documentclass{datasheet}
