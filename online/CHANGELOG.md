# Historial de cambios

## 0.1.1 · compilación 2

TELOS ONLINE ahora tiene su propio buscador y lista de resultados. Conecta Telegram una vez; después busca por canciones, artistas o global sin abrir el chat ni escribir comandos.

Elige una canción y pulsa Descargar. La app obtiene el audio del bot, muestra el progreso, comprueba tamaño, formato y SHA-256 y lo añade a tu biblioteca. Maneja tanto archivos incluidos en el resultado como nuevas respuestas del bot. Descargar no reproduce ni cambia la cola.

Se rechazan resultados de búsquedas anteriores y audios antiguos del chat. Los artistas y colecciones permiten continuar buscando sus canciones. La sesión se conserva en el almacenamiento privado del cliente interno; no se incluyen credenciales en el APK.

Versión de prueba independiente: conserva TELOS estable, sus ajustes y sus playlists. Requiere conexión a Internet y una cuenta de Telegram autorizada. La disponibilidad y los formatos dependen del bot.

## 0.1.0 · compilación 1

Primera prueba independiente TELOS ONLINE. Se instala junto a TELOS con ajustes y playlists separados. Android 10+, ARM64.

El botón de nube abre Buscar online. La consulta abre el cliente oficial Telegram Web dentro de TELOS ONLINE, en el chat de @deezload2bot. Inicia sesión en esa vista la primera vez, envía la consulta y elige el audio. El botón Consulta permite pegar el texto si aún no se había iniciado sesión.

Usa Descargar en el menú del archivo. El puente interno guarda el audio en Music/TELOS Online, valida formato real, tamaño y SHA-256 antes de publicarlo y conserva nombre, bytes y etiquetas. Volver con Biblioteca actualiza la colección. No se encola ni reproduce automáticamente.

La cuenta permanece en el almacenamiento privado del cliente web integrado. No se incluyen claves, tokens ni sesiones en el APK o el repositorio. No se pide acceso total al almacenamiento. El bot y Telegram determinan disponibilidad, catálogo y formatos.

El traslado automático de FLAC está desactivado por defecto en esta prueba. Las actualizaciones ONLINE usan un canal y paquete separados del TELOS estable.

Prueba inicial: análisis, pruebas Flutter/Kotlin y transferencia por bloques automatizada. La búsqueda autenticada y una descarga real del bot requieren iniciar sesión y completar la comprobación física; consultar docs/VERIFICATION.md en el repositorio privado.
