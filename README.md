# Web Scraping - Extractor de Correos y Comentarios

Script en Python que extrae direcciones de correo electrónico y comentarios HTML del código fuente de una página web.

## Diagrama del Algoritmo

![Diagrama Web Scraping](https://raw.githubusercontent.com/Hoffman99/reconocimiento_red/main/web-scraping.png)

## Características

- Extrae correos electrónicos usando expresiones regulares
- Extrae comentarios HTML (`<!-- comentario -->`)
- Normalización automática de URLs
- Manejo básico de errores de argumentos
- Compatible con HTTP y HTTPS

## Requisitos

```bash
pip install requests
