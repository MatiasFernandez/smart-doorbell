# Timbre Smart con ESP8266 y ESPHome


![Proyecto terminado](/fotos/terminado.jpg)

Este es un proyecto para convertir un timbre tradicional inalámbrico en Smart con WiFi.

Me inspire en un [video de The Hookup](https://www.youtube.com/watch?v=xCQoOZNdaGY) pero hice mi propia versión para otro timbre. Esta modificación esta pensada para un timbre que [en Argentina se vende](https://sanderson.com.ar/producto/timbres-inalambricos/timbre-inalambrico-w3/) como **Sanderson QD W3** pero que tambien lo vi en AliExpress o alguna otra página similar.

La idea conceptual de la modificación seguramente pueda extenderse a otros timbres similares.

**Video explicando el proyecto:**

[![Video explicativo](https://img.youtube.com/vi/C8Lh4hxncJc/0.jpg)](https://www.youtube.com/watch?v=C8Lh4hxncJc)

## Funcionalidades

- Poder recibir notificaciones de timbre directo en el celular
- Disparar cualquier automatización que soporte Home Assistant
- Silenciar el sonido del timbre directo desde Home Assistant

## Hardware

- 1 timbre inalámbrico
- 1 placa NodeMCU ESP8266, en mi caso use un Wemos D1 Mini
- 1 cargador de celular

## Software

- Home Assistant como hub de integración
- ESPHome para generar el firmware (se podria usar Tasmota tambien e integrarlo con otros sistemas de home automation)

## Bosquejo del circuito final

![Circuito](/fotos/circuito.png)

## Links útiles

- Proyecto Home Assistant: https://www.home-assistant.io/
- ESPHome: https://esphome.io/
- NodeMCU: https://nodemcu.readthedocs.io/en/release/
- Wemos D1 Mini: https://www.wemos.cc/en/latest/d1/d1_mini.html
