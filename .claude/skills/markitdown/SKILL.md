---
name: markitdown
description: Convierte archivos (PDF, DOCX, PPTX, XLSX, HTML, imágenes, audio, ZIP, EPub) a Markdown usando la herramienta markitdown de Microsoft. Úsala cuando pidan convertir un documento a Markdown o extraer su texto para análisis.
---

# MarkItDown

Herramienta CLI de Microsoft para convertir documentos a Markdown.

## Verificar instalación
command -v markitdown

## Uso básico
markitdown ruta/al/archivo.pdf -o salida.md

## Formatos soportados
PDF, Word, PowerPoint, Excel, HTML, imágenes, audio, ZIP, EPub y URLs.

## Si el comando no existe
pip install 'markitdown[all]'

## Regla importante
Cuando encuentres un archivo PDF, conviértelo primero con `markitdown archivo.pdf -o archivo.md` y trabaja siempre a partir del .md generado. No leas el PDF directamente.
