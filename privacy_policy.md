Política de Privacidad de NextLive
Última actualización: 13 de junio de 2025

Esta Política de Privacidad describe cómo NextLive ("la Aplicación", "nosotros", "nuestro") recopila, utiliza y comparte la información cuando utilizas nuestra aplicación de escritorio.

1. Información que Recopilamos
NextLive es una aplicación de escritorio que se ejecuta localmente en tu computadora. No recopilamos directamente ninguna información personal identificable de nuestros usuarios en nuestros propios servidores. Sin embargo, para funcionar, la Aplicación interactúa con la API de YouTube de Google, lo que implica el manejo de ciertos datos:

Tokens de Autenticación de Google/YouTube: Cuando autorizas NextLive a acceder a tu cuenta de YouTube (a través del proceso de OAuth 2.0 de Google), se genera un token de acceso y un token de actualización. Estos tokens se almacenan localmente en tu computadora (en la carpeta api_tokens dentro de la misma ubicación de la Aplicación, en un archivo .pickle cifrado por la librería de Google) y se utilizan para:

Autenticar tus solicitudes a la API de YouTube.

Realizar acciones en tu nombre, como cambiar la privacidad de un video a "público" si lo has configurado así en la Aplicación.

Refrescar el token de acceso cuando expira, sin necesidad de que vuelvas a iniciar sesión.

IDs de Video de YouTube: Si utilizas la función para hacer videos públicos, la Aplicación maneja los IDs de los videos que tú proporcionas.

Nombres de credenciales: La aplicación te permite asignar un nombre a tus credenciales de autorización para facilitar su gestión.

Archivos de configuración de la Aplicación: La Aplicación guarda tus configuraciones de transmisiones y playlists (rutas de archivo, claves de stream, configuraciones de proxy, programaciones) en archivos JSON (transmisiones.json, playlists.json) y archivos de registro (logs) directamente en tu computadora.

2. Cómo Usamos la Información
La información y los tokens manejados por NextLive se utilizan exclusivamente para los siguientes propósitos, directamente en tu máquina:

Para autenticarte con la API de YouTube y permitir que la Aplicación interactúe con tu canal (por ejemplo, para cambiar la privacidad de videos).

Para ejecutar las transmisiones en vivo según las configuraciones que hayas establecido (archivos de video, playlists, claves de stream, configuraciones de proxy, programaciones).

Para mantener registros de la actividad de la Aplicación y del proceso de transmisión para depuración y monitoreo, almacenados en archivos de registro locales.

La Aplicación NO envía tus tokens de autenticación, IDs de video, claves de stream, datos de proxy, ni ninguna otra información de uso a nuestros servidores, ni la comparte con terceros.

3. Compartición y Divulgación de Información
No compartimos, vendemos, alquilamos ni divulgamos ninguna información sobre nuestros usuarios ni los datos que la Aplicación maneja localmente. Todos los datos sensibles (como tus tokens de acceso a Google) permanecen en tu control, almacenados en tu computadora.

4. Seguridad de los Datos
Nos comprometemos a proteger la seguridad de la información que la Aplicación maneja. Los tokens de autenticación se almacenan utilizando los mecanismos de almacenamiento seguros proporcionados por las librerías oficiales de Google (Python pickle), lo cual proporciona una capa de protección. Sin embargo, dado que la Aplicación es de escritorio y los datos se almacenan localmente, la seguridad final de tu sistema operativo y tus prácticas de seguridad personal son cruciales para proteger tus credenciales.

5. Retención de Datos
La Aplicación retiene los tokens de autenticación y los archivos de configuración y registro indefinidamente en tu sistema local, a menos que los elimines manualmente:

Puedes eliminar tus credenciales de API desde la pestaña "Autorización API" de la Aplicación, lo que eliminará el archivo .pickle correspondiente.

Puedes eliminar tus configuraciones de stream y playlists desde la interfaz de la Aplicación.

Puedes eliminar manualmente las carpetas api_tokens y logs y los archivos transmisiones.json y playlists.json de la ubicación de la Aplicación si deseas eliminar todos los datos locales.

6. Tus Derechos y Opciones
Dado que NextLive no recopila ni almacena tus datos personales en nuestros sistemas, tus derechos con respecto a tus datos son gestionados directamente por Google para la información que se relaciona con tu cuenta de YouTube.

Puedes revocar el acceso de NextLive a tu cuenta de Google en cualquier momento visitando la configuración de seguridad de tu cuenta de Google: https://myaccount.google.com/permissions.

7. Cambios a Esta Política de Privacidad
Podemos actualizar nuestra Política de Privacidad de vez en cuando. Te notificaremos cualquier cambio publicando la nueva Política de Privacidad aquí y/o actualizando la Aplicación. Se te recomienda revisar esta Política de Privacidad periódicamente para cualquier cambio.

8. Contacto
Si tienes preguntas sobre esta Política de Privacidad o sobre las prácticas de NextLive, por favor contáctanos en:

andresillouspreciosinous@gmail.com
