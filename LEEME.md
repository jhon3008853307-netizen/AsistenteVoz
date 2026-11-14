# Asistente de Voz offline (v10)

## Opción A: sin computadora (desde el celular)
1. Crea un repositorio en GitHub y sube todo el contenido de esta carpeta.
2. Pestaña Actions -> "Construir APK" -> Run workflow (descarga el modelo solo).
3. Al terminar, descarga el artefacto "AsistenteVoz-apk", descomprímelo e instala el .apk.

## Opción B: Android Studio
1. Descarga https://alphacephei.com/vosk/models/vosk-model-small-es-0.42.zip
2. Descomprime y renombra la carpeta a `model-es`; ponla en app/src/main/assets/
3. Abre el proyecto, Build > Build APK(s).

## Primer uso
Abre la app, pulsa "Activar asistente", concede permisos (micrófono, llamadas,
contactos, superposición) y desactiva el ahorro de batería. En Xiaomi/Redmi
activa también "Inicio automático" para la app.
