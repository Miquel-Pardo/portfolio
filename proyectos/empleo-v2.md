# Empleo V2

[← Volver al catálogo](../README.md)

**Estado según revisión de 31/10/2026:** Operativa privada  
**Referencia:** V2, operativa privada.

## Problema

Reducir el trabajo repetitivo al revisar ofertas de empleo, conservando los motivos de encaje y evitando enviar candidaturas sin autorización.

## Qué se ha implementado

- Consulta y deduplicación de ofertas con criterios explícitos.
- Estados verificables y seguimiento de evidencias y pendientes.
- Preparación de avisos con registros de los pasos, sin enviar solicitudes automáticamente.

## Aportación de Miquel Angel Pardo

Criterios de selección, diseño del flujo trazable, tratamiento de excepciones y revisión humana; desarrollo dirigido con IA.

La implementación del código se ha realizado con apoyo de IA y Codex; no se atribuye programación manual exclusiva.

## Evidencia disponible

- Se documentó una ejecución privada completa del controlador y revisiones de ofertas.
- Los avisos preparados no constan como enviados; no hay resultados de contratación atribuibles.

## Límites y pendientes

- Falta verificar la entrega final de avisos y medir la utilidad práctica de forma sostenida.
- Algunas plataformas limitan la consulta automática de ofertas.

## Alcance de esta publicación

Caso de proceso con candidatos y ofertas ficticios; no publicar CV, perfiles personales, emails ni historial de candidaturas.

**Tecnologías presentes en el proyecto:** Python, SQLite, HTTP / búsqueda, Telegram, Correo conectado, Checkpoints / outbox.

*Esta ficha resume la evidencia identificada en octubre de 2026. No constituye una certificación técnica, legal o comercial.*
