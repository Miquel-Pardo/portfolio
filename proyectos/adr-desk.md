# ADR Desk

[← Volver al catálogo](../README.md)

**Estado según revisión de 31/10/2026:** RC con bloqueos  
**Referencia:** 0.6.0-rc1, candidata con bloqueos.

## Problema

Ayudar a ordenar documentos y operaciones que un consejero ADR necesita revisar al preparar un cierre anual.

## Qué se ha implementado

- Importación de CSV, Excel, PDF e imágenes con OCR local.
- Detección de errores y duplicados, revisión humana y consolidación.
- Generación de dossiers e informes con exportaciones.

## Aportación de Miquel Angel Pardo

Diseño del proceso documental, criterios de revisión y control humano; coordinación del desarrollo asistido por IA.

La implementación del código se ha realizado con apoyo de IA y Codex; no se atribuye programación manual exclusiva.

## Evidencia disponible

- Hay pruebas técnicas documentadas y un piloto simulado con 20 perfiles ficticios.
- Los perfiles simulados no son usuarios ni clientes reales.

## Límites y pendientes

- No consta piloto comercial con personas reales ni validación completa de utilidad.
- Revisión profesional, derechos, identidad legal y firma de distribución pendientes.

## Alcance de esta publicación

Mostrar un flujo documental sintético; no distribuir datos reales ni presentar los cálculos como certificados.

**Tecnologías presentes en el proyecto:** Python, PySide6, SQLAlchemy / SQLite, RapidOCR / ONNX Runtime, openpyxl / pypdf, ReportLab, PyInstaller / NSIS.

*Esta ficha resume la evidencia identificada en octubre de 2026. No constituye una certificación técnica, legal o comercial.*
