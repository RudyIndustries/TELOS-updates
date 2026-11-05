# Historial de cambios

## 0.8.9 · compilación 30

Descargas recuperables y nueva ventana de actualización

- Corregido el estado de canciones ya guardadas que podía quedarse indefinidamente en Añadiendo a tu biblioteca. La actualización de biblioteca tiene reintentos limitados y una acción para actualizarla sin volver a descargar el archivo.
- En Android 10 o posterior, las canciones descargadas por TELOS aparecen aunque todavía no se haya autorizado la lectura de toda la música. Los archivos de otras aplicaciones siguen requiriendo permiso o una carpeta autorizada.
- Si una transferencia deja de avanzar, TELOS libera el trabajo y permite reintentarlo. Cancelar ya no depende de que Telegram termine de contestar; las respuestas tardías no reactivan trabajos cancelados o fallidos.
- Abrir Ajustes, cambiar el color o volver al buscador conserva las descargas aceptadas. Al volver de Ajustes se reutilizan los resultados vigentes de la misma consulta.
- La lectura del catálogo y el guardado de archivos usan colas separadas, evitando que una nueva búsqueda retrase los acuses del archivo.
- Varios archivos guardados comparten la actualización de biblioteca. Esa lectura no inicia la organización de otras canciones y también reconoce la identidad canónica de los archivos autorizados.
- Se mantiene la verificación de tamaño y SHA-256 antes de publicar el archivo. Las descargas normales conservan la reproducción y la cola manual.
- Las próximas versiones se anuncian en una ventana emergente obligatoria, con Actualizar y Salir. Atrás también cierra TELOS y cancelar el instalador mantiene el aviso. Se retira el aviso superior y se conserva Actualizaciones en Ajustes. Es necesario instalar esta versión para recibir el nuevo comportamiento; la comprobación automática conserva su intervalo.

Actualiza encima de la instalación existente para conservar música, favoritos, playlists y preferencias.

## 0.8.8 · compilación 29

Telegram inmediato, descargas sin interrupciones y almacenamiento de tu música

- Telegram aparece al principio de Ajustes. Conectar abre el inicio de sesión sin esperar comprobaciones de conexión o calidad y no prepara una sesión web al entrar en Ajustes.
- Buscar mantiene Conectar Telegram fijo en la parte superior, encima del campo de búsqueda. Permanece visible al escribir, borrar o desplazar resultados, y sólo desaparece cuando la cuenta está conectada.
- Cancelar el consentimiento o el inicio de sesión deja disponible el mismo botón para reintentarlo.
- Las respuestas antiguas de conexión o calidad no sustituyen el estado de un inicio de sesión más reciente.
- Se agiliza la presentación del consentimiento al evitar inicializar WebView antes de aceptar. La carga de la página oficial y la autenticación siguen dependiendo de Telegram y de la conexión a Internet.
- Descargar una o varias canciones desde Buscar o un álbum ya no detiene ni sustituye la que está sonando. Las descargas normales respetan la reproducción y la cola manual; sólo Preparar y reproducir, elegido expresamente, reproduce al terminar.
- Nuevo botón Administrar almacenamiento en Ajustes: total ocupado por la música, barra de distribución, tamaños por carpeta y detalle de sus canciones, ordenados por espacio ocupado. Sólo incluye música detectada por TELOS; no mezcla fotos, aplicaciones ni sistema.
- Recalcular almacenamiento sólo lee la biblioteca, sin mover archivos. Los tamaños no informados se señalan y no se inventan.

Se mantienen Análogo Hi-Res, la biblioteca, música descargada, favoritos, playlists y ajustes. Actualiza encima de la instalación existente.

## 0.8.7 · compilación 28

Telegram en Ajustes y Análogo Hi-Res automático para USB

- Nuevo bloque Telegram en Ajustes para conectar tu cuenta o desconectarla. Cancelar el consentimiento o el inicio de sesión permite volver a intentarlo.
- Pantalla de consentimiento rediseñada con el icono original de TELOS, tarjetas claras y las opciones Aceptar y conectar y Ahora no.
- Se mantiene la explicación del alcance de Telegram Web, del servicio que recibe las consultas y del envío mientras escribes. Telegram sólo se carga después de aceptar.
- Desconectar pide confirmación y conserva la música descargada, favoritos y playlists. Si el cierre remoto no se confirma, se indica cómo revocar la sesión desde Telegram.
- Análogo Hi-Res se activa por defecto al detectar una salida de audio USB que anuncie frecuencias superiores a 48 kHz, en Android 14 o posterior. Sin esa detección permanece apagado. Puedes desactivarlo y se respeta tu elección.
- Solicita la frecuencia original de la canción cuando existe un formato compatible; conserva la reproducción convencional si Android no lo admite. No aumenta artificialmente la frecuencia de los archivos ni certifica la frecuencia física del DAC.
- El diagnóstico muestra las capacidades declaradas de la salida por separado del archivo, PCM y formato cliente de Android. Cambiar la preferencia conserva canción, posición, pausa y cola. La petición USB bit-perfect continúa siendo independiente.

Actualización Android que conserva música y preferencias. Instálala encima de TELOS sin desinstalar la versión anterior.

## 0.8.5 · compilación 26

Ambilight más visible y con intensidad ajustable

- Se corrige el Ambilight que podía quedarse estático al reiniciar una canción o retroceder dentro de ella.
- Ajustes permite regular la intensidad de 0 a 100 %. La elección se conserva; al máximo aumentan brillo, color, definición y movimiento de las luces.
- Respuesta más rápida a la música, con acentos en las subidas reales de bajos y desplazamiento según bajos, medios y agudos. No cambia el audio ni utiliza micrófono.
- El efecto sigue deteniéndose en segundo plano, con pantalla apagada, al pausar o al desactivar Movimiento. A 0 % también se detiene su análisis.

Actualización Android que conserva música, favoritos, playlists y preferencias.

## 0.8.4 · compilación 25

Ambilight al ritmo y descargas con colaboradores

- Se corrige el reconocimiento del audio cuando la búsqueda muestra al artista principal y el archivo incluye colaboradores. La espera también termina si Telegram deja una consulta pendiente, y se puede cancelar.
- Se mantienen las comprobaciones para distinguir canciones homónimas, versiones y enlaces de otras pistas.
- Cabeceras de Ajustes, playlists y reproductor sin división rectangular superior.
- Ambilight detrás del disco y en los bordes: colores dominantes de la portada y respuesta a bajos, medios y agudos mediante FFT del audio local. Activado por defecto, desactivable en Ajustes; sin micrófono ni cambios en el sonido.
- Play/pausa sobre la carátula de Buscar sin círculo negro y barras neón para identificar la canción actual en búsquedas y playlists.
- El corazón plateado y el minirreproductor abren Favoritos y playlists; se retiran los tres puntos del minirreproductor.
- Imagen personalizada para playlists, con posibilidad de volver a las carátulas automáticas. El selector de destino muestra esa imagen o el mosaico de canciones.

Actualización sólo para Android, conservando música, favoritos, playlists y preferencias.

## 0.8.1 · compilación 22

Tocadiscos y búsqueda más cómodos

- Vinilo negro más grande, surcos finos, reflejos y brazo cromado inspirado en la referencia. Tamaño adaptable para conservar el acceso a los controles.
- Corazón metálico abajo a la derecha del tocadiscos, encima de los controles.
- Arranque y frenado visuales suaves, movimiento del brazo y respuesta al tocar el disco. Se respeta Movimiento y la accesibilidad del sistema.
- Buscar muestra reproducción sobre la carátula, acceso directo a Favoritos/playlists y opciones con tres puntos verticales. El primer toque añade a Favoritos; si ya está añadida, abre el selector de playlists.
- Los resultados Global se guardan y verifican antes de añadirlos a Favoritos, sin reproducir ni cambiar la cola manual.
- Al minimizar con el teclado abierto se descarta el foco antiguo y el espacio residual del teclado al volver; se conserva la consulta y se puede escribir de nuevo.

Actualización Android sobre la instalación existente, conservando música, favoritos, playlists y preferencias.

## 0.8.0 · compilación 21

Puedes seleccionar varias canciones y seguir buscando mientras se descargan. TELOS mantiene hasta dos descargas activas y deja las demás en cola. En Buscar aparece Descargas mientras haya pendientes: muestra cada canción, su progreso y la opción de cancelarla por separado.

Nuevo icono de vidrio dorado, apertura con brillo suave y fundido, y transiciones en Actualizaciones con un anillo de progreso. Los efectos respetan tus preferencias de movimiento.

Los álbumes de la búsqueda Global abren una lista de sus canciones, con el mismo funcionamiento de play y descarga de la búsqueda.

Al final del menú de una canción encontrarás Borrar del dispositivo en rojo. Después de confirmar, se elimina el archivo y el resultado vuelve a estar disponible para descargar. Android puede solicitar también su autorización de borrado.

Actualiza encima de TELOS para conservar sesión, biblioteca, preferencias y calidad seleccionada. La primera conexión sigue usando FLAC por defecto. Recomendar canciones permanece desactivado por defecto; los controles externos conservan la corrección de 0.7.1.

## 0.7.1 · compilación 20

Los controles externos utilizan ahora el mismo Siguiente que TELOS: primero tu cola y, si está vacía y activaste Recomendar canciones, otra pista local recomendada. La disponibilidad se actualiza al cambiar ese ajuste, también en los controles multimedia del Samsung.

Se mejora la compatibilidad de pausa, reanudar, anterior y siguiente con controladoras externas y accesorios que usan la sesión estándar de Android. Esos controles reciben únicamente permisos de transporte y lectura multimedia; las funciones privadas de TELOS siguen reservadas a la app.

Actualiza encima de TELOS para conservar sesión, música, preferencias y calidad seleccionada. Recomendar canciones sigue apagado por defecto.

## 0.7.0 · compilación 19

Ajustes incluye Recomendar canciones, desactivado por defecto. Si lo activas, TELOS continúa con otra canción de tu biblioteca al terminar la cola, también en segundo plano. El botón Siguiente de TELOS también elige una recomendación cuando no quedan pendientes. Tu cola manual y las opciones de repetición tienen prioridad.

Las recomendaciones priorizan el género guardado en las etiquetas del archivo. Si no hay una coincidencia de género, usan artista, álbum, historial de escucha y favoritos. Evitan la pista actual, canciones ocultas y repeticiones recientes. Los detalles de cada canción muestran su género cuando está disponible.

Todo se realiza con archivos locales: no descarga canciones automáticamente ni modifica tu música. Actualiza encima de TELOS para conservar Telegram, calidad elegida, favoritos, playlists e historial.

## 0.6.2 · compilación 18

Corrige el toque en las palabras de Búsquedas recientes: la lista conserva el foco hasta completar el toque, restaura el texto y vuelve a buscar automáticamente en Global y en tu biblioteca.

Las diez consultas recientes también se pueden desplazar sin que el teclado cierre la lista antes de elegir una. Se conserva el borrado separado de consultas y canciones/artistas visitados.

Actualiza encima de TELOS para conservar tu sesión de Telegram, música, favoritos, playlists, historial y calidad seleccionada.

## 0.6.1 · compilación 17

La consulta y el cambio de calidad se confirman en cuanto llega el menú real del bot, sin esperar además el acuse del envío o del botón, que este bot a veces no responde. Se mantiene el cambio con un solo toque y FLAC como formato inicial. Al elegir un formato se muestra «Cambiando calidad…».

TELOS verifica el formato real seleccionado antes de mostrarlo como confirmado; los errores y las respuestas con otra calidad no se presentan como un cambio correcto. La espera restante depende de la conexión con Telegram y del bot.

Actualiza encima de TELOS: se conservan tu sesión, biblioteca, favoritos, playlists y ajustes. TELOS ONLINE continúa retirada.

## 0.6.0 · compilación 16

TELOS reúne las funciones de ONLINE en una sola app. Actualiza encima de tu TELOS habitual: conserva favoritos, playlists, historial y permisos.

BUSCAR muestra juntas tus canciones y las del catálogo Global al escribir. Las disponibles aparecen en color con play; las pendientes se preparan al tocarlas, muestran un reloj y se reproducen al terminar. Las consultas recientes se pueden tocar para volver a buscar.

En Ajustes → Calidad de la Música → Calidad de descarga puedes elegir las opciones reales de tu cuenta del bot: FLAC, MP3 320 o MP3 128 cuando estén disponibles. La primera conexión configura FLAC; luego se respeta tu elección. No modifica la calidad de archivos ya descargados.

Cada usuario conecta su propia cuenta de Telegram. Se explica el alcance de la sesión antes de abrirla y se incluye Desconectar Telegram para revocarla y borrar los datos de conexión del teléfono, conservando tu música. Se reforzaron las validaciones de navegación, mensajes y archivos, y la firma de distribución conserva compatibilidad con las instalaciones existentes.

Los FLAC se guardan por artista en Telos Sound; los demás formatos, por artista en Music/TELOS. La app mantiene un único reproductor local y conserva tu cola manual.

TELOS ONLINE deja de usarse como app separada. Su conexión no se copia: conecta Telegram una vez desde TELOS. La disponibilidad y los formatos dependen del bot.

## 0.5.7 · compilación 15

Añadido «Probar TELOS ONLINE» en Ajustes → Actualizaciones. Descarga una app de prueba independiente, que se instala junto a TELOS con ajustes y playlists separados.

El instalador de prueba usa un canal propio. TELOS comprueba tamaño, SHA-256, paquete, versión y certificado antes de abrir el instalador Android. Las actualizaciones normales siguen usando el canal estable.

Esta versión de TELOS continúa reproduciendo música local. La búsqueda con Telegram pertenece a la app de prueba TELOS ONLINE.

## 0.5.6 · compilación 14

# TELOS 0.5.6

- Buscador fijo: puedes escribir aunque hayas bajado hasta el final de los resultados.
- Toca Buscar de nuevo para volver arriba y abrir el teclado, conservando tu consulta.
- Toca Biblioteca desde una playlist, artista o álbum para volver a tus playlists. Si ya estás en Biblioteca, vuelve al inicio de la lista.

La actualización conserva favoritos, playlists, historial y ajustes. Instala sobre TELOS, sin desinstalar.

## 0.5.5 · compilación 13

# TELOS 0.5.5

- Buscar muestra tus canciones y artistas recientes; al tocar el campo aparecen también las consultas anteriores, incluidas erratas.
- Navegación, carátulas y vinilo optimizados conservando las animaciones y el material glass.
- Actualizaciones más simples, con una acción principal y novedades desplegables.
- Calidad de audio con tarjetas de fuente, PCM y salida; USB bit-perfect arriba y explicaciones en «Más información».
- Organización interna y cachés revisados. El motor Pure Audio mantiene su precisión y configuración.

La actualización conserva favoritos, playlists, ajustes e historial. Instala sobre TELOS; no hace falta desinstalar. El formato del archivo y el PCM observado no certifican el DAC físico.

## 0.5.4 · compilación 12

# TELOS 0.5.4

Android 8 o posterior · ARM64 · compilación 12.

- Buscar muestra el artista coincidente arriba y las canciones debajo. Admite nombres sin espacios y mantiene la tolerancia acotada a erratas.
- Cabecera de Buscar más compacta, con más espacio para resultados.
- Nueva ficha de artista con hasta cinco canciones recomendadas de tu biblioteca y acceso a todas sus canciones.
- Botón Ver discografía: abre los álbumes locales del artista y permite entrar en cada uno. Los archivos sin etiqueta de álbum siguen accesibles en Sin álbum.
- Efecto glass más visible, bordes más redondeados y reflejos suaves en tarjetas, minirreproductor y navegación.
- Play, aleatorio y controles del disco ampliado con acabado glass, sin el relleno celeste plano.
- Cabecera principal con TELOS sin marco rectangular y botón circular de Ajustes separado del borde.

Las recomendaciones, álbumes y carátulas proceden de los archivos de tu dispositivo. No se descarga música ni se consulta un catálogo de Spotify.

Para actualizar ahora: Ajustes → Actualizaciones de TELOS → Buscar actualizaciones. Revisa estos cambios, descarga la actualización y confirma la instalación en Android. No desinstales TELOS: la actualización conserva tus preferencias, playlists e historial.

## 0.5.3 · compilación 11

# TELOS 0.5.3

Android 8 o posterior · ARM64 · compilación 11.

- Dos pulsaciones de Atrás desde Inicio llevan TELOS a segundo plano y conservan la reproducción. Quitarla desde Recientes detiene el audio.
- Minirreproductor persistente al navegar por la biblioteca, artistas, búsqueda, carpetas y playlists. Ajustes conserva su pantalla sin reproductor inferior.
- Minirreproductor, navegación y cabeceras más compactos para mostrar más contenido.
- Favoritos aparece como una playlist de tamaño normal, seguida de las listas creadas.
- Inicio incorpora accesos de dos columnas y recomendaciones de la biblioteca local.
- Botones de play y aleatorio en las colecciones. Playlists con orden por título, artista y arrastre personalizado, guardado en el dispositivo.
- Corregido el aviso incorrecto de que la colección cambió al iniciar en aleatorio. La lista y su inicio se aplican juntos en el servicio de audio.
- La pista que empieza a sonar deja de figurar como pendiente al avanzar. Las entradas repetidas conservan identidades distintas.
- El selector de apariencia de Ajustes se adapta al ancho disponible en pantallas pequeñas.

Para actualizar desde TELOS 0.5.2 o posterior, abre Ajustes → Actualizaciones de TELOS → Buscar actualizaciones. Revisa los cambios, descarga el APK y confirma la instalación en Android. Si tienes una versión anterior, instala este APK una vez encima de la app.

No desinstales TELOS: actualizar encima de la instalación conserva favoritos, playlists, historial, permisos y preferencias. La música permanece local.

## 0.5.2 · compilación 9

TELOS GLASS 0.5.2 para Android 8 o posterior, ARM64.

Novedades:
- Aviso de nueva versión al consultar el canal oficial TELOS-updates de GitHub.
- Pantalla Actualizaciones de TELOS en Ajustes, con la versión instalada y las notas de cambios.
- Descarga del APK con progreso y cancelación, únicamente al pulsar Descargar actualización.
- Verificación de tamaño, SHA-256, paquete, número de versión y firma antes de ofrecer la instalación.
- Apertura del instalador oficial de Android para actualizar encima de la app, conservando sus datos.

La comprobación automática se limita a una consulta cada seis horas; Buscar actualizaciones permite una consulta manual. No se transmiten canciones, consultas ni historial. La música permanece local.

Para quienes tienen versiones anteriores: instala este APK una vez encima de TELOS. A partir de esta versión verás los próximos avisos dentro de la aplicación. Android puede solicitar autorización para instalar desde TELOS y confirmación de cada actualización.

No desinstales TELOS para actualizar. Mantén la instalación existente para conservar favoritos, playlists, preferencias y recientes.

## 0.5.1 · compilación 8

TELOS GLASS 0.5.1 para Android 8 o posterior, ARM64.

Cambios principales:
- Búsqueda local con tolerancia acotada a errores de escritura.
- Consultas recientes y canciones reproducidas desde Buscar, guardadas en el dispositivo.
- Resultados ordenados priorizando coincidencias de título; buscar no carga toda la biblioteca en la cola.
- Interfaz Glass y mejoras de la transición del reproductor.

Esta versión es la referencia anterior al actualizador integrado. Para recibir avisos dentro de la app hay que instalar una vez la versión 0.5.2 o posterior.

Instala como actualización encima de TELOS. Conserva tus preferencias, favoritos y playlists; evita desinstalar la versión existente.
