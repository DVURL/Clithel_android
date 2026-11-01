# Clithel

Asistente de voz personal para Android con unos ojos animados que cambian de color y de emoción. Conversa contigo, tiene memoria propia y puede hacer tareas en tu celular. Usa Gemini, de Google, como cerebro.

## Qué hace

- **Conversa por voz:** escucha lo que dices y responde en voz alta, en el idioma de tu celular.
- **Ojos con emociones:** en el centro de la pantalla hay dos ojos que parpadean y miran a los lados. Cambian de color según lo que hace: blancos en espera, verdes al escucharte, ámbar al pensar y azules al hablar. Al responder puede mostrarse feliz, triste, enojado o sorprendido.
- **Widget:** los mismos ojos animados en la pantalla de inicio. Si lo tocas, Clithel empieza a escucharte.
- **Memoria local:** guarda tus conversaciones y los datos duraderos que le cuentas (nombre, gustos, rutinas) y los usa en sus respuestas.
- **Controla el celular:** abre apps, llama, manda mensajes, pone alarmas y temporizadores, enciende la linterna y ajusta el volumen.
- **Hábitos y recordatorios:** programa avisos que se repiten, por ejemplo "recuérdame beber agua todos los días a las 9".
- **Notificaciones tipo HUD:** avisos con estilo de panel de control para hábitos, temporizadores, alarmas y mensajes enviados.
- **Usa otras apps:** con el permiso de accesibilidad puede leer la pantalla, tocar botones y desplazarse.
- **Lee en voz alta:** abre tu app de libros, lee el texto de la página en voz alta y pasa de página.
- **Más estable:** si Gemini está saturado, reintenta solo y, si un modelo deja de existir, prueba con el siguiente.

## Requisitos

- Celular Android 11 o superior, de 64 bits (arm64-v8a).
- Conexión a internet.
- Una clave de API gratuita de Gemini, que se crea en aistudio.google.com/apikey con tu cuenta de Google.

## Instalación

1. Abre la sección Releases de este repositorio y descarga el APK de la versión más reciente.
2. Ábrelo desde Descargas. Android pedirá permiso para instalar apps desde tu navegador: actívalo.
3. Toca Instalar. Si Play Protect avisa que la app es desconocida, elige Instalar de todos modos.
4. Si ya tenías una versión anterior y no deja instalar, desinstálala primero.

## Primer uso

1. Abre Clithel y mantén presionado el centro de la pantalla para entrar a los ajustes.
2. Escribe tu nombre y pega tu clave de Gemini.
3. Toca "Dar permisos" y acepta micrófono, contactos, llamadas, SMS y notificaciones.
4. Toca "Activar accesibilidad" y activa Clithel. En Android 13 o superior puede hacer falta entrar a "Ajustes de la app", tocar los tres puntos y elegir "Permitir ajustes restringidos".
5. Toca "Probar notificación" para comprobar que los avisos funcionan.
6. Toca los ojos, habla y espera la respuesta. Tócalos de nuevo para interrumpirla.

Para agregar el widget, mantén presionada la pantalla de inicio, toca Widgets y busca Clithel.

## Ejemplos de lo que puedes decir

- "Abre WhatsApp."
- "Llama a mamá."
- "Manda un mensaje a Juan que diga que llego en 10 minutos."
- "Pon un temporizador de 5 minutos."
- "Despiértame mañana a las 7."
- "Recuérdame hacer ejercicio todos los días a las 6 de la tarde."
- "Enciende la linterna."
- "Sube el volumen."
- "Abre Libros y léeme en voz alta."

## Si no te llegan los avisos

- Activa las notificaciones de Clithel en los ajustes del teléfono.
- Pon la batería de Clithel en "Sin restricciones".
- En Xiaomi, Redmi y Poco, activa también "Inicio automático" y las ventanas emergentes en segundo plano.

## Privacidad

- Tu clave de API y tu memoria se guardan solo en el almacenamiento de tu celular.
- Lo que dices se convierte en texto y se envía a la API de Gemini para generar la respuesta.
- El plan gratuito de Gemini tiene límites de uso, y Google puede usar lo que le envías para mejorar sus productos. Evita contarle datos muy privados.
- La accesibilidad solo se usa cuando se lo pides. Clithel no guarda lo que lee en pantalla.
- No incluyas tu clave de API en ningún archivo de este repositorio.

## Cómo se compila

Cada vez que se actualiza la rama main, GitHub Actions compila el proyecto y publica el APK en Releases. El flujo está en `.github/workflows/build.yml`. También se puede abrir el proyecto en Android Studio y ejecutarlo con el botón Run.

## Tecnologías

Kotlin, Jetpack Compose, Room, OkHttp, widgets de Android, reconocimiento y síntesis de voz de Android, servicio de accesibilidad y la API de Gemini.

## Próximamente

- Activación por voz con la palabra "Clithel", sin tocar la pantalla.
- Inicio de sesión para que Clithel te recuerde aunque reinstales la app.
- Organización de archivos.
- Carga de calendarios y hábitos.

## Limitaciones

- Es una versión temprana y puede tener errores.
- El widget solo se anima mientras la app está activa en segundo plano. Si Android la cierra, se queda quieto.
- Android no deja que una app encienda o apague el Wi-Fi por su cuenta.
- Algunas apps protegen su texto y no permiten que se lea la pantalla.
- La lectura en voz alta depende de la app de libros y puede incluir botones o números de página.
