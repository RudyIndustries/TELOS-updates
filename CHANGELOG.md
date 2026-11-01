# Historial de cambios

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
