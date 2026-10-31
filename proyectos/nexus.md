# Nexus

[← Volver al catálogo](../README.md)

**Estado según revisión de 31/10/2026:** Operativa privada  
**Referencia:** Ciclo real documentado para v19; candidata de código v19.1.

## Problema

Unificar desde el móvil una conversación con IA, la definición de un trabajo y su entrega, sin perder la aprobación humana ni el contexto del proyecto.

## Qué se ha implementado

- Chat de texto y voz con hilos diferenciados por proyecto.
- Aprobación explícita de encargos, coordinación con un equipo Windows y recuperación de resultados en Android.
- Persistencia de conversaciones y evidencias, con funciones de historial y borrado lógico.

## Aportación de Miquel Angel Pardo

Definición del flujo móvil–PC y las aprobaciones; diseño de experiencia y coordinación de integración; comprobaciones prácticas con implementación asistida por IA.

La implementación del código se ha realizado con apoyo de IA y Codex; no se atribuye programación manual exclusiva.

## Evidencia disponible

- El recorrido GPT → aprobación → Codex → revisión → reapertura fue documentado en un entorno privado.
- En revisión aislada: 8 de 8 pruebas offline superadas y verificador de exportación correcto; sin usar cuentas ni modelos reales.

## Límites y pendientes

- La validación física específica del desplazamiento y el borrado en v19.1 seguía pendiente.
- El paquete no es un instalador público autocontenido; algunas ejecuciones documentadas fallaron.

## Alcance de esta publicación

Hay una exportación separada con una selección de código propio bajo MIT. Su revisión de publicación, procedencia y alcance de licencia debe cerrarse antes de subir código.

**Tecnologías presentes en el proyecto:** Java Android, Node.js 24 / ESM, SQLite, JSON-RPC / Responses / SSE, DPAPI / Keystore, Tailscale / HTTPS, Sherpa-ONNX / Piper.

*Esta ficha resume la evidencia identificada en octubre de 2026. No constituye una certificación técnica, legal o comercial.*
