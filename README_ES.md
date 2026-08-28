# Prompts para Seedance 2.5: guía práctica de imagen a vídeo

[English](README.md) · [简体中文](README_ZH.md) · [日本語](README_JA.md) · [Español](README_ES.md) · [Prompts en 15 idiomas](prompts/i18n/README.md)

![Portada conceptual de la guía de prompts de Seedance 2.5; no es un resultado de vídeo](assets/seedance-2-5-cover.png)

Esta biblioteca, **recopilada y mantenida por el equipo de bestimage.ai**, contiene **120 escenarios únicos**: los 100 originales se han reescrito y se han añadido 20 nuevos. El núcleo incluye **60 escenas en chino y 40 en inglés**; las **20 nuevas están disponibles tanto en chino como en inglés**. Las 15 versiones lingüísticas ofrecen seis ejemplos comunes por idioma, no una traducción de toda la biblioteca. Las traducciones no cuentan como escenarios adicionales.

Comparte un prompt original y probado siguiendo las [instrucciones para contribuir](CONTRIBUTING.md), incluyendo ajustes, entradas y el resultado real. Las propuestas aceptadas pueden publicarse con atribución después de su revisión.

> **Usar Seedance 2.5 en bestimage.ai:** elige [texto a vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) si partes de una idea o un guion, [imagen a vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) para un fotograma inicial o [referencias a vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) para archivos de referencia. **Las tres páginas están en inglés. El modo de referencias a vídeo exige al menos un vídeo de referencia**, con una función definida explícitamente.
>
> Prepara imágenes estáticas de referencia o fotogramas del guion gráfico con la [API de GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) (**página en inglés**). Es un flujo independiente de generación de imágenes, no una función de vídeo de Seedance. Consulta la [guía de integración de la API de bestimage.ai](docs/bestimage-ai-api-guide.md).
>
> Los parámetros, precios, requisitos de entrada y esquemas API pueden cambiar. Consulta las páginas de bestimage.ai para conocer los detalles actuales. Las imágenes conceptuales no son resultados de Seedance ni demuestran el rendimiento del modelo.

## Cómo escribir un buen prompt para Seedance 2.5

Escribe unas instrucciones de dirección con acciones concretas, referencias asignadas y restricciones de continuidad. Al usar estas propuestas creativas, revisa la geometría, el texto, el habla y la física en los resultados reales.

```text
[Modo] Texto a vídeo / Imagen a vídeo / Referencias a vídeo
[Objetivo] Uso, público, emoción, duración y formato
[Función de cada referencia] Image 1 fija la identidad; Video 1 solo aporta la cámara
[Anclas visuales] Persona, vestuario, producto, escenario, hora y luz
[Cronología] Presentación → acción → giro → plano final
[Cámara] Tamaño de plano, altura, recorrido, velocidad, foco y parada
[Interpretación y física] Mirada, manos, peso, inercia, contacto, tela y agua
[Audio] Diálogo, ambiente, efectos sonoros, música y puntos de sincronía
[Continuidad] Elementos que no pueden cambiar
[Evitar] Deformaciones, duplicados, extremidades extra, texto inventado, logotipos y marcas de agua
```

## Ejemplo listo para copiar

La primera de las [seis recetas completas en español](prompts/i18n/prompt-library.es.md) muestra un vertido controlado sobre un portafiltro de café de cerámica, correspondiente a la escena **04** del catálogo. Define el fotograma inicial, la geometría que debe conservarse, cuatro tramos temporales, el sonido y las restricciones. Las otras cinco recetas cubren tejido en movimiento, una aplicación de lectura, deshielo, una casa con patio y un transportín para gatos.

## Biblioteca completa

El [índice maestro de 120 escenas](prompts/README.md) reúne:

- **60 escenas del núcleo en chino:** [24 escenas de la biblioteca base](prompts/prompt-library.md) y [36 escenas ampliadas](prompts/extended-scenarios.md).
- **40 escenas del núcleo en inglés:** [12 flujos profesionales](prompts/advanced-workflows.en.md) y [28 técnicas creativas](prompts/creative-techniques.en.md).
- **20 nuevos flujos de producción**, disponibles en [inglés](prompts/production-workflows.en.md) y [chino](prompts/production-workflows.zh.md); ambas versiones representan las mismas 20 escenas.

El archivo de [prompts completos en español](prompts/i18n/prompt-library.es.md) contiene seis recetas compartidas con las demás versiones lingüísticas, no 120 traducciones. Consulta el [directorio de 15 idiomas](prompts/i18n/README.md), que también incluye italiano, tailandés y vietnamita.

## Lista de control para imagen a vídeo

- Conserva la identidad, ropa, geometría del producto, cantidad de objetos, composición y luz principal.
- Separa el movimiento del sujeto, del entorno y de la cámara.
- Asigna una sola función a cada archivo de referencia; si usas referencias a vídeo, incluye al menos un vídeo.
- Describe inicio, recorrido, velocidad y punto final de la cámara.
- Reserva tiempo al final para frenar y cerrar la composición según la receta elegida.
- Usa únicamente personas, música, voces, marcas e imágenes propias o autorizadas.

Revisa los consentimientos, derechos de autor, imagen, marca, audio, seguridad, afirmaciones y políticas de la plataforma antes de cualquier uso comercial.

## Acerca de bestimage.ai

El equipo de [bestimage.ai](https://bestimage.ai/) selecciona y mantiene esta biblioteca de prompts, que conecta flujos de trabajo creativos con API de modelos de imagen y vídeo.

## Gana con el programa de afiliados de bestimage.ai

¿Publicas tutoriales, prompts o integraciones de API? Únete al [programa de afiliados de bestimage.ai](https://bestimage.ai/affiliate-program/) y gana comisiones al recomendar bestimage.ai a tu audiencia.

- **20 %** sobre el primer pedido de pago válido de cada usuario referido.
- **10 %** sobre sus pedidos de pago válidos posteriores, realizados durante los **60 días siguientes a su registro**.

Los requisitos de los pedidos y los pagos se rigen por el [acuerdo de afiliación vigente](https://bestimage.ai/affiliate-agreement/).

## Licencia

[MIT](LICENSE).
