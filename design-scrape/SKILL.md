---
name: design-scrape
description: Extrae inteligencia de diseno desde libs oficiales y entrega un JSON de contrato con screenshots de referencia (demos oficiales, 1440 y 390) para chat, Designer y Builder. Usar cuando pidan disenar, construir, crear o hacer una UI, comparar primitivos, capturar referencia visual, o refrescar el corpus. Triggers include disena, construye, crea, haz, screenshot, captura, referencia, design scrape, primitivo, radix, shadcn, headless, chart, and refresh.
metadata:
  version: "1.1"
  type: workflow
  consumers: chat,designer,builder
---

# Design Scrape

Procedimiento reutilizable. Dado un pedido de diseno o construccion, recorre las seis familias y entrega un JSON de contrato mas screenshots de demos oficiales.
