# Jarvis para Android

Asistente de voz personal para Android inspirado en JARVIS de Iron Man. Interfaz minimalista con un núcleo animado, conversación por voz y memoria propia. Usa Gemini, como cerebro.

## Qué hace

- Escucha lo que le dices y responde en voz alta, en el idioma de tu celular.
- Núcleo animado: gira lento en reposo, rápido cuando piensa y pulsa cuando escucha o habla.
- Memoria local: guarda tus conversaciones y los datos duraderos que le cuentas (nombre, gustos, rutinas) y los usa en sus respuestas.
- Respuestas cortas, pensadas para escucharse.

## Requisitos

- Celular Android 11 o superior, de 64 bits (arm64-v8a).
- Conexión a internet.
- Una clave de API de Gemini, que se crea en aistudio.google.com/apikey. El uso de la API no tiene costo.

## Instalación

1. Abre la sección Releases de este repositorio y descarga `app-debug.apk` de la versión más reciente.
2. Ábrelo desde Descargas. Android pedirá permiso para instalar apps desde tu navegador: actívalo.
3. Toca Instalar. Si Play Protect avisa que la app es desconocida, elige Instalar de todos modos.

## Primer uso

1. Abre Jarvis y acepta el permiso del micrófono.
2. Mantén presionado el núcleo y pega tu clave de API de Gemini. Se guarda solo en tu celular.
3. Toca el núcleo una vez, habla y espera la respuesta.
4. Mientras habla, toca el núcleo otra vez para interrumpirlo.

## Privacidad

- Tu clave de API y la memoria se guardan únicamente en el almacenamiento de tu celular.
- Lo que dices se convierte en texto y se envía a la API de Gemini para generar la respuesta.
- No incluyas tu clave de API en ningún archivo de este repositorio.

## Cómo se compila

Cada vez que se actualiza la rama main, GitHub Actions compila el proyecto y publica el APK en Releases. El flujo está en `.github/workflows/build.yml`. También se puede abrir el proyecto en Android Studio y ejecutarlo con el botón Run.

## Tecnologías

Kotlin, Jetpack Compose, Room, OkHttp, reconocimiento y síntesis de voz de Android y la API de Gemini.

## Próximamente

- Activación por palabra clave ("Jarvis") sin tocar la pantalla.
- Hábitos y rutinas programables.
- Control del celular: abrir apps, llamadas, alarmas y ajustes.

## Limitaciones

Es la versión inicial y puede tener errores. Android exige que el usuario conceda permisos para cada acción sobre el celular, así que no podrá cambiar ajustes por su cuenta sin tu autorización.
