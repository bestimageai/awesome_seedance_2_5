# Seedance 2.5: seis recetas de prompts comunes en español

[Todos los idiomas](README.md) · [Índice de 120 escenas](../README.md) · [Inicio](../../README.md)

Mantenido por el **equipo de bestimage.ai**. Estas seis recetas localizadas corresponden a las escenas 04, 31, 37, 43, 46 y 52 del catálogo principal. Son traducciones o adaptaciones de los mismos escenarios, no seis prompts únicos adicionales. No constituyen una traducción completa al español del catálogo chino. Estas propuestas creativas no se han probado; la geometría exacta, el texto, el habla y la física deben revisarse en los resultados reales.

Para un único fotograma inicial, utiliza [Seedance 2.5 de imagen a vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) (página en inglés). Con varios archivos de referencia, el modo [de referencias a vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) (página en inglés) también exige un vídeo de referencia: asigna su función de forma explícita. La [API de GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) (página en inglés) es un flujo independiente de generación de imágenes para preparar fotogramas del guion gráfico, no un punto de acceso de vídeo. Consulta la [guía de integración](../../docs/bestimage-ai-api-guide.md).

## I18N-01. Portafiltro de café de cerámica: un vertido controlado

Escena del catálogo: **04** · Modo: imagen a vídeo · Duración: **20 segundos** · Formato: **16:9**

```text
Usa Image 1 como fotograma inicial: un portafiltro de cerámica azul cobalto con seis nervaduras exteriores, un filtro de papel blanco con café molido seco y una jarra transparente sobre piedra caliza clara. Mantén el número de nervaduras, la silueta sin asa, los pliegues del filtro, el contorno de la jarra y la luz matinal desde la izquierda. El producto no tiene marca.

00:00–00:04: mantén un primer plano del café molido seco; un pico de cuello de cisne de acero inoxidable entra desde la esquina superior derecha sin ocultar el portafiltro.
00:04–00:11: un chorro fino y continuo traza un pequeño círculo dentro del filtro. El café se hincha suavemente; el líquido permanece por debajo del borde del papel y gotea hacia la jarra.
00:11–00:16: el chorro se detiene y el pico se retira. Aleja un poco la cámara para mostrar cómo la jarra se llena gradualmente; no gires el portafiltro ni cambies sus proporciones.
00:16–00:20: mantén una vista de tres cuartos despejada del producto, con espacio vacío a la derecha para añadir texto después.

Audio: vertido suave, goteo ocasional y ambiente tranquilo de la sala; sin habla ni música. Conserva la continuidad del volumen de líquido y el contacto entre objetos sólidos. Sin café flotante, recipientes adicionales, texto legible, logotipos, nubes de vapor ni marcas de agua. Cambia el color de la cerámica solo cuando aportes un nuevo fotograma inicial que coincida.
```

## I18N-02. Sobrecamisa reversible: viento y movimiento del tejido

Escena del catálogo: **31** · Modo: referencias a vídeo · Duración: **20 segundos** · Formato: **9:16**

```text
Image 1 define la identidad de la persona adulta que actúa como modelo y cuyo uso de imagen está autorizado. Image 2 define una sobrecamisa sin marca de color óxido, forro marfil, dos bolsillos de parche y cinco botones delanteros. Video 1 aporta únicamente el cuarto de vuelta lento y el flujo de aire de izquierda a derecha; no copies a la persona ni su ropa. Comienza con la sobrecamisa abierta y la persona de pie en una posición marcada del estudio.

00:00–00:05: plano americano fijo; la persona levanta el borde izquierdo abierto lo justo para mostrar el forro, con la mano sujetando visiblemente el tejido.
00:05–00:12: la persona suelta el borde y gira un cuarto de vuelta hacia la izquierda del encuadre. Un ventilador suave mueve el borde suelto y el pelo de forma constante hacia la derecha del encuadre; los hombros y las costuras de los bolsillos permanecen estables.
00:12–00:16: el flujo de aire disminuye. La tela se asienta por su propio peso en lugar de volver de golpe a su sitio.
00:16–00:20: mantén una postura lateral relajada con la misma altura de cámara y el mismo objetivo.

Audio: ventilador silencioso y movimiento de tela; sin diálogo. Sin dar la vuelta a la prenda mientras se lleva puesta, cambios instantáneos de vestuario, botones adicionales, retoques de piel, cambios de forma corporal, texto, logotipos ni marcas de agua. Esto ilustra el movimiento del tejido, no una prueba certificada de resistencia al viento.
```

## I18N-03. Aplicación de lectura: guardar un pasaje resaltado

Escena del catálogo: **37** · Modo: referencias a vídeo · Duración: **18 segundos** · Formato: **16:9**

```text
Image 1 es la pantalla de lectura aprobada, Image 2 la misma pantalla con un pasaje seleccionado e Image 3 el estado aprobado de la nota guardada. Todo el texto visible ya se proporciona en inglés. Video 1 controla únicamente la trayectoria del puntero y el momento de cada clic. Conserva el marco del dispositivo, la tipografía, los saltos de línea, la posición de lectura y el sentido de lectura de la interfaz; nunca inventes texto del artículo.

00:00–00:04: vista frontal fija del dispositivo sobre un escritorio neutro; el puntero se detiene junto al pasaje mostrado en Image 2.
00:04–00:09: el puntero selecciona ese pasaje una sola vez siguiendo Video 1. Reproduce exactamente el resaltado aprobado sin desplazar otras líneas.
00:09–00:14: pulsa una vez el control de guardado existente y pasa a Image 3. No añadas avisos temporales, contadores, valoraciones ni menús que no aparezcan en las referencias.
00:14–00:18: mantén el estado de la nota guardada para su inspección. Sin movimiento de cámara ni reflejos de pantalla sobre el texto.

Audio: un clic suave por cada clic visible; sin habla, tecleo ni música. Rechaza letras alteradas, controles invertidos, resaltados que se desplazan, punteros duplicados, logotipos y marcas de agua. Para localizar el contenido, proporciona las tres pantallas aprobadas en el idioma de destino; no pidas al modelo de vídeo que traduzca la pantalla.
```

## I18N-04. Deshielo: escorrentía superficial e infiltración

Escena del catálogo: **43** · Modo: referencias a vídeo · Duración: **24 segundos** · Formato: **16:9**

```text
Image 1 es una vista en sección aprobada por un docente de un lecho de tierra inclinado, una capa fina de nieve y una bandeja de recogida transparente en el borde inferior. Image 2 aporta la superposición de flechas aprobada, sin palabras ni números. Video 1 proporciona únicamente el ritmo de la demostración con cámara fija. Mantén constantes los límites de las capas y las dimensiones de la bandeja; se trata de una ilustración didáctica simplificada, no de pruebas experimentales basadas en mediciones.

00:00–00:06: presenta toda la sección con una cámara fija. Muestra una pequeña cantidad de agua de deshielo que se forma en el límite entre la nieve y el suelo.
00:06–00:13: deja que parte del agua descienda por la superficie hacia la bandeja; sigue las flechas superficiales de Image 2 sin aumentar la masa de nieve.
00:13–00:19: muestra otra parte entrando en los poros superiores del suelo, siguiendo las flechas descendentes aprobadas. No hagas que atraviese al instante todas las capas ni sugieras que todos los suelos se comportan igual.
00:19–00:24: mantén ambas vías juntas en la misma vista; las flechas dejan de moverse antes del final.

Audio: agua tenue y ambiente de la sala; sin narración ni música. Sin mediciones inventadas, inundaciones, suelo que desaparece, direcciones de flujo contradictorias, etiquetas, logotipos ni marcas de agua. Añade subtítulos explicativos revisados en posproducción.
```

## I18N-05. Casa con patio: mostrar el recorrido real

Escena del catálogo: **46** · Modo: referencias a vídeo · Duración: **24 segundos** · Formato: **16:9**

```text
Image 1 proporciona el plano aprobado de la planta baja de una casa estrecha con patio. Image 2 e Image 3 establecen la estancia de entrada y el patio exactamente como están amueblados. Video 1 es un recorrido autorizado y controla la ruta y la altura de la cámara. Trata el plano como una restricción espacial, no como una imagen que deba mostrarse. No inventes vistas de la planta superior.

00:00–00:06: comienza justo dentro de la entrada a la altura habitual de los ojos de una persona adulta, con una perspectiva natural; muestra juntos el banco existente y el acceso al patio.
00:06–00:14: avanza lentamente por la ruta de Video 1 manteniendo el acceso a la vista. Detente antes del umbral; la cámara no debe atravesar paredes, muebles ni cristales cerrados.
00:14–00:20: entra al patio por la abertura real y realiza una panorámica suave hacia el parterre original.
00:20–00:24: detente y mira hacia atrás para que el público comprenda la conexión con la estancia de entrada.

Audio: las pisadas cambian del suelo interior al pavimento del patio, con ambiente exterior tranquilo; sin narración. Conserva las anchuras de las puertas, los niveles del suelo, el número de muebles, la dirección de la luz solar y la distancia recorrida. Sin distorsiones de ultra gran angular, habitaciones añadidas, mejoras de lujo, afirmaciones sobre la ubicación, carteles legibles ni marcas de agua.
```

## I18N-06. Transportín para gatos: una primera visita voluntaria

Escena del catálogo: **52** · Modo: referencias a vídeo · Duración: **18 segundos** · Formato: **9:16**

```text
Image 1 define un gato adulto gris atigrado cuyo material de referencia está autorizado. Image 2 define un transportín blando abierto con exterior azul marino, panel lateral de malla y puerta delantera abatida hacia abajo. Video 1 aporta únicamente el acercamiento tranquilo y el movimiento de entrada. Mantén las marcas del pelaje, el tamaño corporal, las costuras del transportín, la abertura de la puerta y el patrón de la malla.

00:00–00:05: cámara baja fija en la entrada del transportín. El gato se acerca al transportín vacío y abierto, se detiene y olfatea el borde; nadie lo empuja ni lo sujeta.
00:05–00:11: el gato entra voluntariamente, primero con las patas delanteras y luego con las traseras, con contacto visible con el suelo. El transportín no se expande ni absorbe al gato a través de su pared lateral.
00:11–00:15: el gato gira una vez dentro del espacio disponible y se acomoda mirando hacia la entrada abierta.
00:15–00:18: mantén la postura relajada. Deja la puerta completamente abierta.

Audio: contacto suave de las patas, movimiento de tela y ambiente tranquilo de la sala; sin ronroneos ni sonidos de angustia añadidos. Sin sedación, manipulación forzada, anatomía imposible, animales duplicados, certificaciones de seguridad, texto, logotipos ni marcas de agua. Si el gato de referencia no entra por voluntad propia, elige otro clip autorizado en lugar de indicar que se le fuerce.
```
