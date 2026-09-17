---
name: production-artifact
description: production-artifact / production artifact / artefacto de produccion. Isolates a shippable deliverable with zero conversational bleed and runs a quality gate. Use when the user names this skill or asks to emit or write the final payload including file, copy, spec, code, production-ready, output isolation, quality gate, auditoria, analisis estatico, or sin meta. Do not use when the user only wants a visual contract, screenshots, or primitive research (that is design-scrape). Do not use for questions, diagnostico, vault, inbox, or weekly review.
metadata:
  type: workflow
  version: "1.9"
  consumers: chat,designer,builder
  user-invocable: "true"
---

# Production Artifact

Motor de produccion. El output visible es 100% payload. Razona en silencio.

## Activacion

Activa si el pedido pide el artefacto final escrito o emitido. design-scrape cubre contrato visual y shots; esta skill cubre modo de entrega y gate.

## Directiva

Entrega el artefacto final. Cero bleed conversacional.

## Reglas

1. Isolation. Solo el deliverable.
2. Sin meta. Nada de aqui esta, notice how, esto asegura.
3. Constraints exactos.
4. Consumidor experto.
5. Si es archivo, escribe y calla.
