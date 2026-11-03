# Clithel

Asistente de voz personal para Android con unos ojos animados que cambian de color y de emoción. Conversa contigo, te recuerda con tu cuenta aunque reinstales la app y hace tareas en tu celular. Usa Gemini, de Google, como cerebro.

## Qué hace

- **Conversa por voz:** escucha lo que dices y responde en voz alta, en el idioma de tu celular.
- **Ojos con emociones:** parpadean, miran a los lados y cambian de color según lo que hace: escuchando, pensando o hablando. Al responder puede verse feliz, triste, enojado o sorprendido.
- **Widget:** los mismos ojos animados en la pantalla de inicio. Al tocarlo, Clithel empieza a escucharte.
- **Cuenta y memoria:** inicia sesión o crea tu cuenta con correo y contraseña. Clithel guarda tu nombre, lo que le cuentas, tus hábitos y tus colores, y los recupera si reinstalas o cambias de celular.
- **Colores y fondo a tu gusto:** siete paletas o un tono propio, y fondos como negro, azul noche, carbón, degradado, estrellas animadas o una foto tuya.
- **Se actualiza desde la app:** avisa cuando hay una versión nueva, la descarga y abre el instalador.
- **Controla el celular:** abre apps, llama, manda mensajes, pone alarmas y temporizadores, enciende la linterna y ajusta el volumen.
- **Hábitos y recordatorios** con notificaciones tipo panel de control.
- **Usa otras apps:** con el permiso de accesibilidad puede leer la pantalla, tocar botones y desplazarse.
- **Lee en voz alta:** abre tu app de libros, lee el texto de la página y pasa de página.

## Requisitos

- Celular Android 11 o superior, de 64 bits.
- Conexión a internet.
- Una clave de API gratuita de Gemini, que se crea en aistudio.google.com/apikey con tu cuenta de Google.

## Instalación

1. Abre la sección Releases y descarga `Clithel.apk` de la versión más reciente.
2. Ábrelo desde Descargas. Android pedirá permiso para instalar apps desde tu navegador: actívalo.
3. Toca Instalar. Si Play Protect avisa que la app es desconocida, elige Instalar de todos modos.
4. Si tenías una versión anterior, desinstálala antes, porque la firma cambió. Desde esta versión, las actualizaciones se instalan desde la propia app.

## Primer uso

1. Abre Clithel y crea tu cuenta, o toca "Continuar sin cuenta".
2. Abre Ajustes (botón AJUSTES, o mantén presionados los ojos). Escribe tu nombre y pega tu clave de Gemini.
3. Toca "Dar permisos" y acepta micrófono, contactos, llamadas, SMS y notificaciones.
4. Toca "Activar accesibilidad" y activa Clithel. En Android 13 o superior puede hacer falta entrar a "Ajustes de la app", tocar los tres puntos y elegir "Permitir ajustes restringidos".
5. Toca "Probar notificación" para comprobar que los avisos funcionan.
6. Toca los ojos, habla y espera la respuesta. Tócalos de nuevo para interrumpirla.

Para el widget: mantén presionada la pantalla de inicio, toca Widgets y busca Clithel.

## Actualizaciones

Clithel revisa al abrirse si hay una versión nueva. También puedes tocar "Buscar actualización" en Ajustes. Para instalarla, Android pedirá una vez permiso para instalar apps desde Clithel.

## Ejemplos de lo que puedes decir

- "Abre WhatsApp."
- "Llama a mamá."
- "Manda un mensaje a Juan que diga que llego en 10 minutos."
- "Pon un temporizador de 5 minutos."
- "Recuérdame hacer ejercicio todos los días a las 6 de la tarde."
- "Enciende la linterna."
- "Abre Libros y léeme en voz alta."

## Si no te llegan los avisos

- Activa las notificaciones de Clithel en los ajustes del teléfono.
- Pon la batería de Clithel en "Sin restricciones".
- En Xiaomi, Redmi y Poco, activa también "Inicio automático" y las ventanas emergentes en segundo plano.

## Privacidad

- Con cuenta, tus datos se guardan en un proyecto de Firebase, de Google: tu correo, tu nombre, lo que Clithel recuerda de ti, tus últimas conversaciones, tus hábitos y tus colores. Las reglas de la base de datos hacen que cada persona solo pueda ver sus propios datos.
- Tu clave de Gemini no se sube a la nube: se queda en tu celular.
- Puedes borrar tu cuenta y tus datos desde Ajustes. Al cerrar sesión, la memoria se borra del celular.
- Lo que dices se convierte en texto y se envía a la API de Gemini para generar la respuesta. El plan gratuito de Gemini tiene límites y Google puede usar lo que le envías para mejorar sus productos. Evita contarle datos muy privados.
- La accesibilidad solo se usa cuando se lo pides y Clithel no guarda lo que lee en pantalla.
- No incluyas tu clave de API en ningún archivo de este repositorio.

## Cómo se compila

Cada vez que se actualiza el código, GitHub Actions compila una versión firmada y la publica en Releases. El flujo está en `.github/workflows/build.yml`. La firma usa los secretos `KEYSTORE_BASE64` y `KEYSTORE_PASSWORD`, y la conexión a la nube usa el archivo `cloud.json`.

## Tecnologías

Kotlin, Jetpack Compose, Room, OkHttp, widgets de Android, voz de Android, servicio de accesibilidad, Firebase (Authentication y Firestore) y la API de Gemini.

## Próximamente

- Activación por voz con la palabra "Clithel", sin tocar la pantalla. La opción actual de Ajustes es experimental y pide una clave de Picovoice.
- Organización de archivos.
- Carga de calendarios y hábitos.

## Limitaciones

- Es una versión temprana y puede tener errores.
- El widget solo se anima mientras la app está activa en segundo plano.
- Android no deja que una app encienda o apague el Wi-Fi por su cuenta.
- Algunas apps protegen su texto y no permiten leer su pantalla.
