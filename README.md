# Clithel

Asistente de voz personal para Android con unos ojos animados que cambian de color y de emoción. Conversa contigo, te recuerda con tu cuenta aunque reinstales la app y hace tareas en tu celular. Usa Gemini, de Google, como cerebro.

## Qué hace

- **Conversa por voz:** escucha lo que dices y responde en voz alta, en el idioma de tu celular.
- **Tu asistente, con tu nombre:** Clithel es la marca de la app, pero tú eliges cómo llamar a tu asistente en Ajustes. Con ese nombre te responde y es la palabra que escucha.
- **Responde a tu voz sin tocar la pantalla:** di el nombre de tu asistente y empieza a escucharte. Funciona en tu celular, sin internet y sin servicios de Google.
- **Ojos con emociones:** parpadean, miran a los lados y cambian de color según lo que hace: escuchando, pensando o hablando. Al responder puede verse feliz, triste, enojado o sorprendido.
- **Widget:** los mismos ojos animados en la pantalla de inicio. Al tocarlo, Clithel empieza a escucharte.
- **Etiquetas de apps:** ponles tu propio nombre a tus apps (por ejemplo "billar" para 8 Ball Pool, o "música" y "libros"). Después di "abre billar" y se abre directo, sin internet y sin gastar peticiones de Gemini.
- **Cuenta y memoria:** inicia sesión o crea tu cuenta con correo y contraseña. Clithel guarda tu nombre, lo que le cuentas, tus hábitos, tus etiquetas y tus colores, y los recupera si reinstalas o cambias de celular.
- **Colores y fondo a tu gusto:** siete paletas o un tono propio, y fondos como negro, azul noche, carbón, degradado, estrellas animadas o una foto tuya.
- **Se actualiza desde la app:** avisa cuando hay una versión nueva, la descarga y abre el instalador.
- **Reporte de errores:** si algo falla, un botón en Ajustes genera un reporte que puedes copiar para que se pueda arreglar.
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
4. Si tenías una versión anterior de otro origen, desinstálala antes, porque la firma cambió. Desde esta versión, las actualizaciones se instalan desde la propia app.

## Primer uso

1. Abre Clithel y crea tu cuenta, o toca "Continuar sin cuenta".
2. Abre Ajustes (botón AJUSTES, o mantén presionados los ojos). Escribe tu nombre, el nombre que quieres para tu asistente y pega tu clave de Gemini.
3. Toca "Dar permisos" y acepta micrófono, contactos, llamadas, SMS y notificaciones.
4. Toca "Activar accesibilidad" y activa Clithel. En Android 13 o superior puede hacer falta entrar a "Ajustes de la app", tocar los tres puntos y elegir "Permitir ajustes restringidos".
5. Toca "Probar notificación" para comprobar que los avisos funcionan.
6. Toca los ojos, habla y espera la respuesta. Tócalos de nuevo para interrumpirla.

Para el widget: mantén presionada la pantalla de inicio, toca Widgets y busca Clithel.

## Etiquetas de apps

1. En Ajustes, entra a "Etiquetas de apps" y toca "Agregar etiqueta".
2. Elige la app y escribe cómo quieres llamarla, por ejemplo "billar".
3. Di "abre billar", "entra a mi aplicación de billar" o solo "billar". Se abrirá al instante.

Las etiquetas también sirven para que Clithel sepa cuál es tu app de música o de libros cuando se lo pides.

## Llamar al asistente por su nombre

1. En Ajustes, escribe el nombre que quieras para tu asistente.
2. Activa "Escuchar siempre". La primera vez se descarga un modelo de voz en español de unos 40 MB, una sola vez.
3. Cuando diga "Listo", aparece una notificación fija que dice "Escuchando". Di el nombre de tu asistente y, tras un bip corto, dile lo que necesitas.

Cómo funciona y qué esperar:
- Usa Vosk, un reconocedor de voz libre que corre en tu celular. No usa internet ni servicios de Google, y no hay pitidos repetidos.
- Gasta más batería que usarlo tocando los ojos.
- Los nombres inventados pueden fallar al principio. Si no responde, prueba con otro nombre o dilo más despacio y cerca del celular.
- Se pausa mientras Clithel habla o lee, para no escucharse a sí mismo.
- Si reinicias el celular, abre la app una vez para que vuelva a escuchar.
- Para abrir apps desde fuera de la app, Android pide permisos extra. En Xiaomi, Redmi y Poco activa "Mostrar ventanas emergentes mientras se ejecuta en segundo plano" y "Mostrar sobre otras apps".

## Si algo falla: reporte de errores

1. Abre Ajustes y toca "Reporte de errores".
2. Espera unos segundos a que termine de revisar.
3. Toca "Copiar" (o "Compartir") y envía el texto a quien te ayuda.

El reporte incluye la versión de la app, el modelo de tu celular, qué permisos tienes dados, si Gemini, GitHub y Firebase responden desde tu internet, y los últimos errores con su hora. No incluye tus claves, tu correo ni lo que has dicho. Si la app se cierra sola, la próxima vez que la abras te ofrece ver el reporte de ese cierre.

## Actualizaciones

Clithel revisa al abrirse si hay una versión nueva. También puedes tocar "Buscar actualización" en Ajustes. Para instalarla, Android pedirá una vez permiso para instalar apps desde Clithel.

## Ejemplos de lo que puedes decir

- "Abre WhatsApp."
- "Abre billar." (con la etiqueta puesta)
- "Llama a mamá."
- "Manda un mensaje a Juan que diga que llego en 10 minutos."
- "Pon un temporizador de 5 minutos."
- "Recuérdame hacer ejercicio todos los días a las 6 de la tarde."
- "Enciende la linterna."
- "Abre mis libros y léeme en voz alta."

## Si no te llegan los avisos

- Activa las notificaciones de Clithel en los ajustes del teléfono.
- Pon la batería de Clithel en "Sin restricciones".
- En Xiaomi, Redmi y Poco, activa también "Inicio automático" y las ventanas emergentes en segundo plano.

## Privacidad

- Con cuenta, tus datos se guardan en un proyecto de Firebase, de Google: tu correo, tu nombre, el nombre de tu asistente, lo que Clithel recuerda de ti, tus últimas conversaciones, tus hábitos, tus etiquetas de apps y tus colores. Las reglas de la base de datos hacen que cada persona solo pueda ver sus propios datos.
- Tu clave de Gemini no se sube a la nube: se queda en tu celular.
- Puedes borrar tu cuenta y tus datos desde Ajustes. Al cerrar sesión, la memoria se borra del celular.
- La escucha del nombre del asistente se procesa en tu celular y no se envía a ningún servidor.
- Lo que le dices a Clithel después de llamarla se convierte en texto y se envía a la API de Gemini para generar la respuesta. El plan gratuito de Gemini tiene límites y Google puede usar lo que le envías para mejorar sus productos. Evita contarle datos muy privados.
- Las órdenes con etiquetas, como "abre billar", se resuelven en tu celular y no se envían a Gemini.
- El registro de errores se guarda solo en tu celular y no se envía a ningún lado. Únicamente sale si tú tocas "Copiar" o "Compartir".
- La accesibilidad solo se usa cuando se lo pides y Clithel no guarda lo que lee en pantalla.
- No incluyas tu clave de API en ningún archivo de este repositorio.

## Cómo se compila

Cada vez que se actualiza el código, GitHub Actions compila una versión firmada y la publica en Releases. El flujo está en `.github/workflows/build.yml`. La firma usa los secretos `KEYSTORE_BASE64` y `KEYSTORE_PASSWORD`, y la conexión a la nube usa el archivo `cloud.json`.

## Tecnologías

Kotlin, Jetpack Compose, Room, OkHttp, widgets de Android, voz de Android, Vosk (reconocimiento de voz sin conexión), servicio de accesibilidad, Firebase (Authentication y Firestore) y la API de Gemini.

## Próximamente

- Ser el asistente predeterminado del celular, para llamarlo con el botón de encendido.
- Organización de archivos.
- Carga de calendarios y hábitos.

## Limitaciones

- Es una versión temprana y puede tener errores.
- El widget solo se anima mientras la app está activa en segundo plano.
- Android no deja que una app encienda o apague el Wi-Fi por su cuenta.
- Android limita abrir otras apps cuando Clithel está en segundo plano. Hace falta dar los permisos extra indicados arriba.
- Algunas apps protegen su texto y no permiten que se lea la pantalla.
- Llamarla por su nombre puede fallar con nombres difíciles y gasta más batería.
- El reporte de errores solo cubre fallos dentro de la app, no los de la compilación en GitHub.
